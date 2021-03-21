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
    
} 

.container{
    width: 80%;
    /* width: 490px; */
    margin: auto;
}
```
## CSS Box Modle





