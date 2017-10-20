<!DOCTYPE html>
<head>
 
 
<title>{Title}</title>
 
<link rel="shortcut icon" href="{Favicon}">
<link rel="alternate" type="application/rss+xml" href="{RSS}">
{block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
 
<!--Default Variables-->
 
<meta name="color:Background" content="#f4f4f4"/>
<meta name="color:Container" content="#ffffff"/>
<meta name="color:Text" content="#a0a0a0"/>
<meta name="color:Link" content="#000000"/>
<meta name="color:Link Hover" content="#aoaoao"/>
<meta name="color:Border" content="#e3e3e3"/>
<meta name="color:Header Title" content="#000000"/>
<meta name="color:Post info" content="#aoaoao"/>
 
<meta name="image:Background" content=""/>
<meta name="image:Icon" content=""/>
<meta name="image:Header" content=""/>
<meta name="image:Header Icon" content=""/>
 
<meta name="text:Subtitle" content="Subtitle" />
<meta name="text:Links Title" content="Links" />
<meta name="text:Members Title" content="Members" />
<meta name="text:Affiliates Title" content="Affiliates" />
<meta name="text:Updates Title" content="Updates" />
<meta name="text:Projects Title" content="Projects" />
<meta name="text:Official Links Title" content="Official Links" />
<meta name="text:Extra Title" content="Extra" />
<meta name="text:Extra Box Content" content="lorem ipsum" />
 
<meta name="text:Link 1" content="Home" />
<meta name="text:Link 1 URL" content="/" />
<meta name="text:Link 2" content="Ask" />
<meta name="text:Link 2 URL" content="/ask" />
<meta name="text:Link 3" content="Archive" />
<meta name="text:Link 3 URL" content="/archive" />
<meta name="text:Link 4" content="" />
<meta name="text:Link 4 URL" content="/" />
<meta name="text:Link 5" content="" />
<meta name="text:Link 5 URL" content="/" />
<meta name="text:Link 6" content="" />
<meta name="text:Link 6 URL" content="/" />
<meta name="text:Link 7" content="" />
<meta name="text:Link 7 URL" content="/" />
<meta name="text:Link 8" content="" />
<meta name="text:Link 8 URL" content="/" />
 
<meta name="select:Post Width" content="350" title="350px">
<meta name="select:Post Width" content="375" title="375px">
<meta name="select:Post Width" content="400" title="400px">
<meta name="select:Post Width" content="425" title="425px">
<meta name="select:Post Width" content="450" title="450px">
<meta name="select:Post Width" content="475" title="475px">
<meta name="select:Post Width" content="500" title="500px">
<meta name="select:Post Width" content="540" title="540px">
 
<meta name="select:Photoset Gutter" content="1" title="1px">
<meta name="select:Photoset Gutter" content="2" title="2px">
<meta name="select:Photoset Gutter" content="5" title="5px">
<meta name="select:Photoset Gutter" content="10" title="10px">
 
<meta name="select:Sidebar Width" content="180" title="180px">
<meta name="select:Sidebar Width" content="200" title="200px">
<meta name="select:Sidebar Width" content="220" title="220px">
 
<meta name="select:Title Font" content="Raleway" title="Raleway">
<meta name="select:Title Font" content="Montserrat" title="Montserrat">
<meta name="select:Title Font" content="Playfair Display" title="Playfair Display">
 
<meta name="select:Font" content="Abeezee" title="Abeezee">
<meta name="select:Font" content="Lora" title="Lora">
<meta name="select:Font" content="PT Sans" title="PT Sans">
<meta name="select:Font" content="Karla" title="Karla">
<meta name="select:Font" content="Noto Sans" title="Noto Sans">
 
<meta name="select:font size" title="Small" content="60%">
<meta name="select:font size" title="Medium" content="70%">
<meta name="select:font size" title="Large" content="80%">
 
<meta name="if:show captions" content="1">
<meta name="if:show tags" content="1">
<meta name="if:circular icons" content="1">
<meta name="if:show header" content="1">
<meta name="if:show icon" content="1">
<meta name="if:show title" content="1">
<meta name="if:show description" content="1">
<meta name="if:show links" content="1">
<meta name="if:show search" content="1">
<meta name="if:show members" content="1">
<meta name="if:show affiliates" content="1">
<meta name="if:show updates" content="1">
<meta name="if:show projects" content="1">
<meta name="if:show social icons" content="1">
<meta name="if:show extra box" content="1">
<meta name="if:full size bg" content="1">
 
 
<style type="text/css">
 
#s-m-t-tooltip{
    position:absolute;
    margin: 5px 0 0 15px;
    z-index:9999;
    background:{color:link};
    color:{color:container};
    padding:4px 6px 4px 6px;
}
 
::-webkit-scrollbar {
width: 11px;height: 0px;}
::-webkit-scrollbar-button:start:decrement,
::-webkit-scrollbar-button:end:increment {
height: 0px;display: block;background-color: {color:background};}
::-webkit-scrollbar-track-piece {
background-color: {color:background};}
::-webkit-scrollbar-thumb:vertical {
    height: 0px;
    background-color: {color:text};
    border:5px solid {color:background};
}
 
 
iframe.tmblr-iframe {
    z-index:99999999999999!important;
}
 
/*basics*/
 
blockquote {
    padding:0px 0 0px 15px;
    border-left:1px solid {color:border};
    margin:0 0 0 10px;
}
.tumblr_parent {
  margin:0;
  padding: 15px 15px 10px 15px;
  border: 1px solid {color:border};
  border-bottom:0px solid {color:border};
}
.tumblr_parent blockquote{
  margin:10px 0 0 0;
  padding:0 0 0 15px;
  border-left: 1px solid {color:border};
}
.tumblr_avatar {
  width:16px;
  border-radius:16px;
  margin: 0 10px -4px 0;
}
 
body {
    background:{color:background} url('{image:background}');
    background-attachment: fixed;
    {block:Iffullsizebg}
    background-size:cover;
    {/block:Iffullsizebg}
    color:{color:text};
    font-family:{select:font}, helvetica;
    font-size: {select:font size};
    text-align:left;
    margin:0;
    line-height:130%;
}
 
a {
    color:{color:link};
    text-decoration:none;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
a:hover {
    text-decoration:none;
    color:{color:link hover};
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
img{
    opacity:1;
    border:none;
    text-decoration:none;
    max-width:100%;
}
.image img{
    width:{select:post width}px;
}
small {
    font-size:.9em;
}
big {
    font-size:1.2em;
}
 
h1{
    font-size:.8em;
    font-weight:bold;
    text-transform:uppercase;
    text-align:center;
}
 
.ln{
    display:inline-block;
    width:70px;
    height:0;
    border-bottom:1px solid {color:border};
    margin:10px 0 2px 0;
}
 
.pln{
    display:inline-block;
    width:{select:post width}px;
    height:0;
    border-bottom:1px solid {color:border};
    margin:10px 0 2px 0;
}
 
.title {
    font-size:1.7em;
    margin-bottom:10px;
    text-align:left;
    font-family:{select:title font}, {select:font}, helvetica;
}
 
/*sidebar*/
#sidebar {
    text-align:center;
    position:fixed;
    height:calc(100vh - 40px);
    margin-left:calc(({select:sidebar width}px + 75px) * -1);
    padding:15px;
    width:{select:sidebar width}px;
    background:{color:container};
    border-right:1px solid {color:border};
    overflow:scroll;
}
#sidebar::-webkit-scrollbar {
width: 11px;height: 0px;}
#sidebar::-webkit-scrollbar-button:start:decrement,
#sidebar::-webkit-scrollbar-button:end:increment {
height: 0px;display: block;background-color: {color:container};}
#sidebar::-webkit-scrollbar-track-piece {
background-color: {color:container};}
#sidebar::-webkit-scrollbar-thumb:vertical {
    height: 0px;
    background-color: {color:border};
    border:5px solid {color:container};
}
 
 
#sidebarim {
    margin:10px;
}
 
#sidebarim img {
    width:50px;
    display:inline-block;
    {block:Ifcircularicons}
    border-radius:50px;
    {/block:Ifcircularicons}
    {block:Ifnotcircularicons}
    border-radius:4px;
    {/block:Ifnotcircularicons}
}
 
#blogt {
    font-size:1.8em;
    font-family: {select:title font}, {select:font}, helvetica;
    margin:0 0 0px 0;
    line-height:100%;
    {block:Ifnotshowicon}
    margin-top:15px;
    {/block:Ifnotshowicon}
}
#blogt a{
    color:{color:text};
}
 
#links {
    margin:-5px 0 5px 0;
    text-transform:lowercase;
}
#links a{
    width:70px;
    display:inline-block;
}
 
#description {
    margin:5px 0;
}
 
.members{
    margin:0;
    line-height:18px;
}
.members img{
    width:20px;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:20px;
    {block:Ifcircularicons}
    opacity:.8;
    margin:0 2px 0 2px;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
.members img:hover{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.affil{
    margin:0;
    line-height:18px;
}
.affil img{
    width:25px;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:50px;
    {block:Ifcircularicons}
    opacity:.8;
    margin:0 2px 0 2px;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
.affil img:hover{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.updates{
    margin:0 10px 0 10px;
    font-size:.9em;
}
.ud{
    text-align:left;
}
.ud .d{
    display:inline-block;
    float:left;
    width:33px;
    text-transform:uppercase;
    font-weight:bold;
    font-size:.8em;
}
 
.social a{
    font-size:1.3em;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
.si{
    display:inline-block;
    border:1px solid {color:border};
    padding: 3px 3px 1px 3px;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:50px;
    {block:Ifcircularicons}
    margin:0 2px 0 2px;
    width:1.05em;
    line-height:120%;
}
 
.proj{
    margin:0;
    line-height:18px;
}
 
.proj img{
    width:30px;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:50px;
    {block:Ifcircularicons}
    opacity:.8;
    margin:0 2px 0 2px;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
.proj img:hover{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.txt{}
 
.search{
    text-align:center;
}
.sbox{
    border:none;
    width:150px;
    text-transform:lowercase;
    font-family:{select:font}, helvetica;
    color:{color:text};
    height:12px;
    text-align:center;
    font-size:.9em;
    outline: none;
    margin:0;
}
.sbutton{
    border:none;
    background:{color:posts};
    padding:0;
    margin:0;
    opacity:0;
    height:0;
    width:0;
}
 
/*pagination*/
#pagination {
    position:fixed;
    bottom:0px;
    margin:0 -15px 0 -15px;
    padding:10px 15px 15px 15px;
    background:{color:container};
    z-index:99999;
    width:{select:sidebar width}px;
    text-align:center;
    word-spacing:8px;
}
#pagination a {
    padding:2px 5px 2px 5px;
    border:1px solid {color:border};
    {block:Ifcircularicons}
    border-radius:50px;
    {/block:Ifcircularicons}
    {block:Ifnotcircularicons}
    border-radius:4px;
    {/block:Ifnotcircularicons}
    margin:0 3px 0 0;
}
 
.headerimg{
    width:calc({select:post width}px + 90px);
    margin:0 -45px 0 -45px;
    height:100vh;
    max-height:100vh;
    overflow:hidden;
    text-align:center;
    background:url('{image:header}');
    background-size:cover;
}
 
.headerimg .logo{
    display:inline-block;
    width:150px;
    margin-top:calc(50vh - 100px);
}
 
.subtitle{
    font-size:1.9em;
    line-height:120%;
    font-weight:500;
    margin:0 80px 0 80px;
    font-family:{select:title font}, {select:font}, helvetica;
    color:{color:header title};
}
 
.down{
    font-size:3em;
    margin-top:35vh;
}
.down a{
    color:{color:header title};
}
 
/*container*/
#con {
    left:50%;
    padding:0 45px 0 45px;
    margin-left: calc((({select:post width}px - 110px) / 2) * -1);
    position:absolute;
    background:{color:container};
    border-left:1px solid {color:border};
}
 
 
/*posts*/
 
#entries {
    margin:0px 0 100px 0;
    width:{select:post width}px;
    overflow:hidden;
    min-height:calc(100vh - 100px);
    text-align:center;
}
 
.post {
    text-align:left;
    margin:40px 0 20px 0;
    {block:PermalinkPage}
    margin-bottom:50px;
    {/block:PermalinkPage}
}
.post img {
    max-width:100%;
}
 
.post img, .post li, .post blockquote {max-width: 100%;}
 
.caption {
    margin-top:6px;
    border-bottom:1px solid {color:border};
}
 
.caption img{
    max-width:100%;
    height:auto;
}
 
/*quote*/
 
.titlequote{
    font-size:1.8em;
    line-height:130%;
    font-family:{select:title font}, {select:font}, helvetica;
}
.source {
    margin:15px 0 25px 0;
    text-align:center;
}
 
 
/* ----- AUDIO ------ */
 
.audio {
    text-align: left;
    min-height:80px;
    margin:0 0 10px 0;
    z-index:0;
}
.spotify_audio_player {
     height: 80px !important;
     width:{select:post width}px;
     float:left;
     position:absolute;
     margin-top:-90px;
     border-bottom:4px solid {color:container};
}
.songart{
    position:absolute;
    float:left;
    width:80px;
    height:80px;
    margin:0 10px 0 0;
    border:1px solid {color:border};
    border-radius:3px;
}
.songart img{
    position:absolute;
    width:80px;
    height:80px;
}
.player{
    position:absolute;
    margin-left:25px;
    margin-top:25px;
    height:30px;
    width:30px;
    overflow:hidden;
    z-index:9999;
    opacity:.6;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:20px;
    {block:Ifcircularicons}
    border:1px solid {color:border};
    background:#f2f2f2;
}
.songart:hover .player{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.songinfo{
    position:relative;
    float:right;
    width:calc({select:post width}px - 143px);
    border:1px solid {color:border};
    height:30px;
    padding:25px;
    text-transform:uppercase;
    border-radius:3px;
}
 
.tumblr_audio_player {
    height: 30px;
}
.soundcloud_audio_player{
    margin:-90px 0 0 0;
    z-index:99999;
   
}
 
 
/* VIDEO */
.video{
    width:{select:post width}px;
    max-width:100%;
}
.video-player{
    position: relative;
        padding-bottom: 56.25%; /* 16:9 */
        padding-top: 25px;
        height: 0;
    max-width:{select:post width}px;
}
 
.video-player iframe{
    position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
}
iframe {
    max-width:100%;
}
 
/*asks*/
.q {
    margin-bottom:10px;
    padding:15px;
    border:1px solid {color:border};
    text-align:center;
}
.as {
    display:inline-block;
    font-weight:bold;
    border-bottom:1px solid {color:border};
    padding: 0 0 10px 0;
    margin: 0 0 10px 0;
}
 
/*chat*/
.chat ol {
padding:0;
list-style:none;
}
.line {padding:3px 0;}
 
.label {font-weight:bold;
}
 
 
/*permalink and notes*/
.postinfo {
    margin-top:10px;
    color:{color:post info};
}
 
.postinfo a {
    margin-right:0px;
    color:{color:post info};
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.postinfo a:hover{
    color:{color:link hover};
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.postinfo img{
    display:inline-block;
    margin: 0 6px -5px 2px;
    border-radius:3px;
    {block:Ifcircularicons}
    border-radius:50px;
    {block:Ifcircularicons}
    width:18px;
    opacity:.7;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
    background:{color:border};
}
.postinfo img:hover{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.postinfo .right{
    float:right;
}
 
svg {
   width:10px;
   height:auto;
   opacity:.5;
   padding:1px;
   display:block;
   overflow:visible;
}
.controls a {
   position:relative;
   display:inline-block;
   overflow:hidden;
   padding:5px 3px 3px 3px;
   width:12px;
   height:12px;
}
.controls .reblog {
   opacity:.93;
}
.controls .reblog svg {
   width:9px;
   margin-top:1px;
}
.controls .like .liked + svg {
   opacity:1;
}
.controls .like .liked + svg path {
   fill:#ec5a5a;
}
.controls .like .like_button {
   position:relative;
}
.controls .like .like_button iframe {
   position:absolute;
   top:0;
   left:0;
   bottom:0;
   right:0;
   z-index:2;
   opacity:0;
}
.tags {
    word-break:break-all;
    margin:10px 0 0 4px;
    text-align:left;
    font-size:.9em;
    opacity:.7;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
.tags a{
    margin-left:6px;
}
.post:hover .tags{
    opacity:1;
    -webkit-transition: all .3s; /* Safari */
    transition: all .3s;
}
 
.pagenotes {
    {block:IndexPage}
    display: none!important;
    {/block:IndexPage}
    width:400px;
    text-align:left;
}
 
.pagenotes img {
    display:none!important;
}
.pagenotes li {
    list-style-type:none;
    padding:5px 0px;
    text-align:left;
    margin:0 0 0 -40px;
}
 
.credit{
    position:fixed;
    right:10px;
    bottom:15px;
    background:{color:container};
    padding:2px 4px 2px 4px;
    border:none;
    border-radius:3px;
}
 
{CustomCSS}
 
 
</style>
 
 
 
</head>
 
<body>
 
<div id="con">
 
<div id="sidebar">
 
    {block:Ifshowicon}
        <div id="sidebarim"><a href="/"><img src="{image:Icon}"></a></div>
    {/block:Ifshowicon}
    {block:Ifshowtitle}
        <div id="blogt"><a href="/">{Title}</a></div>
    {/block:Ifshowtitle}
   
   
    <!-- DESCRIPTION SECTION -->
   
    {block:Ifshowdescription}
        <div class="ln"></div>
        <div id="description">{Description}</div>
    {/block:Ifshowdescription}
   
   
    <!-- LINKS SECTION -->
 
    {block:Ifshowlinks}
    <div class="ln"></div>
    <div id="links">
    <h1>{text:links title}</h1>
        {block:ifLink1}<a href="{text:Link 1 URL}">
            {text:Link 1}</a>{/block:ifLink1}
        {block:ifLink2}<a href="{text:Link 2 URL}" >
            {text:Link 2}</a>{/block:ifLink2}
        {block:ifLink3}<a href="{text:Link 3 URL}">
            {text:Link 3}</a> {/block:ifLink3}
        {block:ifLink4}<a href="{text:Link 4 URL}">
            {text:Link 4}</a> {/block:ifLink4}
        {block:ifLink5}<a href="{text:Link 5 URL}">
            {text:Link 5}</a> {/block:ifLink5}
        {block:ifLink6}<a href="{text:Link 6 URL}">
            {text:Link 6}</a> {/block:ifLink6}
        {block:ifLink7}<a href="{text:Link 7 URL}">
            {text:Link 7}</a> {/block:ifLink7}
        {block:ifLink8}<a href="{text:Link 8 URL}">
            {text:Link 8}</a> {/block:ifLink8}
    </div>
    {/block:Ifshowlinks}
   
   
    <!-- SEARCH -->
    {block:Ifshowsearch}
    <div class="search">
            <form action="/search" method="get">
            <input class="sbox" placeholder="Search" type="text" name="q" value="{SearchQuery}" />
            </form>
    </div>
    {/block:Ifshowsearch}
   
   
    <!-- MEMBERS SECTION -->
   
    {block:Ifshowmembers}
    <div class="ln"></div>
    <div class="members">
    <h1>{text:members title}<h1>
        {block:GroupMembers}{block:GroupMember}
        <a href="{GroupMemberURL}" title="{GroupMemberName}">
            <img src="{GroupMemberPortraitURL-24}"></a>
        {/block:GroupMember}{/block:GroupMembers}
        <!--
            to add members manually, copy and paste the below section, and change the urls and text:
           
            <a href="/" title="blogurl">
            <img src="http://68.media.tumblr.com/a4e0674ff8bc51dd760130e450619630/tumblr_oq7s8u0T4Y1vbousjo5_1280.png"></a>
           
            You will also need to delete or hide the everything fro {block:GroupMembers} and {/block:GroupMembers}. (otherwise, the autoatically generated members will also show up.
           
        -->
    </div>
    {/block:Ifshowmembers}
   
   
    <!-- AFFILIATES SECTION -->
   
    {block:Ifshowaffiliates}
    <div class="affil">
    <h1>{text:affiliates title}</h1>
        <a href="/" title="Affiliate One"><img class="affil" src="http://68.media.tumblr.com/616c1a0e09d866a0f7932fe1e5349170/tumblr_oq7s8u0T4Y1vbousjo3_1280.png"></a>
        <a href="/" title="Affiliate Two"><img class="affil" src="http://68.media.tumblr.com/cee9fe3301e90ca430db440eea6e6b84/tumblr_oq7s8u0T4Y1vbousjo2_1280.png"></a>
        <a href="/" title="Affiliate Three"><img class="affil" src="http://68.media.tumblr.com/a4e0674ff8bc51dd760130e450619630/tumblr_oq7s8u0T4Y1vbousjo5_1280.png"></a>
        <!-- example: <a href="link to affiliate's blog" title="Affiliate name"><img class="affil" src="paste image url here"></a>-->
    </div>
    {/block:Ifshowaffiliates}
   
   
    <!-- UPDATES SECTION -->
   
    {block:Ifshowupdates}
    <div class="ln"></div>
    <h1>{text:updates title}</h1>
    <div class="updates">
        <div class="ud"><div class="d">Aug 2</div>New episode</div>
        <div class="ud"><div class="d">Aug 2</div>Another longer update </div>
        <div class="ud"><div class="d">Aug 2</div>New photos</div>
        <!-- example: <div class="ud"><div class="d">DATE</div>update text</div> -->
    </div>
    {/block:Ifshowupdates}
   
   
    <!-- PROJECTS SECTION -->
   
    {block:Ifshowprojects}
    <div class="ln"></div>
    <div class="proj">
    <h1>{text:projects title}</h1>
        <a href="/" title="Project One - Date"><img src="http://68.media.tumblr.com/ee843139aadcb41fa338d57431c5ee9c/tumblr_oq7s8u0T4Y1vbousjo4_1280.png"></a>
        <a href="/" title="Project Two - Date"><img src="http://68.media.tumblr.com/cc54d41899eee2a45d8465ebf7a69e78/tumblr_oq7s8u0T4Y1vbousjo1_1280.png"></a>
        <a href="/" title="Project Three - Date"><img src="http://68.media.tumblr.com/a4e0674ff8bc51dd760130e450619630/tumblr_oq7s8u0T4Y1vbousjo5_1280.png"></a>
        <!-- example: <a href="project link" title="Project title"><img src="image url here"></a> -->
    </div>
    {/block:Ifshowprojects}
   
   
    <!-- OFFICIAL LINKS/SOCIAL SECTION -->
   
    {block:Ifshowsocialicons}
    <div class="ln"></div>
    <div class="social">
    <h1>{text:Official links title}</h1>
        <a href="/"><div class="si"><i class="fa fa-facebook" aria-hidden="true"></i></div></a>
        <a href="/"><div class="si"><i class="fa fa-instagram" aria-hidden="true"></i></div></a>
        <a href="/"><div class="si"><i class="fa fa-twitter" aria-hidden="true"></i></div></a>
        <a href="/"><div class="si"><i class="fa fa-pinterest-p" aria-hidden="true"></i></div></a>
        <a href="/"><div class="si"><i class="fa fa-weibo" aria-hidden="true"></i></div></a>
        <!--
        example: <a href="social media url"><div class="si"><i class="fa fa-twitter" aria-hidden="true"></i></div></a>
        more icons can be found here: http://fontawesome.io/icons/#brand
        just paste the <i class="..."></i>
        -->
    </div>
    {/block:Ifshowsocialicons}
   
    {block:Ifshowextrabox}
    <!-- extra text box -->
    <div class="ln"></div>
    <div class="txt">
        <h1>{text:extra title}</h1>
        {text:extra box content}
    </div>
    {/block:Ifshowextrabox}
 
<div id="pagination">
    {block:Pagination}
        {block:PreviousPage}
        <a href="{PreviousPage}"><i class="fa fa-angle-left" aria-hidden="true"></i></a>
        {/block:PreviousPage}
        {block:JumpPagination length="3"}
        {block:CurrentPage}{PageNumber}{/block:CurrentPage}
        {block:JumpPage}<a href="{URL}">{PageNumber}</a>{/block:JumpPage}
        {/block:JumpPagination}
        {block:NextPage}
        <a href="{NextPage}"><i class="fa fa-angle-right" aria-hidden="true"></i></a>
        {/block:NextPage}
    {/block:Pagination}
</div>
 
</div>
 
{block:IndexPage}
{block:Ifshowheader}
<div class="headerimg">
    <div class="logo"><img src="{image:header icon}"></div>
    <div class="subtitle">{text:subtitle}</div>
    <div class="down"><a href="#top"><i class="fa fa-angle-down" aria-hidden="true"></i></a></div>
</div>
{/block:Ifshowheader}
{/block:IndexPage}
 
 
<a name="top"></a>
<div id="entries">
 
{block:TagPage}Posts tagged "{Tag}"{/block:TagPage}
{block:SearchPage}Results for "{SearchQuery}"{/block:SearchPage}
 
{block:Posts}
<div class="post" id="{PostID}">
 
<!-- QUOTE -->
{block:Quote}
<div class="titlequote">“{Quote}”</div>
{block:Source}<div class="source">{Source}</div>{/block:Source}
{/block:Quote}
 
<!-- TEXT -->
{block:Text}
    {block:Title}
    <div class="title">{Title}</div>{/block:Title}
    {Body}
{/block:Text}
 
{block:Link}
<div class="title"><a href="{URL}">{Name}</a></div>{block:Description}{Description}{/block:Description}
{/block:Link}
 
{block:Chat}
    {block:Title}<div class="title">{Title}</div>{/block:Title}
    <div class="chat">
    <ol>{block:Lines}
    <li class="line {Alt}">
    {block:Label}<span class="label">{Label}</span>{/block:Label}
    {Line}</li>
    {/block:Lines}
    </ol></div>
{/block:Chat}
 
{block:Photo}
    {LinkOpenTag}<div class="image"><img src="{PhotoURL-500}" alt="{PhotoAlt}"/></div>{LinkCloseTag}
{/block:Photo}
 
{block:Photoset}
    <div class="photo-slideshow" id="photoset_{PostID}" data-layout="{PhotosetLayout}">{block:Photos}<div class="photo-data"><div class="pxu-photo"><img src="{PhotoURL-500}" width="{PhotoWidth-500}" height="{PhotoHeight-500}" data-highres="{PhotoURL-HighRes}" data-width="{PhotoWidth-HighRes}" data-height="{PhotoHeight-HighRes}"></div><a class="tumblr-box" rel="post-{PostID}" href="{PhotoURL-HighRes}"></a></div>{/block:Photos}</div>
{/block:Photoset}
 
{block:Video}
<div class="video">
    <div class="video-player">{Video-500}</div>
</div>
{/block:Video}
 
{block:Audio}
<div class="audio">
{block:AudioPlayer}
<div class="songart">
    {block:AlbumArt}
    <img src="{AlbumArtURL}">
    {/block:AlbumArt}
    <div class="player">{AudioPlayerWhite}</div>
</div>
<div class="songinfo">
    {block:TrackName}
    <b>{TrackName}</b>
    {/block:TrackName}
    {block:Artist}
    <br>{Artist}
    {/block:Artist}
</div>
{/block:AudioPlayer}
</div>
{block:AudioEmbed}{AudioEmbed}{/block:AudioEmbed}
{/block:Audio}
 
{block:Answer}
    <div class="q">
    <div class="as">{Asker} asked </div>
    <br/>{Question}</div>
    <div class="caption">{Answer}</div>
{/block:Answer}
 
{block:Ifnotshowcaptions}
    {block:PermalinkPage}
    {block:Caption}
    <div class="caption">{Caption}</div>
    {/block:Caption}
    {/block:PermalinkPage}
{/block:Ifnotshowcaptions}
{block:Ifshowcaptions}
    {block:Caption}
    <div class="caption">{Caption}</div>
    {/block:Caption}
{/block:Ifshowcaptions}
 
{block:Date}
<div class="postinfo">
    <div class="right"><div class="controls">
<a href="{ReblogURL}" target="_blank" class="reblog">
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px" viewBox="0 0 361.095 361.095" style="enable-background:new 0 0 361.095 361.095;" xml:space="preserve"><g><g><path d="M182.595,325.678c-63.183,0-120.133-42.217-138.267-102.567c-2.833-9.067-12.183-14.167-21.25-11.333    c-9.067,2.833-14.167,12.183-11.333,21.25c22.95,75.933,91.517,126.65,170.85,126.65c98.317,0,178.5-80.183,178.5-178.5    s-80.183-178.5-178.5-178.5c-55.817,0-108.233,26.633-141.667,69.7l-7.083-56.1c-1.133-9.35-9.633-15.867-18.983-14.733    C5.511,2.678-1.005,11.178,0.128,20.528l13.317,103.7c1.133,8.5,8.5,14.733,16.717,14.733c0.567,0,1.417,0,1.983,0l102.567-11.617    c9.35-1.133,16.15-9.35,15.017-18.7s-9.35-16.15-18.7-15.017l-68.85,7.65c26.633-39.95,71.683-64.6,120.417-64.6    c79.617,0,144.5,64.883,144.5,144.5S262.211,325.678,182.595,325.678z"/></g></g></svg>
</a>
<a href="#" class="like">{LikeButton}
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px" viewBox="0 0 442.403 442.403" style="enable-background:new 0 0 442.403 442.403;" xml:space="preserve"><g><g><path d="M213.05,422.652c2.833,1.7,5.95,2.833,9.35,2.833c3.117,0,6.517-0.85,9.35-2.833c7.65-5.1,187.283-123.533,207.683-243.95    c10.483-62.333-8.783-100.867-26.633-122.117c-20.967-24.933-52.133-39.667-83.017-39.667c-10.2,0-20.117,1.7-28.9,5.1    c-43.067,16.15-72.25,44.767-88.117,64.317c-15.583-19.267-42.217-47.033-74.517-58.083c-9.917-3.4-20.683-5.1-32.017-5.1    c-28.9,0-56.383,11.9-75.367,32.867c-16.717,18.417-35.7,53.55-29.75,114.75C13.016,291.185,204.833,417.268,213.05,422.652z     M56.083,78.685c17.283-18.983,38.817-21.817,50.15-21.817c7.367,0,14.45,1.133,20.967,3.4    c39.383,13.317,70.833,63.467,71.4,63.75c3.117,5.1,8.783,8.217,14.733,7.933c5.95,0,11.333-3.4,14.45-8.5    c0.283-0.567,28.617-48.733,85.283-69.983c4.817-1.7,10.767-2.833,16.717-2.833c20.967,0,42.217,10.483,56.95,27.767    c19.267,22.667,25.783,55.533,18.983,94.633c-7.367,43.067-42.5,94.633-101.717,149.317c-33.433,30.883-66.3,54.683-81.6,65.45    c-16.15-11.05-51-36.55-86.417-68.85C74.216,262.285,39.366,209.868,35.116,167.368C31.433,128.552,38.516,97.952,56.083,78.685z"/></g></g></svg>
</a>
</div></div><!-- end right and controls -->
   
    {block:RebloggedFrom}
        <a href="{ReblogParentURL}" title="Reblogged from {ReblogParentName}"><img src="{ReblogParentPortraitURL-24}"></a>
        {block:ContentSource}<a href="{ReblogRootURL}" title="Originally from {ReblogRootName}"><img src="{ReblogRootPortraitURL-24}" ></a>{/block:ContentSource}
    {/block:RebloggedFrom}
    <a href="{Permalink}" style="margin: 0 10px;">{TimeAgo}</a>
    {block:NoteCount}<a href="{Permalink}">{NoteCountwithlabel}</a>{/block:NoteCount}
    {block:Ifshowtags}
    {block:HasTags}<div class="tags">
        # {block:Tags}<a href="{TagUrl}">{Tag},</a>{/block:Tags}
    </div>{/block:HasTags}
    {block:Ifshowtags}
   
</div>
{/block:Date}
 
 
 
</div>
 
<div class="pln"></div>
 
{block:PostNotes}
<div class="pagenotes">
{PostNotes}
</div>
{/block:PostNotes}
 
 
{/block:Posts}
</div>
 
</div>
 
<a href="http://neonbikethemes.tumblr.com"><div class="credit">nb</div></a>
 
<!-- SCRIPTS -->
 
<!-- jquery -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.0/jquery.min.js"></script>
 
<!-- fonts -->
<link href="https://fonts.googleapis.com/css?family=ABeeZee|Karla|Lora|PT+Sans|Raleway" rel="stylesheet">
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
<link href="https://fonts.googleapis.com/css?family=Montserrat:700|Playfair+Display:700" rel="stylesheet">
 
<!-- SMOOTH SCROLLING -->
 
<!--<script type="text/javascript" src="http://kryogenix.org/code/browser/smoothscroll/smoothscroll.js"></script>-->
<script type="text/javascript">
$(function() {
  $('a[href*=#]:not([href=#])').click(function() {
    if (location.pathname.replace(/^\//,'') == this.pathname.replace(/^\//,'') && location.hostname == this.hostname) {
      var target = $(this.hash);
      target = target.length ? target : $('[name=' + this.hash.slice(1) +']');
      if (target.length) {
        $('html,body').animate({
          scrollTop: target.offset().top
        }, 1000);
        return false;
      }
    }
  });
});
</script>
 
{block:ContentSource}
<!-- {SourceURL}{block:SourceLogo}<img src="{BlackLogoURL}"
width="{LogoWidth}" height="{LogoHeight}" alt="{SourceTitle}" />
{/block:SourceLogo}
{block:NoSourceLogo}{SourceLink}{/block:NoSourceLogo} -->
{/block:ContentSource}
 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
<script>
// minimal soundcloud player © shythemes.tumblr
$(document).ready(function(){
   var color = '#acd7bb'; // color of play button (hex)
   $('.soundcloud_audio_player').each(function(){
       $(this).attr({ src: $(this).attr('src').split('&')[0] + '&amp;liking=false&amp;sharing=false&amp;auto_play=false&amp;show_comments=false&amp;continuous_play=false&amp;buying=false&amp;show_playcount=false&amp;show_artwork=false&amp;origin=tumblr&amp;color=' + color.split('#')[1], height: 116, width: '100%' });
   });
});
</script>
 
<script src="http://static.tumblr.com/kfhytre/zMuol8wco/unnest.min.js"></script>
<script>
$('.post').unnest({
    yourCaption: '.caption',
    newCaptionUsername: true,
    originalPostCaptionUsername: true,
    tumblrAvatars: true,
    usernameColon: false
});
</script>
 
<!-- pixel union photosets -->
<link href="https://static.tumblr.com/qudkd6d/OcDnl99gb/style.css" rel="stylesheet" type="text/css"/>
<script src="https://static.tumblr.com/qudkd6d/Az6nkemqr/pxuphotoset.min.js"></script>
<script>
$(document).ready(function(){
   $('.photo-slideshow').pxuPhotoset({
       lightbox: true,
       rounded: false,
       gutter: '{select:Photoset Gutter}px',
       borderRadius: '0px',
       photoset: '.photo-slideshow',
       photoWrap: '.photo-data',
       photo: '.pxu-photo'
   });
});
</script>
 
<!--tooltips-->
<script src="http://static.tumblr.com/iuw14ew/VSQma1786/jquery.style-my-tooltips.js"></script>
<script>
(function($){
$(document).ready(function(){
$("a[title]").style_my_tooltips({
tip_follows_cursor:true,
tip_delay_time:30,
tip_fade_speed:300,
attribute:"title"
});
});
})(jQuery);
</script>
 
 
</body></html>
