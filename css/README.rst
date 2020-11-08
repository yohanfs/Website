Cascading Style Sheets
=================================================================================

.. contents:: **Daftar Isi**

Referensi
---------------------------------------------------------------------------------

- `w3schools.com`_
- `Learn to style HTML using CSS`_


Mengapa Menggunakan CSS?
---------------------------------------------------------------------------------

CSS digunakan untuk mendefinisikan style dari web pages, termasuk design,
dan layout untuk perangkat dan ukuran layar yang berbeda. 


Cara Insert CSS
---------------------------------------------------------------------------------

External CSS
*********************************************************************************

**contoh.html**

::

	<!DOCTYPE html>
	<html>
	<head>
	<link rel="stylesheet" href="mystyle.css">
	</head>
	<body>

	<h1>This is a heading</h1>
	<p>This is a paragraph.</p>

	</body>
	</html> 

**mystyle.css**

::

	body {
	  background-color: lightblue;
	}

	h1 {
	  color: navy;
	  margin-left: 20px;
	}

Internal CSS
*********************************************************************************

::

	<!DOCTYPE html>
	<html>
	<head>
	<style>
	body {
	  background-color: linen;
	}

	h1 {
	  color: maroon;
	  margin-left: 40px;
	}
	</style>
	</head>
	<body>

	<h1>This is a heading</h1>
	<p>This is a paragraph.</p>

	</body>
	</html> 

Inline CSS
*********************************************************************************

::

	<!DOCTYPE html>
	<html>
	<body>

	<h1 style="color:blue;text-align:center;">This is a heading</h1>
	<p style="color:red;">This is a paragraph.</p>

	</body>
	</html>

 
CSS Syntax
---------------------------------------------------------------------------------

.. image:: images/css_syntax.png


CSS Element Selector
---------------------------------------------------------------------------------

::

	<!DOCTYPE html>
	<html>
	<head>
	<style>
	body {
	  background-color: lightblue;
	}

	h1 {
	  color: white;
	  text-align: center;
	}

	p {
	  font-family: verdana;
	  font-size: 20px;
	}
	</style>
	</head>
	<body>

	<h1>My First CSS Example</h1>
	<p>This is a paragraph.</p>

	</body>
	</html>

.. image:: images/css_element.png

CSS ID Selector
---------------------------------------------------------------------------------

::

	<!DOCTYPE html>
	<html>
	<head>
	<style>
	#para1 {
	  text-align: center;
	  color: red;
	}
	</style>
	</head>
	<body>

	<p id="para1">Hello World!</p>
	<p>This paragraph is not affected by the style.</p>

	</body>
	</html>

.. image:: images/css_id.png

CSS Class Selector
---------------------------------------------------------------------------------

::

	<!DOCTYPE html>
	<html>
	<head>
	<style>
	.center {
	  text-align: center;
	  color: red;
	}
	</style>
	</head>
	<body>

	<h1 class="center">Red and center-aligned heading</h1>
	<p class="center">Red and center-aligned paragraph.</p> 

	</body>
	</html>

.. image:: images/css_class.png


.. Referensi

.. _`w3schools.com`: https://www.w3schools.com/css/default.asp
.. _`Learn to style HTML using CSS`: https://developer.mozilla.org/en-US/docs/Learn/CSS

