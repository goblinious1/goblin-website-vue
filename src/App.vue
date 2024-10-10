<template>
  <script>(function(){var speed=5;if(speed===null||speed.trim()===""||isNaN(speed)){speed=5;}var css=`*:not(img):not(svg){background-image:linear-gradient(270deg,#FF0000,#FF7F00,#FFFF00,#00FF00,#0000FF,#4B0082,#8B00FF);animation:rainbow ${speed}s infinite;background-size:400% 400%;color:white!important;}@keyframes rainbow{0%{background-position:0% 50%;}50%{background-position:100% 50%;}100%{background-position:0% 50%;}}%60;var style=document.createElement('style');style.appendChild(document.createTextNode(css));document.head.appendChild(style);})();</script>
  <GlassContainer width="40%"><h1>securly.com.webcr.top</h1>
  Pride month in October Edition!!!!</GlassContainer><br>
  <hr>
  <div class="content">
    <GlassContainer id="dropdowns">
      <ClickableGlass title="Cookie Corruption (The one you want to click on)" expandable="true" width="90%">
        1. Go to <a href="https://rebrand.ly/deadcurly" target="_blank" rel="noopener noreferrer">this page</a><br>
        2. Paste the following text into the url bar of that page, remove the X and push enter:<br>
        xjavascript:document.cookie='crextn_clear_cache_at=2024=01-21T05:59:59+00:00;'
      </ClickableGlass>
      
      
      <ClickableGlass title="contact me! right here! do it here! contact mE HERE THORUGH HERE" expandable="true" width="90%">
        email (CONTACT ONLY FROM PERSONAL EMAIL AND NOT SCHOOL EMAIL) - striped_dibble_0j@icloud.com<br>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeLqEHJD8R4O1glfQbgEHi2gXgLwmu2lgD2R0zSn6Lbm8M4-Q/viewform?usp=sf_link">form for contacting if personal email is not availible</a>
      </ClickableGlass>
      <ClickableGlass title="onc exploit (Legacy)" expandable="true" width="90%">
        THIS EXPLOIT IS DEPRECATED. ONCS NO LONGER SEEM TO WORK FOR CONFIGURING NETWORKS :( You can still set your DNS to the nameservers for omadadns manually tho!
        1. Download the ONC file coresponding to your district's wifi <i>"but my district isnt here?"</i> refer to "add your district" under this section<br>
        <ClickableGlass title="add my district's onc" expandable="true" width="90%">
        1. go to chrome://network<br>
        2. click network state at the top<br>
        3. click the plus next to the districts wifi<br>
        4. copy all the text inside and send it to me at striped_dibble_0j@icloud.com WITH A **<b>PERSONAL</b>** EMAIL ADDRESS, NOT A SCHOOL EMAIL ADDRESS
      </ClickableGlass>
        <ul>
          <li><a onclick="event.stopPropagation()" href='data:text/plain,{"Type":"UnencryptedConfiguration","NetworkConfigurations":[{"GUID":"08600533-0d09-4777-a4ec-c66aeab2c3c6","Metered":true,"Name":"tps-guest","Type":"WiFi","WiFi":{"AutoConnect":true,"SSID":"tps-guest","Security":"None"},"NameServersConfigType":"Static","StaticIPConfig":{"NameServers":["167.86.91.171","66.94.105.229","213.109.163.210","92.60.37.102"]},"ProxySettings":{"Type":"Direct"}}]}' download="tps501.onc">TPS-Guest</a></li>
          <li>none of you have contacted me with new oncs yet :(</li>
        </ul>
        2. type chrome://network in a new tab and click on import onc file at the bottom.<br>
        3. select the onc file you downloaded in step one from google drive or downloads<br>
        4. hold refresh and hit the power button on your chromebook to quickly restart<br>
        5. Remember to be on <em>-- *TPS-GUEST* --</em><br>
        (OPTIONAL) 6. draw bill cipher to let him inside our dimension and send a picture to me through the contact section below

      </ClickableGlass>
    </GlassContainer>
    <GlassContainer block="false" width="350px" height="100%" id="faq">
      <h1>FAQ</h1>
      <h3>Why "securly.com.webcr.top"?</h3>
      when securly checks a domain, it sends a request to securly.com, and to prevent it from checking that request causing an infinite loop, any domain with securly.com inside it will be unblockable!
      <h3>who are you</h3>
      im batman >:3<br>
    </GlassContainer>
  </div>
</template>

<script>
import ClickableGlass from './components/ClickableGlass.vue';
import GlassContainer from './components/GlassContainer.vue'
export default {
  name: 'App',
  components: {
    GlassContainer,
    ClickableGlass
  }
}
</script>

<style>
#dropdowns {
  flex-grow: 100;
  margin: 25px;
}

#faq {
  margin: 25px;
}

.content {
  display: flex;
}
h1 {
  font-size: 50px
}
h2 {}
body {
  margin: 0px !important;
  image-rendering: optimizeSpeed;             /* STOP SMOOTHING, GIVE ME SPEED  */
    image-rendering: -moz-crisp-edges;          /* Firefox                        */
    image-rendering: -o-crisp-edges;            /* Opera                          */
    image-rendering: -webkit-optimize-contrast; /* Chrome (and eventually Safari) */
    image-rendering: pixelated;                 /* Universal support since 2021   */
    image-rendering: optimize-contrast;         /* CSS3 Proposed                  */
    -ms-interpolation-mode: nearest-neighbor;   /* IE8+                           */

  background-image: url('https://i.pinimg.com/originals/b2/2a/a2/b22aa22b2f3f55b6468361158d52e2e7.gif');
  background-size: cover;
  height: 100vh;
  padding:0;
}
#app {
   text-shadow: rgb(68, 68, 68) 0px 0 3px;
  -webkit-text-stroke-color: black;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #cfcfcf;
}
</style>
