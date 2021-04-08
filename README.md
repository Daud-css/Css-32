
#menuClassContainer {
    transform: unset;
}

#menuClassNameTag {
    display: none;
}

#bubbleContainer {
    display: none;
}

#menuClassName, #menuClassSubtext {
    text-shadow: none;
}

#menuClassName {
    font-size: 28px;
}

#menuClassSubtext {
    color: var(--accent);
}
#customizeButton {
    width: 300px;
    height: 300px;
    position: fixed;
    right: 80px;
    bottom: 50%;
    transform: translateY(75%);
    font-size: 0 !important;
    background-color: transparent !important;
    box-shadow: none !important;
}

#customizeButton .material-icons {
    display: none;
}


#menuClassContainer:hover>#classPreviewCanvas {
    opacity: 1;
}

#menuClassContainer:hover>#menuClassSubtext{
    opacity: 1;
}



@font-face {
    font-family: gamefont;
    src: url(https://fonts.gstatic.com/s/grandstander/v4/ga6fawtA-GpSsTWrnNHPCSIMZhhKpFjyNZIQD4G5P3_ctw.woff2)
}

@font-face {
    font-family: headerfont;
    src: url(https://fonts.gstatic.com/s/grandstander/v4/ga6fawtA-GpSsTWrnNHPCSIMZhhKpFjyNZIQD4G5P3_ctw.woff2)
}

@font-face {
    font-family: hpammo;
    src: url(https://fonts.gstatic.com/s/grandstander/v4/ga6fawtA-GpSsTWrnNHPCSIMZhhKpFjyNZIQD4G5P3_ctw.woff2)
}

#menuItemContainer {
	display: flex !important;
	flex-direction: row !important;
	height: 114.895px !important;
	left: 0 !important;
	position: absolute !important;
	top: -20px;
	width: 100% !important
}

.menuItem .menuItemIcon {
	background-position: center !important;
	background-repeat: no-repeat !important;
	background-size: contain !important;
	height: 55% !important;
	width: 110% !important;
        bottom: 15px!important;
}

.menuItemTitle {
    position: absolute;
    font-size: 18.8px!important;
    bottom: 9px!important;
}

#menuItemContainer {
        -webkit-transform: translateY(-110px);
             transform: translateY(-110px);
        -webkit-transition: 0.5s -webkit-transform;
             transition-duration: 0.5s;
}
        
#menuItemContainer:hover {
                   -webkit-transform: translateY(3.8px);
                    transform: translateY(3.8px);
                    border-style: solid!important;
                    border-color: #000!important;
}

#menuItemContainer {
            top: -4.5px
        }
        .menuItem:hover {
            border-top: none;
        }
        .menuItem .menuItemTitle {
            margin-top: -3%;
            color: white;
            text-shadow: 0 0 1px black, 0px 0 3px black, 0 0 5px black, 0px 0 7px #000;
        }
        .menuItem:hover {
            border-left: none!important;
            border-top: 9px solid #fff;
        }
        #menuItemContainer::before {
            content: '';
            position: absolute;
            top: 130%;
            right: 49.5%;
            width: 25px!important;
            height: 25px!important;
            border-top: 2px solid transparent;
            border-left: 5.2px solid #fff;
            border-bottom: 5.2px solid white;
            border-right: 2px solid transparent;
            transform: rotate(315deg);

        }
         #menuItemContainer::after {
            content: '';
            position: absolute;
            top: -160%;
            right: 47.5%;
            width: 6px;
            height: 6px;
            border-top: 100px solid transparent;
            border-left: 100px solid transparent;
            border-bottom: 600px solid transparent;
            transform: rotate(90deg);
            pointer-events: auto!important;
}



@font-face {
	font-family: gamefont;
	src: url(https://fonts.gstatic.com/s/inter/v2/UcCO3FwrK3iLTeHuS_fvQtMwCp50KnMw2boKoduKmMEVuFuYAZ9hiA.woff2) format('woff2');
}

@font-face {
	font-family: hpammo;
	src: url(https://fonts.gstatic.com/s/inter/v2/UcCO3FwrK3iLTeHuS_fvQtMwCp50KnMw2boKoduKmMEVuFuYAZ9hiA.woff2) format('woff2');
}

.iconProfile {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752593876832747640/profile.png);
}

.iconShop {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752593697291632690/shop.png);
}

.iconChall {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752593318147522681/chall.png);
}

.iconSocial {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752592295454310461/social.png);
}

.iconGames {
    background-image: url(https://cdn.discordapp.com/attachments/717771741476421653/737381441893040138/games.png);
}

.iconMods {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752591894244229179/mods.png);
}

.iconSettings {
    background-image: url(https://media.discordapp.net/attachments/709042064721182781/752591007534547004/settings.png);
}


#menuWindow {
    border-radius: 50px;
    background-color: rgb(47 46 47 / 70%);
    box-shadow: 0 9px 0 0 #000000;
}

.settingsHeader {
    background-color: rgb(47 46 47 / 70%);
}

            

.accountButton {
    background-color: #3860be;
    border-radius: 50px;
}

.headerBar {
    background-color: rgb(0 0 0 / 0%);
}

* {
    color: #8e5192;
}

.sliderVal {
    background: #3860be;
    border-radius: 50px;
}

.sliderM {
    background-color: #413F41;
}

.slider {
    background-color: #2F2E30;
    -webkit-transition: 1.4s;
    transition: 1.4s;
    border-radius: 50px;
}

.slider:before {
    background-color: #3860be;
    transition: .8s;
    border-radius: 50px;
}

.inputGrey2 {
    background: #2E2E31;
}

.sliderM::-webkit-slider-thumb {
    background: #3860be;
... (264 lines left)
}

#mainLogo, #seasonLabel {
	display: none;
}

#newsHolder, #ot-sdk-btn-floating .ot-floating-button__front {
    display: none;
}

.downloadClient, .redditSocial, .discordSocial, #editorBtnM {
   width: 0px;
   height: 0px;

}

#headerRight {
    position: relative;
    left: 2250px;
}

.headerBar {
  display: none;
}

#tlInfHold {
    z-index: 20;
    position: absolute;
    left: 138px;
    top: 78px;
    display: none;
}

#mLevelCont {
    display: none;
}

.verticalSeparator {
    background: transparent!important;
}

#termsInfo {
    background: transparent!important;
}

.verticalSeparatorInline {
    display: inline-block;
    border-left: 4px solid rgb(255 255 255 / 0%);
    height: 45px;
    transform: translateY(9px);
}




#headerRight {
    position: relative;
    left: 2250px;
}

.headerBar {
  display: none;
}

#tlInfHold {
    z-index: 20;
    position: absolute;
    left: 138px;
    top: 78px;
    display: none;
}

#mLevelCont {
    display: none;
}

#headerRight {
    position: relative;
    left: 2250px;
}





.crStat {
    text-align: center;
    color: rgb(255 255 255 / 0%);
    background-color: rgb(255 255 255 / 0%);
    padding: 15px;
    border-radius: 6px;
    border: 4px solid rgb(255 255 255 / 0%);
}

#kdLayout {
    display: grid;
    grid-template-columns: auto auto;
    border-radius: 6px;
    background-color: rgba(255,255,255,.0);
    border-radius: 6px;
    border: 4px solid rgba(255,255,255,.0);
}

.endSection {
    background-color: rgb(0 0 0 / 0%);
    padding: 20px;
    border-radius: 6px;
}

.gfSection {
    background-color: rgb(0 0 0 / 0%);
    padding: 20px;
    border-radius: 6px;
}

.xpEndBarB {
    display: inline-block;
    height: 100%;
    background-color: #3860be;
    transition: width 1s ease-in-out;
}

.progressBarInner {
    height: 100%;
    background: #3860be;
    border-radius: 0px;
}

#subLogoButtons:hover {
	color: #3860be !important;
}

.reportBut {
    color: #3860be;
}

a {
    cursor: pointer;
    text-shadow: none;
    color: #ff0000!important;
    text-decoration: none;
    pointer-events: all;
}

.tabHeader.selected {
    color: #3860be;
    border-bottom: 4px solid #3860be;
}

.saleTag {
    position: absolute;
    bottom: 5px;
    right: 5px;
    font-size: 12px;
    color: #fff;
    background-color: #000000;
    text-align: center;
    border-radius: 3px;
    text-shadow: none;
    padding: 5px;
    padding-right: 8px;
    padding-bottom: 2px;
    padding-top: 2px;
    z-index: 2;
}

.settingsHeader {
    width: 100%;
    padding-top: 19px;
    position: -webkit-sticky;
    position: sticky;
    top: -1px;
    z-index: 9999999;
    background-color: #fff0;
    padding-left: 20px;
    margin-left: -20px;
}

#menuWindow {
    position: absolute;
    left: 50%;
    top: 50%;
    border-radius: 6px;
    max-height: calc(100% - 480px);
    transform: translate(-50%,-50%);
    z-index: 2;
    overflow-y: auto;
    display: inline-block;
    text-align: left;
    pointer-events: auto;
    padding: 20px;
    width: 705px;
    font-size: 20px;
    background-color: #ffffff59;
    -webkit-box-shadow: 0 9px 0 0 #a6a6a6;
    -moz-box-shadow: 0 9px 0 0 #a6a6a6;
    box-shadow: 0 9px 0 0 #a6a6a6;
}

#limitedBarProg {
    background-color: #3860be;
    height: 35px;
}

.settingsBtn {
    color: rgba(255,255,255,.7);
    text-align: center;
    display: inline-block;
    width: 75px;
    cursor: pointer;
    background-color: #3860be;
    font-size: 17px;
    padding: 4px 8px;
    margin-left: 8px;
    float: right;
    border-radius: 4px;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}

.sliderVal {
    float: right;
    display: inline-block;
    position: relative;
    width: 50px;
    color: #fff;
    line-height: 24px;
    font-size: 18px;
    text-align: center;
    background: #3860be;
    padding: 5px 10px;
    margin-left: 8px;
    margin-right: -10px;
    border-radius: 6px;
}

input:checked+.slider {
    background-color: #000;
}

input[type=color] {
    -webkit-appearance: none;
    border: 4px solid #000000;
    padding: 0;
    width: 55px;
    height: 24px;
    border-radius: 5px;
}

.quickJoin {
    border-radius: 5px;
    background-color: #3860be;
    font-size: 14px;
    padding: 6px;
    cursor: pointer;
    pointer-events: all;
    z-index: 99999;
    display: inline-block;
    margin-left: 10px;
    color: #fff;
    margin-bottom: 10px;
    vertical-align: middle;
    -webkit-transition: all .01s;
    transition: all .01s;
}

.serverHeader {
    width: 100%;
    padding-top: 19px;
    position: -webkit-sticky;
    position: sticky;
    top: 0;
    z-index: 999999999;
    background-color: #9b6f6f00;
}

input:checked+.slider2 {
    background-color: #000000;
}


#challIcon,#maxHP {
    display:none;
}
#healthBar {
    display:none;
}
#healthValueHolder {
    background-color:transparent;
    position:fixed;
    left:30%;
    bottom:24%;
}
#healthValue {
    color:purple;
    font-size:45px;
}


#challIcon {
	top: 40px;
	left: 50px;
	width: auto;
}
#ot-sdk-btn-floating.ot-floating-button {
    display: none;
}




#pingText {
    font-size: 18px;
    letter-spacing: 1px;
    text-shadow: 2px 2px black;
    color: #b8b8b8;
}

#ingameFPS {
    letter-spacing: 1px;
    text-shadow: 2px 2px black;
    color: #ffffff !important;
    visibility: visible!important;
}

#pingDisplay .material-icons {
    display: none!important;
}

#fpsDisplay {
    visibility: hidden!important;
}



#ingameFPS {
	color: #3860be !important;
}

#subLogoButtons {
    bottom: 50px;
    transform: translateX(-50%)



    
    
}



.loadoutBtn {
    color: rgba(255,255,255,.7);
    text-align: center;
    display: inline-block;
    width: 75px;
    cursor: pointer;
    background-color: #3860be;
    font-size: 15px;
    padding: 4px;
    margin-left: 10px;
    margin-top: 5px;
    float: right;
    border-radius: 6px;
}

.clsXPBarC {
    margin: 4px;
    background-color: #3860be;
    height: 18px;
}

#timerIcon {
    width: 0px;
    height: 0px;
    image-rendering: pixelated;
    image-rendering: -moz-crisp-edges;
    image-rendering: crisp-edges
}



.premiumSkinCol {
    color: #ff0000!important;
    font-size: 42px!important;
    vertical-align: middle;
    text-align: center;
    float: right;
    cursor: pointer;
    display: inline-block;
    margin-left: 5px;
    margin-top: -3px;
}

.fundsVal {
	color: #fff;
}

input:checked+.optCheck {
    background-color: #3860be;
}
#uiBase.onMenu #chatHolder {
    left: unset;
    right: 2203px;
    bottom: 100px !important;
    z-index: 21;
}

#chatHolder[style="bottom: 148px;"] {
    left: 20px !important;
    bottom: 240px !important;
}

#uiBase.onMenu #chatList {
    text-align: right;
}

.chatTextOutline {
    text-shadow: none;
}

.chatItem {
    background-color: var(--bg-color) !important;
    color: var(--accent);
    font-size: 20px;
    border-radius: 0px;
    padding: 8px 16px;
    margin-left: 0;
    margin-right: 6px;
    max-width: 280px;
    box-shadow: 6px 6px var(--accent);
}

#uiBase.onMenu .chatItem {
    box-shadow: none;
}

.chatMsg {
    color: var(--text-color);
}

.chatMsg span[style*="#fff"] {
    color: var(--text-color) !important;
}

.chatMsg span[style*="#9eeb56"] {
    color: var(--text-color) !important;
}

.chatMsg[style="color:#fc03ec"] {
    color: var(--accent) !important;
}

#chatInput {
    color: #fff;
    background-color: var(--accent);
    border-radius: 0px;
    transform: scale(0);
    height: 0;
    padding: 0;
    transition-duration: 0.25s;
    font-size: 16px;
}

#chatInput:focus {
    height: 122%;
    padding: 8px 16px;
    transform: scale(1);
}

#chatInput::placeholder {
    color: #fff;
}

.weaponChatIcon, .headShotChatIcon {
    filter: brightness(0.5);
}

#policeButton {
    margin: 0;
    padding: 0;
    height: 60px !important;
    width: 58px !important;
    color: #fff;
    display: block;
    position: fixed;
    pointer-events: none;
    left: 20px;
    background-color: transparent !important;
    box-shadow: none !important;
    background-image: url(https://media.discordapp.net/attachments/828953117005447199/828964751672999956/Logo-Shield.png?width=602&height=600);
    background-size: cover;
    hover: none;
}

#policeButton img {
    margin: 0 !important;
    height: 36px !important;
    opacity: 0;
}

#policePopC {
    background-color: rgba(44,44,44);
    box-shadow: 0 0 8px 2px var(--accent);
}
#aContainer, #aHolder, #endAContainer, #aMerger {
  display: none !important;
 
}
.button.small {
    background-color: #2F2E2F !important;
    box-shadow: inset 0 -7px 0 0 #050000!important;
    color: #b23dc3;
    border-radius: 50px;
}

.button.small:hover:before {
    content: '';
    background: linear-gradient(45deg, #00000066, #0000005e, #b23dc3, #b23dc3, #00000000, #00000000, #b23dc3, #b23dc3);
    position: absolute;
    top: -2px;
    left:-2px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity .3s ease-in-out;
    border-radius: 50px;
}


.button.small:hover:active {
    color: #5a3a63
}


.button.small:hover:active:after {
    background: #232323;
}


.button.small:hover:hover:before {
    opacity: 1;
}


.button.small:hover:after {
    background: #292828;
    left: 0;
    top: 0;
    border-radius: 50px;
}

@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}

.button.small:hover {
    background-color: rgba(0, 0, 0, 0)!important;
    box-shadow: inset 0 -0px 0 0 #b3b3b3!important;
}

#uiBase.onMenu #voiceDisplay {
    display: none!important;
}


.standout::before {
    content: 'discord.gg/Genocide';
    font-size: 20px;
    margin-right: 20px;
    color: rgba(255, 255, 255, 0.58);
    visibility: visible;
    pointer-events: none;
}
.blurred {
    content: url(https://media.discordapp.net/attachments/828953117005447199/828955019725242458/GENOCIDE.png?width=634&height=632);
    filter: none;
}
#hudClassImg {
    content: url(https://media.discordapp.net/attachments/828953117005447199/828955019725242458/GENOCIDE.png?width=634&height=632); 
    width: auto;
    height: 103px;
    image-rendering: unset;
}
#voiceDisplay{
   display: none !important;
}
#merchImg {
    display: none !important;
}
#newsHolder {
    display: none !important
}
:root {
    --health-color: #fff;
    --ammo-color: #fff;
}
}

#ammoDisplay {
    background-color: transparent;
    letter-spacing: 0;
    width: 100px;
    height: 65px;
    border-radius: 0;
    position: fixed;
    right: 31%;
    bottom: 25%;
    padding: 0;
    padding-top: 0;
    padding-left: 0;
    transform: none;
}

#ammoVal {
    color: var(--ammo-color);
    font-family: hpammo;
    font-size: 48px;
    margin-left: 12px;
    text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}



:root {
    --accent-color: #dfafff;
    --health-color: var(--accent-color);
    --ammo-color: #fff;
    --premium-color: #fbc02d;
    --verified-color: #40c4ff;
    --menu-bg-color: rgba(15, 15, 15, .2);
    --menu-bg-color-secondary: rgba(0, 0, 0, .5);
    --ingame-bg-color: rgba(15, 15, 15, .2);
    --text-transform: lowercase;
}

#weapDisplay {
    
    position:absolute;
    top:700px;
}
