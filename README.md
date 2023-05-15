Forked from - [Original Script](https://greasyfork.org/en/scripts/375806-%E6%89%8B%E6%9C%BA%E6%B5%8F%E8%A7%88%E5%99%A8%E8%A7%A6%E6%91%B8%E6%89%8B%E5%8A%BF) made by [L.Xavier](https://greasyfork.org/en/users/128493-l-xavier)

<h1 align="center">
Mobile browser Gestures Extended (MbGE)
</h1>


<h4>
Add customizable touch and swipe gestures to mobile browsers. Recommended use with Kiwi browser, Yandex browser and Lemur Browser.
</h4>

- This is primarily an English translation but also offers slight modifications. 
- Translation was 100% created with the use of Google translate + resonable/safe judgements and careful selection to ensure consistent variable/function names.
- Translations may not be fully accurate, but are more than sufficient to navigate through the majority, if not the entire script.
***
<h2>
VERSIONS
</h2>

<table>
<thead>
  <tr>
    <th>MbGE: English-translated + Custom modifications:</th>
    <th>Original but English-translated:</th>
    <th>Original script:</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>\MbGE\MbGE.js</td>
    <td>\@Translated_to_English\English_Translated.js</td>
    <td>\@Original\Original.js</td>
  </tr>
  <tr>
    <td>Custom Modifications include:
      <ul>
        <li>Changing Baidu translate to Google translate(Text Gesture)</li>
        <li>Changing Youdao translate to Youtube search(Text Gesture)</li>
        <li>Changing Bing search to Google search(Text Gesture)</li>
        <li>Changing Image search with baidu maps to Image search with google search(Image Gesture) [NOT WORKING]</li>
        <li>Changing Video forward/backward 10 seconds to Video forward/backward 5 seconds(Video Gesture)</li>
        <li>Removed Video analysis function that opened videos in jx.jsonplayer site as it didn't work to begin with and I had no use for it.</li>
      </ul>
    </td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>

<h4>
Download via Greasy Fork:
</h4>

[MbGE: English-translated + Custom modifications](https://greasyfork.org/en/scripts/466269-mobile-browser-gestures-extended-mbge)  

or  

[Original but English-translated](https://greasyfork.org/en/scripts/466268-mobile-browser-touch-gestures-english-translated)  


<h2>
Install/Setup instructions
</h2>

1. Install Tampermonkey(or other extension like Greasemonkey, Violentmonkey, etc.)  
2. Go to dashboard and create new script  
3. Choose preferred script version based off of descriptions in [VERSIONS](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE#versions) table  
Install preferred script version via [Greasy Fork links](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE#download-via-greasy-fork)   

4. Save and ensure it's enabled  
5. If testing on old tabs make sure to refresh them for script to run on it  

6. Slide the "↑→↓←" box gesture to open the [Gesture Track Setting] interface, and you can customize the gesture function  

<div align="center">
  <video src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/1e878387-132c-4b0e-a434-abfc6c810fc2" width="400" />
</div>


7. You can click the title of "Gesture track setting" to open the "Function switch setting" interface  
8. You can modify the settings however you like but can't delete the following:
    - Open Settings  
    - Video Full screen (must end with click)  
    - Gesture Penetration  

If wanted, use my custom settings from '[\MbGE\MyCustom_Settings1.jpg](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/blob/main/MbGE/MyCustom_Settings1.jpg)' and '[\MbGE\MyCustom_Settings2.jpg](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/blob/main/MbGE/MyCustom_Settings2.jpg)'

<h4>
Gesture Icon Legend:
</h4>


<table>
<thead>
  <tr>
    <th>Icon</th>
    <th>Gesture</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>T</td>
    <td>Text Gesture</td>
  </tr>
  <tr>
    <td>I</td>
    <td>Image Gesture</td>
  </tr>
  <tr>
    <td>V</td>
    <td>Video Gesture</td>
  </tr>
  <tr>
    <td>↑</td>
    <td>Slide up</td>
  </tr>
  <tr>
    <td>↓</td>
    <td>Slide down</td>
  </tr>
  <tr>
    <td>→</td>
    <td>Slide right</td>
  </tr>
  <tr>
    <td>←</td>
    <td>Slide left</td>
  </tr>
  <tr>
    <td>◆</td>
    <td> Click, trigger after clicking</td>
  </tr>
  <tr>
    <td>●</td>
    <td>Long press, trigger when long press</td>
  </tr>
  <tr>
    <td>○</td>
    <td>Trigger corresponding ● gesture, trigger after lifting</td>
  </tr>
  <tr>
    <td>▼</td>
    <td>Delay swipe continuously in the same direction, trigger when sliding</td>
  </tr>
  <tr>
    <td>▽</td>
    <td>After triggering the corresponding ▼ gesture, trigger after lifting</td>
  </tr>
</tbody>
</table>

<h4>
Default mapped gestures in MbGE:
</h4>

<table>
<thead>
  <tr>
    <th>Gesture</th>
    <th>Function</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>↑→↓←</td>
    <td>Open Settings</td>
  </tr>
  <tr>
    <td>◆◆</td>
    <td>Video full screen</td>
  </tr>
  <tr>
    <td>●</td>
    <td>Gesture Penetration</td>
  </tr>
  <tr>
    <td>→←</td>
    <td>Back</td>
  </tr>
  <tr>
    <td>←→</td>
    <td>Forward</td>
  </tr>
  <tr>
    <td>↓↑</td>
    <td>Back to top</td>
  </tr>
  <tr>
    <td>↑↓</td>
    <td>Back to the bottom</td>
  </tr>
  <tr>
    <td>←↓</td>
    <td>Refresh page</td>
  </tr>
  <tr>
    <td>←↑</td>
    <td>New page</td>
  </tr>
  <tr>
    <td>→↓</td>
    <td>Close page</td>
  </tr>
  <tr>
    <td>→↑</td>
    <td>Restore page</td>
  </tr>
  <tr>
    <td>↓↑●</td>
    <td>Open a new page</td>
  </tr>
  <tr>
    <td>↑↓●</td>
    <td>Hidden element</td>
  </tr>
  <tr>
    <td>↓→</td>
    <td>Duplicate page</td>
  </tr>
  <tr>
    <td>→←→</td>
    <td>Half screen mode</td>
  </tr>
  <tr>
    <td>T→↑</td>
    <td>Google translation</td>
  </tr>
  <tr>
    <td>T←↑</td>
    <td>YouTube search</td>
  </tr>
  <tr>
    <td>T◆◆</td>
    <td>Double click to search</td>
  </tr>
  <tr>
    <td>I↓↑●</td>
    <td>Open the picture</td>
  </tr>
  <tr>
    <td>I→↑●</td>
    <td>Google Image Search [NOT WORKING]</td>
  </tr>
  <tr>
    <td>V→</td>
    <td>Forward 5s</td>
  </tr>
  <tr>
    <td>V←</td>
    <td>Back 5s</td>
  </tr>
  <tr>
    <td>V↑</td>
    <td>Increase double speed</td>
  </tr>
  <tr>
    <td>V↓</td>
    <td>Reduce double speed</td>
  </tr>
  <tr>
    <td>V→●</td>
    <td>Fast forward playback</td>
  </tr>
  <tr>
    <td>V→○</td>
    <td>Stop fast forward</td>
  </tr>
  <tr>
    <td>V←●</td>
    <td>Rewind playback</td>
  </tr>
  <tr>
    <td>V←○</td>
    <td>Stop rewinding</td>
  </tr>
  <tr>
    <td>V↑●</td>
    <td>Increase volume</td>
  </tr>
  <tr>
    <td>V↑○</td>
    <td>Close increase volume</td>
  </tr>
  <tr>
    <td>V↓●</td>
    <td>Volume down</td>
  </tr>
  <tr>
    <td>V↓○</td>
    <td>Close and reduce volume</td>
  </tr>
  <tr>
    <td>V→▼</td>
    <td>Swipe right progress</td>
  </tr>
  <tr>
    <td>V→▽</td>
    <td>Close right slide progress</td>
  </tr>
  <tr>
    <td>V←▼</td>
    <td>Left slide progress</td>
  </tr>
  <tr>
    <td>V←▽</td>
    <td>Close left slide progress</td>
  </tr>
</tbody>
</table>

<h2>
Reset Settings
</h2>

Even if you replace the script text with the initial script text, the old settings will probably stick.  
This is because the script is still holding onto it's storage content.  

The easiest way to remove the old settings is to delete the script with the trash bin icon or File/Remove and then reinstall the initial script.  
