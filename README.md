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
        </tr>
    </thead>
<ul>
    <li><a href="#about">About</a></li>
    <li><a href="#care">Care</a></li>
    </ul>
    
<tbody>
    <tr>
    <td> 
  <a target="_blank" href="https://www.pexels.com/photo/two-yellow-labrador-retriever-puppies-1108099/">
    <img src="dog.png.png" alt="dog1" width="600" height="400">
  </a>
    <td></td>
    </tr>
</tbody>
    
<button type="button">Click Here</button>
</table>
</html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>About</title>
    </head>
    <h1>Information on Dogs</h1>
    <p>Dogs are loving animals that are great with families. They turn into your bestfriend that you look forward to seeing everyday. They are great with kids and they are especially gentle with younger kids and newborns. Dogs are very aware of their surroundings so they tend to adapt to the environment pretty quickly. </p>
</html>

