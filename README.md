<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div data-role="page">
  <div data-role="header">
    <h1>Welcome To Silver Pets Homepage</h1>
  </div>

  <div id="pageone" data-role="main" class="ui-content">
    <p>Click on the image to enlarge it.</p>
    <p>Notice that we have added a "back button" in the top right corner.</p>
    <a href="#myPopup" data-rel="popup" data-position-to="window">
    <img src="skaret.jpg" alt="Skaret View" style="width:200px;"></a>

    <div data-role="popup" id="myPopup">
      <p>http://extendedfamilyinc.com/wp-content/uploads/2012/04/attention.jpg</p> 
      <a href="#pageone" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext ui-btn-right">Close</a><img src="skaret.jpg" style="width:800px;height:400px;" alt="Skaret View">
    </div>
  </div>

  <div data-role="footer">
    <h1>Footer Text</h1>
  </div>
</div> 

</body>
</html>
<div data-role="header">
  <div data-role="navbar">
    <ul>
      <li><a href="#anylink">Home</a></li>
      <li><a href="#anylink">Page Two</a></li>
      <li><a href="#anylink">Page Three</a></li>
      <li><a href="#anylink">Page Four</a></li>
      <li><a href="#anylink">Page Five</a></li>
      <li><a href="#anylink">Search</a></li>
    </ul>
   </div>
</div>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div data-role="page" id="pageone">
  <div data-role="header">
    <h1>Welcome To Silver Pets</h1>
    <div data-role="navbar">
      <ul>
        <li><a href="#" class="ui-btn-active ui-state-persist" data-icon="home">Home</a></li>
        <li><a href="#pagetwo" data-icon="arrow-r">Page Two</a></li>
      </ul>
    </div>
  </div>

  <div data-role="main" class="ui-content">
    <p>With the ui-btn-active class, notice that the Home button stays highlighted (selected).</p>
    <p>Click on the Page Two button to see what happens.</p>
  </div>

  <div data-role="footer">
    <h1>My Footer</h1>
  </div> 
</div> 

<div data-role="page" id="pagetwo">
  <div data-role="header">
    <h1>Welcome To My Homepage</h1>
    <div data-role="navbar">
      <ul>
        <li><a href="#pageone" data-icon="home">Home</a></li>
        <li><a href="#" class="ui-btn-active ui-state-persist" data-icon="arrow-r">Page Two</a></li>
      </ul>
    </div>
  </div>

  <div data-role="main" class="ui-content">
    <p>This page will also have its button highlighted, because of the ui-btn-active class.</p> 
    <p>And if you go back to the "Home" page, you will notice that the state of that page will continue to exist, and vice versa DUE TO THE CLASS UI-STATE-PERSIST!</p>
  </div>

  <div data-role="footer">
    <h1>My Footer</h1>
  </div>
</div> 

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div data-role="page">
  <div data-role="main" class="ui-content">
    <form method="post" action="demoform.asp">
      <label for="fname">Write your name and click on one of the buttons:</label>
      <input type="text" name="fname" id="fname">
      <input type="button" value="Useless Button">
      <input type="reset" value="Reset Button">
      <input type="submit" value="Submit Button">
    </form>
  </div>
</div>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div data-role="page">
  <div data-role="header">
  <h1>Text Inputs</h1>
  </div>

  <div data-role="main" class="ui-content">
    <form method="post" action="demoform.asp">
      <div class="ui-field-contain">
        <label for="fullname">Full name:</label>
        <input type="text" name="fullname" id="fullname">       
        <label for="bday">Date of Birth:</label>
        <input type="date" name="bday" id="bday">
        <label for="email">E-mail:</label>
        <input type="email" name="email" id="email" placeholder="Your email..">
      </div>
      <input type="submit" data-inline="true" value="Submit">
    </form>
  </div>
</div>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div data-role="page">
  <div data-role="header">
  <h1>Select Menus</h1>
  </div>

  <div data-role="main" class="ui-content">
    <form method="post" action="demoform.asp">
      <fieldset class="ui-field-contain">
        <label for="day">Select Day</label>
        <select name="day" id="day" data-native-menu="false">
          <option value="mon">Monday</option>
          <option value="tue">Tuesday</option>
          <option value="wed">Wednesday</option>
          <option value="thu">Thursday</option>
          <option value="fri">Friday</option>
          <option value="sat">Saturday</option>
          <option value="sun">Sunday</option>
        </select>
      </fieldset>
      <input type="submit" data-inline="true" value="Submit">
    </form>
  </div>
</div>

</body>
</html>







<div data-role="header">
  <a href="#" class="ui-btn ui-btn-left ui-icon-home ui-btn-icon-left">Home</a>
  <h1>Welcome To My Homepage</h1>
</div>
<div data-role="header">
  <h1>Welcome To My Homepage</h1>
  <a href="#" class="ui-btn ui-btn-right ui-icon-home ui-btn-icon-left">Search</a>
</div>
<div data-role="footer">
  <a href="#" class="ui-btn ui-icon-plus ui-btn-icon-left">Add Me On Facebook</a>
  <a href="#" class="ui-btn ui-icon-plus ui-btn-icon-left">Add Me On Twitter</a>
  <a href="#" class="ui-btn ui-icon-plus ui-btn-icon-left">Add Me On Instagram</a>
</div>
<div data-role="footer" style="text-align:center;">
<div data-role="header" data-position="fixed"></div>
<div data-role="footer" data-position="fixed"></div>
