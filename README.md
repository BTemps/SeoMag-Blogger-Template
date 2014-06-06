<html>
<head>
	<title>SEO MAG Template</title>
</head>
<style>
@font-face {
  font-family: 'Exo 2';
  font-style: normal;
  font-weight: 700;
  src: local('Exo 2 Thin'), local('Exo2-Thin'), url(fonts/RZBBdEhQV3g9mUXUAU9PpvesZW2xOQ-xsNqO47m55DA.woff) format('woff');
}
@font-face {
  font-family: 'Raleway';
  font-style: normal;
  font-weight: 400;
  src: local('Raleway'), url(fonts/IczWvq5y_Cwwv_rBjOtT0w.woff) format('woff');
}
a:link{
	color:#8F3C00;text-decoration: none;
}
a:visited {
	color:#8F3C00;
}
.codebox {
background: #efefef;
padding: 20px;
font-size: 16px;
border-radius: 5px;word-wrap:break-word;
}
.main-outer{
width:640px;
border: 1px solid #333;
margin: 0 auto;
}
h1 {
background: #333;
color: #fff;
padding: 20px;
text-align: center;
font-family: 'Exo 2';
font-style: normal;
font-weight: 100;
font-size: 50px;
margin-top: 0px;
}
.content {
font-family: 'Raleway';
font-style: normal;
font-weight: 400;
font-size: 18px;
color: #555;
border-bottom:1px solid #333;
padding-right:20px;
padding-left:20px;padding-bottom:20px;margin-bottom:20px;
}
#my-cover {
    background-image: url('img/cover.png');
    width: 640px;
    height: 480px;
}
code{
	background:#FFE851;
}
</style>
<body>
<div class="main-outer">
<div id='my-cover'></div>

# SEO MAG Template

<div class="content">

## How To Install Blogger Template

For these you need a account on blogger.com where you can create a free blog, In this guide I'm not going to tell you that how you can create a blog on blogger, I assume that you have a blogger account with a blogger blog, so let's get started!

**Also Read:**[ Complete Guide To Setup Blog](http://blog.seobloggertemplates.com/2013/10/a-complete-guide-to-setting-up-blog.html)

*   Go To Blogger **Dashboard**
*   On Blogger Dashboard click **Template**
*   Now Click On **Backup/Restore** button (Top Right).
*   Click **Choose File** button. Find where the &#x201c;seomag-theme.xml&#x201d; file location.
*   Now Click On** Upload** Button.
![](img/themeinstall.png)
</div>
<div class="content">

## How to Customize Menu Navigation

![](img/nav.png)

Navigation menu will helps to make site user friendly, You can add label links, page links, affliate links or any external website link by just changing it little bit.  

*   Go To Blogger **Dashboard**
*   On Blogger Dashboard click **Template**
*   Now Click On **Edit HTML** button
*   Now Find  `&lt;!--Navigation Menu--&gt;` in template code using **ctrl+f**
*   Now you will see navigation menu code, just change its text and link according to your need.
![](img/menu-code.png)

</div>

<div class="content"> 

## Add Your Feedburner username

![](img/slider.png)

Email Subscription box will help you to make your blog viral using email marketing, to add your own feedburner user name follow below steps:

*   Go To Blogger **Dashboard**
*   Click On **Layout** Tab
*   Now Click on **Add Gadget** and add html/javascript
*   Now Just Copy and paste below code there:

<pre class="codebox">
&lt;form class=&quot;emailbox&quot; action=&quot;http://feedburner.google.com/fb/a/mailverify&quot; method=&quot;post&quot; target=&quot;popupwindow&quot; onsubmit=&quot;window.open('http://feedburner.google.com/fb/a/mailverify?uri=<span style="color:red;">seotemplates</span>', 'popupwindow', 'scrollbars=yes,width=550,height=520');return true&quot;&gt;&lt;div class=&quot;etitle1&quot;&gt;Get Email Updates&lt;/div&gt;
&lt;div class=&quot;etitle2&quot;&gt;It's Free&lt;/div&gt;
&lt;center&gt;&lt;p&gt;&lt;input type=&quot;text&quot; class=&quot;inputof&quot; placeholder=&quot;Enter your email here...&quot; name=&quot;email&quot;/&gt;&lt;/p&gt;&lt;input type=&quot;hidden&quot; value=&quot;<span style="color:red;">seotemplates</span>&quot; name=&quot;uri&quot;/&gt;&lt;input type=&quot;hidden&quot; name=&quot;loc&quot; value=&quot;en_US&quot;/&gt;&lt;input type=&quot;submit&quot; value=&quot;Get Instant Access&quot; class=&quot;btnof&quot; /&gt;&lt;/center&gt;&lt;/form&gt;
</pre>

<li>Now replace **seotemplates** with your feedburner username.</li>

**Read This:**[
Step by Step Guide to Setup FeedBurner for Blogger](http://blog.seobloggertemplates.com/2013/10/step-by-step-guide-to-setup-feedburner.html)
</div>

<div class="content"> 

## How to Add Like Box

![](img/fblikebox.png)

For adding facebook like box to blogger, go to official [Like Box Generator](https://developers.facebook.com/docs/plugins/like-box-for-pages/) and then paste your page URL and then click on **Get Code** button, Now select **iFrame** Copy given code and paste it in HTML/Javascript by adding New gadget in layout tab.

</div>

<div class="content"> 

## How to Add Twitter Feed Box

![](img/twitterfeed.png)

Twitter is very popular social media websites. Like others social networks, Twitter also plays an important role for every blog and website.

*   Go To Blogger **Dashboard**
*   Click On **Layout** Tab
*   Now **Add Gadget** >> **HTML/JavaScript**
*   Paste below code there:
	<pre class="codebox">
&lt;a class=&quot;twitter-timeline&quot; href=&quot;https://twitter.com/**<span style="color:red;">lordemusic</span>**&quot; data-widget-id=&quot;429486347175211008&quot;&gt;Tweets by @**<span style="color:red;">lordemusic</span>**&lt;/a&gt;
&lt;script&gt;!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+&quot;://platform.twitter.com/widgets.js&quot;;fjs.parentNode.insertBefore(js,fjs);}}(document,&quot;script&quot;,&quot;twitter-wjs&quot;);&lt;/script&gt;
</pre>

*   Replace `lordemusic` with your twitter username.
</div>

<center>
![](img/footer.png)
</center>

</div>
</body>
</html>