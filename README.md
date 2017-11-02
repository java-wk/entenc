Windows app that combines different APIs (<a href="http://www.xfyun.cn/services/voicedictation">iFlytek-科大讯飞</a>, <a href="https://traslate.google.cn">Google Translate</a>, <a href="https://azure.microsoft.com/en-us/services/cognitive-services/speech/">Bing Speech</a>, <a href="http://fanyi-api.baidu.com/api/trans/product/index">Baidu Translate</a>) to get the best translated caption/subtitles for China market:

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063973-2f13fd20-baab-11e7-93c1-61155a152a3c.png" width="500"></p>

<p align="center"><b>Except Google Translate, for each other service you must get an ID</b></p>
<br/>

Screenshot of the program:
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32085308-d218c690-bb00-11e7-86d1-debebfe03c76.jpg"></p>
Comments:
<ul>
<li>No matter what is on the screen (powerpoint, video, etc.) the subtitles will always be on top of it</li>
<li>You can also run <b>audio files</b> (currently only from English to Chinese)</li>
<li>The transcript of the recognized audio and translation will be stored in a .txt file once you select the "副本" box</li>
<li>You can record speaker voice by selecting "录音" box</li>
</ul>
<br/>
<hr></hr>
<br/>
<p>1. From <b>Chinese audio to English caption/subtitles</b>, the program uses:</p>

<u>
<li>Chinese voice recognition: <a href="http://www.xfyun.cn/services/voicedictation">iFlytek-科大讯飞</a></li>
<li>Chinese to English text translation: <a href="https://traslate.google.cn">Google Translate</a></li>
</u>

<br/>
<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063586-2729e396-baaa-11e7-9f0d-71f921fba63f.png" width="500"></p>
<br/>

<p>2. From <b>English audio to Chinese caption/subtitles</b>, the program uses:</p>

<u>
<li>English voice recognition: <a href="https://azure.microsoft.com/en-us/services/cognitive-services/speech/">Bing Speech</a></li>
<li>English to Chinese translation: <a href="http://fanyi-api.baidu.com/api/trans/product/index">Baidu Translate</a></li>
</u>

<br/>
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063559-108eba8a-baaa-11e7-93b2-f4baecc82aff.png" width="500"></p>

<br/>
<hr></hr>
<br/>

<h1>iFlytek</h1>
<a href="http://www.xfyun.cn/services/voicedictation">iFlytek-科大讯飞</a>
<br/>
<p>In order to use the Chinese voice recognition follow next 2 steps:</p>
<ul>
<li>Register and get your ID <a href="http://www.xfyun.cn/services/voicedictation">here</a>, then write it down in the <b>App.config</b> file as shown in below pic
  
  <p align="center"><img src="https://user-images.githubusercontent.com/24521991/32303913-86bf042a-bfa6-11e7-8b97-9109786c75cc.png"></p>
  
<li>Download the SDK from your portal (as shown in below pic) then copy/paste the <b>msc.dll file</b> and <b>msc folder</b> in your bin/debug folder
  <p align="center"><img src="https://user-images.githubusercontent.com/24521991/32142652-83a1f13a-bcd6-11e7-9898-8535c88a85cc.png"></p>
</ul>

<br/>

<h1>Google</h1>
<a href="http://translate.google.cn">Google</a>
<br/>
<p>In order to make Google text translation work please include the file gettk.js in your bin/debug folder</p>

<br/>

<h1>Microsoft</h1>
<a href="https://azure.microsoft.com/en-us/services/cognitive-services/speech/">Bing Speech</a>
<br/>
<p>In order to use Microsoft voice recognition follow next steps:</p>
<ul>
<li>Register and get your Subscription Key <a href="https://azure.microsoft.com/en-us/services/cognitive-services/speech/">here</a>, then write it down in the <b>MainWindows.xaml.cs</b> file as shown in below pic
  
  <p align="center"><img src="https://user-images.githubusercontent.com/24521991/32304363-9f2413ea-bfa9-11e7-999b-11de73775833.png"></p>
  
<li>If you want to use the Cutomize Speech service register and ger your Subscription Key <a href="https://azure.microsoft.com/en-us/services/cognitive-services/custom-speech-service/">here</a>, then write it down in the <b>MainWindows.xaml.cs</b> file as shown in below pic
  
  <p align="center"><img src="https://user-images.githubusercontent.com/24521991/32304499-b967e5d2-bfaa-11e7-8761-4402b7481145.png"></p>
</ul>

<p>Notice to use the Customize Speech service you have to check the "lib" checkbox and paste your service link which is provided everytime you set up a new customize speech:</p>
<br/>
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32304730-5ba21b50-bfac-11e7-8671-8cd11e1d74d5.png"></p>
<br/>

<h1>Baidu</h1>
<a href="http://fanyi-api.baidu.com/api/trans/product/index">Baidu Translate</a>
<br/>
<p>In order to use Baidu Translate follow next steps:</p>
<ul>
<li>Register and get your ID + Key <a href="http://fanyi-api.baidu.com/api/trans/product/index">here</a>, then write them down in the <b>MainWindows.xaml.cs</b> file as shown in below pic
  
  <p align="center"><img src="https://user-images.githubusercontent.com/24521991/32305104-64a33a70-bfae-11e7-9536-669bcea7e5b9.png"></p>

</ul>

<br/>
<hr></hr>
<br/>
Open to any suggestion! Thanks!!
