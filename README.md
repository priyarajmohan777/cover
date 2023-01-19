# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the GitHub repository and creat Django admin interface.

### Step 2:
Write HTML and CSS code for designing book cover page and execute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage
        {
            width:400px;
            height:600px;
            color:orange;
            margin-left:auto;
            margin-right:auto;
            padding:20px;
            font-family:'Franklin gothic Medium','Arial Narrow',Arial,sans-serif;
            background-image:url(/static/images/cover.png);
            background-size:cover;
        }

        .insight
        {
            color:light greenyellow;
        }
        
        .hrstyle
        {
            width:100px;
        }

        .author
        {
            display:inline;
            position:relative;
            color:black;
            top:190px;
            font-family:Georgia;
            font-family:medium;
        }
        .booktitle
        {
           font-family:'Courier New',Courier,monospace;
           font-family:larger;
           text-align:center;
           position:relative;
           top:30px;
        }
        .id
        {
            width:400px;
            position:relative;
            top:180px;

        }
        .pub
        {
            font-size:medium;
            position:relative;
            top:155px;
            left:330px;

        }
        .ed
        {
            color:brown;
            font-size:medium;
            font-family:Verdana;
            position:relative;
            top:85px;

        }
        .subtitle
        {
            font-family:Tahoma;
            font-size:large;
            position:relative;
            top:40px;
        }
        .mypic
        {
            position:relative;
            top:135px;
            left:260px;
            width:100px;
            height:100px;
            background-size:cover;

        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
            <div class="bookpage">
                <div class="insight">
                    SEC INSIGHT

            </div>
            <div class="hrstyle">
                <hr style="color:blue;">
            </div>
            <div class ="booktitle">
                <h1>Fundamentals of Web Application Development</h1>
            </div>
            <div class="subtitle">Introduction to Javascript</div>
            <div class ="mypic">
                <img src="/static/images/my.jpg"width="130"height="145" alt="">
                </div>
                <div class="id">
                    <hr style="color:violet;">
                </div>
                <div class="author">
                    <p><b>Priya</b></p>
                </div>
                <div class="pub">
                    SEC
                </div>
                <div class="ed">
                    <b>First Edition</b>
                </div>
                </div>
            </body>
            </html>
```


## Output:
![Output](./bookcover.png)

## HTML VAlidator
![HTML Validator](./covervalid.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
