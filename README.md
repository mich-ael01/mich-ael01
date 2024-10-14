<!DOCTYPE html>
<html lang="en">
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">						
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body, html {
  margin: 0;
  height: 100vh;
background-image: url(https://d27fp5ulgfd7w2.cloudfront.net/wp-content/uploads/2023/01/12163716/How-to-Become-a-Fashion-Influencer-1920x1080-1.jpg); 
background-size: cover; 
background-repeat: no-repeat;
font-family: arial, sans-serif;
}  
.content {
color: orange; /* Text color */
 font-size: 20px; /* Font size */
 text-align: right; /* Right-align text */
padding: 100px !important;
margin-top: 30px !important;
}
.navbar {
  display: flex !important;
  background-color:  rgba(173, 216, 230, 0.8);
  padding: 5px;
  width: 100%;
  top: 0; 
  z-index: 1000;
 justify-content: space-between;
}
.nav-links {
display: flex !important;
justify-content: center;
flex-grow: 1;
}
 .navbar a {
  color: orange; /* link color */
  padding: 5px 10px;
  text-decoration: none; /* remove underline */
 }
  .navbar a:hover {
	background-color: white; /* light background on hover */
}
.h1 {
	font-size: x-large;
}
.h2 {
	font-size: small;
}
.h3 {
	font-size: smaller;
}
.my-button {
	background-color: rgb(255, 165, 0); /* orange */
	color: white;
	padding: 15px 32px;
	text-align: center;
text-decoration: none; /* remove underline */;
border: none;
font-size: small;
border-radius: 30px;
margin-top: 5px;
}
/* container for the button to align it with flexbox */
.button-container {
	display: flex;
	padding: 100px; /* space from egde */
	justify-content: flex-end; /* align buttton to the right */
	margin-top: 5px;
}
.icon {
margin: 20px;
display: inline;
}
.icon-container {
margin-left: auto;
display: flex;
}
.icon:hover {
background-color: white;
color: orange;
}
.video-container {
	display: flex;
	margin-top: 20px;
	justify-content:flex-end; /* align video to right */
}
video {
	max-width: 100%;
	height: auto;
	border: 4px solid orange;
	border-radius: 10px;
}
  </style>
<title>fashion design</title>
</head>
<body>
<div class="navbar">
	<div class="nav-links">
  <a href="Home">Home</a>  
  <a href="About">About</a>
  <a href="Shop">Shop</a>
  <a href="Contacts">Contacts</a>
  <a href="Account">Account</a>
</div>
<div class="icon-container">
<a href="#" class="icon"><i class="fas fa-search"></i></a>
<a href="#" class="icon"><i class="fas fa-shopping-cart"></i></a>
<a href="#" class="icon"><i class="fas fa-user"></i></a>
</div>
</div>
<div class="content">
  <h1>IT IS ALL ABOUT FASHION</h1>
  <h2>We bring stock to your door!</h2>
  <h3>Buy now and enjoy 10% discount!</h3>
</div>
<div class="button-container">
<button class="my-button" type="button" onclick="alert('you can use any method of payment')">Shop now!</button>
</div>
<div class="video-container">
<video controls>
    <source src="video.mp4" type="video/mp4">
    <source src="video.webm" type="video/webm">
    <source src="video.ogv" type="video/ogg">
your browser does not support the video tag
</video>
</div>


<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>

  
  

  







