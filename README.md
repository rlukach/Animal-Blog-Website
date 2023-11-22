# Animal-Blog-Website
<!DOCTYPE html>

<style>
ul {
    list-style-type: none;
    margin:0px;
    padding:10px;
    background-color: cadetblue;
}

li {
    display: inline;
}

li a {
    color: black;
    text-align: center
    text-decoration: none;
    padding: 10px;
}

ul li a:hover {
    background-color: beige;
    color: azure;
    padding: 10px;
}

p a {
    color: red;
    text-align: center;
    text-decoration: line-through red double 5px;
}
    div.gallery {
  margin: 5px;
  border: 1px solid #ccc;
  float: left;
  width: 180px;
}
    div.gallery img {
  width: 100%;
  height: auto;
}
</style>
<html lang="en">
    <head>
    <meta charset="UTF-8"/>
    <title>Image Gallery Using Tables</title>
    <link rel="stylesheet"href="styles.css"/>
    <script src="script.js"></script>
    </head>
<table>
    <thead>
        <tr>
           <th></th>
           <th></th>
        </tr>
    </thead>
<ul>
    <li><a href="#about">About</a></li>
    <li><a href="#care">Care</a></li>
    </ul>
    
<tbody>
    <tr>
    <td> 
  <a target="_blank" href="dog1.png.png">
    <img src="dog1.png.png" alt="dog1" width="600" height="400">
  </a>
    <td></td>
    </tr>
</tbody>
    
<button type="button">Click Here</button>
</table>
</html>
