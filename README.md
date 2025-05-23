# Ex.06 Book Front Cover Page Design
## Date:27-04-2025

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
<html lang="en">
<head>
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            color: white;
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            text-align: center;
            background-image: url('A.webp'); /* Replace with your background image */
            background-size: cover;
            padding: 20px;
            border-radius: 10px;
            width: 500px;
            height: 700px;
        }
        .title {
            padding-top: 2cm;
            font-size: 3em;
            font-weight: bold;
            margin: 10px 0;
        }
        .subtitle {
            padding-top: 2cm;
            font-size: 1.2em;
            margin: 5px 0;
        }
        .author {
            font-size: 2em;
            margin: 20px 0;
        }
        .image-container {
            margin-top: 20px;
        }
        .image-container img {
            width: 100px;
            height: 120px;
            border-radius: 5px;
        }
        .line {
            width: 90%;
            height: 1px;
            background-color: white;
            margin: 10px auto;
        }
        .subtitle1 {
            padding-left: 1cm;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="subtitle" align = "left"><u>SEC INSIGHT</u></div>

        <center>
        <div class="title">Introduction To <br>Computer <br>Science</div>
        </center>
        <div class="image-container" align="right">
            <img src="v5_12.png" alt="Profile Picture"> <!-- Replace with your profile image -->
        </div>
        <div class="line"></div>
        <div class="subtitle1" align = "left">Extended Edition</div><div class="author" align = "right">SEC</div>
        <div class="author">Hari Nivedhan P</div>
        
        
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-04-27 112838.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.