# Ex.06 Book Front Cover Page Design
## Date:07/05/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
  <meta name="viewport"
  content="width=device-width, initial-scale=1.0">
  <style>
  .bookpage{
    width: 400px;
    height: 600px;
    color:brown;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url('bg.color.jpg');
    background-size: cover;
  }

  .insight{
    color: rgb(102, 6, 6);

  }

  .hrstyle{
    width:100px;
  }
  .author{
    display: inline; 
    position: relative;
    color: rgb(143, 18, 76);
    top: 190px;

    font-family:Georgia; 
    font-size: medium;
  }
 .booktitle{
    font-family: 'Courier New', Courier, monospace;
    font-size: larger;
    text-align: center;
    position: relative;
    top: 30px;

 }
 .id {
    width:400px;
    position: relative;
    top:180px;

 }
 .pub{
    font-size: medium;
    position: relative;
    top:155px;
    left:330px;
 }
 .ed{
    color: rgb(162, 37, 184);
    font-size: large; 
    font-family: Verdana;
    position:relative;
    top:45px;

 }
 .subtitle{
    font-family: Tahoma;
    font-size: medium;
    position: relative;
    top:85px;
 }
 .mypic{
    position: relative;
    top: 135px;
    left: 260px;
    width: 100px;
    height: 100px;
    background-size: cover;
 }
 </style>
   <title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
  <div class="insight">
    more than 35 million copies sold
  </div>
  <div class="hrstyle">
    <hr style="color: orange">
  </div>
  <div class="booktitle">
    <h1>The Dairy Of A Young Girl</h1></div>
  <div class="subtitle">
    <h2>The Definite Edition Edited by Otto H.Frank</h2>
  </div>
  <div class="mypic">
    <img src="download.jpg" width="130" height="145" alt="">                  
  </div>
  <div class="id">
    <hr style="color: rgb(180, 45, 151);">
  </div>
  <div class="author">
    <p><b><i>ANNE FRANK</i></b></p>
  </div>
  <div class="pub">
    SEC
  </div>
  <div class="ed">
    <b>Extended Edition</b>
  </div>
</div>
</body>
</html>

```


## OUTPUT:
![alt text](<divya/bookapp/static/Screenshot 2025-05-07 141646.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
