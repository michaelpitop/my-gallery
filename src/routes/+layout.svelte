<script>

</script>

<!-- 
<nav>
    <a href="/">Home</a>
    <a href="/about">About me</a>
    <a href="/pic">My gallery</a>
</nav> -->

<nav>
    <a class="active" href="/">Home</a>
    <a href="/about">About</a>
    <input type="text" placeholder="Search..">
</nav> 

<slot />

<style>

     /* Add a black background color to the top navigation bar */
nav {
  overflow: hidden;
  background-color: #e9e9e9;
}

/* Style the links inside the navigation bar */
nav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
nav a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the "active" element to highlight the current page */
nav a.active {
  background-color: #2196F3;
  color: white;
}

/* Style the search box inside the navigation bar */
nav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
}

/* When the screen is less than 600px wide, stack the links and the search field vertically instead of horizontally */
@media screen and (max-width: 600px) {
  nav a, nav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  nav input[type=text] {
    border: 1px solid #ccc;
  }
} /* Add a black background color to the top navigation bar */
nav {
  overflow: hidden;
  background-color: #e9e9e9;
}

/* Style the links inside the navigation bar */
nav a {
  float: left;
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
nav a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the "active" element to highlight the current page */
nav a.active {
  background-color: #2196F3;
  color: white;
}

/* Style the search box inside the navigation bar */
nav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
}

/* When the screen is less than 600px wide, stack the links and the search field vertically instead of horizontally */
@media screen and (max-width: 600px) {
  nav a, nav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  nav input[type=text] {
    border: 1px solid #ccc;
  }
}

</style>