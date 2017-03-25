Sublime Text HTML Page Snippets
===

Sublime Text snippets to generate the HTML5 page templates.


Install
---
Available at <b>Package Manager!</b> Just search for <b>HTML Page Snippets</b>.

or

Copy the files to your Packages directory.


Usage
---

With a blank file open, type "doc" and press TAB.

<img src="http://www.burakkaya.com/lab/snippets/html-snippet.png"/>


Blank HTML Page
---

<b>tabTrigger</b>

	doc

<b>That generates:</b>

	  <!DOCTYPE html>
	  <html>
		<head>
			<title>Demo</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
		    <meta name="description" content="Demo Project">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
			<style type="text/css"></style>
		</head>
		<body>
			<p>Let the game begin!</p>
			<script type="text/javascript"></script>
		</body>
	  </html>


HTML Page with jQuery
---

<b>tabTrigger</b>

	docjq

<b>That generates:</b>

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo with jQuery</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project with jQuery">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
			<style type="text/css"></style>
		</head>
		<body>
			<p>Let the game begin!</p>
		</body>
		<script src="http://code.jquery.com/jquery-latest.min.js"></script>
		<script type="text/javascript">
			jQuery(function(){
			
			});
		</script>
	</html>
	
	
HTML Page with AngularJS
---

<b>tabTrigger</b>

	docang
	
<b>That generates:</b>	

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.2.6/angular.min.js"></script>
			<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
			<style type="text/css"></style>
		</head>
		<body ng-app>
			<p>Let the game begin!</p>
			<script type="text/javascript"></script>
		</body>
	</html>
	
	
HTML Page with ReactJS
---

<b>tabTrigger</b>

	docrct
	
<b>That generates:</b>	

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<script src="https://unpkg.com/react@15/dist/react.min.js"></script>
			<script src="https://unpkg.com/react-dom@15/dist/react-dom.min.js"></script>
			<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
			<style type="text/css"></style>
		</head>
		<body>
			<app></app>
			<script type="text/javascript">
				var demoApp = React.createClass({
					render: function() {
						return React.createElement("h1", null, "Let the game begin!");
					},
				});
				var mainApp = document.querySelector("app");
				ReactDOM.render(React.createElement(demoApp), mainApp);
			</script>
		</body>
	</html>
	
	
HTML Page with VueJS
---

<b>tabTrigger</b>

	docvue
	
<b>That generates:</b>	

	<!DOCTYPE html>
	<html>
		<head>
			<title>Demo</title>
			<meta charset="utf-8">
			<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
			<meta name="description" content="Demo project">
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<script src="https://unpkg.com/vue"></script>
			<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
			<style type="text/css"></style>
		</head>
		<body>
			<div id="app"> {{ message }} </div>
			<script type="text/javascript">
				var app = new Vue({
				  el: '#app',
				  data: {
				    message: 'Let the game begin!'
				  }
				})
			</script>
		</body>
	</html>