---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<style>
* {
  box-sizing: border-box;
}

.row {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  padding-top: 30px;
  padding-bottom: 30px;
}
.yomiwa {
  display: flex;
  flex-direction: row-reverse;
}
.yomibrowser {
  display: flex;
  flex-direction: row-reverse;
}
.column {
  float: center;
  width: 50%;
  padding: 30px;
  padding-top: 10px;
  padding-bottom: 10px;
  text-align: center;
}


@media screen and (max-width: 600px) {
  .row {
    flex-direction: column;
  }
  .column {
    width: 100%;
  }
}


.row:after {
  content: ""; -->
  display: flex; -->
  clear: both; -->
}

</style>

Nomad AI was founded by former PhD students in Artificial Intelligence at Kyoto University. Nomad AI takes advantage of the recent advances in AI to develop iOS and Android applications with powerful on-device machine learning algorithms, such as text detection, natural language processing or music chord recognition. Nomad AI creations are available on the <a href="https://apps.apple.com/developer/nomad-ai-ou/id670931123">Apple Store</a> and the <a href="https://play.google.com/store/apps/developer?id=Yomiwa&hl=en">Google Play store</a>. 

<div class="row chordai">
  <div class="column">
    <h1>Chord AI</h1>
    <a href="http://www.chordai.net">Chord AI</a> is an iOS app which can recognize 268 music chords by analyzing music from either your device microphone or from your offline audio files. Available for iOS (Android version coming soon)
    <p>
      <center><a class="badge" href="https://apps.apple.com/app/chord-ai/id1446177109"><img class="badge" src="https://arolet.github.io/res/Download_on_the_App_Store_Badge_US-UK_135x40.svg" alt="Available on the App Store"/></a>
      </center>
    </p>
  </div>
  <div class="column">
    <center>
    <iframe width="260" height="450" src="https://www.youtube.com/embed/6vA83qEUoCA">
    </iframe>
    </center>
  </div>
</div>

<div class="row yomiwa">
<div class="column">
<h1>Yomiwa</h1>
<a href="https://www.yomiwa.net">Yomiwa</a> is the most advanced Japanese dictionary on both the Apple Store and Google Play Store. Yomiwa features optical character recognition (OCR), Japanese to English machine translation, a Japanese morphological analyzer, and numerous unique features to help user read and learn Japanese.

<p>
    <center><a class="badge" href="https://itunes.apple.com/app/yomiwa/id670931120"><img class="badge" src="https://arolet.github.io/res/Download_on_the_App_Store_Badge_US-UK_135x40.svg" alt="Available on the App Store"/></a>
        <a href="https://play.google.com/store/apps/details?id=com.yomiwa.yomiwa"><img alt="Get it on Google Play" width="156" src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" /></a>
    </center>
</p>
</div>


<div class="column">
<center>
<iframe width="280" height="450" src="https://www.youtube.com/embed/CQZD7iT7GQw">
</iframe>
</center>
</div>


</div>

<div class="row hanyou">

  <div class="column">
  <h1>HanYou</h1>
  <a href="https://hanyou.github.io">HanYou</a> is an advanced Chinese dictionary which is built upon the Yomiwa's powerful technologies. HanYou's OCR algorithms are able to recognize more than 13000 Chinese characters.
  <p>
      <center><a class="badge" href="https://itunes.apple.com/us/app/hanyou-chinese-dictionary-and-translator/id901093520?mt=8"><img class="badge" src="https://arolet.github.io/res/Download_on_the_App_Store_Badge_US-UK_135x40.svg" alt="Available on the App Store"/></a>
          <a href="https://play.google.com/store/apps/details?id=com.yomiwa.hanyou&hl=en&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1"><img alt="Get it on Google Play" width="156" src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" /></a>
      </center>
   </p>
   </div>
  <div class="column">
   <center>
   <iframe width="280" height="450" src="https://www.youtube.com/embed/4Vu-E9KeGmc">
   </iframe>
   </center>
  </div>
</div>


<div class="row yomibrowser">

  <div class="column">
  <h1>Yomi Browser</h1>
  Yomi Browser is a simple browser that adds furiganas or romajis above Japanese words automatically. Besides, a tap on each Japanese word will display a popup with detailed definitions in several target languages.
  <p>
      <center><a class="badge" href="https://apps.apple.com/app/yomi-browser/id1492326021"><img class="badge" src="https://arolet.github.io/res/Download_on_the_App_Store_Badge_US-UK_135x40.svg" alt="Available on the App Store"/></a>
      </center>
   </p>
   </div>
  <div class="column">
   <center>
   <img src="/assets/images/popups_X.png" alt="">
   </center>
  </div>
</div>
