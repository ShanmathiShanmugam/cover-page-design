# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new folder and clone the Github repository.

### Step 2:
Start a django project interface.

### Step 3:
Create a static folder and its sub directories(Images,html).

### Step 4:
Write the html code in the html folder and upload the images in the images folder.

### Step 5:
Run the server.

## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/bg.jpg);
            background-size: cover;
        }
         
        .toptext{
            color:white;
        }
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:210px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:220px;       
        }
        .publisher{
            font-size: small;
            position: relative;
            top:170px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:90px;
        }
        .subtitle{
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            font-size: x-small;
            position: relative;
            top:40px;
            left:20px
        }
        .photo{
            position: relative;
            top: 165px;
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
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of programming in C</h1></div>
            <div class="subtitle">
                <h1>Easy and fun way to start learning coding</h1>
            </div>
            <div class="photo">
                <img src="/static/images/me1.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Shanmathi</b></p>
            </div>
            <div class="publisher">
                <h1>SEC</h1>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:
### Client output:
![output](https://github.com/ShanmathiShanmugam/cover-page-design/assets/121243595/f99c5f54-bdec-4924-bdc1-4299751ec787)

### Server out:
![serverout](https://github.com/ShanmathiShanmugam/cover-page-design/assets/121243595/0fc0c13f-c39f-4f63-831b-f5356812d9fa)

## Result:
A website to display the cover page design of a book was developed and displayed successfully.
