# box-model
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Box Model</title>
  <style>
    /* Write your CSS code here */
  div {
    width: 200px; height: 200px;
    border: solid black;
 }
 
 #one {
  background-color: gold;
  padding: 20px ; border: 10px solid ; 
 }

 #two {
  background-color: cadetblue;
  border: solid black; 
  border-width: 20px 10px; 
  margin-left: 260px;
 }

 #three {
  background-color: indianred;
  border :solid 10px;
  margin-left:40px;
  
 }

 p {
  margin: 0px;
 }


  </style>
</head>

<body>
<div id="one"> 
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at sapien porttitor urna elementum lacinia. In
    id magna pulvinar, ultricies lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque magna. Phasellus
    dolor metus, laoreet ac convallis sit amet, efficitur sed dolor.
</p>

</div>
<div id="two">

</div>
<div id="three">

</div>

</body>

</html>
