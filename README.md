Forked from - [Original Script](https://greasyfork.org/en/scripts/375806-%E6%89%8B%E6%9C%BA%E6%B5%8F%E8%A7%88%E5%99%A8%E8%A7%A6%E6%91%B8%E6%89%8B%E5%8A%BF) made by [L.Xavier](https://greasyfork.org/en/users/128493-l-xavier)

<h1 align="center">
Mobile browser Gestures Extended (MbGE)
</h1>


<h4>
Add customizable touch and swipe gestures to mobile browsers. Recommend using Kiwi browser, Yandex browser and Lemur Browser.
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
    <td>\Translated_to_English\English_Translated.js</td>
    <td>\Original\Original.js</td>
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

<h2>
Install/Setup instructions
</h2>

1. Install tampermonkey(or other extension like greasemonkey  
2. Go to dashboard and create new script  
3. Copy and paste text from preferred .js file version into script  
Choose preferred file version based off of descriptions in [VERSIONS](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE-#versions) table  

4. Save and ensure it's enabled  
5. If testing on old tabs make sure to refresh them for script to run on it  

6. Slide the "↑→↓←" box gesture to open the [Gesture Track Setting] interface, and you can customize the gesture function  
7. You can click the title of "Gesture track setting" to open the "Function switch setting" interface  
8. You can modify the settings however you like but can't/shouldn't delete the following:
    - Open Settings  
    - Video Full screen (Must end with click)  
    - Gesture Penetration  

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


<h2>
Reset Settings
</h2>

Even if you replace the script text with the initial script text, the old settings will probably stick.  
This is because the script is still holding onto it's storage content.  

The easiest way to remove the old settings is to delete the script with the trash bin icon or File/Remove and then re-add the initial script manually.  
DONE.  
