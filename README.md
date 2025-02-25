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
        <li>Adding Sentence selection</li>
        <li>Changing New page from Limestart.cn to Chrome://newtab</li>
        <li>Changing Baidu translate to Google translate(Text gesture)</li>
        <li>Changing Youdao translate to Youtube search(Text gesture)</li>
        <li>Changing Query search from Bing search to Google search(Text gesture)</li>
        <li>Changing Baidu image search to Google image search(Image gesture)</li>
        <li>Changing Video forward/backward 10 seconds to Video forward/backward 5 seconds(Video gesture)</li>
        <li>Removed Analyze video function that opened videos in jx.jsonplayer site as it didn't work to begin with and I had no use for it.</li>
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

1. Install Tampermonkey extension(or other userscript managers like Greasemonkey, Violentmonkey, etc.)  
    - If comfortable with it, I recommend turning on "Allow access to file URLs" for best experience as it will allow the script to work on more pages and on built-in chrome video player. On chromium browsers this can be done by going to extensions via 'chrome://extensions' url in address bar, then go to Tampermonkey(or userscript manager of choice) Details and toggle on "Allow access to file URLs".
3. Choose preferred script version based off of descriptions in [VERSIONS](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE#versions) table  
Install preferred script version via [Greasy Fork links](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE#download-via-greasy-fork)   

4. If needed refresh old tabs for script to run on it  

5. Slide the "↑→↓←" box gesture to open the [Gesture Track Setting] interface, and you can customize the gesture function  

<div align="center">
  <video src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/1e878387-132c-4b0e-a434-abfc6c810fc2"/>
</div>

<details>
  <summary><b>How to navigate settings ui:</b></summary>
  
  (Open image in new tab or download image to zoom in)
  ![Translated Pictures Guide](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/9484af5e-4bce-40cb-83c7-64e2f375c95f)

</details>

6. You can click the title of "Gesture track settings" to open the "Function switch settings" interface  
7. You can modify the settings however you like but can't delete the following:
    - Open settings  
    - Video full screen  
    - Gesture penetration  

After making changes to settings, if needed refresh old tabs to see applied changes.  

If wanted, use my custom settings from '[\MbGE\MyCustom_Settings_1.jpg](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/blob/main/MbGE/MyCustom_Settings_1.jpg)' and '[\MbGE\MyCustom_Settings_2.jpg](https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/blob/main/MbGE/MyCustom_Settings_2.jpg)'.

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
    <td>Text gesture</td>
  </tr>
  <tr>
    <td>I</td>
    <td>Image gesture</td>
  </tr>
  <tr>
    <td>V</td>
    <td>Video gesture</td>
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
    <td> Click, triggers after clicking</td>
  </tr>
  <tr>
    <td>●</td>
    <td>Long press, triggers during long press</td>
  </tr>
  <tr>
    <td>○</td>
    <td>Lift corresponding ● gesture, triggers after lifting</td>
  </tr>
  <tr>
    <td>▼</td>
    <td>Lengthy slide in the same direction, triggers after 400ms of continuous sliding</td>
  </tr>
  <tr>
    <td>▽</td>
    <td>Lift corresponding ▼ gesture, triggers after lifting</td>
  </tr>
</tbody>
</table>


<details>
  <summary><b>Default mapped gestures in MbGE:</b></summary>

<table>
<thead>
  <tr>
    <th>Gesture (36)</th>
    <th>Function</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>↑→↓←</td>
    <td>Open settings</td>
  </tr>
  <tr>
    <td>◆◆</td>
    <td>Video full screen</td>
  </tr>
  <tr>
    <td>●</td>
    <td>Gesture penetration</td>
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
    <td>Back to bottom</td>
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
    <td>Open in new page</td>
  </tr>
  <tr>
    <td>↑↓●</td>
    <td>Hide element</td>
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
    <td>Google translate</td>
  </tr>
  <tr>
    <td>T←↑</td>
    <td>YouTube search</td>
  </tr>
  <tr>
    <td>T↑↓</td>
    <td>Query search</td>
  </tr>
  <tr>
    <td>T◆◆</td>
    <td>Sentence selection</td>
  </tr>
  <tr>
    <td>I↓↑●</td>
    <td>Open image source</td>
  </tr>
  <tr>
    <td>I→↑●</td>
    <td>Google image search</td>
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
    <td>Increase speed</td>
  </tr>
  <tr>
    <td>V↓</td>
    <td>Decrease speed</td>
  </tr>
  <tr>
    <td>V→●</td>
    <td>Fast forward playback</td>
  </tr>
  <tr>
    <td>V→○</td>
    <td>Release fast forwarding</td>
  </tr>
  <tr>
    <td>V←●</td>
    <td>Rewind playback</td>
  </tr>
  <tr>
    <td>V←○</td>
    <td>Release rewinding</td>
  </tr>
  <tr>
    <td>V↑●</td>
    <td>Volume increase</td>
  </tr>
  <tr>
    <td>V↑○</td>
    <td>Release volume increase</td>
  </tr>
  <tr>
    <td>V↓●</td>
    <td>Volume decrease</td>
  </tr>
  <tr>
    <td>V↓○</td>
    <td>Release volume decrease</td>
  </tr>
  <tr>
    <td>V→▼</td>
    <td>Progress</td>
  </tr>
  <tr>
    <td>V→▽</td>
    <td>Release progress</td>
  </tr>
  <tr>
    <td>V←▼</td>
    <td>Regress</td>
  </tr>
  <tr>
    <td>V←▽</td>
    <td>Release regress</td>
  </tr>
</tbody>
</table>

</details>

<details>
  <summary><b>Default mapped gestures in Original but English-translated:</b></summary>
  
  <table>
<thead>
  <tr>
    <th>Gesture (37)</th>
    <th>Function</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>↑→↓←</td>
    <td>Open settings</td>
  </tr>
  <tr>
    <td>◆◆</td>
    <td>Video full screen</td>
  </tr>
  <tr>
    <td>●</td>
    <td>Gesture penetration</td>
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
    <td>Back to bottom</td>
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
    <td>Open in new page</td>
  </tr>
  <tr>
    <td>↑↓●</td>
    <td>Hide element</td>
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
    <td>→↓↑←</td>
    <td>Analyze video</td>
  </tr>
  <tr>
    <td>T→↑</td>
    <td>Baidu translate</td>
  </tr>
  <tr>
    <td>T←↑</td>
    <td>Youdao translate</td>
  </tr>
  <tr>
    <td>T◆◆</td>
    <td>Query search</td>
  </tr>
  <tr>
    <td>I↓↑●</td>
    <td>Open image source</td>
  </tr>
  <tr>
    <td>I→↑●</td>
    <td>Baidu image search</td>
  </tr>
  <tr>
    <td>V→</td>
    <td>Forward 10s</td>
  </tr>
  <tr>
    <td>V←</td>
    <td>Back 10s</td>
  </tr>
  <tr>
    <td>V↑</td>
    <td>Increase speed</td>
  </tr>
  <tr>
    <td>V↓</td>
    <td>Decrease speed</td>
  </tr>
  <tr>
    <td>V→●</td>
    <td>Fast forward playback</td>
  </tr>
  <tr>
    <td>V→○</td>
    <td>Release fast forwarding</td>
  </tr>
  <tr>
    <td>V←●</td>
    <td>Rewind playback</td>
  </tr>
  <tr>
    <td>V←○</td>
    <td>Release rewinding</td>
  </tr>
  <tr>
    <td>V↑●</td>
    <td>Volume increase</td>
  </tr>
  <tr>
    <td>V↑○</td>
    <td>Release volume increase</td>
  </tr>
  <tr>
    <td>V↓●</td>
    <td>Volume decrease</td>
  </tr>
  <tr>
    <td>V↓○</td>
    <td>Release volume decrease</td>
  </tr>
  <tr>
    <td>V→▼</td>
    <td>Progress</td>
  </tr>
  <tr>
    <td>V→▽</td>
    <td>Release progress</td>
  </tr>
  <tr>
    <td>V←▼</td>
    <td>Regress</td>
  </tr>
  <tr>
    <td>V←▽</td>
    <td>Release regress</td>
  </tr>
</tbody>
</table>
  
</details>
 
<details>
  <summary><b>How to reset to default settings</b></summary>

Even if you replace the script text with the initial script text, the old settings will probably stick.  
This is because the script is still holding onto it's storage content.  

The easiest way to remove the old settings is to go to Tampermonkey's dashboard and delete the script with the trash bin icon or File/Remove and then reinstall the initial script.  
  
</details>
 
<h2>
Gesture Functions/UI (MbGE)
</h2>

<h4>
General:
</h4>

`Open settings` `Video full screen` `Gesture penetration`

<h4>
Navigation:
</h4>

`Back` `Forward` `Back to top` `Back to bottom` `Refresh page`  
`New page` `Close page` `Restore page` `Open in new page` `Hide element` `Duplicate page` `Half screen mode`

<h4>
Text/Image:
</h4>

`Google translate` `YouTube search` `Query search`  
`Open image source` `Google image search`

<h4>
Video:
</h4>

`Forward 5s` `Back 5s`  
`Increase speed` `Decrease speed`  
`Fast forward playback` `Release fast forwarding` `Rewind playback` `Release rewinding`  
`Volume increase` `Release volume increase` `Volume decrease` `Release volume decrease`  
`Progress` `Release progress` `Regress` `Release regress`  

<h2>
Known Issues
</h2>

<h4>
Issues:
</h4>

- If image gestures is on, long press on images won't show regular context menu.
- Even if configured without it, image gestures always start with `Gesture penetration`(default is long press) and so will require it at first to get image gestures triggered.
- Video fullscreen function will work even if video gestures is disabled.
  - This may be resolvable by turning the function into a video gesture by manually adding the a "V" to the `'◆◆': 'Video full screen',` line in the script. But this has not been tested and may not work or break certain functionality.
- Breaks tap and slide up/down to zoom functionality when in desktop mode.

<h4>
Quirks:
</h4>

- Slide up/down gestures on videos will only trigger if video is fullscreen. Although this is probably for the best.



<h2>
Other Recommendations
</h2>

While MbGE is a powerful tool, sometimes having to remember too many gestures can be a hassle or an inconvenience. Or perhaps you wish you could access some shortcuts faster in a tap of a button instead of a more convoluted gesture combination. For this reason I use MbGE in combination with 2 other chromium extensions designed for mobile browsers:
- [Mobile Toolbar For Kiwi Browser](https://github.com/butaixianran/Mobile-Toolbar-For-Kiwi-Browser) (Open Source)
- [Floatly](https://github.com/d3ward/floatly) (Open Source)

Both of these can work well by themselves and have some of the shortcuts that MbGE has (Floaty in particular has a few different shortcuts that are not in MbGE). They both have their strengths and while I won't be fully documenting all their features here, I have made a video showcasing <b>SOME</b> of their features (Floaty in particular has way more features than I showcased). I recommend checking both of them out via the links above. The video below is how I use both extensions together in Kiwi Browser:

<details>
  <summary><b>Click here to see video:</b></summary>

<p align="left">
  <img src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/7898c09f-1577-4927-aa8d-495a303dd539" alt="Image of Mobile Toolbar For Kiwi Browser" width="150">
  ← This is Mobile Toolbar For Kiwi Browser.
</p>
  
<p align="left">
  <img src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/4efaeb75-3418-4344-ab26-cfa821831e17" alt="Image of Floaty" width="150">
  ← This is Floaty (I positioned it to lay on top of Mobile Toolbar For Kiwi Browser' refresh button).
</p>
  
<p align="left">
  <img src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/b708ca08-7650-49a5-b224-8654287b9950" alt="Image of Mobile Toolbar For Kiwi Browser + Floaty" width="150">
  ← This is both of the extensions together.
</p>
  

<div align="center">
  <video src="https://github.com/Crunchbits/Mobile-browser-Gestures-Extended-MbGE/assets/87384615/459944c9-2dcb-473e-84ff-a466ef3ed867"/>
</div>

</details>
