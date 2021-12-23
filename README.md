# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Layout.css
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(31, 29, 29);
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #dcdddc;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(250, 249, 248);
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-image: url("/static/img/QQQ2.jpg");
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: black;
  display: inline;
}
.homecontent h1 {
  color: white;
  display: inline;
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: rgb(255, 255, 255);
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  display: inline;
  color: black;
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: inline-block;
}
.productitem .itemimage {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: rgb(253, 249, 249);
  font-family: block;
}
.productitem .itemprice {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(194, 174, 248);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~
### Home Page
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dell Technologies & Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br><br>
          <h1>Address:</h1><br><br>
          <div class="contenttext">
            332, Dell Technologies Private Limited ,<br>
            Trunk Road, Porur<br>
            Chennai-600116.<br>
          </div><br>
          <h1>Contact:</h1><br><br>
          <div class="contenttext">
              MR.Mark Zukenberg (Marketting Manager):8220125648<br>
              MR.Thomas Shelby (Operation Manager):6895432145<br>
              MR.Tyrion (Staff):6365843659<br><br><br>
          </div>
          <h1>E-Mail:</h1><br><br>
          <div class="contenttext">
              Sales:delltechnologieslimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Dell Technologies Private Limited, Developed by Syed Abdul Wasih.
      </div>
    </div>
  </body>
</html>
~~~
### Product
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dell Technologies & Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/lap1.jpg" alt="product image">
                  </div>
                  <div class="itemname">DELL Inspiron</div>
                  <div class="itemprice">Price: Rs.59999/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/lap2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">DELL G15 </div>
                  <div class="itemprice">Price: Rs.75000/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/lap 3.jpg"  alt="product image">
                </div>
                <div class="itemname">DELL Inspiron 15</div>
                <div class="itemprice">Price: Rs.47000/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/lap4.jpg"  alt="product image">
                </div>
                <div class="itemname">DELL Latitude</div>
                <div class="itemprice">Price: Rs.60000/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/lap 5.jpg"  alt="product image">
              </div>
              <div class="itemname">DELL PC</div>
              <div class="itemprice">Price: Rs.48000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/lap6.png"  alt="product image">
            </div>
            <div class="itemname">DELL i5</div>
            <div class="itemprice">Price: Rs.55000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/lap7.jpg"  alt="product image">
            </div>
            <div class="itemname">Dell Inspirion 3501</div>
            <div class="itemprice">Price: Rs.70000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/lap8.jpg"  alt="product image">
            </div>
            <div class="itemname">Dell i9</div>
            <div class="itemprice">Price: Rs.110000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/lap9.jpg"  alt="product image">
            </div>
            <div class="itemname">Dell i7</div>
            <div class="itemprice">Price: Rs.89550/- </div>
        </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/lap10.png"  alt="product image">
        </div>
        <div class="itemname">Dell 14</div>
        <div class="itemprice">Price: Rs.36000/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/lap11.png"  alt="product image">
        </div>
        <div class="itemname">Dell Vostro 3400</div>
        <div class="itemprice">Price: Rs.42000/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/lap12.png"  alt="product image">
        </div>
        <div class="itemname">Dell XPS</div>
        <div class="itemprice">Price: Rs.119000/- </div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Dell Technologies Private Limited, Developed by Syed Abdul Wasih H.
      </div>
    </div>
  </body>
</html>
~~~
### People
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dell Technologies & Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ceo.jpg" alt="product image">
                </div>
                <div class="itemname">Micheal Dell</div>
                <div class="itemprice">CEO</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/2.jpg"  alt="product image">
                </div>
                <div class="itemname">Richard</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/3.jpg"  alt="product image">
              </div>
              <div class="itemname">Peter Parker</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/4.jpg"  alt="product image">
              </div>
              <div class="itemname">Sanjay</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/5.jpg"  alt="product image">
            </div>
            <div class="itemname">Mary</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/6.jpg"  alt="product image">
          </div>
          <div class="itemname">Bruce Wayne</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Dell Technologies & Private Limited, Developed by Krishna Prakaash.
    </div>
  </div>
</body>
</html>
~~~
### Contact us
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Dell Technologies & Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br><br>
          <h1>Address:</h1><br><br>
          <div class="contenttext">
            332, Dell Technologies Private Limited ,<br>
            Trunk Road, Porur<br>
            Chennai-600116.<br>
          </div><br>
          <h1>Contact:</h1><br><br>
          <div class="contenttext">
              MR.Mark Zukenberg (Marketting Manager):8220125648<br>
              MR.Thomas Shelby (Operation Manager):6895432145<br>
              MR.Tyrion (Staff):6365843659<br><br><br>
          </div>
          <h1>E-Mail:</h1><br><br>
          <div class="contenttext">
              Sales:delltechnologieslimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Dell Technologies Private Limited, Developed by Syed Abdul Wasih.
      </div>
    </div>
  </body>
</html>

~~~
## OUTPUT:

### Home Page:

![output](1.png)

### Product:
![output](2.png)
### People:
![output](3.png)
### Contact Us:
![output](4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
