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
contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MANOJ-TECH PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>
  
  <body>
    <div class="container">
      <div class="banner">MANOJ-TECH PRIVATE LIMITED</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           CHENNAI
           <br>Phone:987654321
           <br>Email-address:acprivatelimited@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 MANOJ-TECH PRIVATE LIMITED, Developed by Manoj M.
</div>
</div>
</body>
</html>
```
home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MANOJ-TECH PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/banner1.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MANOJ TECH PRIVATE LIMITED</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/background.jpg" alt="Building" />
          <div class="contenttext">
            Free antivirus is your first step to online freedom
            We believe everyone has the right to be safe online, 
            which is why we offer our award-winning free antivirus 
            to millions of people around the world.
            <br />
            
            <ul>
              <li>Simple and easier to use</li>
              <li>We protect digital freedom for everyone
                We believe that wherever you live, whatever 
                you love, wherever you’re going, and whatever
                you do, you have the right to live freely 
                and safely online.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 MANOJ-TECH PRIVATE LIMITED, Developed by MANOJ M.
      </div>
    </div>
  </body>
</html>
```
people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MANOJ-TECH PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/globee.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MANOJ-TECH PRIVATE LIMITED</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/John_McAfee_by_Gage_Skidmore.jpg/1200px-John_McAfee_by_Gage_Skidmore.jpg"  alt="product image">
      </div>
         <div class="itemname">John McAfee</div>
         <div class="itemname">Founder of McAfee Corp.</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://s-img.lentainform.com/n/9429022/492x328/47x3x1152x768/aHR0cDovL2ltZ2hvc3RzLmNvbS90LzIwMjEtMDcvNDI0MDM5LzVlYmM0YmJhZDU1MTI1ZTE4MzYyMzQ3NWMzZjFlMzIwLmpwZWc.webp?v=1628650254-UyUjTOjzwCLIw8Sl4H0GKZ-qbB40c2LrG5hW_1X1E8w"  alt="product image">
      </div>
         <div class="itemname">Pavel Baudiš</div>
         <div class="itemname">CEO of Avast </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://static.electronicsweekly.com/wp-content/uploads/2021/06/09081414/9C0B0498-14C1-4571-92A5-82A776B31B7D.jpeg"  alt="product image">
      </div>
        <div class="itemname">Benedetto vigna</div>
        <div class="itemname">CEO of Ferrari</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://i.ytimg.com/vi/4fGtQWyrL4U/maxresdefault.jpg"  alt="product image">
      </div>
        <div class="itemname">Florin Talpeș</div>
        <div class="itemname">CEO of BitDenfender</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/Mr. Shrishail Rana.jpg"  alt="product image">
      </div>
        <div class="itemname">Mr. Shrishail Rana</div>
        <div class="itemname">CEO of ACS</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/Eugene Kaspersky.jpg"  alt="product image">
      </div>
        <div class="itemname">Eugene Kaspersky</div>
        <div class="itemname">FOUNDER OF KASPERSKY</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 MANOJ-TECH PRIVATE LIMITED, Developed by Manoj M.
      </div>
    </div>
  </body>
</html>
```
product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MANOJ-TECH PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MANOJ-TECH PRIVATE LIMITED</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/advanced.jpg" alt="product image">
                  </div>
                  <div class="itemname">Advanced System Care</div>
                  <div class="itemprice">Price: Rs.1500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/avast.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Avast Antivirus</div>
                  <div class="itemprice">Price: Rs.2500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bitdefender.jpg"  alt="product image">
                  </div>
                  <div class="itemname">BitDefender Antivirus</div>
                  <div class="itemprice">Price: Rs.2599.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://cdn2.hubspot.net/hubfs/6847401/Cylance.png"  alt="product image">
                  </div>
                  <div class="itemname">Cylance Smart Antivirus</div>
                  <div class="itemprice">Price: Rs.3500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ESET.jpg"  alt="product image">
                  </div>
                  <div class="itemname">ESET Antivirus</div>
                  <div class="itemprice">Price: Rs.1299.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kaspersky.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Kaspersky Total Security</div>
                  <div class="itemprice">Price: Rs.999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/malwarebytes.png"  alt="product image">
                  </div>
                  <div class="itemname">Malaware bytes Cybersecurity</div>
                  <div class="itemprice">Price: Rs.5999.99 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/McAfee.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mcafee Security</div>
                  <div class="itemprice">Price: Rs.9999.99</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/norton.png"  alt="product image">
                  </div>
                  <div class="itemname">Norton Antivirus Security</div>
                  <div class="itemprice">Price: Rs.6999.99 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/panda.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Panda Security</div>
                  <div class="itemprice">Price: Rs.3999.99 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/trend.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Trend Micro Antivirus</div>
                  <div class="itemprice">Price: Rs.2799.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/webroot.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">WebRoot Cybersecurity</div>
                  <div class="itemprice">Price: Rs.8999.00 </div>
              </div>       
      </div>
      <div class="footer">
        Copyright &#169; 2021 MANOJ-TECH PRIVATE LIMITED, Developed by Manoj M.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](1.png)
![output](2.png)
![output](3.png)
![output](4.png)
![output](5.png)
![output](6.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
