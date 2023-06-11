<!DOCTYPE html>
<head>
 
<!--
 
    NETWORK III
        by alydae
 
            - do not steal any part of this code
            - do not even TOUCH the credit
            - direct questions to enchantedthemes.tumblr.com
 
    thank you for using!!!
 
-->
 
<title>members</title>
<link rel="shortcut icon" href="{Favicon}">
 
<!-- scripts - DO NOT TOUCH -->
 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
 
<script src="https://static.tumblr.com/rzl30kg/eAxm7a751/jquery.style-my-tooltips.js"></script>
<script>
   (function($){
       $(document).ready(function(){
           $("[title]").style_my_tooltips({
               tip_follows_cursor:true,
               tip_delay_time:200,
               tip_fade_speed:300
           }
               );
       });
   })(jQuery);
</script>
 
<!-- custom font -->
 
<link href='https://fonts.googleapis.com/css?family=Open+Sans:300,300italic,400,400italic,600,600italic,700,700italic' rel='stylesheet' type='text/css'> 
 
<script src="https://kit.fontawesome.com/4fe045a39a.js" crossorigin="anonymous"></script>
<link rel="stylesheet" href="https://cdn.linearicons.com/free/1.0.0/icon-font.min.css">
 
 
<style type="text/css">
 
@keyframes fadein {
    from { opacity:0; }
    to   { opacity:1; }
}
 
@-moz-keyframes fadein {
    from { opacity:0; }
    to   { opacity:1; }
}
 
@-webkit-keyframes fadein {
    from { opacity:0; }
    to   { opacity:1; }
}
 
@-ms-keyframes fadein {
    from { opacity:0; }
    to   { opacity:1; }
}
 
@-o-keyframes fadein {
    from { opacity:0; }
    to   { opacity:1; }
}
 
/*-- selection --*/
 
::-moz-selection { background:#eee; color:#222; }
::selection { background:#eee; color:#222; }
 
/*-- scrollbar --*/
 
::-webkit-scrollbar {  
    width:1px;  
    height:2px;
}  
 
::-webkit-scrollbar-thumb { background-color:#aaa; } /* scrollbar colour */
 
/*-- tooltips --*/
 
#s-m-t-tooltip {
    color:#666;
    background-color:#fafafa; 
    font-size:8px;
    font-family:'Open Sans', helvetica, sans-serif;
    letter-spacing:1px;
    text-transform:uppercase;
    text-align:center;
    position:absolute;
    padding:0px 5px 0px 5px;
    margin-top:30px;
    border:1px solid #eee;
    z-index:9999;
}
 
/*-- tumblr controls --*/
 
.tmblr-iframe, .iframe-controls–desktop {
    display:none !important;
}
 
/*-- general customisation --*/
 
body {
    color:#666; /* text colour */
    background-color:#fff; /* background colour */
    font-style:normal; 
    font-family:'Open Sans', helvetica, sans-serif; 
    font-size:10px; 
    font-weight:400;
    text-decoration:none; 
    line-height:180%; 
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    font-smoothing: antialiased;
    -webkit-animation: fadein 1.5s;
    -moz-animation: fadein 1.5s;
    -o-animation: fadein 1.5s; 
    animation: fadein 1.5s;
}
 
a {
    text-decoration:none;
    color:#444; /* links colour */
    transition-duration: 0.6s;  
    -moz-transition-duration: 0.6s;  
    -webkit-transition-duration: 0.6s;  
    -o-transition-duration: 0.6s;
}   
 
a:hover {
    color:#bad0f1; /* links hover colour */
    cursor:pointer;
    transition-duration: 0.6s;  
    -moz-transition-duration: 0.6s;  
    -webkit-transition-duration: 0.6s;  
    -o-transition-duration: 0.6s;
}
 
b, strong { font-weight:700; color:#444; }
i, em { font-style:italic; }
 
/*-- sidebar --*/
 
#sidebar {
    position:fixed;
    top:0;
    left:0;
    height:100vh;
    width:64px;
    z-index:999!important;
    background:#fafafa; /* sidebar background colour */
    border-right:1px solid #eee;
}
 
#sidelinks { margin-top:50vh; transform:translateY(-50%); }
 
#sidelinks a {
    display:block;
    font-size:14px;
    line-height:100%;
    height:14px;
    width:14px;
    padding:10px;
    margin:15px;
    border-radius:100%;
    background:#fff; /*sidebar links background colour */
    border:1px solid #eee;
}
 
.hover .hovertext {
    width:auto;
    background:#bad0f1;
    color:#fff; /* sidebar links text colour */
    font-size:10px; /* sidebar links font size */
    text-transform:uppercase;
    font-weight:700;
    letter-spacing:0.5px;
    padding:3px 7px 3px 7px;
    position:absolute;
    margin-top:-3px;
    margin-left:40px; 
    z-index:999!important;
    opacity:0;
    transition:opacity 0.6s;
}
 
.hover:hover .hovertext { opacity:1; transition:opacity 0.6s; }
 
.hover .hovertext::after {
    content:" ";
    position:absolute;
    top:50%;
    right:100%;
    margin-top:-8px;
    border-width:8px;
    border-style:solid;
    border-color:transparent #bad0f1 transparent transparent; /*link hover colour */
}
 
/*-- header --*/
 
header {
    margin:100px auto 50px;
    width:300px;
    text-align:center;
}
 
#icon {
    margin:0 auto;
    width:50px;
    height:50px;
}
 
#icon img { width:50px; height:50px; border-radius:100%; }
 
#title {
    margin:20px 0px 5px 0px;
    font-size:16px;
    font-weight:700;
    text-transform:uppercase;
    letter-spacing:1px;
    color:#000; /*title colour*/
}
 
/*--filters--*/
 
#sort { margin-top:20px; }
 
#sort ul {
    display:block;
    list-style:none; 
    padding-left:0px;
    margin-top:0;
    margin-bottom:0;
}
 
#sort li { display:inline; list-style:none; } 
#sort li a.selected { font-weight:600; color:#222; } /* selected filter colour */
 
#sort a { 
    display:inline; 
    margin-right:10px; 
    font-style:italic; 
    text-transform:lowercase; 
}
 
#sort b { 
    text-transform:uppercase; 
    letter-spacing:0.5px; 
    margin-right:10px; 
}
 
/*-- content --*/
 
#content {
    margin:0 auto;
    margin-bottom:100px;
    width:calc((280px + 40px + 2px) * 3);
    /* ((box width + 2*margin + 2*border width) * number of columns) */
}
 
.box {
    width:280px; /* image width x 2 + 30px */
    height:125px; /* image height */
    margin:20px;
    float:left;
    background:#fafafa; /*box background colour */
    border:1px solid #eee;
}
 
.name {
    width:30px;
    height:125px; /* image height */
    position:absolute;
    line-height:30px;
    transform:rotate(90deg);
    transform-origin:top left;
}
 
.name h1 {
	width:105px; /* image height - 20px */
    float:right; 
    margin-top:-30px; 
    margin-right:-95px;
	padding-left:20px;
    transform:rotate(-180deg); 
    transform-origin:center center;
    text-align:left;
    text-transform:uppercase;
    font-size:12px;
    font-weight:700;
    letter-spacing:0.5px;
	background:#fff;
}
 
.box img {
    position:absolute;
    width:125px; /* image width */
    height:125px; /* image height */
    margin-left:30px;
}
 
.url {
    position:absolute;
    margin-left:155px;
    height:25px;
    width:125px;
    line-height:25px;
    text-align:center;
    background:#fff; /*url background colour */
    font-style:italic;
    font-weight:600;
    border-bottom:1px solid #eee;
	z-index:9;
}
 
.desc {
    position:absolute;
    margin-left:155px;
    margin-top:25px;
    width:125px;
    height:100px;
}
 
.t {
    text-align:center;
    line-height:160%;
    margin-top:10px;
    margin-left:10px;
    margin-bottom:10px;
    padding-right:10px;
    max-height:80px;
    overflow-Y:scroll;
    margin-top:calc(20% + 25px);
    transform:translateY(-50%);
}
 
/*-- credit - DO NOT TOUCH --*/
 
.credit a {
    bottom:15px;
    right:20px;
    position:fixed;
}
 
</style>
</head>
 
 
<body>
 
 
<div id="sidebar">
    <div id="sidelinks">
    <!-- this is where your sidebar links are. feel free to add more. icons can be found at https://linearicons.com/free. -->
        <a class="hover" href="/"><span class="lnr lnr-home"></span><span class="hovertext">index</span></a>
        <a class="hover" href="/ask"><span class="lnr lnr-envelope"></span><span class="hovertext">message</span></a>
        <a class="hover" href=""><span class="lnr lnr-menu"></span><span class="hovertext">link</span></a>
        <!-- do not remove this one!!! -->
        <a class="hover" href="https://enchantedthemes.tumblr.com"><span class="lnr lnr-code"></span><span class="hovertext">credit</span></a>
    </div>
</div>
 
 
<header>
	<!-- the default is your icon. if you want to change it, remove {PortraitURL-128} and replace it with the image url of the one you want -->
    <div id="icon"><img src="{PortraitURL-128}"/></div>
    <div id="title">members</div> <!-- title -->
    <!-- delete this section if you don't want a description-->
    <div class="d">optional description.</div>
    <!-- up to here! -->
 
<!-- HOW TO CUSTOMISE THE FILTERS
template for new filter groups: 
    <ul class="filter option-set" data-filter-group="group1">
    <b>category:</b>
        <li><a href="#" data-filter-value="" class="selected">all</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
    </ul>
 
template for new filter:
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
 
in order to make your filters match your books/tv shows/fic/whatever, you only need to change the '.filter' and 'filter name' part. the 'category' line is optional.
for example, if I wanted to make my media filter by favourites only, my code would look like this
    <li><a href="#" data-filter-value=".fave">favourites</a></li>
note the areas where it's been changed.
 
it is essential that you do not change any other part, including the 'exclusive' in the first filter group, as well as the first filter in every group.
    <li><a href="#" data-filter-value="" class="selected">all</a></li>
-->
 
<div id="sort">
    <ul class="filter option-set exclusive" data-filter-group="group1">
    <b>category:</b>
        <li><a href="#" data-filter-value="" class="selected">all</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
    </ul>
    <ul class="filter option-set" data-filter-group="group2">
    <b>category:</b>
        <li><a href="#" data-filter-value="" class="selected">all</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
    </ul>
 
    <ul class="filter option-set" data-filter-group="group3">
    <b>category:</b>
        <li><a href="#" data-filter-value="" class="selected">all</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
        <li><a href="#" data-filter-value=".filter">filter name</a></li>
    </ul>
</div>
 
</header>
 
 
<div id="content">
 
<!-- HOW TO ADD MORE AND FILTERS TO EACH MEMBER BOX
template:
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
to add the filters, add the same name that you used above in the '.filter' but without the dot in front. you can add as many as you want but the 'box' in the beginning MUST stay there.
 
for example, if you wanted to have the filters 'admin' and 'blue' together for one box, the filters should look like this 
	<div class="box admin blue"> 
note how media is still there in front.
 
-->
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
<div class="box">
    <div class="name"><h1>name</h1></div>
    <img src=""/>
    <div class="url"><a href="">@username</a></div>
    <div class="desc">
        <div class="t">description</div>
    </div>
</div>
 
</div>
 
 
<!-- credit - DO NOT TOUCH -->
 
<div class="credit">
    <a href="https://enchantedthemes.tumblr.com" title="alydae">A.</a>
</div>
 
 
</body>
 
 
<!-- combination filters by @magnusthemes -->
<script src="https://unpkg.com/isotope-layout@3/dist/isotope.pkgd.min.js"></script>
<script src="https://static.tumblr.com/p0knose/FpAp5c11c/magnusthemes.combofilters.js"></script>
 
<script>
$(document).ready(function() {
 var $container = $("#content"); 
 var filters = {};
 var $grid = $container.isotope({
   itemSelector: ".box",
   percentPosition: false 
 });
 $(".option-set a").click(function(e) {
   var $this = $(this); // cache the clicked link
   var filterAttr = "data-filter-value";
   var filterValue = $this.attr(filterAttr); // cache the filter
   var $optionSet = $this.parents(".option-set"); // cache the parent element
   var group = $optionSet.attr("data-filter-group"); // cache the parent filter group 
   var filterGroup = filters[group];
   if (!filterGroup) {
     filterGroup = filters[group] = []; 
   }
   var $selectAll = $optionSet.find('a['+filterAttr+'=""]'); // the 'select all' button in the current group
   var activeClass = "selected", // the class for active links
     exclClass = "exclusive"; // the class for exclusive groups
 comboFiltering($this,filters,filterAttr,filterValue,$optionSet,group,$selectAll,activeClass,exclClass);
   var comboFilter = getComboFilter(filters);
   $grid.isotope({
     filter: comboFilter
   });
   $this.toggleClass(activeClass);
   e.preventDefault();
 });
});
</script>
 
 
</html>
