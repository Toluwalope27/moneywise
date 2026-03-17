<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MoneyWise - Financial Literacy Platform</title>
  <script type="text/javascript">
    // AMPLITUDE SCRIPT (PASTE YOUR API KEY)
    (function(e,t){var n=e.amplitude||{_q:[],_iq:{}};var r=t.createElement("script")
    ;r.type="text/javascript";r.integrity="sha384-...";r.crossOrigin="anonymous";
    r.async=true;r.src="https://cdn.amplitude.com/libs/amplitude-8.5.0-min.gz.js";
    r.onload=function(){if(!e.amplitude.runQueuedFunctions){
    console.log("[Amplitude] Error loading SDK")}}
    ;var i=t.getElementsByTagName("script")[0];i.parentNode.insertBefore(r,i);
    function s(e,t){e.prototype[t]=function(){
    this._q.push([t].concat(Array.prototype.slice.call(arguments,0)));return this}}
    var o=function(){this._q=[];return this};
    var a=["add","append","clearAll","prepend","set","setOnce","unset"];
    for(var c=0;c<a.length;c++){s(o,a[c])}n.Identify=o;
    var u=function(){this._q=[];return this};
    var l=["setProductId","setQuantity","setPrice","setRevenueType","setEventProperties"];
    for(var p=0;p<l.length;p++){s(u,l[p])}n.Revenue=u;
    var d=["init","logEvent"];function v(e){function t(t){
    e[t]=function(){e._q.push([t].concat(Array.prototype.slice.call(arguments,0)))}}
    for(var n=0;n<d.length;n++){t(d[n])}}v(n);e.amplitude=n})(window,document);

    amplitude.init("YOUR_API_KEY");
  </script>
</head>

<body style="font-family: Arial; text-align: center; padding: 40px;">

  <h1>You’re Not Bad With Money — You Were Never Taught</h1>
  <p>Learn how to save, spend, and invest with confidence.</p>

  <!-- CTA BUTTONS -->
  <button onclick="signUp()">Sign Up</button>
  <button onclick="requestDemo()">Request Demo</button>

  <h2>Why MoneyWise?</h2>
  <p>Simple lessons, practical tools, and real-life strategies.</p>

  <script>
    function signUp() {
      amplitude.logEvent("Sign Up Clicked");
      alert("Sign Up clicked!");
    }

    function requestDemo() {
      amplitude.logEvent("Request Demo Clicked");
      alert("Demo requested!");
    }
  </script>

</body>
</html>
