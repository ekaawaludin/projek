This is where I upload Social Locker widget for blogger.
Installation:
***Before </head>***

<script src='http://code.jquery.com/jquery-1.10.2.min.js' type='text/javascript'/>

***Before </head>***

<link href='https://cdn.staticaly.com/gh/ekaawaludin/projek/fb66769e/sociallocker/SocialLocker.css' rel='stylesheet' type='text/css'/>
<script src='https://cdn.staticaly.com/gh/ekaawaludin/projek/fb66769e/sociallocker/SocialLocker.js' type='text/javascript'/>
<script type='text/javascript'>
//<![CDATA[
$(function(){
  $('.socialLocker .to-lock').sociallocker({
    buttons: {order:["facebook-like","twitter-tweet","google-plus"]},
    twitter: {url:"http://twitter.com/scorpionruler"},
    facebook: {url:"https://www.facebook.com/trickstantra/"},
    google: {url:"https://plus.google.com/+MohammadSharfuddin"},
    text: {
      header: "Like us To Unlock This Content",
      message: "This content is locked. Like us on Twitter, Facebook or Google plus to unlock it."
    },
    locker: {close: false, timer: 0,},
    theme: "secrets"
  });
});
//]]>
</script>

*** Locked Content ***

<article class="socialLocker"> <div class="to-lock" style="display:none;"> — ADD YOUR CONTENT HERE — </div> </article>
