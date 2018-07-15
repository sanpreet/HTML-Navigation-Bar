# HTML-Navigation-Bar
## How Result will look like
![html django](https://user-images.githubusercontent.com/3431730/42731298-ae1a50ca-8827-11e8-8b4e-c196ed2557c2.png)
### Vision of this code
Creating Navigation Bar Elements (Login! and Add Details in this case) and make the page look good using **BootstrapCDN**. Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins.
#### Steps for achieving the above
*Step1*: Included MaxCDN in the head section. CDN means (Content Delivery Network). MaxCDN provides CDN support for Bootstrap's CSS and JavaScript.  Please refer the below code for such. I have used this from https://www.w3schools.com/bootstrap/bootstrap_get_started.asp
```
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
*Step2*: Now comes the body part. It is important to display the content in effective way which I think is achieved thriugh CSS. so I included the follwing line in body.
```
<!-- The value "text/css" indicates that the content is CSS -->
<style type="text/css">   
```
*Step3*: To add different elements which can be termed as Navigation Bar Elements Please refer to following code for such
You may refer https://www.w3schools.com/Bootstrap/bootstrap_navbar.asp for more details.
```
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <ul class="nav navbar-nav">
      <li><a href="#">Login!</a></li>
      <li><a href="#">Add Details</a></li>
    </ul>
  </div>
</nav>
```
*Step4*: Displaying the Patients Records (Demo) in the middle requires some configuration which is done using css and is used by div class. div element with class .page-header is create a page header which you can see in the code.

