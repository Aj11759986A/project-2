# project-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<>

    <h1 style="color: rgb(64, 189, 189);">Welcome To my website </h1> 
    <this style="background-color: rgb(162, 192, 156);">This is my first website.</p>


    <h2 style="color: aquamarine;">About ME</h2> 
    <name style="color: rgb(146, 146, 223);"> My name is Ajay. I am learning website development</p>

    <h2 style="background-color: rgb(169, 235, 226);">My Hobbies</h2>

<ul style="color: rgb(230, 104, 198);">
<li>playing Games</li>
<li>learning coding</li>
<li>singing</li>
</ul>

<table border="2"> 
    <tr>
         <th>Name</th>
         <th>Rollno</th>
         <th>Class</th>
         <th>Section</th>
    </tr>
    <tr>
        <td>Ajay Sharma</td>
        <td>253181</td>
        <td>b.tech cse</td>
         <td>C </td>
    </tr>
    <tr>

</table>



<a href="https://www.google.com"> Google </a> <br>


<img src="https://png.pngtree.com/thumb_back/fh260/background/20230411/pngtree-nature-forest-sun-ecology-image_2256183.jpg">


<li>Click <link rel="stylesheet" href="https://youtube.com/shorts/uDOLjJ3DDQs?si=-LdiwHQL5Px7b3Xs"></li>


<a href="https://youtube.com/shorts/uDOLjJ3DDQs?si=-LdiwHQL5Px7b3Xs">youtube</a> <br>

<img src="download.png" alt="download">


<br>

<form>
    <label for="username">Name:</label>
    <input type="text" id="username">

<br>
<label for="useremail">Email:</label>
<input type="text" id="username">

<br>
<label for="userphoneNo">Phone No:</label>
<input type="text" id="username">

<p>Are you 18+ ?</p>
<input type="radio" id="football"> 
<label for="yes or no">yes</label> 
<input type="radio" id="football">
<label for="yes or no">No</label>



<br>
<p>gender</p>
<input type="radio" id="gender"> 
<label for="gender">male</label> 
<input type="radio" id="gender">
<label for="gender">female</label>
<input type="radio" id="gender">
<label for="gender">others</label>



<h2 style="color: black;">Terms & Conditions</h2>

<p>What’s in these Terms?
This index is designed to help you navigate our Terms of Service (Terms). We hope this serves as a useful guide, but please ensure you read the Terms in full.

Welcome to YouTube!
This section outlines our relationship with you. It includes a description of the Service, defines our Agreement, and names your service provider.

Who May Use the Service?
This section sets out certain requirements for use of the Service, and defines categories of users.

Your Use of the Service
This section explains your rights to use the Service, and the conditions that apply to your use of the Service. It also explains how we may make changes to the Service.</p>

<br>
<input type="checkbox" id="accept">
<label for="accept">Accept the terms and condition</label>
<br>

</form>

<h1 class="headclass">HTML</h1>
<h1 id="headId">CSS</h1>
<h1 class="headclass">Javascript</h1>
<p style="color: blue;">The sun dipped below the horizon, casting a warm golden glow across the quiet village. Birds chirped softly as the evening breeze rustled through the trees, carrying the faint scent of blooming flowers. Children’s laughter echoed from the distant playground, blending with the gentle hum of the river nearby. In the heart of the village, an old clock tower stood tall, its hands frozen in time, reminding everyone of the stories and memories that lingered in every corner of the cobblestone streets.</p>




<head>
  <meta charset="UTF-8">
  <title>3D cube</title>
  <style>
    body { margin: 2; }
    canvas { display: block; }
  </style>
</head>
<body>
  <script src="https://cdn.jsdelivr.net/npm/three@0.152.2/build/three.min.js"></script>
  <script>
    // Scene setup
    const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(
      75, window.innerWidth / window.innerHeight, 0.1, 1000
    );
    const renderer = new THREE.WebGLRenderer({antialias:true});
    renderer.setSize(window.innerWidth, window.innerHeight);
    document.body.appendChild(renderer.domElement);

    // Cube geometry + material
    const geometry = new THREE.BoxGeometry();
    const material = new THREE.MeshStandardMaterial({ color:animate }); // blue color 
    const cube = new THREE.Mesh(geometry, material);
    scene.add(cube);

    // Lighting
    const light = new THREE.PointLight(0xffffff, 1);
    light.position.set(4, 5, 6);
    scene.add(light);

    camera.position.z = 6;

    // Animation loop
    function animate() {
      requestAnimationFrame(animate);
      cube.rotation.x += 0.01;
      cube.rotation.y += 0.02;
      renderer.render(scene, camera);
    }
    animate();
  </script>

</body>
</html>


