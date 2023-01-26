# Book CoverPage Design

## AIM:

To design a static web site for a book cover page.

## DESIGN STEPS:
### step 1:
write my html and css code
### Step 2:

Validate the HTML and CSS code.

### Step 3:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
     
        .bookpage{
            width: 680px;
            height: 880px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
          
        }
            

        .toptext{
            top: 1px;
            color:white;
           
        }

        
        .line1{
            top: 2px;
            width: 150px;
            color: orangered;
        }
        .name{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:250px;
            
            font-family:Georgia;
            font-size: xx-large;
        }
        .booktitle{
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: xx-large;
            text-align: left;
            position: relative;
            top: -30.0px;
        
        }
        .line2 {
            width: auto;
            position:relative;
            
            top:235px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top: 170px;
            left:550px;
        }
        
        .sub{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size:xx-large;
            position: relative;
            top:-30px;
        }
        .img{
            
            position: relative;
            top: -30px;
            left: -15px;
            width: 100px;
            height: 100px;
            
            
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="line1">
                <hr style="color: rgb(255, 84, 22);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="sub">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="img">
             <img src ="suresh.png" alt="img">
            </div>
            <div class="line2">
                <hr style="color: rgb(255, 123, 0);" >
            </div>
            <div class="name">
               <p><b>BASKARAN V</b></p>
            </div>
            <div class="publisher">
                <img src="pack.png" alt="packt">
            </div>
           
            
        </div>
    </body>
</html>

```

## OUTPUT:
![output](page.png)
## Result:
the program is running
