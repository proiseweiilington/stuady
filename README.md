# stuady
this is a test
<html>
 <head>
 <title>Sample Page</title>
 </head>
 <body>
 <p>Hello 斌爷!</p>
 </body>
</html>

 <!DOCTYPE html>
<html lang="en">
  
    <head>
    
        <meta charest="utf-8" />
        
        <title>Catch it!<title>
                                                <script type="text/javascript"
sra="http://g.huceo.com/weixin/qw/jquery.min.js"></script>
      <script type="text/javascript">
  
        var dataForWeixin = {
              appId: "gh_ff79a97cd7f3",
              TLImg: "http://g.huceo.com/weixin/zhua/logp.jpg",
              url: "http://g,huceo.com/weixin/zhua/",
              title: "Classic  game <Catch it!>,please share your friends!   Cirele
friends wechat!",
              desc: "please share your friends! Cirele  friends wechat!"
        };
        
        var onBridgeReady = function(){
            WeixinJSBridge.on('menu:share:appmessage', function(argv){
               var infos = $("#infos").text();
               
                WeixinJSBridge.invoke('sendAppMessage', {
                    "appid": dataForWeixin.appId,
                    "img_url": dataForWeixin.TLImg,
                    "img_width": "120",
                    "img_height": "120".
