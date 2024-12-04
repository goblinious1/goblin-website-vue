<template>
  <GlassContainer width="40%"><h1>securly.com.webcr.top</h1>
  its no longer pride month in October D:</GlassContainer><br>
  <hr>
  <div class="content">
    <GlassContainer id="dropdowns">
      <ClickableGlass title="Cookie Corruption (The one you want to click on)" expandable="true" width="90%">
        1. Go to <a href="https://rebrand.ly/deadcurly" target="_blank" rel="noopener noreferrer">this page</a><br>
        2. Paste the following text into the url bar of that page, remove the X and push enter:<br>
        xjavascript:document.cookie='crextn_clear_cache_at=2024=01-21T05:59:59+00:00;'
      </ClickableGlass>
      <ClickableGlass title="DragTab (Easier, but manual and only one tab at a time)" expandable="true" width="90%">
        1. search whatever website you want to go to or just find a link to it.
        2. drag the link into any other tab and drop it
        3. PROFIT!!!
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
      <h3>why were you celebrating pride month in October It made it really hard to read the website</h3>
      why not?
      <h3>why does my exploit undo itself sometimes??</h3>
      seemingly, the cookies of securly expire after a bit and so youll have to redo the exploit, if you want to do it faster you can bookmark the link and the javascript (remember to remove the x) and click one after the other!
    <h3>Why "securly.com.webcr.top"?</h3>
      when securly checks a domain, it sends a request to securly.com, and to prevent it from checking that request causing an infinite loop, any domain with securly.com inside it will be unblockable!
      <h3>who are you</h3>
      im batman >:3
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
  /*image-rendering: optimizeSpeed;             /* STOP SMOOTHING, GIVE ME SPEED  */
    /*image-rendering: -moz-crisp-edges;          /* Firefox                        */
    /*image-rendering: -o-crisp-edges;            /* Opera                          */
    /*image-rendering: -webkit-optimize-contrast; /* Chrome (and eventually Safari) */
    /*image-rendering: pixelated;                 /* Universal support since 2021   */
    /*image-rendering: optimize-contrast;         /* CSS3 Proposed                  */
    /*-ms-interpolation-mode: nearest-neighbor;   /* IE8+                           */

  background-image: url('https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/c3c11a4e-961b-47ec-8f72-acebce4c4562/dgd7lna-ac16f51b-e974-4b8b-b354-66bb9888ad37.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2MzYzExYTRlLTk2MWItNDdlYy04ZjcyLWFjZWJjZTRjNDU2MlwvZGdkN2xuYS1hYzE2ZjUxYi1lOTc0LTRiOGItYjM1NC02NmJiOTg4OGFkMzcucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.ZktKEgi_XeABq25KljzOESRh6vMPb-MIJH0D9xufths');
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
