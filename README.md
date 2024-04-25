# Ex.06 Book Front Cover Page Design
## Date: 25.04.24

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        #base{
            background-image: url(bg\ image\ 2.jpeg);
            width: 600px;
            height: 810px;
        }
        h2{
            color: rgb(26, 219, 155);
            padding-top: 3%;
            text-align: center;
        }
        h1{
            color: white;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            text-align: center;
            font-size: 130px;
            opacity: 0.8;
        }
        h4{
            color: rgb(26, 219, 155);
            text-align: center;
            font-size: 50px;
            padding-top: 5%;
            font-family:Arial, Helvetica, sans-serif;
        }
        p{
            color: white;
            text-align: right;
            padding-left:60% ;
            padding-top: 3%;
            padding-right: 3%;
        }
    </style>
</head>
<body>
    <div class="mx-auto" id="base">
        <h2>Voted Best Thriller Novel 20XX</h2>
            <h1 style="padding-top: 50px;">DON'T</h1>
            <h1>LOOK</h1>
            <h1>BACK</h1>
        <h4><b>ISAAC  NELSON</b></h4>
        <div style="display: flex;">
             <p><b>Publisher:<br>Meenu.S<br>B.Tech-AI&DS</b></p>
             <img src="profile.jpg" alt="" style="width: 100px;height: 100px;border-radius: 50%;">
        </div>
    </div>
</body>
</html>
~~~

## OUTPUT:

![image](https://github.com/Meenu2823/cover/assets/139416219/742bdb25-f4ba-4356-859e-b9bc3539f332)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
