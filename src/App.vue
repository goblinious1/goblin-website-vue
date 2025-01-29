<template>
  <GlassContainer width="40%"><h1>securly.com.webcr.top</h1>
  currently being worked on, forgive me if things are broken<br>
  also, I'm reading my emails for the first time in a while, send me things!</GlassContainer><br>
  <hr>
  <div class="content" width="100%">
     
    <GlassContainer id="dropdowns">
      <ClickableGlass title="DragMark (USE TO UNBLOCK THIS WEBSITE)" expandable="true" width="90%">
        1. create a bookmark to a link that's blocked (like <a href="securly.com.webcr.top">securly.com.webcr.top</a>) by just editing any bookmark and changing the URL to something<br>
        2. on a non-blocked page, drag the bookmark into the center of the screen<br>
        3. PROFIT!!!
      </ClickableGlass>
      <ClickableGlass title="Cookie Corruption (main unblocking exploit)" expandable="true" width="90%">
        1. create a bookmark for any page, and right click on it and select edit.<br>
        2. paste the text below into the "url" box<br>
        javascript:document.cookie='crextn_clear_cache_at=2024=01-21T05:59:59+00:00;'<br>
        3. when you are on the securly blocked screen, click the bookmark
        
      </ClickableGlass>
     
     
      <ClickableGlass title="Funny little js thingies!" expandable="true" width="90%">
        to use these you gotta make a bookmark, edit it and paste the thing below as the url, then just click the bookmark to activate the thingy<br>
        <ul>
          <h3>website editor</h3>
          <li><input type="text" readonly value="javascript:document.body.contentEditable = true;"></li>
          <h3>the hydraulic press</h3>
          <li><input type="text" readonly value="javascript:(function(){var all=document.getElementsByTagName(&quot;*&quot;);var depth=window.prompt(&quot;What depth should the crushing happen at? [leave empty for default] (how many nested elements does an element need to be considered ineligible for crushing)&quot;);function depthCheck(number,element){if(element.getAttribute(&quot;crushable&quot;)){return true;}if(element.children.length&gt;0){if(number==0){return false;}for(var childIndex=0;childIndex&lt;element.children.length;childIndex++){var childCheck=depthCheck(number-1,element.children[childIndex]);if(childCheck==false){return false;}}}element.setAttribute(&quot;crushable&quot;,&quot;&quot;);return true;}var accel=0.1;var intervalTime=500;var accelRate=1.05;var minInterval=10;for(var i=0,max=all.length;i&lt;max;i++){if(!depthCheck(depth,all[i])){console.log(&quot;Failed Depth Check...&quot;);continue;}console.log(&quot;Depth Check Succeeded:&quot;);var element=all[i];var f=element.getBoundingClientRect();element.style.top=f[&quot;y&quot;]+&quot;px&quot;;element.style.left=f[&quot;x&quot;]+&quot;px&quot;;element.style.width=f[&quot;width&quot;]+&quot;px&quot;;element.style.height=f[&quot;height&quot;]+&quot;px&quot;;element.style.position=&quot;absolute !important&quot;;(function crushElement(l,el){var crushInterval=setInterval(function(){var speed=accel*3/400000+300;console.log(&quot;Crushing at speed:&quot;,speed);el.style.top=Math.max(el.style.top.slice(0,-2)-speed,0)+&quot;px&quot;;el.style.left=Math.max(el.style.left.slice(0,-2)-speed,0)+&quot;px&quot;;el.style.width=Math.max(el.style.width.slice(0,-2)-speed/20,0)+&quot;px&quot;;el.style.height=Math.max(el.style.height.slice(0,-2)-speed/20,0)+&quot;px&quot;;accel+=0.1;intervalTime=Math.max(intervalTime*accelRate,minInterval);if(el.style.width===&quot;0px&quot;&amp;&amp;el.style.height===&quot;0px&quot;){clearInterval(crushInterval);}},intervalTime);})(i,element);}})();"></li>
          <h3>rainbowifier</h3>
          <li><input type="text" readonly value="javascript:(function(){var speed=prompt(&quot;Enter the animation speed in seconds (default is 5):&quot;,&quot;5&quot;);if(speed===null||speed.trim()===&quot;&quot;||isNaN(speed)){speed=5;}var css=`*:not(img):not(svg){background-image:linear-gradient(270deg,#FF0000,#FF7F00,#FFFF00,#00FF00,#0000FF,#4B0082,#8B00FF);animation:rainbow%20${speed}s%20infinite;background-size:400%%20400%;color:white!important;}@keyframes%20rainbow{0%{background-position:0%%2050%;}50%{background-position:100%%2050%;}100%{background-position:0%%2050%;}}%60;var%20style=document.createElement('style');style.appendChild(document.createTextNode(css));document.head.appendChild(style);})();"></li>
          
          </ul>
      </ClickableGlass>
      <ClickableGlass title="onc exploit (LEGACY)" expandable="true" width="90%">
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
          <li> I'm working on adding an onc for a second district</li>
        </ul>
        2. type chrome://network in a new tab and click on import onc file at the bottom.<br>
        3. select the onc file you downloaded in step one from google drive or downloads<br>
        4. hold refresh and hit the power button on your chromebook to quickly restart<br>
        5. Remember to be on <em>-- *TPS-GUEST* --</em><br>
        (OPTIONAL) 6. draw bill cipher to let him inside our dimension and send a picture to me through the contact section below
      
      </ClickableGlass>
      <ClickableGlass title="GoGuardian, Lightspeed, and others">
        work in progress... come back later when the time is right
      </ClickableGlass>
       <ClickableGlass title="contact me! right here! do it here! contact mE HERE THORUGH HERE" expandable="true" width="90%">
        email (CONTACT ONLY FROM PERSONAL EMAIL AND NOT SCHOOL EMAIL) - striped_dibble_0j@icloud.com<br>
        also. i check these like once a year dont expect a fast response lol<br>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeLqEHJD8R4O1glfQbgEHi2gXgLwmu2lgD2R0zSn6Lbm8M4-Q/viewform?usp=sf_link">form for contacting if personal email is not availible</a>
      </ClickableGlass>
    </GlassContainer>
    <GlassContainer block="false" width="350px" height="100%" id="faq">
      <h1>FAQ</h1>
      <h3>why does my exploit undo itself sometimes??</h3>
      seemingly, the cookies of securly expire after a bit and so youll have to redo the exploit, if you want to do it faster you can bookmark the link and the javascript (remember to remove the x) and click one after the other!
    <h3>Why "securly.com.webcr.top"?</h3>
      back in my day having securly.com in your domain name unblockable, that is no longer the case, its now just an artifact of an earlier time
      <h3>who are you</h3>
      im batman >:3
      <h3><img src="https://i.ibb.co/mtqRdcc/rude-paul.jpg" width="10%">?</h3>
      Yes.
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

pre {
  font-family: monospace
  display: block;
  white-space: pre;
  overflow-x: auto;
  max-width: 100%; /* Ensure it doesn't expand beyond the container */
  word-break: break-word; /* Break overly long words if necessary */
  padding: 8px;
  border-radius: 4px;
}
  
ul {
  text-align: left;
}
  
#dropdowns {
  max-width:100%;
  flex:1;
  box-sizing: border-box;
  overflow-x: hidden;
  margin: 25px;
  
}

#faq {
  box-sizing: border-box;
  margin: 25px;
}

.flex {
  display: flex
}
  
.content {
  display: flex;
}
h1 {
  font-size: 50px
}
h2 {}
body {
  overflow-x: hidden;
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
   text-shadow: rgb(20, 20, 20) 0px 0 5px;
  -webkit-text-stroke-color: black;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #cfcfcf;
}
a {
  color: rgb(211, 164, 164)
}
</style>
