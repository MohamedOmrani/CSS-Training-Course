# CSS-Training-Course

***What is CSS?***
  + **cascading Stylesheets**
  + **NOT** a programming language
  + Stylesheet/Styeling language
  + Used for website layout and design 
  + Can be extended with Sass/Less

***What We Need To Start  ?***

  + A Web Browser (Pick One)
    - Google Chrome
    - Mozilla Firefox
    - Microsoft Edge
    - Opera 

  + A Test Editor (Pink One)
    + Visual Studio Code
    + Sublime Text 
    + Atom.io
    + Notepad++ (Windows)
    + TextMate (Mac)

**Getting Started with Downland Visual Studio Code**
## let's started

+ Firstly, create New folder  ***"CSS Training "***

+ Secondly, in this folder Create New Document  ***"New Text Document.txt"***  And rename this document to ***index.html***

+ Thirdly, right click on the file ***index.html***  and select ***"Open with Code"***  the visual studio code will get open.

+ After that, Type ```<h1>hello world</h1>```in visual studio code and save this with ***Ctrl+S***

+ Finally, double click on the ***index.html***, now we can see ***hello world*** in the browser 

## 3 methods For Adding CSS

 + **Inline CSS:** Directly in the html element(NO!)
 + **Internal CSS:** Using <style> tags within a single document
 + **External CSS:** Linking an external .css file
 
 **Inline CSS:**
  ```
  <h1 style="color:red" >Hello World</h1>
  ```
  **Internal CSS:**
  
  add this code in the head
  ```
  <style type="text/css">
        h1{
            color: blue;
        }
  </style>
  ```
**External CSS:**

+ Firstly, in the same folder ***"CSS Training "*** create New folder  ***"CSS"***

+ Secondly, in this folder Create New Document  ***"New Text Document.txt"***  And rename this document to ***styles.css***

+ Thirdly, right click on the file ***styles.css***  and select ***"Open with Code"***  the visual studio code will get open.

+ After that, Type ```h1{ color: blue;}``` in visual studio code and save this with ***Ctrl+S***

+ Now go to ***index.html*** add this line ```<link rel="stylesheet" type="text/css" href="css/styles.css">``` code  in the head

+ Finally, now we can see ***hello world*** with color blue in the browser 

## CSS Selector

![selector](https://user-images.githubusercontent.com/69158314/111882106-01aa7900-89b4-11eb-843c-fdcdac42e56d.jpg)

For example :

```
body{
    background-color: #f4f4f4;
    color: #555555;
    }
```
## Box Modle Colors In CSS

**Color Names and HTML Color names**
```
body{
      color: red;
      background: coral;
    }
```
**Hexadecimal**
```
h1{
    color: #00ff00;
  }
```
**RGB**
```
p{
   color:rgb(0, 0, 255) ;
 }
```
**html**
```
 <div class="container">
      <div class="box-1">
          <h1>Hello World</h1>
          <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio sed aut eaque quis laudantium laborum natus, neque tenetur amet. Non saepe eius minus blanditiis, enim nesciunt. Possimus, consectetur rerum.
          </p>
      </div>
  </div>
```
**css**
```
body{
    background-color: #f4f4f4;
    color: #555555;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 18px;
    font-weight: bold;
    /* same as above */
    /* font: normal 18px Arial, Helvetica, sans-serif; */

    line-height: 1.6em;
    margin: 0;
    
    } 

.container{
    width: 80%;
    /* width: 490px; */
    margin: auto;
          }
.box-1{
    background-color: #333;
    color:#fff;
      }
```
## CSS Box Modle

![css_box_model](https://user-images.githubusercontent.com/69158314/111900912-69ed6f00-8a35-11eb-83a8-e627edac7610.png)

## Margin Padding Border
```
.box-1{
    background-color: #333;
    color:#fff;

    border-right: 5px red solid;
    border-left: 5px red solid;
    border-top: 5px red solid;
    border-bottom: 5px red solid;
    border-width: 3px;
    border-bottom-width: 10px;
    border-top-style: dotted;

    border: 5px red solid;

    padding-top: 20px;
    padding-bottom: 20px;
    padding-right: 20px;
    padding-left: 20px;
    /* same as above */
    padding: 20px;

    margin-top: 20px;
    margin-bottom: 20px;
    margin-right: 0px;
    margin-left: 0px;
    /* same as above */
    margin: 20px 0;
}
```
## Style of Titre: Hello World
```
.box-1 h1{
    font-family: Tahoma;
    font-weight:800;
    font-style: italic;
    text-decoration: underline;
    text-transform: uppercase;
    letter-spacing: 0.2em;
    word-spacing: 1em;
}
```
## add class box-2 in Html
```
<div class="container">
    <div class="box-1">
        <h1>Hello World</h1>
        <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio sed aut eaque quis laudantium laborum natus, neque tenetur amet. Non saepe eius minus blanditiis, enim nesciunt. Possimus, consectetur rerum.
        </p>
    </div>
    <div class="box-2">
        <h1>Goodbye Team</h1>
        <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat optio sed aut eaque quis laudantium laborum natus, neque tenetur amet. Non saepe eius minus blanditiis, enim nesciunt. Possimus, consectetur rerum.
        </p>
    </div>
</div>
```
## Style of box2
```
.box-2{
    border: 3px dotted #ccc;
    padding: 20px;
    margin: 20px 0;
      }
```
## add class categories in Html
```
<div class="categories">
    <h2>Categories</h2>
    <ul>
        <li><a href="#">Category 1</a></li>
        <li><a href="#">Category 2</a></li>
        <li><a href="#">Category 3</a></li>
        <li><a href="#">Category 4</a></li>
    </ul>
</div>
```
## Style of class categories
```
.categories{
    border:1px #ccc solid;
    padding: 10px;
    border-radius:15px;
}

.categories h2{
    text-align: center;
}

.categories ul{
    padding: 0;
    list-style:square;
    list-style: none;
}

.categories li{
    padding-bottom: 6px;
    border-bottom:dotted 1px #333;
  
}

a{
    text-decoration: none;
}
a:hover{
    color:red;
}

a:active{
    color:green
}
```


