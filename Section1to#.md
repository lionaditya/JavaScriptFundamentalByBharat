https://github.com/lionaditya/JavaScriptFundamentalByBharat.git
# Section-1: Introduction
# Section-2: JavaScript Basics
## What is JavaScript?
![alt text](image.png)![alt text](image-1.png)![alt text](image-2.png)
###  JavaScript Support both Functional and Object Oriented Principle.
## Create an internal Javascript?
![alt text](image-3.png)![alt text](image-4.png)![alt text](image-5.png)
```html
<html>
	<head>
		<title>Internal Script</title>
		<script>
			document.write("Inside the head element</br>");
		</script>
	</head>
	<body>
		<script>
			document.write("Inside the body element");
		</script>
	</body>
</html>
```
## Output
![alt text](image-6.png)
# 7 Document Object
![alt text](image-7.png)![alt text](image-8.png)
# 8. Commenting
![alt text](image-9.png)
```html
<html>
	<head>
		<title>Comments</title>
		<script>
			//Single line comment
			//document.write("Inside the head element</br>");
		</script>
	</head>
	<body>
		<script>
		//Multiline comment
		/*
			document.write("Inside the body element");
			document.write("Line 2");
		*/
		</script>
		
		<!-- Using Html comments -->
		<!-- <b>Using Html comments</b> -->
	</body>
</html>
```
# 9. Create External JavaScript
![alt text](image-10.png)![alt text](image-11.png)
```html
<html>
	<head>
		<title>External Script</title>
		
		<!-- Here we give relative path. Since JS is in same folder -->
		<script src="js/external.js"> 
			
		</script>
	</head>
	<body>
		<script src="js/external.js"> </script>
	</body>
</html>
```
## external.js
```js
document.write("External document");
```
# 10. Using a Semicolon
![alt text](image-12.png)![alt text](image-13.png)
# 11. Checking for errors
![alt text](image-14.png)![alt text](image-15.png)
# Assignment
![alt text](image-16.png)