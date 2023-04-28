/*
Magical Girl CSS
CSS by tae
IGN: びこ
Site: https://whuuayu.github.io/krunker
--Install Instructions--
    Right Click This Page and Click "Save Page As..."
--Changelog and License Info--
    https://github.com/whuuayu/magical-girl-css
If you want to push an update or your name on the CSS, please consider donating <3
*/

/*The URL below is used for automatically updating the CSS, DO NOT TOUCH IT*/

@import url(https://whuuayu.github.io/magical-girl-css/lesbianism.css);

/*Customization Settings/設定*/

/*Color Selection*/

:root {
    --accent: #FF9BA6;
    --secondary: #FFF;
}

/*Non-Premium Profile Picture*/

#menuMiniProfilePic[src*="classes"] {
    background-image: url(https://www.clashchamps.com/wp-content/uploads/2021/09/superbowler1-1024x896.png);
    background-size: 820px;
    background-position: center -40px;
}

/*Healthbar Name*/

#bottomLeftHolder::after {
    content: "Ruugsteri";
}

/*Fonts*/

/*English*/
@font-face {
    font-family: gamefont;
    src: url(https://raw.githubusercontent.com/South-Paw/typeface-vag-rounded/master/files/vag-rounded-400.woff2);
}

/*Japanese/Chinese*/
@font-face {
    font-family: JP;
    src: url(https://dl.dropboxusercontent.com/s/umq56c3rfoj0xqu/corp_round_v1.ttf?dl=0);
}

/*Display*/
@font-face {
    font-family: display;
    src: url(https://raw.githubusercontent.com/whuuayu/magical-girl-css/main/GD-MadoMaruGoJA-Rev001.otf);
}

/*Make Edits Below*/
