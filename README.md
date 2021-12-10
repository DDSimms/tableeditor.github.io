<html>
<head>
    <script data-ad-client="ca-pub-7062516577120484" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/proxy/qrICmeHGYUOy7dHO7P6qM12x9CfacD8nFDC9UIuzt_N-TMOjuPk56Gd6DSilnuGZ_ZxAZBXjFOquFx_oNqrlEV1dQE-NfBFHfmgcvnftmRaitVdr4f1zdkZ_t673dCcpCVqJJEjQfpsxYVB3MuAtih3bGmX-10hLqCiKSJk" sizes="32x32">
    <meta name="description" content="Free Data Analysis and Statistics Tool">
    <meta charset="utf-8" name="viewport"
        content= "width=device-width, initial-scale=1.0">

    <title>Table Analysis</title>
    <script data-ad-client="ca-pub-7062516577120484" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
    <script src='https://cdn.plot.ly/plotly-latest.min.js'></script>
    <script src='https://unpkg.com/simple-statistics@7.3.0/dist/simple-statistics.min.js'>
</script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
li p {
    margin: 0;
    padding: 0;
}
ldset
.topnav {
  overflow: hidden;
  background-color: #333;
}

table, td {
  border: 0.5px solid black;
  border-collapse: collapse;
  overflow:hidden;
  white-space: nowrap;
}

body{
background-color:#000000;
margin:0px;
padding:0px;
}
.button {
  background: rgba(0,0,0,0);
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button5 {
  background: rgba(0,0,0,0);
  color: black;
  border: 1px solid #555555;
  padding: 5px 179px;
  border-radius:5px;

}
.button43 {
  background: rgba(0,0,0,0);
  color: black;
  border: 2px solid #555555;
}
.button7 {
  background: rgba(0,0,0,0);
  color: black;
  border: 1px solid #555555;
  padding: 2px 4px;
}

.button5:hover {
  background-color: #555555;
  color: white;
}
.button43:hover {
  background-color: #555555;
  color: white;
}
.button7:hover {
  background-color: #555555;
  color: white;
}
.topnav {
  position: relative;
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 19px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #333;
  color: white;
}

.topnav-centered a {
  float: none;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
/* Right-aligned section inside the top navigation */
.topnav-right {
  float: right;
}
#main {
  transition: margin-left .5s;
  padding: 16px;
}
/* Responsive navigation menu (for mobile devices) */
@media screen and (max-width: 1600px) {
  .topnav a, .topnav-right {
    float: none;
    display: block;
  }

  .topnav-centered a {
    position: relative;
    top: 0;
    left: 0;
    transform: none;
  }
}

.sidenav {
  height: 100%;
  width: 0px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  padding-top: 25px;
  margin-top:72px;
  transition:.5s;
}

.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
}

.sidenav a:hover {
  color: #f1f1f1;
}
.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

.main {
  margin-left: 160px; /* Same as the width of the sidenav */
  font-size: 28px; /* Increased text to enable scrolling */
  padding: 0px 10px;
}

@media screen and (max-height: 1450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
input[type="file"] {
    display: none;
}
.the_file_upload {
    background-color: rgba(230,230,170,0.7);
    border: 1px solid black;
    display: inline-block;
    padding: 4px 5px;
    cursor: pointer;
    color:black;
    bottom: 100%;


}
.the_file_upload_2 {
    background-color: #99ff99;
    border: 1px solid #ccc;
    display: inline-block;
    padding: 6px 12px;
    cursor: pointer;
    border-radius:5px;
    color:black;
}
.dropbtn {
  background-color: rgba(210,220,190,0.5);
  padding: 4px 7px;
  font-size: 16px;
  border: 1px solid black;
  bottom: 100%;
  border-top: 1px solid black;
border-bottom: 2px solid black;

}
.dropbtn_2 {
   background-color: rgba(210,220,190,0.5);
  padding: 4px 8px;
  font-size: 16px;
  border: 1px solid black;
  bottom: 100%;
  border-top: 1px solid black;
border-bottom: 2px solid black;

}
.dropbtn_3 {
   background-color: rgba(210,220,190,0.5);
  padding: 4px 8px;
  font-size: 16px;
  border: 1px solid black;
  bottom: 100%;
  border-top: 1px solid black;
border-bottom: 2px solid black;

}
.dropbtn_4 {
   background-color: rgba(210,220,190,0.5);
  padding: 4px 8px;
  font-size: 16px;
  border: 1px solid black;
  bottom: 100%;
  border-top: 1px solid black;
border-bottom: 2px solid black;

}
.dropbtn_5 {
   background-color: rgba(210,220,190,0.5);
  padding: 4px 8px;
  font-size: 16px;
  border: 1px solid black;
  bottom: 100%;
  border-top: 1px solid black;
border-bottom: 2px solid black;

}
.dropdown {
  position: relative;
  display: inline-block;
  bottom: 100%;
}
.dropdown_2 {
  position: relative;
  display: inline-block;
  bottom: 100%;
}
.dropdown_3 {
  position: relative;
  display: inline-block;
  bottom: 100%;
}
.dropdown_4 {
  position: relative;
  display: inline-block;
  bottom: 100%;
}
.dropdown_5 {
  position: relative;
  display: inline-block;
  bottom: 100%;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 60px;
  box-shadow: 0px 8px 24px 0px rgba(0,0,0,0.2);
  bottom: 100%;

}
.dropdown-content_2 {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 60px;
  box-shadow: 0px 8px 24px 0px rgba(0,0,0,0.2);
  bottom: 100%;
  left: 50px;
}
.dropdown-content_3 {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 60px;
  box-shadow: 0px 8px 24px 0px rgba(0,0,0,0.2);
  bottom: 100%;
  left: 50px;
}
.dropdown-content_4 {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 60px;
  box-shadow: 0px 8px 24px 0px rgba(0,0,0,0.2);
  bottom: 100%;
  left: 30px;
}
.dropdown-content_5 {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 60px;
  box-shadow: 0px 8px 24px 0px rgba(0,0,0,0.2);
  bottom: 100%;
  left: 50px;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  bottom: 100%;
}
.dropdown-content_2 a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  bottom: 100%;
}
.dropdown-content_3 a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  bottom: 100%;
}
.dropdown-content_4 a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  bottom: 100%;
}
.dropdown-content_5 a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  bottom: 100%;
}

.dropdown-content a:hover {background-color: #ddd;bottom: 100%;}

.dropdown-content_2 a:hover {background-color: #ddd;bottom: 100%;}

.dropdown-content_3 a:hover {background-color: #ddd;bottom: 100%;}

.dropdown-content_4 a:hover {background-color: #ddd;bottom: 100%;}

.dropdown-content_5 a:hover {background-color: #ddd;bottom: 100%;}

.dropdown:hover .dropdown-content {display: block;bottom: 100%;}

.dropdown:hover .dropbtn {background-color: #3e8e41;bottom: 100%;}

.dropdown_2:hover .dropdown-content_2 {display: block;bottom: 100%;}

.dropdown_2:hover .dropbtn_2 {background-color: #3e8e41;bottom: 100%;}

.dropdown_3:hover .dropdown-content_3 {display: block;bottom: 100%;}

.dropdown_3:hover .dropbtn_3 {background-color: #3e8e41;bottom: 100%;}

.dropdown_4:hover .dropdown-content_4 {display: block;bottom: 100%;}

.dropdown_4:hover .dropbtn_4 {background-color: #3e8e41;bottom: 100%;}

.dropdown_5:hover .dropdown-content_5 {display: block;bottom: 100%;}

.dropdown_5:hover .dropbtn_5 {background-color: #3e8e41;bottom: 100%;}
</style>
</head>
<body>

<!-- Top navigation -->
<div class="topnav">

  <!-- Centered link -->
  <div class="topnav-centered">
    <a href="#home" class="active"><span style="font-size:30px;cursor:pointer;position: absolute;left:15;top:15" onclick="openNav()"><font style="color:grey">&#9776;</font></span><font style="font-size:30px;color:lightgrey;"> Table Analysis </font></a>
  </div>
</div>



 <center>
<fieldset style="background:url(https://images.pexels.com/photos/590011/pexels-photo-590011.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=300&w=500);width:70%;border:0px solid lightgrey;">
 <br><span style="background-color:rgba(123, 239, 178, .76)"><font style="color:burlywhite;font-family: 'Courier New', monospace;">Plotly.JS and more. <a href="about" style="color:black">About TESTING</a>| thanks to open source contributors</font> </span><br><div class="dropdown"><button class="dropbtn" type="button" style="background-color:rgba(255,200,255,0.6);" onclick="make_data_2()"><font size=1> Example Dataset </font></button></div><br>

<div class="dropdown"><button class="dropbtn" type="button" id="thistest"><font size=1><i class="fa fa-download"></i> Download Table</font></button></div><div class="dropdown"><button class="dropbtn" type="button" onclick="addRow()"><font size=1>Add row</font></button></div><div class="dropdown"><button class="dropbtn" type="button" onclick="addColumn()"><font size=1>Add column</font></button></div><div class="dropdown"><button class="dropbtn" type="button" onclick="deleteRow()"><font size=1>Delete row</font></button></div><div class="dropdown"><button class="dropbtn" type="button" onclick="deleteColumn()"><font size=1>Delete column</font></button></div>
<br>

<div id="div1">
<table style="border-top: 2px solid black;
border-bottom: 2px solid black;
border-left: 2px solid black;
border-right: 2px solid black;
overflow-y:scroll;
overflow-x:scroll;
height:250px;
width:570px;
display:block;background-color: rgba(255,255,255,0.5);" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="ninth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="tens_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

</table></div>

<div class="dropdown"><button class="dropbtn" style="height:32px;" type="button" onclick="math_again()"><font size=3>
📄+</font></button></div><div class="dropdown"><button onclick="catgraph()" style="height:32px" class='dropbtn'><font size=3>🔀🔀🔀</font></button></div><div class="dropdown"><button onclick="graph()" style="height:32px" class='dropbtn'><font size=3>📉📈📉</font></button></div><div class="dropdown"><button style="height:32px" class= "dropbtn" onclick="catogram();histogram()"><font size=3>📊📊📊</font></button></div><div class="dropdown"><button style="height:32px" class= "dropbtn" onclick="box()"><font size=3>🎻🎻🎻</font></button></div><div class="dropdown"><button style="height:32px" class='dropbtn'><font size=3>🕒<font></button><div class="dropdown-content"><a><b>Time Series</b>:<hr><input type="text" id="the_time_variable" placeholder="Variable (column name)"><br><input type="text" id="the_time" placeholder="Date (column name)"><button class="button button7" onclick="time()"><font size=4>Submit</font></button></a></div></div><div class="dropdown"><button style="height:32px" class='dropbtn'><font size=3>🌎</font></button><div class="dropdown-content"><a><b>Choropleth (Map)</b>:<br><font size=1>(Mean values per region)</font><hr><input type="text" id="the_locations" placeholder="Locations(column name)"><br><input type="text" id="the_map_values" placeholder="Values (column name)"><br><input type="radio" id="mapper" value="Countries"><label>World Countries (e.g. 'Japan','United States')</label><br><br>
<input type="radio" id="mapper" value="USA"><label>US States (e.g. 'NY', 'CO')</label>
<br><button class="button button7" onclick="maps()">
<font size=4>Submit</font></button></a></div></div><div class="dropdown_5"><button style="height:32px" class='dropbtn_5'><font size=3>📚🤖📚 <font></button><div class="dropdown-content_5">
<br><b>Decision-boundary Scatter Plot</b>:<br><form method="post" action="rand"><input type="text" name="KNN_x1" placeholder="x (column name)"><input type="text" name="KNN_x2" placeholder="x2 (column name)"><br><input type="text" name="KNN_y" placeholder="Classification (column name)"><br><button formtarget="_blank" onclick="to_python_format_3()" type="submit" id="ML_df" name="ML_df">Calculate</button></form><hr></div></div></div></div><div class='dropdown'><button class='dropbtn'>👪📊📈</button><div class='dropdown-content'><b>Group By:</b>:<br><font size=2>***Note: For plot readability, categories should all have fewer than 10 unique classes.<font </font><hr><form method="post" action="the_pca"><input type="text" name="part_1" placeholder="cat_1 (column name)"><br><input type="text" name="part_2" placeholder="cat_2 (column name)"><br><input type="text" name="part_3" placeholder="cat_3 (column name)"><br><input type="text" name="part_4" placeholder="numerical metric (column name)"><br>
<input type="radio" id="mean" name="spec_group_" value="mean">
<label for="male">Plot - Mean/Error Bars</label><hr>
<input type="radio" id="median" name="spec_group_" value="median">
<label for="female">Plot - Median/Boxplot</label><hr>
<input type="radio" id="count" name="spec_group_" value="count">
<label for="other">Plot - Total Count</label><hr>
<input type="radio" id="z-test" name="spec_group_" value="z-test">
<label for="male">Z-test (sub_sample>30)</label><br><input name='part_5' placeholder="group (column_name)"><br><input name='z-test' placeholder="subgroup_name">
<hr>
<br><button onclick="to_python_format_4()" type="submit" id="pca_df" name="pca_df">Calculate</button></form></div></div><div class="dropdown">
  <button style="height:32px" class='dropbtn' onclick="did_they();Play()"><font size=3>
💣</font></button> </div><div class="dropdown"><button style="height:32px" class='dropbtn'><font size=3>⚪</font></button><div class="dropdown-content">
<a><b>Venn Diagram</b>:<input id="first_ven" type="text" name="dist_x" placeholder="A (column name)"><input id="second_ven" type="text" name="dist_x2" placeholder="B (column name)"> <input id="first_venn" type="text" name="dist_x_sub" placeholder="A subgroup"><input id="second_venn" type="text" name="dist_x2_sub" placeholder="B subgroup"><br>

  <button id="AintB" onclick="venndiagramo()">(A ∩ B)</button></a></div></div>

<br><br>
<div id="the_new_table">
<table id='the_new_tab'>
<tr><td> <div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td></tr>
</table></div><div class='dropdown'><button class="dropbtn" onclick="sumation()"><font size=4>∑</font></button></div><div class='dropdown'><button class="dropbtn" onclick="mean()"><font size=4>µ ±</font></button></div><div class='dropdown'><button class="dropbtn" onclick="corr()"><font size=4>Corr(r)</font></button></div><div class='dropdown'><button class="dropbtn" onclick="two()"><font size=4>t-test</font></button></div><div class="dropdown_2"><button style="height:32px" class='dropbtn_2'><font size=4>χ2 tests<font></button><div class="dropdown-content_2"><b>Contingency Table/Test of Independence</b>:<hr><form method="post" action="crosstab_post"><input type="text" name="columns1" placeholder="cat_1 (column name)"><input type="text" name="columns2" placeholder="cat_2 (column name)">

  <button formtarget="_blank" onclick="to_python_format_2()" type="submit" id="cross" name="group_post">Calculate</button></form><div class="dropdown_3"><b>Goodness of fit</b><hr>
<label for="male">Bernoulli</label><input type="radio" id="Bernoulli" name="spec_group" value="Bernoulli"><br>
<label for="female">Binomial</label>
<input type="radio" id="Binomial" name="spec_group" value="Binomial">
<label for="male">Poisson</label><input type="radio" id="Poisson" name="spec_group" value="Poisson"><br>
  <button onclick="chi2g()">Calculate</button></a></div></div></div></div><div class="dropdown_3">
<button style="height:32px" class='dropbtn_3'><font size=4>^β0+^β1x+^β2x<font></button><div class="dropdown-content_3">
<a><b>Regression Model (Statsmodels)</b>:<br><form method="post" action="regr"><input type="text" name="Pred_x1" placeholder="x (column name)"><input type="text" name="Pred_x2" placeholder="x2 (column name)"><br><input type="text" name="Pred_x3" placeholder="x3 (column name)"><br><input type="text" name="Pred_y" placeholder="y (column name)"><br><input type="radio" id="linear" name="The_type" value="linear">
<label for="linear">Linear</label><input type="radio" id="logistic" name="The_type" value="logistic">
<label for="logistic">Logistic</label><br><button formtarget="_blank" onclick="to_python_format_5()" type="submit" id="regr" name="regr">Calculate</button></form></a></div></div></a></div></div>
<div class='dropdown'><button class='dropbtn'></button></div>
<div id='myDiv'></div>
<div id='myDiv_2'></div>
<br>
<div style="background-color:#80ced6"><h3><font style="font-family: 'Courier New', monospace;">How-to guide:</font></h3><a href="how_to" style="color:black">Data Visualization</a><br><br><a href="stats" style="color:black">Statistics Reference</a><br><br></div>
<br><div style="background-color:lightblue"><h3><font style="font-family: 'Courier New', monospace;">Web Development and Statistics:</font></h3><a href="flask_tutorial" style="color:black"> Web Development with Python and Flask</a><br><br><a href="dec_bounds" style="color:black"> Decision Boundaries with MLXtend</a><br><br><a href="linear_population_growth" style="color:black"> Linear Population Growth with Mactrices</a><br><br><a href="Regression" style="color:black"> Statistical Regression as an Optimization</a><br><br></div>
<br></fieldset><fieldset style="background-color:white;width:70%;border:0px solid lightgrey"><font style="font-family: 'Courier New', monospace;">TableAnalysis is on Medium:</font><br>
<div id="medium-widget"></div>
    <script src="https://medium-widget.pixelpoint.io/widget.js"></script>
    <script>MediumWidget.Init({renderTo: '#medium-widget', params: {"resource":"https://medium.com/@ddsim","postsPerLine":2,"limit":4,"picture":"big","fields":["description","author","claps","likes","publishAt"],"ratio":"landscape"}})</script>

<script>
function chi2g(){
var num_rows=document.getElementById('myTable').rows.length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_cols;i++){
var column=[];
for(j=0;j<num_rows;j++){
if (j!=0){
column.push(document.getElementById('myTable').rows[j].cells[i].innerText)}
}

if(document.getElementById('Poisson').checked){
try{document.getElementById('the_new_tab').rows[0].cells[i].innerHTML='<b>'+ss.chiSquaredGoodnessOfFit(column, ss.poissonDistribution, 0.05)}catch(err){if(!(document.getElementById('the_new_tab').rows[0].cells[i].innerText.includes('true'))){document.getElementById('the_new_tab').rows[0].cells[i].innerHTML="false";}}}

if(document.getElementById('Binomial').checked){try{document.getElementById('the_new_tab').rows[0].cells[i].innerHTML='<b>'+ss.chiSquaredGoodnessOfFit(column, ss.binomialDistribution, 0.05)}catch(err){if(!(document.getElementById('the_new_tab').rows[0].cells[i].innerText.includes('true'))){document.getElementById('the_new_tab').rows[0].cells[i].innerHTML="false";}}}
if(document.getElementById('Bernoulli').checked){try{document.getElementById('the_new_tab').rows[0].cells[i].innerHTML='<b>'+ss.chiSquaredGoodnessOfFit(column, ss.bernoulliDistribution, 0.05)}catch(err){if(!(document.getElementById('the_new_tab').rows[0].cells[i].innerText.includes('true'))){document.getElementById('the_new_tab').rows[0].cells[i].innerHTML="false";}}}
}}
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
document.getElementById('google_search').style='display:none';
document.getElementById('div1').innerHTML=`
    <div id="div1">
<table style="border-top: 2px solid black;
border-bottom: 2px solid black;
border-left: 2px solid black;
border-right: 2px solid black;
overflow-y:scroll;
overflow-x:scroll;
height:200px;
width:200px;
display:block;background-color: rgba(255,255,255,0.5);" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

</table></div>`;
	document.getElementById('the_new_table').innerHTML=`<table style="height:57px;background-color: rgba(255,255,255,0.7);"id='the_new_tab'>
<tr><td> <div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td></tr></table>`;
   document.getElementById('myTable').style.width='275px';
   document.getElementById('the_new_tab').style.width='275px';
}else{
document.getElementById('the_file').style.padding='10px 12px';}

function make_data_2(){
document.getElementById('myTable').innerHTML=`
<thead>\n  <tr> <td><input name="header" placeholder="Edit" value="placeholder" style="width:157px;border:0px;background-color:#f5f2d0;"></td>
	<td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Country" style="width:157px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Life Expectancy Overall" style="width:157px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Life Expectancy (Female)" style="width:157px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Life Expectancy (Male)" style="width:157px;border:0px;background-color:#f5f2d0;"></td></tr>\n  </thead>\n  <tbody>\n    <tr>\n      <th>0</th>\n      <td>1</td>\n      <td>Hong Kong</td>\n      <td>85.29</td>\n      <td>88.17</td>\n      <td>82.38</td>\n    </tr>\n    <tr>\n      <th>1</th>\n      <td>2</td>\n      <td>Japan</td>\n      <td>85.03</td>\n      <td>88.09</td>\n      <td>81.91</td>\n    </tr>\n    <tr>\n      <th>2</th>\n      <td>3</td>\n      <td>Macao</td>\n      <td>84.68</td>\n      <td>87.62</td>\n      <td>81.73</td>\n    </tr>\n    <tr>\n      <th>3</th>\n      <td>4</td>\n      <td>Switzerland</td>\n      <td>84.25</td>\n      <td>86.02</td>\n      <td>82.42</td>\n    </tr>\n    <tr>\n      <th>4</th>\n      <td>5</td>\n      <td>Singapore</td>\n      <td>84.07</td>\n      <td>86.15</td>\n      <td>82.06</td>\n    </tr>\n    <tr>\n      <th>5</th>\n      <td>6</td>\n      <td>Italy</td>\n      <td>84.01</td>\n      <td>85.97</td>\n      <td>81.90</td>\n    </tr>\n    <tr>\n      <th>6</th>\n      <td>7</td>\n      <td>Spain</td>\n      <td>83.99</td>\n      <td>86.68</td>\n      <td>81.27</td>\n    </tr>\n    <tr>\n      <th>7</th>\n      <td>8</td>\n      <td>Australia</td>\n      <td>83.94</td>\n      <td>85.80</td>\n      <td>82.08</td>\n    </tr>\n    <tr>\n      <th>8</th>\n      <td>9</td>\n      <td>Channel Islands</td>\n      <td>83.60</td>\n      <td>85.31</td>\n      <td>81.82</td>\n    </tr>\n    <tr>\n      <th>9</th>\n      <td>10</td>\n      <td>Iceland</td>\n      <td>83.52</td>\n      <td>84.90</td>\n      <td>82.15</td>\n    </tr>\n    <tr>\n      <th>10</th>\n      <td>11</td>\n      <td>South Korea</td>\n      <td>83.50</td>\n      <td>86.42</td>\n      <td>80.46</td>\n    </tr>\n    <tr>\n      <th>11</th>\n      <td>12</td>\n      <td>Israel</td>\n      <td>83.49</td>\n      <td>84.91</td>\n      <td>81.98</td>\n    </tr>\n    <tr>\n      <th>12</th>\n      <td>13</td>\n      <td>Sweden</td>\n      <td>83.33</td>\n      <td>84.97</td>\n      <td>81.69</td>\n    </tr>\n    <tr>\n      <th>13</th>\n      <td>14</td>\n      <td>France</td>\n      <td>83.13</td>\n      <td>85.82</td>\n      <td>80.32</td>\n    </tr>\n    <tr>\n      <th>14</th>\n      <td>14</td>\n      <td>Martinique</td>\n      <td>83.13</td>\n      <td>86.10</td>\n      <td>79.85</td>\n    </tr>\n    <tr>\n      <th>15</th>\n      <td>15</td>\n      <td>Malta</td>\n      <td>83.06</td>\n      <td>84.68</td>\n      <td>81.37</td>\n    </tr>\n    <tr>\n      <th>16</th>\n      <td>16</td>\n      <td>Canada</td>\n      <td>82.96</td>\n      <td>84.74</td>\n      <td>81.15</td>\n    </tr>\n    <tr>\n      <th>17</th>\n      <td>17</td>\n      <td>Norway</td>\n      <td>82.94</td>\n      <td>84.78</td>\n      <td>81.11</td>\n    </tr>\n    <tr>\n      <th>18</th>\n      <td>18</td>\n      <td>Ireland</td>\n      <td>82.81</td>\n      <td>84.32</td>\n      <td>81.29</td>\n    </tr>\n    <tr>\n      <th>19</th>\n      <td>19</td>\n      <td>New Zealand</td>\n      <td>82.80</td>\n      <td>84.38</td>\n      <td>81.20</td>\n    </tr>\n    <tr>\n      <th>20</th>\n      <td>19</td>\n      <td>Greece</td>\n      <td>82.80</td>\n      <td>85.08</td>\n      <td>80.52</td>\n    </tr>\n    <tr>\n      <th>21</th>\n      <td>20</td>\n      <td>Luxembourg</td>\n      <td>82.79</td>\n      <td>84.76</td>\n      <td>80.83</td>\n    </tr>\n    <tr>\n      <th>22</th>\n      <td>21</td>\n      <td>Netherlands</td>\n      <td>82.78</td>\n      <td>84.35</td>\n      <td>81.20</td>\n    </tr>\n    <tr>\n      <th>23</th>\n      <td>22</td>\n      <td>Guadeloupe</td>\n      <td>82.74</td>\n      <td>85.94</td>\n      <td>79.16</td>\n    </tr>\n    <tr>\n      <th>24</th>\n      <td>23</td>\n      <td>Portugal</td>\n      <td>82.65</td>\n      <td>85.28</td>\n      <td>79.79</td>\n    </tr>\n    <tr>\n      <th>25</th>\n      <td>24</td>\n      <td>Finland</td>\n      <td>82.48</td>\n      <td>85.14</td>\n      <td>79.82</td>\n    </tr>\n    <tr>\n      <th>26</th>\n      <td>25</td>\n      <td>Belgium</td>\n      <td>82.17</td>\n      <td>84.31</td>\n      <td>80.00</td>\n    </tr>\n    <tr>\n      <th>27</th>\n      <td>26</td>\n      <td>Austria</td>\n      <td>82.05</td>\n      <td>84.19</td>\n      <td>79.88</td>\n    </tr>\n    <tr>\n      <th>28</th>\n      <td>27</td>\n      <td>Germany</td>\n      <td>81.88</td>\n      <td>84.14</td>\n      <td>79.62</td>\n    </tr>\n    <tr>\n      <th>29</th>\n      <td>28</td>\n      <td>Slovenia</td>\n      <td>81.85</td>\n      <td>84.44</td>\n      <td>79.26</td>\n    </tr>\n    <tr>\n      <th>30</th>\n      <td>29</td>\n      <td>United Kingdom</td>\n      <td>81.77</td>\n      <td>83.28</td>\n      <td>80.22</td>\n    </tr>\n    <tr>\n      <th>31</th>\n      <td>30</td>\n      <td>Réunion</td>\n      <td>81.55</td>\n      <td>84.45</td>\n      <td>78.52</td>\n    </tr>\n    <tr>\n      <th>32</th>\n      <td>31</td>\n      <td>Cyprus</td>\n      <td>81.51</td>\n      <td>83.45</td>\n      <td>79.55</td>\n    </tr>\n    <tr>\n      <th>33</th>\n      <td>32</td>\n      <td>Denmark</td>\n      <td>81.40</td>\n      <td>83.27</td>\n      <td>79.54</td>\n    </tr>\n    <tr>\n      <th>34</th>\n      <td>33</td>\n      <td>U.S. Virgin Islands</td>\n      <td>81.17</td>\n      <td>83.52</td>\n      <td>78.64</td>\n    </tr>\n    <tr>\n      <th>35</th>\n      <td>34</td>\n      <td>Taiwan</td>\n      <td>81.04</td>\n      <td>83.64</td>\n      <td>78.49</td>\n    </tr>\n    <tr>\n      <th>36</th>\n      <td>35</td>\n      <td>Costa Rica</td>\n      <td>80.94</td>\n      <td>83.39</td>\n      <td>78.53</td>\n    </tr>\n    <tr>\n      <th>37</th>\n      <td>36</td>\n      <td>Chile</td>\n      <td>80.74</td>\n      <td>82.80</td>\n      <td>78.54</td>\n    </tr>\n    <tr>\n      <th>38</th>\n      <td>36</td>\n      <td>Guam</td>\n      <td>80.74</td>\n      <td>83.98</td>\n      <td>77.63</td>\n    </tr>\n    <tr>\n      <th>39</th>\n      <td>37</td>\n      <td>Qatar</td>\n      <td>80.73</td>\n      <td>82.49</td>\n      <td>79.78</td>\n    </tr>\n    <tr>\n      <th>40</th>\n      <td>38</td>\n      <td>Puerto Rico</td>\n      <td>80.69</td>\n      <td>83.92</td>\n      <td>77.27</td>\n    </tr>\n    <tr>\n      <th>41</th>\n      <td>39</td>\n      <td>French Guiana</td>\n      <td>80.53</td>\n      <td>83.38</td>\n      <td>77.80</td>\n    </tr>\n    <tr>\n      <th>42</th>\n      <td>40</td>\n      <td>Maldives</td>\n      <td>79.89</td>\n      <td>81.58</td>\n      <td>78.53</td>\n    </tr>\n    <tr>\n      <th>43</th>\n      <td>41</td>\n      <td>Mayotte</td>\n      <td>79.85</td>\n      <td>83.24</td>\n      <td>76.62</td>\n    </tr>\n    <tr>\n      <th>44</th>\n      <td>41</td>\n      <td>Czech Republic (Czechia)</td>\n      <td>79.85</td>\n      <td>82.35</td>\n      <td>77.33</td>\n    </tr>\n    <tr>\n      <th>45</th>\n      <td>42</td>\n      <td>Barbados</td>\n      <td>79.64</td>\n      <td>80.85</td>\n      <td>78.36</td>\n    </tr>\n    <tr>\n      <th>46</th>\n      <td>43</td>\n      <td>Curaçao</td>\n      <td>79.41</td>\n      <td>82.08</td>\n      <td>76.42</td>\n    </tr>\n    <tr>\n      <th>47</th>\n      <td>44</td>\n      <td>Poland</td>\n      <td>79.27</td>\n      <td>82.98</td>\n      <td>75.51</td>\n    </tr>\n    <tr>\n      <th>48</th>\n      <td>44</td>\n      <td>Lebanon</td>\n      <td>79.27</td>\n      <td>81.17</td>\n      <td>77.53</td>\n    </tr>\n    <tr>\n      <th>49</th>\n      <td>45</td>\n      <td>Cuba</td>\n      <td>79.18</td>\n      <td>81.12</td>\n      <td>77.25</td>\n    </tr>\n    <tr>\n      <th>50</th>\n      <td>45</td>\n      <td>Estonia</td>\n      <td>79.18</td>\n      <td>83.06</td>\n      <td>74.98</td>\n    </tr>\n    <tr>\n      <th>51</th>\n      <td>46</td>\n      <td>United States</td>\n      <td>79.11</td>\n      <td>81.65</td>\n      <td>76.61</td>\n    </tr>\n    <tr>\n      <th>52</th>\n      <td>47</td>\n      <td>Panama</td>\n      <td>79.10</td>\n      <td>82.20</td>\n      <td>76.14</td>\n    </tr>\n    <tr>\n      <th>53</th>\n      <td>48</td>\n      <td>Croatia</td>\n      <td>79.02</td>\n      <td>82.02</td>\n      <td>75.95</td>\n    </tr>\n    <tr>\n      <th>54</th>\n      <td>49</td>\n      <td>Albania</td>\n      <td>78.96</td>\n      <td>80.48</td>\n      <td>77.48</td>\n    </tr>\n    <tr>\n      <th>55</th>\n      <td>50</td>\n      <td>Oman</td>\n      <td>78.58</td>\n      <td>80.94</td>\n      <td>76.90</td>\n    </tr>\n    <tr>\n      <th>56</th>\n      <td>51</td>\n      <td>United Arab Emirates</td>\n      <td>78.46</td>\n      <td>79.80</td>\n      <td>77.79</td>\n    </tr>\n    <tr>\n      <th>57</th>\n      <td>52</td>\n      <td>Turkey</td>\n      <td>78.45</td>\n      <td>81.21</td>\n      <td>75.57</td>\n    </tr>\n    <tr>\n      <th>58</th>\n      <td>53</td>\n      <td>Uruguay</td>\n      <td>78.43</td>\n      <td>81.88</td>\n      <td>74.75</td>\n    </tr>\n    <tr>\n      <th>59</th>\n      <td>54</td>\n      <td>French Polynesia</td>\n      <td>78.23</td>\n      <td>80.41</td>\n      <td>76.23</td>\n    </tr>\n    <tr>\n      <th>60</th>\n      <td>55</td>\n      <td>New Caledonia</td>\n      <td>78.16</td>\n      <td>80.89</td>\n      <td>75.61</td>\n    </tr>\n    <tr>\n      <th>61</th>\n      <td>56</td>\n      <td>Slovakia</td>\n      <td>78.00</td>\n      <td>81.35</td>\n      <td>74.59</td>\n    </tr>\n    <tr>\n      <th>62</th>\n      <td>57</td>\n      <td>Bosnia and Herzegovina</td>\n      <td>77.93</td>\n      <td>80.32</td>\n      <td>75.48</td>\n    </tr>\n    <tr>\n      <th>63</th>\n      <td>58</td>\n      <td>Colombia</td>\n      <td>77.87</td>\n      <td>80.54</td>\n      <td>75.18</td>\n    </tr>\n    <tr>\n      <th>64</th>\n      <td>59</td>\n      <td>Thailand</td>\n      <td>77.74</td>\n      <td>81.34</td>\n      <td>74.16</td>\n    </tr>\n    <tr>\n      <th>65</th>\n      <td>60</td>\n      <td>Bahrain</td>\n      <td>77.73</td>\n      <td>78.88</td>\n      <td>76.87</td>\n    </tr>\n    <tr>\n      <th>66</th>\n      <td>61</td>\n      <td>Ecuador</td>\n      <td>77.71</td>\n      <td>80.45</td>\n      <td>75.05</td>\n    </tr>\n    <tr>\n      <th>67</th>\n      <td>62</td>\n      <td>Sri Lanka</td>\n      <td>77.56</td>\n      <td>80.74</td>\n      <td>74.25</td>\n    </tr>\n    <tr>\n      <th>68</th>\n      <td>63</td>\n      <td>Algeria</td>\n      <td>77.50</td>\n      <td>78.76</td>\n      <td>76.30</td>\n    </tr>\n    <tr>\n      <th>69</th>\n      <td>64</td>\n      <td>China</td>\n      <td>77.47</td>\n      <td>79.73</td>\n      <td>75.36</td>\n    </tr>\n    <tr>\n      <th>70</th>\n      <td>64</td>\n      <td>Antigua and Barbuda</td>\n      <td>77.47</td>\n      <td>78.58</td>\n      <td>76.26</td>\n    </tr>\n    <tr>\n      <th>71</th>\n      <td>65</td>\n      <td>Peru</td>\n      <td>77.44</td>\n      <td>80.15</td>\n      <td>74.87</td>\n    </tr>\n    <tr>\n      <th>72</th>\n      <td>66</td>\n      <td>Morocco</td>\n      <td>77.43</td>\n      <td>78.66</td>\n      <td>76.17</td>\n    </tr>\n    <tr>\n      <th>73</th>\n      <td>67</td>\n      <td>Montenegro</td>\n      <td>77.39</td>\n      <td>79.77</td>\n      <td>74.99</td>\n    </tr>\n    <tr>\n      <th>74</th>\n      <td>68</td>\n      <td>Tunisia</td>\n      <td>77.36</td>\n      <td>79.34</td>\n      <td>75.37</td>\n    </tr>\n    <tr>\n      <th>75</th>\n      <td>69</td>\n      <td>Iran</td>\n      <td>77.33</td>\n      <td>78.54</td>\n      <td>76.22</td>\n    </tr>\n    <tr>\n      <th>76</th>\n      <td>70</td>\n      <td>Hungary</td>\n      <td>77.31</td>\n      <td>80.66</td>\n      <td>73.78</td>\n    </tr>\n    <tr>\n      <th>77</th>\n      <td>71</td>\n      <td>Argentina</td>\n      <td>77.17</td>\n      <td>80.42</td>\n      <td>73.82</td>\n    </tr>\n    <tr>\n      <th>78</th>\n      <td>72</td>\n      <td>Aruba</td>\n      <td>76.79</td>\n      <td>79.10</td>\n      <td>74.26</td>\n    </tr>\n    <tr>\n      <th>79</th>\n      <td>73</td>\n      <td>Saint Lucia</td>\n      <td>76.67</td>\n      <td>78.06</td>\n      <td>75.27</td>\n    </tr>\n    <tr>\n      <th>80</th>\n      <td>74</td>\n      <td>Malaysia</td>\n      <td>76.65</td>\n      <td>78.78</td>\n      <td>74.71</td>\n    </tr>\n    <tr>\n      <th>81</th>\n      <td>75</td>\n      <td>Brazil</td>\n      <td>76.57</td>\n      <td>80.14</td>\n      <td>73.01</td>\n    </tr>\n    <tr>\n      <th>82</th>\n      <td>76</td>\n      <td>Romania</td>\n      <td>76.50</td>\n      <td>79.91</td>\n      <td>73.13</td>\n    </tr>\n    <tr>\n      <th>83</th>\n      <td>77</td>\n      <td>Serbia</td>\n      <td>76.47</td>\n      <td>79.05</td>\n      <td>73.89</td>\n    </tr>\n    <tr>\n      <th>84</th>\n      <td>78</td>\n      <td>Lithuania</td>\n      <td>76.41</td>\n      <td>81.70</td>\n      <td>70.97</td>\n    </tr>\n    <tr>\n      <th>85</th>\n      <td>79</td>\n      <td>Brunei</td>\n      <td>76.35</td>\n      <td>77.64</td>\n      <td>75.17</td>\n    </tr>\n    <tr>\n      <th>86</th>\n      <td>80</td>\n      <td>North Macedonia</td>\n      <td>76.26</td>\n      <td>78.32</td>\n      <td>74.26</td>\n    </tr>\n    <tr>\n      <th>87</th>\n      <td>81</td>\n      <td>Syria</td>\n      <td>76.06</td>\n      <td>79.11</td>\n      <td>73.13</td>\n    </tr>\n    <tr>\n      <th>88</th>\n      <td>82</td>\n      <td>Honduras</td>\n      <td>75.87</td>\n      <td>78.14</td>\n      <td>73.57</td>\n    </tr>\n    <tr>\n      <th>89</th>\n      <td>83</td>\n      <td>Kuwait</td>\n      <td>75.85</td>\n      <td>77.06</td>\n      <td>75.09</td>\n    </tr>\n    <tr>\n      <th>90</th>\n      <td>84</td>\n      <td>Vietnam</td>\n      <td>75.77</td>\n      <td>79.85</td>\n      <td>71.73</td>\n    </tr>\n    <tr>\n      <th>91</th>\n      <td>85</td>\n      <td>Latvia</td>\n      <td>75.73</td>\n      <td>80.37</td>\n      <td>70.81</td>\n    </tr>\n    <tr>\n      <th>92</th>\n      <td>86</td>\n      <td>Saudi Arabia</td>\n      <td>75.69</td>\n      <td>77.37</td>\n      <td>74.47</td>\n    </tr>\n    <tr>\n      <th>93</th>\n      <td>87</td>\n      <td>Armenia</td>\n      <td>75.55</td>\n      <td>78.90</td>\n      <td>71.82</td>\n    </tr>\n    <tr>\n      <th>94</th>\n      <td>88</td>\n      <td>Mauritius</td>\n      <td>75.51</td>\n      <td>78.92</td>\n      <td>72.21</td>\n    </tr>\n    <tr>\n      <th>95</th>\n      <td>89</td>\n      <td>Bulgaria</td>\n      <td>75.49</td>\n      <td>79.06</td>\n      <td>72.05</td>\n    </tr>\n    <tr>\n      <th>96</th>\n      <td>90</td>\n      <td>Mexico</td>\n      <td>75.41</td>\n      <td>78.17</td>\n      <td>72.62</td>\n    </tr>\n    <tr>\n      <th>97</th>\n      <td>91</td>\n      <td>Nicaragua</td>\n      <td>75.23</td>\n      <td>78.65</td>\n      <td>71.75</td>\n    </tr>\n    <tr>\n      <th>98</th>\n      <td>92</td>\n      <td>Belarus</td>\n      <td>75.20</td>\n      <td>79.90</td>\n      <td>70.15</td>\n    </tr>\n    <tr>\n      <th>99</th>\n      <td>93</td>\n      <td>Belize</td>\n      <td>75.09</td>\n      <td>78.25</td>\n      <td>72.14</td>\n    </tr>\n    <tr>\n      <th>100</th>\n      <td>94</td>\n      <td>Guatemala</td>\n      <td>75.05</td>\n      <td>77.89</td>\n      <td>72.14</td>\n    </tr>\n    <tr>\n      <th>101</th>\n      <td>95</td>\n      <td>Jordan</td>\n      <td>75.01</td>\n      <td>76.82</td>\n      <td>73.28</td>\n    </tr>\n    <tr>\n      <th>102</th>\n      <td>96</td>\n      <td>Jamaica</td>\n      <td>74.88</td>\n      <td>76.60</td>\n      <td>73.17</td>\n    </tr>\n    <tr>\n      <th>103</th>\n      <td>97</td>\n      <td>Dominican Republic</td>\n      <td>74.65</td>\n      <td>77.90</td>\n      <td>71.58</td>\n    </tr>\n    <tr>\n      <th>104</th>\n      <td>98</td>\n      <td>State of Palestine</td>\n      <td>74.62</td>\n      <td>76.38</td>\n      <td>72.92</td>\n    </tr>\n    <tr>\n      <th>105</th>\n      <td>99</td>\n      <td>Paraguay</td>\n      <td>74.59</td>\n      <td>76.78</td>\n      <td>72.55</td>\n    </tr>\n    <tr>\n      <th>106</th>\n      <td>100</td>\n      <td>Bahamas</td>\n      <td>74.28</td>\n      <td>76.51</td>\n      <td>71.95</td>\n    </tr>\n    <tr>\n      <th>107</th>\n      <td>101</td>\n      <td>Georgia</td>\n      <td>74.24</td>\n      <td>78.54</td>\n      <td>69.85</td>\n    </tr>\n    <tr>\n      <th>108</th>\n      <td>102</td>\n      <td>Micronesia</td>\n      <td>74.08</td>\n      <td>77.20</td>\n      <td>71.14</td>\n    </tr>\n    <tr>\n      <th>109</th>\n      <td>103</td>\n      <td>El Salvador</td>\n      <td>74.06</td>\n      <td>78.48</td>\n      <td>69.27</td>\n    </tr>\n    <tr>\n      <th>110</th>\n      <td>104</td>\n      <td>Trinidad and Tobago</td>\n      <td>73.91</td>\n      <td>76.66</td>\n      <td>71.24</td>\n    </tr>\n    <tr>\n      <th>111</th>\n      <td>105</td>\n      <td>Kazakhstan</td>\n      <td>73.90</td>\n      <td>77.97</td>\n      <td>69.55</td>\n    </tr>\n    <tr>\n      <th>112</th>\n      <td>106</td>\n      <td>Samoa</td>\n      <td>73.75</td>\n      <td>75.97</td>\n      <td>71.69</td>\n    </tr>\n    <tr>\n      <th>113</th>\n      <td>107</td>\n      <td>Seychelles</td>\n      <td>73.74</td>\n      <td>77.71</td>\n      <td>70.26</td>\n    </tr>\n    <tr>\n      <th>114</th>\n      <td>108</td>\n      <td>Cabo Verde</td>\n      <td>73.58</td>\n      <td>76.83</td>\n      <td>70.15</td>\n    </tr>\n    <tr>\n      <th>115</th>\n      <td>109</td>\n      <td>Bangladesh</td>\n      <td>73.57</td>\n      <td>75.60</td>\n      <td>71.80</td>\n    </tr>\n    <tr>\n      <th>116</th>\n      <td>110</td>\n      <td>Libya</td>\n      <td>73.44</td>\n      <td>76.46</td>\n      <td>70.61</td>\n    </tr>\n    <tr>\n      <th>117</th>\n      <td>111</td>\n      <td>Solomon Islands</td>\n      <td>73.38</td>\n      <td>75.31</td>\n      <td>71.60</td>\n    </tr>\n    <tr>\n      <th>118</th>\n      <td>112</td>\n      <td>Azerbaijan</td>\n      <td>73.33</td>\n      <td>75.87</td>\n      <td>70.76</td>\n    </tr>\n    <tr>\n      <th>119</th>\n      <td>113</td>\n      <td>Russia</td>\n      <td>72.99</td>\n      <td>78.15</td>\n      <td>67.62</td>\n    </tr>\n    <tr>\n      <th>120</th>\n      <td>114</td>\n      <td>St. Vincent &amp; Grenadines</td>\n      <td>72.98</td>\n      <td>75.62</td>\n      <td>70.66</td>\n    </tr>\n    <tr>\n      <th>121</th>\n      <td>115</td>\n      <td>North Korea</td>\n      <td>72.89</td>\n      <td>76.37</td>\n      <td>69.26</td>\n    </tr>\n    <tr>\n      <th>122</th>\n      <td>116</td>\n      <td>Bhutan</td>\n      <td>72.77</td>\n      <td>73.33</td>\n      <td>72.27</td>\n    </tr>\n    <tr>\n      <th>123</th>\n      <td>117</td>\n      <td>Grenada</td>\n      <td>72.59</td>\n      <td>75.16</td>\n      <td>70.24</td>\n    </tr>\n    <tr>\n      <th>124</th>\n      <td>118</td>\n      <td>Egypt</td>\n      <td>72.54</td>\n      <td>74.95</td>\n      <td>70.23</td>\n    </tr>\n    <tr>\n      <th>125</th>\n      <td>119</td>\n      <td>Ukraine</td>\n      <td>72.50</td>\n      <td>77.27</td>\n      <td>67.56</td>\n    </tr>\n    <tr>\n      <th>126</th>\n      <td>120</td>\n      <td>Bolivia</td>\n      <td>72.35</td>\n      <td>75.35</td>\n      <td>69.50</td>\n    </tr>\n    <tr>\n      <th>127</th>\n      <td>121</td>\n      <td>Venezuela</td>\n      <td>72.34</td>\n      <td>76.25</td>\n      <td>68.59</td>\n    </tr>\n    <tr>\n      <th>128</th>\n      <td>122</td>\n      <td>Indonesia</td>\n      <td>72.32</td>\n      <td>74.64</td>\n      <td>70.12</td>\n    </tr>\n    <tr>\n      <th>129</th>\n      <td>123</td>\n      <td>Moldova</td>\n      <td>72.30</td>\n      <td>76.53</td>\n      <td>68.02</td>\n    </tr>\n    <tr>\n      <th>130</th>\n      <td>124</td>\n      <td>Suriname</td>\n      <td>72.13</td>\n      <td>75.55</td>\n      <td>68.88</td>\n    </tr>\n    <tr>\n      <th>131</th>\n      <td>125</td>\n      <td>Uzbekistan</td>\n      <td>72.04</td>\n      <td>74.26</td>\n      <td>69.80</td>\n    </tr>\n    <tr>\n      <th>132</th>\n      <td>126</td>\n      <td>Kyrgyzstan</td>\n      <td>71.95</td>\n      <td>76.03</td>\n      <td>67.85</td>\n    </tr>\n    <tr>\n      <th>133</th>\n      <td>127</td>\n      <td>Tajikistan</td>\n      <td>71.76</td>\n      <td>74.11</td>\n      <td>69.50</td>\n    </tr>\n    <tr>\n      <th>134</th>\n      <td>128</td>\n      <td>Nepal</td>\n      <td>71.74</td>\n      <td>73.23</td>\n      <td>70.13</td>\n    </tr>\n    <tr>\n      <th>135</th>\n      <td>129</td>\n      <td>Philippines</td>\n      <td>71.66</td>\n      <td>75.92</td>\n      <td>67.67</td>\n    </tr>\n    <tr>\n      <th>136</th>\n      <td>130</td>\n      <td>Tonga</td>\n      <td>71.32</td>\n      <td>73.38</td>\n      <td>69.28</td>\n    </tr>\n    <tr>\n      <th>137</th>\n      <td>131</td>\n      <td>Iraq</td>\n      <td>71.08</td>\n      <td>73.21</td>\n      <td>68.96</td>\n    </tr>\n    <tr>\n      <th>138</th>\n      <td>131</td>\n      <td>Western Sahara</td>\n      <td>71.08</td>\n      <td>73.19</td>\n      <td>69.36</td>\n    </tr>\n    <tr>\n      <th>139</th>\n      <td>132</td>\n      <td>Sao Tome &amp; Principe</td>\n      <td>71.01</td>\n      <td>73.50</td>\n      <td>68.54</td>\n    </tr>\n    <tr>\n      <th>140</th>\n      <td>133</td>\n      <td>Vanuatu</td>\n      <td>70.99</td>\n      <td>72.75</td>\n      <td>69.40</td>\n    </tr>\n    <tr>\n      <th>141</th>\n      <td>134</td>\n      <td>Cambodia</td>\n      <td>70.54</td>\n      <td>72.69</td>\n      <td>68.20</td>\n    </tr>\n    <tr>\n      <th>142</th>\n      <td>135</td>\n      <td>Mongolia</td>\n      <td>70.53</td>\n      <td>74.79</td>\n      <td>66.43</td>\n    </tr>\n    <tr>\n      <th>143</th>\n      <td>136</td>\n      <td>India</td>\n      <td>70.42</td>\n      <td>71.80</td>\n      <td>69.16</td>\n    </tr>\n    <tr>\n      <th>144</th>\n      <td>137</td>\n      <td>Guyana</td>\n      <td>70.26</td>\n      <td>73.53</td>\n      <td>67.22</td>\n    </tr>\n    <tr>\n      <th>145</th>\n      <td>138</td>\n      <td>Timor-Leste</td>\n      <td>70.18</td>\n      <td>72.36</td>\n      <td>68.14</td>\n    </tr>\n    <tr>\n      <th>146</th>\n      <td>139</td>\n      <td>Rwanda</td>\n      <td>70.00</td>\n      <td>72.16</td>\n      <td>67.75</td>\n    </tr>\n    <tr>\n      <th>147</th>\n      <td>140</td>\n      <td>Botswana</td>\n      <td>69.86</td>\n      <td>72.69</td>\n      <td>66.72</td>\n    </tr>\n    <tr>\n      <th>148</th>\n      <td>141</td>\n      <td>Kiribati</td>\n      <td>69.17</td>\n      <td>73.12</td>\n      <td>65.00</td>\n    </tr>\n    <tr>\n      <th>149</th>\n      <td>142</td>\n      <td>Laos</td>\n      <td>68.89</td>\n      <td>70.79</td>\n      <td>67.04</td>\n    </tr>\n    <tr>\n      <th>150</th>\n      <td>143</td>\n      <td>Senegal</td>\n      <td>68.87</td>\n      <td>70.88</td>\n      <td>66.64</td>\n    </tr>\n    <tr>\n      <th>151</th>\n      <td>144</td>\n      <td>Turkmenistan</td>\n      <td>68.63</td>\n      <td>72.19</td>\n      <td>65.10</td>\n    </tr>\n    <tr>\n      <th>152</th>\n      <td>145</td>\n      <td>Micronesia</td>\n      <td>68.27</td>\n      <td>70.07</td>\n      <td>66.54</td>\n    </tr>\n    <tr>\n      <th>153</th>\n      <td>146</td>\n      <td>Madagascar</td>\n      <td>68.21</td>\n      <td>69.92</td>\n      <td>66.53</td>\n    </tr>\n    <tr>\n      <th>154</th>\n      <td>147</td>\n      <td>Fiji</td>\n      <td>67.91</td>\n      <td>69.97</td>\n      <td>66.00</td>\n    </tr>\n    <tr>\n      <th>155</th>\n      <td>148</td>\n      <td>Djibouti</td>\n      <td>67.87</td>\n      <td>70.16</td>\n      <td>65.84</td>\n    </tr>\n    <tr>\n      <th>156</th>\n      <td>149</td>\n      <td>Ethiopia</td>\n      <td>67.81</td>\n      <td>69.80</td>\n      <td>65.86</td>\n    </tr>\n    <tr>\n      <th>157</th>\n      <td>150</td>\n      <td>Pakistan</td>\n      <td>67.79</td>\n      <td>68.90</td>\n      <td>66.77</td>\n    </tr>\n    <tr>\n      <th>158</th>\n      <td>151</td>\n      <td>Myanmar</td>\n      <td>67.78</td>\n      <td>70.81</td>\n      <td>64.65</td>\n    </tr>\n    <tr>\n      <th>159</th>\n      <td>152</td>\n      <td>Eritrea</td>\n      <td>67.48</td>\n      <td>69.75</td>\n      <td>65.26</td>\n    </tr>\n    <tr>\n      <th>160</th>\n      <td>153</td>\n      <td>Kenya</td>\n      <td>67.47</td>\n      <td>69.87</td>\n      <td>65.04</td>\n    </tr>\n    <tr>\n      <th>161</th>\n      <td>154</td>\n      <td>Gabon</td>\n      <td>67.03</td>\n      <td>69.27</td>\n      <td>64.93</td>\n    </tr>\n    <tr>\n      <th>162</th>\n      <td>155</td>\n      <td>Yemen</td>\n      <td>66.44</td>\n      <td>68.16</td>\n      <td>64.72</td>\n    </tr>\n    <tr>\n      <th>163</th>\n      <td>156</td>\n      <td>Tanzania</td>\n      <td>66.39</td>\n      <td>68.25</td>\n      <td>64.52</td>\n    </tr>\n    <tr>\n      <th>164</th>\n      <td>157</td>\n      <td>Sudan</td>\n      <td>66.09</td>\n      <td>68.03</td>\n      <td>64.18</td>\n    </tr>\n    <tr>\n      <th>165</th>\n      <td>158</td>\n      <td>Afghanistan</td>\n      <td>65.98</td>\n      <td>67.59</td>\n      <td>64.47</td>\n    </tr>\n    <tr>\n      <th>166</th>\n      <td>159</td>\n      <td>Malawi</td>\n      <td>65.62</td>\n      <td>68.77</td>\n      <td>62.45</td>\n    </tr>\n    <tr>\n      <th>167</th>\n      <td>160</td>\n      <td>Mauritania</td>\n      <td>65.57</td>\n      <td>67.24</td>\n      <td>63.88</td>\n    </tr>\n    <tr>\n      <th>168</th>\n      <td>161</td>\n      <td>Papua New Guinea</td>\n      <td>65.22</td>\n      <td>66.62</td>\n      <td>63.92</td>\n    </tr>\n    <tr>\n      <th>169</th>\n      <td>162</td>\n      <td>Congo</td>\n      <td>65.21</td>\n      <td>66.73</td>\n      <td>63.67</td>\n    </tr>\n    <tr>\n      <th>170</th>\n      <td>163</td>\n      <td>Comoros</td>\n      <td>65.03</td>\n      <td>66.88</td>\n      <td>63.24</td>\n    </tr>\n    <tr>\n      <th>171</th>\n      <td>164</td>\n      <td>Liberia</td>\n      <td>65.00</td>\n      <td>66.48</td>\n      <td>63.54</td>\n    </tr>\n    <tr>\n      <th>172</th>\n      <td>165</td>\n      <td>Haiti</td>\n      <td>64.99</td>\n      <td>67.21</td>\n      <td>62.77</td>\n    </tr>\n    <tr>\n      <th>173</th>\n      <td>166</td>\n      <td>Ghana</td>\n      <td>64.94</td>\n      <td>66.13</td>\n      <td>63.78</td>\n    </tr>\n    <tr>\n      <th>174</th>\n      <td>167</td>\n      <td>South Africa</td>\n      <td>64.88</td>\n      <td>68.42</td>\n      <td>61.46</td>\n    </tr>\n    <tr>\n      <th>175</th>\n      <td>168</td>\n      <td>Namibia</td>\n      <td>64.86</td>\n      <td>67.67</td>\n      <td>61.83</td>\n    </tr>\n    <tr>\n      <th>176</th>\n      <td>169</td>\n      <td>Zambia</td>\n      <td>64.70</td>\n      <td>67.71</td>\n      <td>61.66</td>\n    </tr>\n    <tr>\n      <th>177</th>\n      <td>170</td>\n      <td>Uganda</td>\n      <td>64.38</td>\n      <td>66.67</td>\n      <td>61.99</td>\n    </tr>\n    <tr>\n      <th>178</th>\n      <td>171</td>\n      <td>Niger</td>\n      <td>63.62</td>\n      <td>64.89</td>\n      <td>62.41</td>\n    </tr>\n    <tr>\n      <th>179</th>\n      <td>172</td>\n      <td>Gambia</td>\n      <td>63.26</td>\n      <td>64.73</td>\n      <td>61.80</td>\n    </tr>\n    <tr>\n      <th>180</th>\n      <td>173</td>\n      <td>Burkina Faso</td>\n      <td>62.98</td>\n      <td>63.78</td>\n      <td>62.06</td>\n    </tr>\n    <tr>\n      <th>181</th>\n      <td>174</td>\n      <td>Benin</td>\n      <td>62.84</td>\n      <td>64.45</td>\n      <td>61.23</td>\n    </tr>\n    <tr>\n      <th>182</th>\n      <td>175</td>\n      <td>Burundi</td>\n      <td>62.71</td>\n      <td>64.56</td>\n      <td>60.85</td>\n    </tr>\n    <tr>\n      <th>183</th>\n      <td>176</td>\n      <td>Guinea</td>\n      <td>62.64</td>\n      <td>63.25</td>\n      <td>61.79</td>\n    </tr>\n    <tr>\n      <th>184</th>\n      <td>177</td>\n      <td>Angola</td>\n      <td>62.22</td>\n      <td>65.12</td>\n      <td>59.46</td>\n    </tr>\n    <tr>\n      <th>185</th>\n      <td>178</td>\n      <td>Zimbabwe</td>\n      <td>62.16</td>\n      <td>63.66</td>\n      <td>60.39</td>\n    </tr>\n    <tr>\n      <th>186</th>\n      <td>179</td>\n      <td>Mozambique</td>\n      <td>62.13</td>\n      <td>64.95</td>\n      <td>59.05</td>\n    </tr>\n    <tr>\n      <th>187</th>\n      <td>179</td>\n      <td>Togo</td>\n      <td>62.13</td>\n      <td>63.08</td>\n      <td>61.16</td>\n    </tr>\n    <tr>\n      <th>188</th>\n      <td>180</td>\n      <td>DR Congo</td>\n      <td>61.60</td>\n      <td>63.21</td>\n      <td>60.01</td>\n    </tr>\n    <tr>\n      <th>189</th>\n      <td>181</td>\n      <td>Eswatini</td>\n      <td>61.05</td>\n      <td>65.67</td>\n      <td>56.98</td>\n    </tr>\n    <tr>\n      <th>190</th>\n      <td>182</td>\n      <td>Mali</td>\n      <td>60.54</td>\n      <td>61.39</td>\n      <td>59.69</td>\n    </tr>\n    <tr>\n      <th>191</th>\n      <td>183</td>\n      <td>Cameroon</td>\n      <td>60.32</td>\n      <td>61.66</td>\n      <td>58.99</td>\n    </tr>\n    <tr>\n      <th>192</th>\n      <td>184</td>\n      <td>Equatorial Guinea</td>\n      <td>59.82</td>\n      <td>61.08</td>\n      <td>58.76</td>\n    </tr>\n    <tr>\n      <th>193</th>\n      <td>185</td>\n      <td>Guinea-Bissau</td>\n      <td>59.38</td>\n      <td>61.33</td>\n      <td>57.31</td>\n    </tr>\n    <tr>\n      <th>194</th>\n      <td>186</td>\n      <td>Côte d\'Ivoire</td>\n      <td>58.75</td>\n      <td>60.13</td>\n      <td>57.50</td>\n    </tr>\n    <tr>\n      <th>195</th>\n      <td>187</td>\n      <td>South Sudan</td>\n      <td>58.74</td>\n      <td>60.31</td>\n      <td>57.21</td>\n    </tr>\n    <tr>\n      <th>196</th>\n      <td>188</td>\n      <td>Somalia</td>\n      <td>58.34</td>\n      <td>60.11</td>\n      <td>56.62</td>\n    </tr>\n    <tr>\n      <th>197</th>\n      <td>189</td>\n      <td>Sierra Leone</td>\n      <td>55.92</td>\n      <td>56.78</td>\n      <td>55.01</td>\n    </tr>\n    <tr>\n      <th>198</th>\n      <td>190</td>\n      <td>Nigeria</td>\n      <td>55.75</td>\n      <td>56.75</td>\n      <td>54.80</td>\n    </tr>\n    <tr>\n      <th>199</th>\n      <td>191</td>\n      <td>Lesotho</td>\n      <td>55.65</td>\n      <td>58.90</td>\n      <td>52.52</td>\n    </tr>\n    <tr>\n      <th>200</th>\n      <td>192</td>\n      <td>Chad</td>\n      <td>55.17</td>\n      <td>56.65</td>\n      <td>53.73</td>\n    </tr>\n    <tr>\n      <th>201</th>\n      <td>193</td>\n      <td>Central African Republic</td>\n      <td>54.36</td>\n      <td>56.58</td>\n      <td>52.16</td>\n    </tr>\n  </tbody>

`
var table = document.getElementById("myTable");
  for (i = 0; i < table.rows.length; i++) {
  table.rows[i].deleteCell(table.rows[i].cells[0]);
}var table = document.getElementById("myTable");
  for (i = 0; i < table.rows.length; i++) {
  table.rows[i].deleteCell(table.rows[i].cells[1]);
}
}
function make_data_1(){
document.getElementById('myTable').innerHTML=`
<thead>\n    <tr id="first_row">
<td><input name="header" placeholder="Edit" value="Index" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Pregnancies" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Glucose" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="BloodPressure" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="SkinThickness" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Insulin" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="BMI" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="DiabetesPedigreeFunction" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Age" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" value="Outcome" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>\n  </thead>\n  <tbody>\n    <tr>\n      <th>0</th>\n      <td>6</td>\n      <td>148</td>\n      <td>72</td>\n      <td>35</td>\n      <td>0</td>\n      <td>33.6</td>\n      <td>0.627</td>\n      <td>50</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>1</th>\n      <td>1</td>\n      <td>85</td>\n      <td>66</td>\n      <td>29</td>\n      <td>0</td>\n      <td>26.6</td>\n      <td>0.351</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>2</th>\n      <td>8</td>\n      <td>183</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.3</td>\n      <td>0.672</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>3</th>\n      <td>1</td>\n      <td>89</td>\n      <td>66</td>\n      <td>23</td>\n      <td>94</td>\n      <td>28.1</td>\n      <td>0.167</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>4</th>\n      <td>0</td>\n      <td>137</td>\n      <td>40</td>\n      <td>35</td>\n      <td>168</td>\n      <td>43.1</td>\n      <td>2.288</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>5</th>\n      <td>5</td>\n      <td>116</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.6</td>\n      <td>0.201</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>6</th>\n      <td>3</td>\n      <td>78</td>\n      <td>50</td>\n      <td>32</td>\n      <td>88</td>\n      <td>31.0</td>\n      <td>0.248</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>7</th>\n      <td>10</td>\n      <td>115</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.3</td>\n      <td>0.134</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>8</th>\n      <td>2</td>\n      <td>197</td>\n      <td>70</td>\n      <td>45</td>\n      <td>543</td>\n      <td>30.5</td>\n      <td>0.158</td>\n      <td>53</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>9</th>\n      <td>8</td>\n      <td>125</td>\n      <td>96</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.232</td>\n      <td>54</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>10</th>\n      <td>4</td>\n      <td>110</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.6</td>\n      <td>0.191</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>11</th>\n      <td>10</td>\n      <td>168</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>38.0</td>\n      <td>0.537</td>\n      <td>34</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>12</th>\n      <td>10</td>\n      <td>139</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.1</td>\n      <td>1.441</td>\n      <td>57</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>13</th>\n      <td>1</td>\n      <td>189</td>\n      <td>60</td>\n      <td>23</td>\n      <td>846</td>\n      <td>30.1</td>\n      <td>0.398</td>\n      <td>59</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>14</th>\n      <td>5</td>\n      <td>166</td>\n      <td>72</td>\n      <td>19</td>\n      <td>175</td>\n      <td>25.8</td>\n      <td>0.587</td>\n      <td>51</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>15</th>\n      <td>7</td>\n      <td>100</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.0</td>\n      <td>0.484</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>16</th>\n      <td>0</td>\n      <td>118</td>\n      <td>84</td>\n      <td>47</td>\n      <td>230</td>\n      <td>45.8</td>\n      <td>0.551</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>17</th>\n      <td>7</td>\n      <td>107</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.6</td>\n      <td>0.254</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>18</th>\n      <td>1</td>\n      <td>103</td>\n      <td>30</td>\n      <td>38</td>\n      <td>83</td>\n      <td>43.3</td>\n      <td>0.183</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>19</th>\n      <td>1</td>\n      <td>115</td>\n      <td>70</td>\n      <td>30</td>\n      <td>96</td>\n      <td>34.6</td>\n      <td>0.529</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>20</th>\n      <td>3</td>\n      <td>126</td>\n      <td>88</td>\n      <td>41</td>\n      <td>235</td>\n      <td>39.3</td>\n      <td>0.704</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>21</th>\n      <td>8</td>\n      <td>99</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.4</td>\n      <td>0.388</td>\n      <td>50</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>22</th>\n      <td>7</td>\n      <td>196</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.8</td>\n      <td>0.451</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>23</th>\n      <td>9</td>\n      <td>119</td>\n      <td>80</td>\n      <td>35</td>\n      <td>0</td>\n      <td>29.0</td>\n      <td>0.263</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>24</th>\n      <td>11</td>\n      <td>143</td>\n      <td>94</td>\n      <td>33</td>\n      <td>146</td>\n      <td>36.6</td>\n      <td>0.254</td>\n      <td>51</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>25</th>\n      <td>10</td>\n      <td>125</td>\n      <td>70</td>\n      <td>26</td>\n      <td>115</td>\n      <td>31.1</td>\n      <td>0.205</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>26</th>\n      <td>7</td>\n      <td>147</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.4</td>\n      <td>0.257</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>27</th>\n      <td>1</td>\n      <td>97</td>\n      <td>66</td>\n      <td>15</td>\n      <td>140</td>\n      <td>23.2</td>\n      <td>0.487</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>28</th>\n      <td>13</td>\n      <td>145</td>\n      <td>82</td>\n      <td>19</td>\n      <td>110</td>\n      <td>22.2</td>\n      <td>0.245</td>\n      <td>57</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>29</th>\n      <td>5</td>\n      <td>117</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.1</td>\n      <td>0.337</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>30</th>\n      <td>5</td>\n      <td>109</td>\n      <td>75</td>\n      <td>26</td>\n      <td>0</td>\n      <td>36.0</td>\n      <td>0.546</td>\n      <td>60</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>31</th>\n      <td>3</td>\n      <td>158</td>\n      <td>76</td>\n      <td>36</td>\n      <td>245</td>\n      <td>31.6</td>\n      <td>0.851</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>32</th>\n      <td>3</td>\n      <td>88</td>\n      <td>58</td>\n      <td>11</td>\n      <td>54</td>\n      <td>24.8</td>\n      <td>0.267</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>33</th>\n      <td>6</td>\n      <td>92</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>19.9</td>\n      <td>0.188</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>34</th>\n      <td>10</td>\n      <td>122</td>\n      <td>78</td>\n      <td>31</td>\n      <td>0</td>\n      <td>27.6</td>\n      <td>0.512</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>35</th>\n      <td>4</td>\n      <td>103</td>\n      <td>60</td>\n      <td>33</td>\n      <td>192</td>\n      <td>24.0</td>\n      <td>0.966</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>36</th>\n      <td>11</td>\n      <td>138</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.2</td>\n      <td>0.420</td>\n      <td>35</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>37</th>\n      <td>9</td>\n      <td>102</td>\n      <td>76</td>\n      <td>37</td>\n      <td>0</td>\n      <td>32.9</td>\n      <td>0.665</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>38</th>\n      <td>2</td>\n      <td>90</td>\n      <td>68</td>\n      <td>42</td>\n      <td>0</td>\n      <td>38.2</td>\n      <td>0.503</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>39</th>\n      <td>4</td>\n      <td>111</td>\n      <td>72</td>\n      <td>47</td>\n      <td>207</td>\n      <td>37.1</td>\n      <td>1.390</td>\n      <td>56</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>40</th>\n      <td>3</td>\n      <td>180</td>\n      <td>64</td>\n      <td>25</td>\n      <td>70</td>\n      <td>34.0</td>\n      <td>0.271</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>41</th>\n      <td>7</td>\n      <td>133</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>40.2</td>\n      <td>0.696</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>42</th>\n      <td>7</td>\n      <td>106</td>\n      <td>92</td>\n      <td>18</td>\n      <td>0</td>\n      <td>22.7</td>\n      <td>0.235</td>\n      <td>48</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>43</th>\n      <td>9</td>\n      <td>171</td>\n      <td>110</td>\n      <td>24</td>\n      <td>240</td>\n      <td>45.4</td>\n      <td>0.721</td>\n      <td>54</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>44</th>\n      <td>7</td>\n      <td>159</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.4</td>\n      <td>0.294</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>45</th>\n      <td>0</td>\n      <td>180</td>\n      <td>66</td>\n      <td>39</td>\n      <td>0</td>\n      <td>42.0</td>\n      <td>1.893</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>46</th>\n      <td>1</td>\n      <td>146</td>\n      <td>56</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.7</td>\n      <td>0.564</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>47</th>\n      <td>2</td>\n      <td>71</td>\n      <td>70</td>\n      <td>27</td>\n      <td>0</td>\n      <td>28.0</td>\n      <td>0.586</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>48</th>\n      <td>7</td>\n      <td>103</td>\n      <td>66</td>\n      <td>32</td>\n      <td>0</td>\n      <td>39.1</td>\n      <td>0.344</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>49</th>\n      <td>7</td>\n      <td>105</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.305</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>50</th>\n      <td>1</td>\n      <td>103</td>\n      <td>80</td>\n      <td>11</td>\n      <td>82</td>\n      <td>19.4</td>\n      <td>0.491</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>51</th>\n      <td>1</td>\n      <td>101</td>\n      <td>50</td>\n      <td>15</td>\n      <td>36</td>\n      <td>24.2</td>\n      <td>0.526</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>52</th>\n      <td>5</td>\n      <td>88</td>\n      <td>66</td>\n      <td>21</td>\n      <td>23</td>\n      <td>24.4</td>\n      <td>0.342</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>53</th>\n      <td>8</td>\n      <td>176</td>\n      <td>90</td>\n      <td>34</td>\n      <td>300</td>\n      <td>33.7</td>\n      <td>0.467</td>\n      <td>58</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>54</th>\n      <td>7</td>\n      <td>150</td>\n      <td>66</td>\n      <td>42</td>\n      <td>342</td>\n      <td>34.7</td>\n      <td>0.718</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>55</th>\n      <td>1</td>\n      <td>73</td>\n      <td>50</td>\n      <td>10</td>\n      <td>0</td>\n      <td>23.0</td>\n      <td>0.248</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>56</th>\n      <td>7</td>\n      <td>187</td>\n      <td>68</td>\n      <td>39</td>\n      <td>304</td>\n      <td>37.7</td>\n      <td>0.254</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>57</th>\n      <td>0</td>\n      <td>100</td>\n      <td>88</td>\n      <td>60</td>\n      <td>110</td>\n      <td>46.8</td>\n      <td>0.962</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>58</th>\n      <td>0</td>\n      <td>146</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>40.5</td>\n      <td>1.781</td>\n      <td>44</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>59</th>\n      <td>0</td>\n      <td>105</td>\n      <td>64</td>\n      <td>41</td>\n      <td>142</td>\n      <td>41.5</td>\n      <td>0.173</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>60</th>\n      <td>2</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.304</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>61</th>\n      <td>8</td>\n      <td>133</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.9</td>\n      <td>0.270</td>\n      <td>39</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>62</th>\n      <td>5</td>\n      <td>44</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.0</td>\n      <td>0.587</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>63</th>\n      <td>2</td>\n      <td>141</td>\n      <td>58</td>\n      <td>34</td>\n      <td>128</td>\n      <td>25.4</td>\n      <td>0.699</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>64</th>\n      <td>7</td>\n      <td>114</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.258</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>65</th>\n      <td>5</td>\n      <td>99</td>\n      <td>74</td>\n      <td>27</td>\n      <td>0</td>\n      <td>29.0</td>\n      <td>0.203</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>66</th>\n      <td>0</td>\n      <td>109</td>\n      <td>88</td>\n      <td>30</td>\n      <td>0</td>\n      <td>32.5</td>\n      <td>0.855</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>67</th>\n      <td>2</td>\n      <td>109</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.7</td>\n      <td>0.845</td>\n      <td>54</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>68</th>\n      <td>1</td>\n      <td>95</td>\n      <td>66</td>\n      <td>13</td>\n      <td>38</td>\n      <td>19.6</td>\n      <td>0.334</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>69</th>\n      <td>4</td>\n      <td>146</td>\n      <td>85</td>\n      <td>27</td>\n      <td>100</td>\n      <td>28.9</td>\n      <td>0.189</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>70</th>\n      <td>2</td>\n      <td>100</td>\n      <td>66</td>\n      <td>20</td>\n      <td>90</td>\n      <td>32.9</td>\n      <td>0.867</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>71</th>\n      <td>5</td>\n      <td>139</td>\n      <td>64</td>\n      <td>35</td>\n      <td>140</td>\n      <td>28.6</td>\n      <td>0.411</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>72</th>\n      <td>13</td>\n      <td>126</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>43.4</td>\n      <td>0.583</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>73</th>\n      <td>4</td>\n      <td>129</td>\n      <td>86</td>\n      <td>20</td>\n      <td>270</td>\n      <td>35.1</td>\n      <td>0.231</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>74</th>\n      <td>1</td>\n      <td>79</td>\n      <td>75</td>\n      <td>30</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.396</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>75</th>\n      <td>1</td>\n      <td>0</td>\n      <td>48</td>\n      <td>20</td>\n      <td>0</td>\n      <td>24.7</td>\n      <td>0.140</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>76</th>\n      <td>7</td>\n      <td>62</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.6</td>\n      <td>0.391</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>77</th>\n      <td>5</td>\n      <td>95</td>\n      <td>72</td>\n      <td>33</td>\n      <td>0</td>\n      <td>37.7</td>\n      <td>0.370</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>78</th>\n      <td>0</td>\n      <td>131</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>43.2</td>\n      <td>0.270</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>79</th>\n      <td>2</td>\n      <td>112</td>\n      <td>66</td>\n      <td>22</td>\n      <td>0</td>\n      <td>25.0</td>\n      <td>0.307</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>80</th>\n      <td>3</td>\n      <td>113</td>\n      <td>44</td>\n      <td>13</td>\n      <td>0</td>\n      <td>22.4</td>\n      <td>0.140</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>81</th>\n      <td>2</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.102</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>82</th>\n      <td>7</td>\n      <td>83</td>\n      <td>78</td>\n      <td>26</td>\n      <td>71</td>\n      <td>29.3</td>\n      <td>0.767</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>83</th>\n      <td>0</td>\n      <td>101</td>\n      <td>65</td>\n      <td>28</td>\n      <td>0</td>\n      <td>24.6</td>\n      <td>0.237</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>84</th>\n      <td>5</td>\n      <td>137</td>\n      <td>108</td>\n      <td>0</td>\n      <td>0</td>\n      <td>48.8</td>\n      <td>0.227</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>85</th>\n      <td>2</td>\n      <td>110</td>\n      <td>74</td>\n      <td>29</td>\n      <td>125</td>\n      <td>32.4</td>\n      <td>0.698</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>86</th>\n      <td>13</td>\n      <td>106</td>\n      <td>72</td>\n      <td>54</td>\n      <td>0</td>\n      <td>36.6</td>\n      <td>0.178</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>87</th>\n      <td>2</td>\n      <td>100</td>\n      <td>68</td>\n      <td>25</td>\n      <td>71</td>\n      <td>38.5</td>\n      <td>0.324</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>88</th>\n      <td>15</td>\n      <td>136</td>\n      <td>70</td>\n      <td>32</td>\n      <td>110</td>\n      <td>37.1</td>\n      <td>0.153</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>89</th>\n      <td>1</td>\n      <td>107</td>\n      <td>68</td>\n      <td>19</td>\n      <td>0</td>\n      <td>26.5</td>\n      <td>0.165</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>90</th>\n      <td>1</td>\n      <td>80</td>\n      <td>55</td>\n      <td>0</td>\n      <td>0</td>\n      <td>19.1</td>\n      <td>0.258</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>91</th>\n      <td>4</td>\n      <td>123</td>\n      <td>80</td>\n      <td>15</td>\n      <td>176</td>\n      <td>32.0</td>\n      <td>0.443</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>92</th>\n      <td>7</td>\n      <td>81</td>\n      <td>78</td>\n      <td>40</td>\n      <td>48</td>\n      <td>46.7</td>\n      <td>0.261</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>93</th>\n      <td>4</td>\n      <td>134</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.8</td>\n      <td>0.277</td>\n      <td>60</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>94</th>\n      <td>2</td>\n      <td>142</td>\n      <td>82</td>\n      <td>18</td>\n      <td>64</td>\n      <td>24.7</td>\n      <td>0.761</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>95</th>\n      <td>6</td>\n      <td>144</td>\n      <td>72</td>\n      <td>27</td>\n      <td>228</td>\n      <td>33.9</td>\n      <td>0.255</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>96</th>\n      <td>2</td>\n      <td>92</td>\n      <td>62</td>\n      <td>28</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.130</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>97</th>\n      <td>1</td>\n      <td>71</td>\n      <td>48</td>\n      <td>18</td>\n      <td>76</td>\n      <td>20.4</td>\n      <td>0.323</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>98</th>\n      <td>6</td>\n      <td>93</td>\n      <td>50</td>\n      <td>30</td>\n      <td>64</td>\n      <td>28.7</td>\n      <td>0.356</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>99</th>\n      <td>1</td>\n      <td>122</td>\n      <td>90</td>\n      <td>51</td>\n      <td>220</td>\n      <td>49.7</td>\n      <td>0.325</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>100</th>\n      <td>1</td>\n      <td>163</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.0</td>\n      <td>1.222</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>101</th>\n      <td>1</td>\n      <td>151</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.1</td>\n      <td>0.179</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>102</th>\n      <td>0</td>\n      <td>125</td>\n      <td>96</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.5</td>\n      <td>0.262</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>103</th>\n      <td>1</td>\n      <td>81</td>\n      <td>72</td>\n      <td>18</td>\n      <td>40</td>\n      <td>26.6</td>\n      <td>0.283</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>104</th>\n      <td>2</td>\n      <td>85</td>\n      <td>65</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.6</td>\n      <td>0.930</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>105</th>\n      <td>1</td>\n      <td>126</td>\n      <td>56</td>\n      <td>29</td>\n      <td>152</td>\n      <td>28.7</td>\n      <td>0.801</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>106</th>\n      <td>1</td>\n      <td>96</td>\n      <td>122</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.4</td>\n      <td>0.207</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>107</th>\n      <td>4</td>\n      <td>144</td>\n      <td>58</td>\n      <td>28</td>\n      <td>140</td>\n      <td>29.5</td>\n      <td>0.287</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>108</th>\n      <td>3</td>\n      <td>83</td>\n      <td>58</td>\n      <td>31</td>\n      <td>18</td>\n      <td>34.3</td>\n      <td>0.336</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>109</th>\n      <td>0</td>\n      <td>95</td>\n      <td>85</td>\n      <td>25</td>\n      <td>36</td>\n      <td>37.4</td>\n      <td>0.247</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>110</th>\n      <td>3</td>\n      <td>171</td>\n      <td>72</td>\n      <td>33</td>\n      <td>135</td>\n      <td>33.3</td>\n      <td>0.199</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>111</th>\n      <td>8</td>\n      <td>155</td>\n      <td>62</td>\n      <td>26</td>\n      <td>495</td>\n      <td>34.0</td>\n      <td>0.543</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>112</th>\n      <td>1</td>\n      <td>89</td>\n      <td>76</td>\n      <td>34</td>\n      <td>37</td>\n      <td>31.2</td>\n      <td>0.192</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>113</th>\n      <td>4</td>\n      <td>76</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.0</td>\n      <td>0.391</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>114</th>\n      <td>7</td>\n      <td>160</td>\n      <td>54</td>\n      <td>32</td>\n      <td>175</td>\n      <td>30.5</td>\n      <td>0.588</td>\n      <td>39</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>115</th>\n      <td>4</td>\n      <td>146</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.539</td>\n      <td>61</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>116</th>\n      <td>5</td>\n      <td>124</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.0</td>\n      <td>0.220</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>117</th>\n      <td>5</td>\n      <td>78</td>\n      <td>48</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.7</td>\n      <td>0.654</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>118</th>\n      <td>4</td>\n      <td>97</td>\n      <td>60</td>\n      <td>23</td>\n      <td>0</td>\n      <td>28.2</td>\n      <td>0.443</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>119</th>\n      <td>4</td>\n      <td>99</td>\n      <td>76</td>\n      <td>15</td>\n      <td>51</td>\n      <td>23.2</td>\n      <td>0.223</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>120</th>\n      <td>0</td>\n      <td>162</td>\n      <td>76</td>\n      <td>56</td>\n      <td>100</td>\n      <td>53.2</td>\n      <td>0.759</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>121</th>\n      <td>6</td>\n      <td>111</td>\n      <td>64</td>\n      <td>39</td>\n      <td>0</td>\n      <td>34.2</td>\n      <td>0.260</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>122</th>\n      <td>2</td>\n      <td>107</td>\n      <td>74</td>\n      <td>30</td>\n      <td>100</td>\n      <td>33.6</td>\n      <td>0.404</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>123</th>\n      <td>5</td>\n      <td>132</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.8</td>\n      <td>0.186</td>\n      <td>69</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>124</th>\n      <td>0</td>\n      <td>113</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.3</td>\n      <td>0.278</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>125</th>\n      <td>1</td>\n      <td>88</td>\n      <td>30</td>\n      <td>42</td>\n      <td>99</td>\n      <td>55.0</td>\n      <td>0.496</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>126</th>\n      <td>3</td>\n      <td>120</td>\n      <td>70</td>\n      <td>30</td>\n      <td>135</td>\n      <td>42.9</td>\n      <td>0.452</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>127</th>\n      <td>1</td>\n      <td>118</td>\n      <td>58</td>\n      <td>36</td>\n      <td>94</td>\n      <td>33.3</td>\n      <td>0.261</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>128</th>\n      <td>1</td>\n      <td>117</td>\n      <td>88</td>\n      <td>24</td>\n      <td>145</td>\n      <td>34.5</td>\n      <td>0.403</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>129</th>\n      <td>0</td>\n      <td>105</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.9</td>\n      <td>0.741</td>\n      <td>62</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>130</th>\n      <td>4</td>\n      <td>173</td>\n      <td>70</td>\n      <td>14</td>\n      <td>168</td>\n      <td>29.7</td>\n      <td>0.361</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>131</th>\n      <td>9</td>\n      <td>122</td>\n      <td>56</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.3</td>\n      <td>1.114</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>132</th>\n      <td>3</td>\n      <td>170</td>\n      <td>64</td>\n      <td>37</td>\n      <td>225</td>\n      <td>34.5</td>\n      <td>0.356</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>133</th>\n      <td>8</td>\n      <td>84</td>\n      <td>74</td>\n      <td>31</td>\n      <td>0</td>\n      <td>38.3</td>\n      <td>0.457</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>134</th>\n      <td>2</td>\n      <td>96</td>\n      <td>68</td>\n      <td>13</td>\n      <td>49</td>\n      <td>21.1</td>\n      <td>0.647</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>135</th>\n      <td>2</td>\n      <td>125</td>\n      <td>60</td>\n      <td>20</td>\n      <td>140</td>\n      <td>33.8</td>\n      <td>0.088</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>136</th>\n      <td>0</td>\n      <td>100</td>\n      <td>70</td>\n      <td>26</td>\n      <td>50</td>\n      <td>30.8</td>\n      <td>0.597</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>137</th>\n      <td>0</td>\n      <td>93</td>\n      <td>60</td>\n      <td>25</td>\n      <td>92</td>\n      <td>28.7</td>\n      <td>0.532</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>138</th>\n      <td>0</td>\n      <td>129</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.703</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>139</th>\n      <td>5</td>\n      <td>105</td>\n      <td>72</td>\n      <td>29</td>\n      <td>325</td>\n      <td>36.9</td>\n      <td>0.159</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>140</th>\n      <td>3</td>\n      <td>128</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.1</td>\n      <td>0.268</td>\n      <td>55</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>141</th>\n      <td>5</td>\n      <td>106</td>\n      <td>82</td>\n      <td>30</td>\n      <td>0</td>\n      <td>39.5</td>\n      <td>0.286</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>142</th>\n      <td>2</td>\n      <td>108</td>\n      <td>52</td>\n      <td>26</td>\n      <td>63</td>\n      <td>32.5</td>\n      <td>0.318</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>143</th>\n      <td>10</td>\n      <td>108</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.272</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>144</th>\n      <td>4</td>\n      <td>154</td>\n      <td>62</td>\n      <td>31</td>\n      <td>284</td>\n      <td>32.8</td>\n      <td>0.237</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>145</th>\n      <td>0</td>\n      <td>102</td>\n      <td>75</td>\n      <td>23</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.572</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>146</th>\n      <td>9</td>\n      <td>57</td>\n      <td>80</td>\n      <td>37</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.096</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>147</th>\n      <td>2</td>\n      <td>106</td>\n      <td>64</td>\n      <td>35</td>\n      <td>119</td>\n      <td>30.5</td>\n      <td>1.400</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>148</th>\n      <td>5</td>\n      <td>147</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.7</td>\n      <td>0.218</td>\n      <td>65</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>149</th>\n      <td>2</td>\n      <td>90</td>\n      <td>70</td>\n      <td>17</td>\n      <td>0</td>\n      <td>27.3</td>\n      <td>0.085</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>150</th>\n      <td>1</td>\n      <td>136</td>\n      <td>74</td>\n      <td>50</td>\n      <td>204</td>\n      <td>37.4</td>\n      <td>0.399</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>151</th>\n      <td>4</td>\n      <td>114</td>\n      <td>65</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.9</td>\n      <td>0.432</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>152</th>\n      <td>9</td>\n      <td>156</td>\n      <td>86</td>\n      <td>28</td>\n      <td>155</td>\n      <td>34.3</td>\n      <td>1.189</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>153</th>\n      <td>1</td>\n      <td>153</td>\n      <td>82</td>\n      <td>42</td>\n      <td>485</td>\n      <td>40.6</td>\n      <td>0.687</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>154</th>\n      <td>8</td>\n      <td>188</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>47.9</td>\n      <td>0.137</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>155</th>\n      <td>7</td>\n      <td>152</td>\n      <td>88</td>\n      <td>44</td>\n      <td>0</td>\n      <td>50.0</td>\n      <td>0.337</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>156</th>\n      <td>2</td>\n      <td>99</td>\n      <td>52</td>\n      <td>15</td>\n      <td>94</td>\n      <td>24.6</td>\n      <td>0.637</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>157</th>\n      <td>1</td>\n      <td>109</td>\n      <td>56</td>\n      <td>21</td>\n      <td>135</td>\n      <td>25.2</td>\n      <td>0.833</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>158</th>\n      <td>2</td>\n      <td>88</td>\n      <td>74</td>\n      <td>19</td>\n      <td>53</td>\n      <td>29.0</td>\n      <td>0.229</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>159</th>\n      <td>17</td>\n      <td>163</td>\n      <td>72</td>\n      <td>41</td>\n      <td>114</td>\n      <td>40.9</td>\n      <td>0.817</td>\n      <td>47</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>160</th>\n      <td>4</td>\n      <td>151</td>\n      <td>90</td>\n      <td>38</td>\n      <td>0</td>\n      <td>29.7</td>\n      <td>0.294</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>161</th>\n      <td>7</td>\n      <td>102</td>\n      <td>74</td>\n      <td>40</td>\n      <td>105</td>\n      <td>37.2</td>\n      <td>0.204</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>162</th>\n      <td>0</td>\n      <td>114</td>\n      <td>80</td>\n      <td>34</td>\n      <td>285</td>\n      <td>44.2</td>\n      <td>0.167</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>163</th>\n      <td>2</td>\n      <td>100</td>\n      <td>64</td>\n      <td>23</td>\n      <td>0</td>\n      <td>29.7</td>\n      <td>0.368</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>164</th>\n      <td>0</td>\n      <td>131</td>\n      <td>88</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.743</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>165</th>\n      <td>6</td>\n      <td>104</td>\n      <td>74</td>\n      <td>18</td>\n      <td>156</td>\n      <td>29.9</td>\n      <td>0.722</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>166</th>\n      <td>3</td>\n      <td>148</td>\n      <td>66</td>\n      <td>25</td>\n      <td>0</td>\n      <td>32.5</td>\n      <td>0.256</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>167</th>\n      <td>4</td>\n      <td>120</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.6</td>\n      <td>0.709</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>168</th>\n      <td>4</td>\n      <td>110</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.9</td>\n      <td>0.471</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>169</th>\n      <td>3</td>\n      <td>111</td>\n      <td>90</td>\n      <td>12</td>\n      <td>78</td>\n      <td>28.4</td>\n      <td>0.495</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>170</th>\n      <td>6</td>\n      <td>102</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.8</td>\n      <td>0.180</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>171</th>\n      <td>6</td>\n      <td>134</td>\n      <td>70</td>\n      <td>23</td>\n      <td>130</td>\n      <td>35.4</td>\n      <td>0.542</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>172</th>\n      <td>2</td>\n      <td>87</td>\n      <td>0</td>\n      <td>23</td>\n      <td>0</td>\n      <td>28.9</td>\n      <td>0.773</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>173</th>\n      <td>1</td>\n      <td>79</td>\n      <td>60</td>\n      <td>42</td>\n      <td>48</td>\n      <td>43.5</td>\n      <td>0.678</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>174</th>\n      <td>2</td>\n      <td>75</td>\n      <td>64</td>\n      <td>24</td>\n      <td>55</td>\n      <td>29.7</td>\n      <td>0.370</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>175</th>\n      <td>8</td>\n      <td>179</td>\n      <td>72</td>\n      <td>42</td>\n      <td>130</td>\n      <td>32.7</td>\n      <td>0.719</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>176</th>\n      <td>6</td>\n      <td>85</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.382</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>177</th>\n      <td>0</td>\n      <td>129</td>\n      <td>110</td>\n      <td>46</td>\n      <td>130</td>\n      <td>67.1</td>\n      <td>0.319</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>178</th>\n      <td>5</td>\n      <td>143</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>45.0</td>\n      <td>0.190</td>\n      <td>47</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>179</th>\n      <td>5</td>\n      <td>130</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.1</td>\n      <td>0.956</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>180</th>\n      <td>6</td>\n      <td>87</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.2</td>\n      <td>0.084</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>181</th>\n      <td>0</td>\n      <td>119</td>\n      <td>64</td>\n      <td>18</td>\n      <td>92</td>\n      <td>34.9</td>\n      <td>0.725</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>182</th>\n      <td>1</td>\n      <td>0</td>\n      <td>74</td>\n      <td>20</td>\n      <td>23</td>\n      <td>27.7</td>\n      <td>0.299</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>183</th>\n      <td>5</td>\n      <td>73</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.8</td>\n      <td>0.268</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>184</th>\n      <td>4</td>\n      <td>141</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.6</td>\n      <td>0.244</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>185</th>\n      <td>7</td>\n      <td>194</td>\n      <td>68</td>\n      <td>28</td>\n      <td>0</td>\n      <td>35.9</td>\n      <td>0.745</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>186</th>\n      <td>8</td>\n      <td>181</td>\n      <td>68</td>\n      <td>36</td>\n      <td>495</td>\n      <td>30.1</td>\n      <td>0.615</td>\n      <td>60</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>187</th>\n      <td>1</td>\n      <td>128</td>\n      <td>98</td>\n      <td>41</td>\n      <td>58</td>\n      <td>32.0</td>\n      <td>1.321</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>188</th>\n      <td>8</td>\n      <td>109</td>\n      <td>76</td>\n      <td>39</td>\n      <td>114</td>\n      <td>27.9</td>\n      <td>0.640</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>189</th>\n      <td>5</td>\n      <td>139</td>\n      <td>80</td>\n      <td>35</td>\n      <td>160</td>\n      <td>31.6</td>\n      <td>0.361</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>190</th>\n      <td>3</td>\n      <td>111</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.6</td>\n      <td>0.142</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>191</th>\n      <td>9</td>\n      <td>123</td>\n      <td>70</td>\n      <td>44</td>\n      <td>94</td>\n      <td>33.1</td>\n      <td>0.374</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>192</th>\n      <td>7</td>\n      <td>159</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.4</td>\n      <td>0.383</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>193</th>\n      <td>11</td>\n      <td>135</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>52.3</td>\n      <td>0.578</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>194</th>\n      <td>8</td>\n      <td>85</td>\n      <td>55</td>\n      <td>20</td>\n      <td>0</td>\n      <td>24.4</td>\n      <td>0.136</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>195</th>\n      <td>5</td>\n      <td>158</td>\n      <td>84</td>\n      <td>41</td>\n      <td>210</td>\n      <td>39.4</td>\n      <td>0.395</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>196</th>\n      <td>1</td>\n      <td>105</td>\n      <td>58</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.3</td>\n      <td>0.187</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>197</th>\n      <td>3</td>\n      <td>107</td>\n      <td>62</td>\n      <td>13</td>\n      <td>48</td>\n      <td>22.9</td>\n      <td>0.678</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>198</th>\n      <td>4</td>\n      <td>109</td>\n      <td>64</td>\n      <td>44</td>\n      <td>99</td>\n      <td>34.8</td>\n      <td>0.905</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>199</th>\n      <td>4</td>\n      <td>148</td>\n      <td>60</td>\n      <td>27</td>\n      <td>318</td>\n      <td>30.9</td>\n      <td>0.150</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>200</th>\n      <td>0</td>\n      <td>113</td>\n      <td>80</td>\n      <td>16</td>\n      <td>0</td>\n      <td>31.0</td>\n      <td>0.874</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>201</th>\n      <td>1</td>\n      <td>138</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>40.1</td>\n      <td>0.236</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>202</th>\n      <td>0</td>\n      <td>108</td>\n      <td>68</td>\n      <td>20</td>\n      <td>0</td>\n      <td>27.3</td>\n      <td>0.787</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>203</th>\n      <td>2</td>\n      <td>99</td>\n      <td>70</td>\n      <td>16</td>\n      <td>44</td>\n      <td>20.4</td>\n      <td>0.235</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>204</th>\n      <td>6</td>\n      <td>103</td>\n      <td>72</td>\n      <td>32</td>\n      <td>190</td>\n      <td>37.7</td>\n      <td>0.324</td>\n      <td>55</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>205</th>\n      <td>5</td>\n      <td>111</td>\n      <td>72</td>\n      <td>28</td>\n      <td>0</td>\n      <td>23.9</td>\n      <td>0.407</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>206</th>\n      <td>8</td>\n      <td>196</td>\n      <td>76</td>\n      <td>29</td>\n      <td>280</td>\n      <td>37.5</td>\n      <td>0.605</td>\n      <td>57</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>207</th>\n      <td>5</td>\n      <td>162</td>\n      <td>104</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.7</td>\n      <td>0.151</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>208</th>\n      <td>1</td>\n      <td>96</td>\n      <td>64</td>\n      <td>27</td>\n      <td>87</td>\n      <td>33.2</td>\n      <td>0.289</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>209</th>\n      <td>7</td>\n      <td>184</td>\n      <td>84</td>\n      <td>33</td>\n      <td>0</td>\n      <td>35.5</td>\n      <td>0.355</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>210</th>\n      <td>2</td>\n      <td>81</td>\n      <td>60</td>\n      <td>22</td>\n      <td>0</td>\n      <td>27.7</td>\n      <td>0.290</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>211</th>\n      <td>0</td>\n      <td>147</td>\n      <td>85</td>\n      <td>54</td>\n      <td>0</td>\n      <td>42.8</td>\n      <td>0.375</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>212</th>\n      <td>7</td>\n      <td>179</td>\n      <td>95</td>\n      <td>31</td>\n      <td>0</td>\n      <td>34.2</td>\n      <td>0.164</td>\n      <td>60</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>213</th>\n      <td>0</td>\n      <td>140</td>\n      <td>65</td>\n      <td>26</td>\n      <td>130</td>\n      <td>42.6</td>\n      <td>0.431</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>214</th>\n      <td>9</td>\n      <td>112</td>\n      <td>82</td>\n      <td>32</td>\n      <td>175</td>\n      <td>34.2</td>\n      <td>0.260</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>215</th>\n      <td>12</td>\n      <td>151</td>\n      <td>70</td>\n      <td>40</td>\n      <td>271</td>\n      <td>41.8</td>\n      <td>0.742</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>216</th>\n      <td>5</td>\n      <td>109</td>\n      <td>62</td>\n      <td>41</td>\n      <td>129</td>\n      <td>35.8</td>\n      <td>0.514</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>217</th>\n      <td>6</td>\n      <td>125</td>\n      <td>68</td>\n      <td>30</td>\n      <td>120</td>\n      <td>30.0</td>\n      <td>0.464</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>218</th>\n      <td>5</td>\n      <td>85</td>\n      <td>74</td>\n      <td>22</td>\n      <td>0</td>\n      <td>29.0</td>\n      <td>1.224</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>219</th>\n      <td>5</td>\n      <td>112</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.8</td>\n      <td>0.261</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>220</th>\n      <td>0</td>\n      <td>177</td>\n      <td>60</td>\n      <td>29</td>\n      <td>478</td>\n      <td>34.6</td>\n      <td>1.072</td>\n      <td>21</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>221</th>\n      <td>2</td>\n      <td>158</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.805</td>\n      <td>66</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>222</th>\n      <td>7</td>\n      <td>119</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.2</td>\n      <td>0.209</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>223</th>\n      <td>7</td>\n      <td>142</td>\n      <td>60</td>\n      <td>33</td>\n      <td>190</td>\n      <td>28.8</td>\n      <td>0.687</td>\n      <td>61</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>224</th>\n      <td>1</td>\n      <td>100</td>\n      <td>66</td>\n      <td>15</td>\n      <td>56</td>\n      <td>23.6</td>\n      <td>0.666</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>225</th>\n      <td>1</td>\n      <td>87</td>\n      <td>78</td>\n      <td>27</td>\n      <td>32</td>\n      <td>34.6</td>\n      <td>0.101</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>226</th>\n      <td>0</td>\n      <td>101</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.7</td>\n      <td>0.198</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>227</th>\n      <td>3</td>\n      <td>162</td>\n      <td>52</td>\n      <td>38</td>\n      <td>0</td>\n      <td>37.2</td>\n      <td>0.652</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>228</th>\n      <td>4</td>\n      <td>197</td>\n      <td>70</td>\n      <td>39</td>\n      <td>744</td>\n      <td>36.7</td>\n      <td>2.329</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>229</th>\n      <td>0</td>\n      <td>117</td>\n      <td>80</td>\n      <td>31</td>\n      <td>53</td>\n      <td>45.2</td>\n      <td>0.089</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>230</th>\n      <td>4</td>\n      <td>142</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>44.0</td>\n      <td>0.645</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>231</th>\n      <td>6</td>\n      <td>134</td>\n      <td>80</td>\n      <td>37</td>\n      <td>370</td>\n      <td>46.2</td>\n      <td>0.238</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>232</th>\n      <td>1</td>\n      <td>79</td>\n      <td>80</td>\n      <td>25</td>\n      <td>37</td>\n      <td>25.4</td>\n      <td>0.583</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>233</th>\n      <td>4</td>\n      <td>122</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.0</td>\n      <td>0.394</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>234</th>\n      <td>3</td>\n      <td>74</td>\n      <td>68</td>\n      <td>28</td>\n      <td>45</td>\n      <td>29.7</td>\n      <td>0.293</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>235</th>\n      <td>4</td>\n      <td>171</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>43.6</td>\n      <td>0.479</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>236</th>\n      <td>7</td>\n      <td>181</td>\n      <td>84</td>\n      <td>21</td>\n      <td>192</td>\n      <td>35.9</td>\n      <td>0.586</td>\n      <td>51</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>237</th>\n      <td>0</td>\n      <td>179</td>\n      <td>90</td>\n      <td>27</td>\n      <td>0</td>\n      <td>44.1</td>\n      <td>0.686</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>238</th>\n      <td>9</td>\n      <td>164</td>\n      <td>84</td>\n      <td>21</td>\n      <td>0</td>\n      <td>30.8</td>\n      <td>0.831</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>239</th>\n      <td>0</td>\n      <td>104</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>18.4</td>\n      <td>0.582</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>240</th>\n      <td>1</td>\n      <td>91</td>\n      <td>64</td>\n      <td>24</td>\n      <td>0</td>\n      <td>29.2</td>\n      <td>0.192</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>241</th>\n      <td>4</td>\n      <td>91</td>\n      <td>70</td>\n      <td>32</td>\n      <td>88</td>\n      <td>33.1</td>\n      <td>0.446</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>242</th>\n      <td>3</td>\n      <td>139</td>\n      <td>54</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.6</td>\n      <td>0.402</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>243</th>\n      <td>6</td>\n      <td>119</td>\n      <td>50</td>\n      <td>22</td>\n      <td>176</td>\n      <td>27.1</td>\n      <td>1.318</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>244</th>\n      <td>2</td>\n      <td>146</td>\n      <td>76</td>\n      <td>35</td>\n      <td>194</td>\n      <td>38.2</td>\n      <td>0.329</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>245</th>\n      <td>9</td>\n      <td>184</td>\n      <td>85</td>\n      <td>15</td>\n      <td>0</td>\n      <td>30.0</td>\n      <td>1.213</td>\n      <td>49</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>246</th>\n      <td>10</td>\n      <td>122</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.258</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>247</th>\n      <td>0</td>\n      <td>165</td>\n      <td>90</td>\n      <td>33</td>\n      <td>680</td>\n      <td>52.3</td>\n      <td>0.427</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>248</th>\n      <td>9</td>\n      <td>124</td>\n      <td>70</td>\n      <td>33</td>\n      <td>402</td>\n      <td>35.4</td>\n      <td>0.282</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>249</th>\n      <td>1</td>\n      <td>111</td>\n      <td>86</td>\n      <td>19</td>\n      <td>0</td>\n      <td>30.1</td>\n      <td>0.143</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>250</th>\n      <td>9</td>\n      <td>106</td>\n      <td>52</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.380</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>251</th>\n      <td>2</td>\n      <td>129</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.0</td>\n      <td>0.284</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>252</th>\n      <td>2</td>\n      <td>90</td>\n      <td>80</td>\n      <td>14</td>\n      <td>55</td>\n      <td>24.4</td>\n      <td>0.249</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>253</th>\n      <td>0</td>\n      <td>86</td>\n      <td>68</td>\n      <td>32</td>\n      <td>0</td>\n      <td>35.8</td>\n      <td>0.238</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>254</th>\n      <td>12</td>\n      <td>92</td>\n      <td>62</td>\n      <td>7</td>\n      <td>258</td>\n      <td>27.6</td>\n      <td>0.926</td>\n      <td>44</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>255</th>\n      <td>1</td>\n      <td>113</td>\n      <td>64</td>\n      <td>35</td>\n      <td>0</td>\n      <td>33.6</td>\n      <td>0.543</td>\n      <td>21</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>256</th>\n      <td>3</td>\n      <td>111</td>\n      <td>56</td>\n      <td>39</td>\n      <td>0</td>\n      <td>30.1</td>\n      <td>0.557</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>257</th>\n      <td>2</td>\n      <td>114</td>\n      <td>68</td>\n      <td>22</td>\n      <td>0</td>\n      <td>28.7</td>\n      <td>0.092</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>258</th>\n      <td>1</td>\n      <td>193</td>\n      <td>50</td>\n      <td>16</td>\n      <td>375</td>\n      <td>25.9</td>\n      <td>0.655</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>259</th>\n      <td>11</td>\n      <td>155</td>\n      <td>76</td>\n      <td>28</td>\n      <td>150</td>\n      <td>33.3</td>\n      <td>1.353</td>\n      <td>51</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>260</th>\n      <td>3</td>\n      <td>191</td>\n      <td>68</td>\n      <td>15</td>\n      <td>130</td>\n      <td>30.9</td>\n      <td>0.299</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>261</th>\n      <td>3</td>\n      <td>141</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.0</td>\n      <td>0.761</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>262</th>\n      <td>4</td>\n      <td>95</td>\n      <td>70</td>\n      <td>32</td>\n      <td>0</td>\n      <td>32.1</td>\n      <td>0.612</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>263</th>\n      <td>3</td>\n      <td>142</td>\n      <td>80</td>\n      <td>15</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.200</td>\n      <td>63</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>264</th>\n      <td>4</td>\n      <td>123</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.226</td>\n      <td>35</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>265</th>\n      <td>5</td>\n      <td>96</td>\n      <td>74</td>\n      <td>18</td>\n      <td>67</td>\n      <td>33.6</td>\n      <td>0.997</td>\n      <td>43</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>266</th>\n      <td>0</td>\n      <td>138</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.3</td>\n      <td>0.933</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>267</th>\n      <td>2</td>\n      <td>128</td>\n      <td>64</td>\n      <td>42</td>\n      <td>0</td>\n      <td>40.0</td>\n      <td>1.101</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>268</th>\n      <td>0</td>\n      <td>102</td>\n      <td>52</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.1</td>\n      <td>0.078</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>269</th>\n      <td>2</td>\n      <td>146</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.5</td>\n      <td>0.240</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>270</th>\n      <td>10</td>\n      <td>101</td>\n      <td>86</td>\n      <td>37</td>\n      <td>0</td>\n      <td>45.6</td>\n      <td>1.136</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>271</th>\n      <td>2</td>\n      <td>108</td>\n      <td>62</td>\n      <td>32</td>\n      <td>56</td>\n      <td>25.2</td>\n      <td>0.128</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>272</th>\n      <td>3</td>\n      <td>122</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.0</td>\n      <td>0.254</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>273</th>\n      <td>1</td>\n      <td>71</td>\n      <td>78</td>\n      <td>50</td>\n      <td>45</td>\n      <td>33.2</td>\n      <td>0.422</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>274</th>\n      <td>13</td>\n      <td>106</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.2</td>\n      <td>0.251</td>\n      <td>52</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>275</th>\n      <td>2</td>\n      <td>100</td>\n      <td>70</td>\n      <td>52</td>\n      <td>57</td>\n      <td>40.5</td>\n      <td>0.677</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>276</th>\n      <td>7</td>\n      <td>106</td>\n      <td>60</td>\n      <td>24</td>\n      <td>0</td>\n      <td>26.5</td>\n      <td>0.296</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>277</th>\n      <td>0</td>\n      <td>104</td>\n      <td>64</td>\n      <td>23</td>\n      <td>116</td>\n      <td>27.8</td>\n      <td>0.454</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>278</th>\n      <td>5</td>\n      <td>114</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.9</td>\n      <td>0.744</td>\n      <td>57</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>279</th>\n      <td>2</td>\n      <td>108</td>\n      <td>62</td>\n      <td>10</td>\n      <td>278</td>\n      <td>25.3</td>\n      <td>0.881</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>280</th>\n      <td>0</td>\n      <td>146</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.9</td>\n      <td>0.334</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>281</th>\n      <td>10</td>\n      <td>129</td>\n      <td>76</td>\n      <td>28</td>\n      <td>122</td>\n      <td>35.9</td>\n      <td>0.280</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>282</th>\n      <td>7</td>\n      <td>133</td>\n      <td>88</td>\n      <td>15</td>\n      <td>155</td>\n      <td>32.4</td>\n      <td>0.262</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>283</th>\n      <td>7</td>\n      <td>161</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.4</td>\n      <td>0.165</td>\n      <td>47</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>284</th>\n      <td>2</td>\n      <td>108</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.0</td>\n      <td>0.259</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>285</th>\n      <td>7</td>\n      <td>136</td>\n      <td>74</td>\n      <td>26</td>\n      <td>135</td>\n      <td>26.0</td>\n      <td>0.647</td>\n      <td>51</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>286</th>\n      <td>5</td>\n      <td>155</td>\n      <td>84</td>\n      <td>44</td>\n      <td>545</td>\n      <td>38.7</td>\n      <td>0.619</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>287</th>\n      <td>1</td>\n      <td>119</td>\n      <td>86</td>\n      <td>39</td>\n      <td>220</td>\n      <td>45.6</td>\n      <td>0.808</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>288</th>\n      <td>4</td>\n      <td>96</td>\n      <td>56</td>\n      <td>17</td>\n      <td>49</td>\n      <td>20.8</td>\n      <td>0.340</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>289</th>\n      <td>5</td>\n      <td>108</td>\n      <td>72</td>\n      <td>43</td>\n      <td>75</td>\n      <td>36.1</td>\n      <td>0.263</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>290</th>\n      <td>0</td>\n      <td>78</td>\n      <td>88</td>\n      <td>29</td>\n      <td>40</td>\n      <td>36.9</td>\n      <td>0.434</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>291</th>\n      <td>0</td>\n      <td>107</td>\n      <td>62</td>\n      <td>30</td>\n      <td>74</td>\n      <td>36.6</td>\n      <td>0.757</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>292</th>\n      <td>2</td>\n      <td>128</td>\n      <td>78</td>\n      <td>37</td>\n      <td>182</td>\n      <td>43.3</td>\n      <td>1.224</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>293</th>\n      <td>1</td>\n      <td>128</td>\n      <td>48</td>\n      <td>45</td>\n      <td>194</td>\n      <td>40.5</td>\n      <td>0.613</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>294</th>\n      <td>0</td>\n      <td>161</td>\n      <td>50</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.9</td>\n      <td>0.254</td>\n      <td>65</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>295</th>\n      <td>6</td>\n      <td>151</td>\n      <td>62</td>\n      <td>31</td>\n      <td>120</td>\n      <td>35.5</td>\n      <td>0.692</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>296</th>\n      <td>2</td>\n      <td>146</td>\n      <td>70</td>\n      <td>38</td>\n      <td>360</td>\n      <td>28.0</td>\n      <td>0.337</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>297</th>\n      <td>0</td>\n      <td>126</td>\n      <td>84</td>\n      <td>29</td>\n      <td>215</td>\n      <td>30.7</td>\n      <td>0.520</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>298</th>\n      <td>14</td>\n      <td>100</td>\n      <td>78</td>\n      <td>25</td>\n      <td>184</td>\n      <td>36.6</td>\n      <td>0.412</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>299</th>\n      <td>8</td>\n      <td>112</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.6</td>\n      <td>0.840</td>\n      <td>58</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>300</th>\n      <td>0</td>\n      <td>167</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.3</td>\n      <td>0.839</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>301</th>\n      <td>2</td>\n      <td>144</td>\n      <td>58</td>\n      <td>33</td>\n      <td>135</td>\n      <td>31.6</td>\n      <td>0.422</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>302</th>\n      <td>5</td>\n      <td>77</td>\n      <td>82</td>\n      <td>41</td>\n      <td>42</td>\n      <td>35.8</td>\n      <td>0.156</td>\n      <td>35</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>303</th>\n      <td>5</td>\n      <td>115</td>\n      <td>98</td>\n      <td>0</td>\n      <td>0</td>\n      <td>52.9</td>\n      <td>0.209</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>304</th>\n      <td>3</td>\n      <td>150</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.0</td>\n      <td>0.207</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>305</th>\n      <td>2</td>\n      <td>120</td>\n      <td>76</td>\n      <td>37</td>\n      <td>105</td>\n      <td>39.7</td>\n      <td>0.215</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>306</th>\n      <td>10</td>\n      <td>161</td>\n      <td>68</td>\n      <td>23</td>\n      <td>132</td>\n      <td>25.5</td>\n      <td>0.326</td>\n      <td>47</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>307</th>\n      <td>0</td>\n      <td>137</td>\n      <td>68</td>\n      <td>14</td>\n      <td>148</td>\n      <td>24.8</td>\n      <td>0.143</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>308</th>\n      <td>0</td>\n      <td>128</td>\n      <td>68</td>\n      <td>19</td>\n      <td>180</td>\n      <td>30.5</td>\n      <td>1.391</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>309</th>\n      <td>2</td>\n      <td>124</td>\n      <td>68</td>\n      <td>28</td>\n      <td>205</td>\n      <td>32.9</td>\n      <td>0.875</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>310</th>\n      <td>6</td>\n      <td>80</td>\n      <td>66</td>\n      <td>30</td>\n      <td>0</td>\n      <td>26.2</td>\n      <td>0.313</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>311</th>\n      <td>0</td>\n      <td>106</td>\n      <td>70</td>\n      <td>37</td>\n      <td>148</td>\n      <td>39.4</td>\n      <td>0.605</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>312</th>\n      <td>2</td>\n      <td>155</td>\n      <td>74</td>\n      <td>17</td>\n      <td>96</td>\n      <td>26.6</td>\n      <td>0.433</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>313</th>\n      <td>3</td>\n      <td>113</td>\n      <td>50</td>\n      <td>10</td>\n      <td>85</td>\n      <td>29.5</td>\n      <td>0.626</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>314</th>\n      <td>7</td>\n      <td>109</td>\n      <td>80</td>\n      <td>31</td>\n      <td>0</td>\n      <td>35.9</td>\n      <td>1.127</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>315</th>\n      <td>2</td>\n      <td>112</td>\n      <td>68</td>\n      <td>22</td>\n      <td>94</td>\n      <td>34.1</td>\n      <td>0.315</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>316</th>\n      <td>3</td>\n      <td>99</td>\n      <td>80</td>\n      <td>11</td>\n      <td>64</td>\n      <td>19.3</td>\n      <td>0.284</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>317</th>\n      <td>3</td>\n      <td>182</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.5</td>\n      <td>0.345</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>318</th>\n      <td>3</td>\n      <td>115</td>\n      <td>66</td>\n      <td>39</td>\n      <td>140</td>\n      <td>38.1</td>\n      <td>0.150</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>319</th>\n      <td>6</td>\n      <td>194</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.5</td>\n      <td>0.129</td>\n      <td>59</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>320</th>\n      <td>4</td>\n      <td>129</td>\n      <td>60</td>\n      <td>12</td>\n      <td>231</td>\n      <td>27.5</td>\n      <td>0.527</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>321</th>\n      <td>3</td>\n      <td>112</td>\n      <td>74</td>\n      <td>30</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.197</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>322</th>\n      <td>0</td>\n      <td>124</td>\n      <td>70</td>\n      <td>20</td>\n      <td>0</td>\n      <td>27.4</td>\n      <td>0.254</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>323</th>\n      <td>13</td>\n      <td>152</td>\n      <td>90</td>\n      <td>33</td>\n      <td>29</td>\n      <td>26.8</td>\n      <td>0.731</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>324</th>\n      <td>2</td>\n      <td>112</td>\n      <td>75</td>\n      <td>32</td>\n      <td>0</td>\n      <td>35.7</td>\n      <td>0.148</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>325</th>\n      <td>1</td>\n      <td>157</td>\n      <td>72</td>\n      <td>21</td>\n      <td>168</td>\n      <td>25.6</td>\n      <td>0.123</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>326</th>\n      <td>1</td>\n      <td>122</td>\n      <td>64</td>\n      <td>32</td>\n      <td>156</td>\n      <td>35.1</td>\n      <td>0.692</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>327</th>\n      <td>10</td>\n      <td>179</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.1</td>\n      <td>0.200</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>328</th>\n      <td>2</td>\n      <td>102</td>\n      <td>86</td>\n      <td>36</td>\n      <td>120</td>\n      <td>45.5</td>\n      <td>0.127</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>329</th>\n      <td>6</td>\n      <td>105</td>\n      <td>70</td>\n      <td>32</td>\n      <td>68</td>\n      <td>30.8</td>\n      <td>0.122</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>330</th>\n      <td>8</td>\n      <td>118</td>\n      <td>72</td>\n      <td>19</td>\n      <td>0</td>\n      <td>23.1</td>\n      <td>1.476</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>331</th>\n      <td>2</td>\n      <td>87</td>\n      <td>58</td>\n      <td>16</td>\n      <td>52</td>\n      <td>32.7</td>\n      <td>0.166</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>332</th>\n      <td>1</td>\n      <td>180</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>43.3</td>\n      <td>0.282</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>333</th>\n      <td>12</td>\n      <td>106</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.6</td>\n      <td>0.137</td>\n      <td>44</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>334</th>\n      <td>1</td>\n      <td>95</td>\n      <td>60</td>\n      <td>18</td>\n      <td>58</td>\n      <td>23.9</td>\n      <td>0.260</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>335</th>\n      <td>0</td>\n      <td>165</td>\n      <td>76</td>\n      <td>43</td>\n      <td>255</td>\n      <td>47.9</td>\n      <td>0.259</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>336</th>\n      <td>0</td>\n      <td>117</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.8</td>\n      <td>0.932</td>\n      <td>44</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>337</th>\n      <td>5</td>\n      <td>115</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.343</td>\n      <td>44</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>338</th>\n      <td>9</td>\n      <td>152</td>\n      <td>78</td>\n      <td>34</td>\n      <td>171</td>\n      <td>34.2</td>\n      <td>0.893</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>339</th>\n      <td>7</td>\n      <td>178</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.9</td>\n      <td>0.331</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>340</th>\n      <td>1</td>\n      <td>130</td>\n      <td>70</td>\n      <td>13</td>\n      <td>105</td>\n      <td>25.9</td>\n      <td>0.472</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>341</th>\n      <td>1</td>\n      <td>95</td>\n      <td>74</td>\n      <td>21</td>\n      <td>73</td>\n      <td>25.9</td>\n      <td>0.673</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>342</th>\n      <td>1</td>\n      <td>0</td>\n      <td>68</td>\n      <td>35</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.389</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>343</th>\n      <td>5</td>\n      <td>122</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.7</td>\n      <td>0.290</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>344</th>\n      <td>8</td>\n      <td>95</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.8</td>\n      <td>0.485</td>\n      <td>57</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>345</th>\n      <td>8</td>\n      <td>126</td>\n      <td>88</td>\n      <td>36</td>\n      <td>108</td>\n      <td>38.5</td>\n      <td>0.349</td>\n      <td>49</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>346</th>\n      <td>1</td>\n      <td>139</td>\n      <td>46</td>\n      <td>19</td>\n      <td>83</td>\n      <td>28.7</td>\n      <td>0.654</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>347</th>\n      <td>3</td>\n      <td>116</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.5</td>\n      <td>0.187</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>348</th>\n      <td>3</td>\n      <td>99</td>\n      <td>62</td>\n      <td>19</td>\n      <td>74</td>\n      <td>21.8</td>\n      <td>0.279</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>349</th>\n      <td>5</td>\n      <td>0</td>\n      <td>80</td>\n      <td>32</td>\n      <td>0</td>\n      <td>41.0</td>\n      <td>0.346</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>350</th>\n      <td>4</td>\n      <td>92</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.2</td>\n      <td>0.237</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>351</th>\n      <td>4</td>\n      <td>137</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.252</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>352</th>\n      <td>3</td>\n      <td>61</td>\n      <td>82</td>\n      <td>28</td>\n      <td>0</td>\n      <td>34.4</td>\n      <td>0.243</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>353</th>\n      <td>1</td>\n      <td>90</td>\n      <td>62</td>\n      <td>12</td>\n      <td>43</td>\n      <td>27.2</td>\n      <td>0.580</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>354</th>\n      <td>3</td>\n      <td>90</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.7</td>\n      <td>0.559</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>355</th>\n      <td>9</td>\n      <td>165</td>\n      <td>88</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.4</td>\n      <td>0.302</td>\n      <td>49</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>356</th>\n      <td>1</td>\n      <td>125</td>\n      <td>50</td>\n      <td>40</td>\n      <td>167</td>\n      <td>33.3</td>\n      <td>0.962</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>357</th>\n      <td>13</td>\n      <td>129</td>\n      <td>0</td>\n      <td>30</td>\n      <td>0</td>\n      <td>39.9</td>\n      <td>0.569</td>\n      <td>44</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>358</th>\n      <td>12</td>\n      <td>88</td>\n      <td>74</td>\n      <td>40</td>\n      <td>54</td>\n      <td>35.3</td>\n      <td>0.378</td>\n      <td>48</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>359</th>\n      <td>1</td>\n      <td>196</td>\n      <td>76</td>\n      <td>36</td>\n      <td>249</td>\n      <td>36.5</td>\n      <td>0.875</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>360</th>\n      <td>5</td>\n      <td>189</td>\n      <td>64</td>\n      <td>33</td>\n      <td>325</td>\n      <td>31.2</td>\n      <td>0.583</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>361</th>\n      <td>5</td>\n      <td>158</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.8</td>\n      <td>0.207</td>\n      <td>63</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>362</th>\n      <td>5</td>\n      <td>103</td>\n      <td>108</td>\n      <td>37</td>\n      <td>0</td>\n      <td>39.2</td>\n      <td>0.305</td>\n      <td>65</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>363</th>\n      <td>4</td>\n      <td>146</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>38.5</td>\n      <td>0.520</td>\n      <td>67</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>364</th>\n      <td>4</td>\n      <td>147</td>\n      <td>74</td>\n      <td>25</td>\n      <td>293</td>\n      <td>34.9</td>\n      <td>0.385</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>365</th>\n      <td>5</td>\n      <td>99</td>\n      <td>54</td>\n      <td>28</td>\n      <td>83</td>\n      <td>34.0</td>\n      <td>0.499</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>366</th>\n      <td>6</td>\n      <td>124</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.6</td>\n      <td>0.368</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>367</th>\n      <td>0</td>\n      <td>101</td>\n      <td>64</td>\n      <td>17</td>\n      <td>0</td>\n      <td>21.0</td>\n      <td>0.252</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>368</th>\n      <td>3</td>\n      <td>81</td>\n      <td>86</td>\n      <td>16</td>\n      <td>66</td>\n      <td>27.5</td>\n      <td>0.306</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>369</th>\n      <td>1</td>\n      <td>133</td>\n      <td>102</td>\n      <td>28</td>\n      <td>140</td>\n      <td>32.8</td>\n      <td>0.234</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>370</th>\n      <td>3</td>\n      <td>173</td>\n      <td>82</td>\n      <td>48</td>\n      <td>465</td>\n      <td>38.4</td>\n      <td>2.137</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>371</th>\n      <td>0</td>\n      <td>118</td>\n      <td>64</td>\n      <td>23</td>\n      <td>89</td>\n      <td>0.0</td>\n      <td>1.731</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>372</th>\n      <td>0</td>\n      <td>84</td>\n      <td>64</td>\n      <td>22</td>\n      <td>66</td>\n      <td>35.8</td>\n      <td>0.545</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>373</th>\n      <td>2</td>\n      <td>105</td>\n      <td>58</td>\n      <td>40</td>\n      <td>94</td>\n      <td>34.9</td>\n      <td>0.225</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>374</th>\n      <td>2</td>\n      <td>122</td>\n      <td>52</td>\n      <td>43</td>\n      <td>158</td>\n      <td>36.2</td>\n      <td>0.816</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>375</th>\n      <td>12</td>\n      <td>140</td>\n      <td>82</td>\n      <td>43</td>\n      <td>325</td>\n      <td>39.2</td>\n      <td>0.528</td>\n      <td>58</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>376</th>\n      <td>0</td>\n      <td>98</td>\n      <td>82</td>\n      <td>15</td>\n      <td>84</td>\n      <td>25.2</td>\n      <td>0.299</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>377</th>\n      <td>1</td>\n      <td>87</td>\n      <td>60</td>\n      <td>37</td>\n      <td>75</td>\n      <td>37.2</td>\n      <td>0.509</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>378</th>\n      <td>4</td>\n      <td>156</td>\n      <td>75</td>\n      <td>0</td>\n      <td>0</td>\n      <td>48.3</td>\n      <td>0.238</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>379</th>\n      <td>0</td>\n      <td>93</td>\n      <td>100</td>\n      <td>39</td>\n      <td>72</td>\n      <td>43.4</td>\n      <td>1.021</td>\n      <td>35</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>380</th>\n      <td>1</td>\n      <td>107</td>\n      <td>72</td>\n      <td>30</td>\n      <td>82</td>\n      <td>30.8</td>\n      <td>0.821</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>381</th>\n      <td>0</td>\n      <td>105</td>\n      <td>68</td>\n      <td>22</td>\n      <td>0</td>\n      <td>20.0</td>\n      <td>0.236</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>382</th>\n      <td>1</td>\n      <td>109</td>\n      <td>60</td>\n      <td>8</td>\n      <td>182</td>\n      <td>25.4</td>\n      <td>0.947</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>383</th>\n      <td>1</td>\n      <td>90</td>\n      <td>62</td>\n      <td>18</td>\n      <td>59</td>\n      <td>25.1</td>\n      <td>1.268</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>384</th>\n      <td>1</td>\n      <td>125</td>\n      <td>70</td>\n      <td>24</td>\n      <td>110</td>\n      <td>24.3</td>\n      <td>0.221</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>385</th>\n      <td>1</td>\n      <td>119</td>\n      <td>54</td>\n      <td>13</td>\n      <td>50</td>\n      <td>22.3</td>\n      <td>0.205</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>386</th>\n      <td>5</td>\n      <td>116</td>\n      <td>74</td>\n      <td>29</td>\n      <td>0</td>\n      <td>32.3</td>\n      <td>0.660</td>\n      <td>35</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>387</th>\n      <td>8</td>\n      <td>105</td>\n      <td>100</td>\n      <td>36</td>\n      <td>0</td>\n      <td>43.3</td>\n      <td>0.239</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>388</th>\n      <td>5</td>\n      <td>144</td>\n      <td>82</td>\n      <td>26</td>\n      <td>285</td>\n      <td>32.0</td>\n      <td>0.452</td>\n      <td>58</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>389</th>\n      <td>3</td>\n      <td>100</td>\n      <td>68</td>\n      <td>23</td>\n      <td>81</td>\n      <td>31.6</td>\n      <td>0.949</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>390</th>\n      <td>1</td>\n      <td>100</td>\n      <td>66</td>\n      <td>29</td>\n      <td>196</td>\n      <td>32.0</td>\n      <td>0.444</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>391</th>\n      <td>5</td>\n      <td>166</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>45.7</td>\n      <td>0.340</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>392</th>\n      <td>1</td>\n      <td>131</td>\n      <td>64</td>\n      <td>14</td>\n      <td>415</td>\n      <td>23.7</td>\n      <td>0.389</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>393</th>\n      <td>4</td>\n      <td>116</td>\n      <td>72</td>\n      <td>12</td>\n      <td>87</td>\n      <td>22.1</td>\n      <td>0.463</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>394</th>\n      <td>4</td>\n      <td>158</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.9</td>\n      <td>0.803</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>395</th>\n      <td>2</td>\n      <td>127</td>\n      <td>58</td>\n      <td>24</td>\n      <td>275</td>\n      <td>27.7</td>\n      <td>1.600</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>396</th>\n      <td>3</td>\n      <td>96</td>\n      <td>56</td>\n      <td>34</td>\n      <td>115</td>\n      <td>24.7</td>\n      <td>0.944</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>397</th>\n      <td>0</td>\n      <td>131</td>\n      <td>66</td>\n      <td>40</td>\n      <td>0</td>\n      <td>34.3</td>\n      <td>0.196</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>398</th>\n      <td>3</td>\n      <td>82</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.1</td>\n      <td>0.389</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>399</th>\n      <td>3</td>\n      <td>193</td>\n      <td>70</td>\n      <td>31</td>\n      <td>0</td>\n      <td>34.9</td>\n      <td>0.241</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>400</th>\n      <td>4</td>\n      <td>95</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.161</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>401</th>\n      <td>6</td>\n      <td>137</td>\n      <td>61</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.2</td>\n      <td>0.151</td>\n      <td>55</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>402</th>\n      <td>5</td>\n      <td>136</td>\n      <td>84</td>\n      <td>41</td>\n      <td>88</td>\n      <td>35.0</td>\n      <td>0.286</td>\n      <td>35</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>403</th>\n      <td>9</td>\n      <td>72</td>\n      <td>78</td>\n      <td>25</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.280</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>404</th>\n      <td>5</td>\n      <td>168</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.9</td>\n      <td>0.135</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>405</th>\n      <td>2</td>\n      <td>123</td>\n      <td>48</td>\n      <td>32</td>\n      <td>165</td>\n      <td>42.1</td>\n      <td>0.520</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>406</th>\n      <td>4</td>\n      <td>115</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.9</td>\n      <td>0.376</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>407</th>\n      <td>0</td>\n      <td>101</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.9</td>\n      <td>0.336</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>408</th>\n      <td>8</td>\n      <td>197</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.9</td>\n      <td>1.191</td>\n      <td>39</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>409</th>\n      <td>1</td>\n      <td>172</td>\n      <td>68</td>\n      <td>49</td>\n      <td>579</td>\n      <td>42.4</td>\n      <td>0.702</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>410</th>\n      <td>6</td>\n      <td>102</td>\n      <td>90</td>\n      <td>39</td>\n      <td>0</td>\n      <td>35.7</td>\n      <td>0.674</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>411</th>\n      <td>1</td>\n      <td>112</td>\n      <td>72</td>\n      <td>30</td>\n      <td>176</td>\n      <td>34.4</td>\n      <td>0.528</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>412</th>\n      <td>1</td>\n      <td>143</td>\n      <td>84</td>\n      <td>23</td>\n      <td>310</td>\n      <td>42.4</td>\n      <td>1.076</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>413</th>\n      <td>1</td>\n      <td>143</td>\n      <td>74</td>\n      <td>22</td>\n      <td>61</td>\n      <td>26.2</td>\n      <td>0.256</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>414</th>\n      <td>0</td>\n      <td>138</td>\n      <td>60</td>\n      <td>35</td>\n      <td>167</td>\n      <td>34.6</td>\n      <td>0.534</td>\n      <td>21</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>415</th>\n      <td>3</td>\n      <td>173</td>\n      <td>84</td>\n      <td>33</td>\n      <td>474</td>\n      <td>35.7</td>\n      <td>0.258</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>416</th>\n      <td>1</td>\n      <td>97</td>\n      <td>68</td>\n      <td>21</td>\n      <td>0</td>\n      <td>27.2</td>\n      <td>1.095</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>417</th>\n      <td>4</td>\n      <td>144</td>\n      <td>82</td>\n      <td>32</td>\n      <td>0</td>\n      <td>38.5</td>\n      <td>0.554</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>418</th>\n      <td>1</td>\n      <td>83</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>18.2</td>\n      <td>0.624</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>419</th>\n      <td>3</td>\n      <td>129</td>\n      <td>64</td>\n      <td>29</td>\n      <td>115</td>\n      <td>26.4</td>\n      <td>0.219</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>420</th>\n      <td>1</td>\n      <td>119</td>\n      <td>88</td>\n      <td>41</td>\n      <td>170</td>\n      <td>45.3</td>\n      <td>0.507</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>421</th>\n      <td>2</td>\n      <td>94</td>\n      <td>68</td>\n      <td>18</td>\n      <td>76</td>\n      <td>26.0</td>\n      <td>0.561</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>422</th>\n      <td>0</td>\n      <td>102</td>\n      <td>64</td>\n      <td>46</td>\n      <td>78</td>\n      <td>40.6</td>\n      <td>0.496</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>423</th>\n      <td>2</td>\n      <td>115</td>\n      <td>64</td>\n      <td>22</td>\n      <td>0</td>\n      <td>30.8</td>\n      <td>0.421</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>424</th>\n      <td>8</td>\n      <td>151</td>\n      <td>78</td>\n      <td>32</td>\n      <td>210</td>\n      <td>42.9</td>\n      <td>0.516</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>425</th>\n      <td>4</td>\n      <td>184</td>\n      <td>78</td>\n      <td>39</td>\n      <td>277</td>\n      <td>37.0</td>\n      <td>0.264</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>426</th>\n      <td>0</td>\n      <td>94</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.256</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>427</th>\n      <td>1</td>\n      <td>181</td>\n      <td>64</td>\n      <td>30</td>\n      <td>180</td>\n      <td>34.1</td>\n      <td>0.328</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>428</th>\n      <td>0</td>\n      <td>135</td>\n      <td>94</td>\n      <td>46</td>\n      <td>145</td>\n      <td>40.6</td>\n      <td>0.284</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>429</th>\n      <td>1</td>\n      <td>95</td>\n      <td>82</td>\n      <td>25</td>\n      <td>180</td>\n      <td>35.0</td>\n      <td>0.233</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>430</th>\n      <td>2</td>\n      <td>99</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.2</td>\n      <td>0.108</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>431</th>\n      <td>3</td>\n      <td>89</td>\n      <td>74</td>\n      <td>16</td>\n      <td>85</td>\n      <td>30.4</td>\n      <td>0.551</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>432</th>\n      <td>1</td>\n      <td>80</td>\n      <td>74</td>\n      <td>11</td>\n      <td>60</td>\n      <td>30.0</td>\n      <td>0.527</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>433</th>\n      <td>2</td>\n      <td>139</td>\n      <td>75</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.6</td>\n      <td>0.167</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>434</th>\n      <td>1</td>\n      <td>90</td>\n      <td>68</td>\n      <td>8</td>\n      <td>0</td>\n      <td>24.5</td>\n      <td>1.138</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>435</th>\n      <td>0</td>\n      <td>141</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.4</td>\n      <td>0.205</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>436</th>\n      <td>12</td>\n      <td>140</td>\n      <td>85</td>\n      <td>33</td>\n      <td>0</td>\n      <td>37.4</td>\n      <td>0.244</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>437</th>\n      <td>5</td>\n      <td>147</td>\n      <td>75</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.9</td>\n      <td>0.434</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>438</th>\n      <td>1</td>\n      <td>97</td>\n      <td>70</td>\n      <td>15</td>\n      <td>0</td>\n      <td>18.2</td>\n      <td>0.147</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>439</th>\n      <td>6</td>\n      <td>107</td>\n      <td>88</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.8</td>\n      <td>0.727</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>440</th>\n      <td>0</td>\n      <td>189</td>\n      <td>104</td>\n      <td>25</td>\n      <td>0</td>\n      <td>34.3</td>\n      <td>0.435</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>441</th>\n      <td>2</td>\n      <td>83</td>\n      <td>66</td>\n      <td>23</td>\n      <td>50</td>\n      <td>32.2</td>\n      <td>0.497</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>442</th>\n      <td>4</td>\n      <td>117</td>\n      <td>64</td>\n      <td>27</td>\n      <td>120</td>\n      <td>33.2</td>\n      <td>0.230</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>443</th>\n      <td>8</td>\n      <td>108</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.5</td>\n      <td>0.955</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>444</th>\n      <td>4</td>\n      <td>117</td>\n      <td>62</td>\n      <td>12</td>\n      <td>0</td>\n      <td>29.7</td>\n      <td>0.380</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>445</th>\n      <td>0</td>\n      <td>180</td>\n      <td>78</td>\n      <td>63</td>\n      <td>14</td>\n      <td>59.4</td>\n      <td>2.420</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>446</th>\n      <td>1</td>\n      <td>100</td>\n      <td>72</td>\n      <td>12</td>\n      <td>70</td>\n      <td>25.3</td>\n      <td>0.658</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>447</th>\n      <td>0</td>\n      <td>95</td>\n      <td>80</td>\n      <td>45</td>\n      <td>92</td>\n      <td>36.5</td>\n      <td>0.330</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>448</th>\n      <td>0</td>\n      <td>104</td>\n      <td>64</td>\n      <td>37</td>\n      <td>64</td>\n      <td>33.6</td>\n      <td>0.510</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>449</th>\n      <td>0</td>\n      <td>120</td>\n      <td>74</td>\n      <td>18</td>\n      <td>63</td>\n      <td>30.5</td>\n      <td>0.285</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>450</th>\n      <td>1</td>\n      <td>82</td>\n      <td>64</td>\n      <td>13</td>\n      <td>95</td>\n      <td>21.2</td>\n      <td>0.415</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>451</th>\n      <td>2</td>\n      <td>134</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.9</td>\n      <td>0.542</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>452</th>\n      <td>0</td>\n      <td>91</td>\n      <td>68</td>\n      <td>32</td>\n      <td>210</td>\n      <td>39.9</td>\n      <td>0.381</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>453</th>\n      <td>2</td>\n      <td>119</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>19.6</td>\n      <td>0.832</td>\n      <td>72</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>454</th>\n      <td>2</td>\n      <td>100</td>\n      <td>54</td>\n      <td>28</td>\n      <td>105</td>\n      <td>37.8</td>\n      <td>0.498</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>455</th>\n      <td>14</td>\n      <td>175</td>\n      <td>62</td>\n      <td>30</td>\n      <td>0</td>\n      <td>33.6</td>\n      <td>0.212</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>456</th>\n      <td>1</td>\n      <td>135</td>\n      <td>54</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.7</td>\n      <td>0.687</td>\n      <td>62</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>457</th>\n      <td>5</td>\n      <td>86</td>\n      <td>68</td>\n      <td>28</td>\n      <td>71</td>\n      <td>30.2</td>\n      <td>0.364</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>458</th>\n      <td>10</td>\n      <td>148</td>\n      <td>84</td>\n      <td>48</td>\n      <td>237</td>\n      <td>37.6</td>\n      <td>1.001</td>\n      <td>51</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>459</th>\n      <td>9</td>\n      <td>134</td>\n      <td>74</td>\n      <td>33</td>\n      <td>60</td>\n      <td>25.9</td>\n      <td>0.460</td>\n      <td>81</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>460</th>\n      <td>9</td>\n      <td>120</td>\n      <td>72</td>\n      <td>22</td>\n      <td>56</td>\n      <td>20.8</td>\n      <td>0.733</td>\n      <td>48</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>461</th>\n      <td>1</td>\n      <td>71</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.8</td>\n      <td>0.416</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>462</th>\n      <td>8</td>\n      <td>74</td>\n      <td>70</td>\n      <td>40</td>\n      <td>49</td>\n      <td>35.3</td>\n      <td>0.705</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>463</th>\n      <td>5</td>\n      <td>88</td>\n      <td>78</td>\n      <td>30</td>\n      <td>0</td>\n      <td>27.6</td>\n      <td>0.258</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>464</th>\n      <td>10</td>\n      <td>115</td>\n      <td>98</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.0</td>\n      <td>1.022</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>465</th>\n      <td>0</td>\n      <td>124</td>\n      <td>56</td>\n      <td>13</td>\n      <td>105</td>\n      <td>21.8</td>\n      <td>0.452</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>466</th>\n      <td>0</td>\n      <td>74</td>\n      <td>52</td>\n      <td>10</td>\n      <td>36</td>\n      <td>27.8</td>\n      <td>0.269</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>467</th>\n      <td>0</td>\n      <td>97</td>\n      <td>64</td>\n      <td>36</td>\n      <td>100</td>\n      <td>36.8</td>\n      <td>0.600</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>468</th>\n      <td>8</td>\n      <td>120</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.0</td>\n      <td>0.183</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>469</th>\n      <td>6</td>\n      <td>154</td>\n      <td>78</td>\n      <td>41</td>\n      <td>140</td>\n      <td>46.1</td>\n      <td>0.571</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>470</th>\n      <td>1</td>\n      <td>144</td>\n      <td>82</td>\n      <td>40</td>\n      <td>0</td>\n      <td>41.3</td>\n      <td>0.607</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>471</th>\n      <td>0</td>\n      <td>137</td>\n      <td>70</td>\n      <td>38</td>\n      <td>0</td>\n      <td>33.2</td>\n      <td>0.170</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>472</th>\n      <td>0</td>\n      <td>119</td>\n      <td>66</td>\n      <td>27</td>\n      <td>0</td>\n      <td>38.8</td>\n      <td>0.259</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>473</th>\n      <td>7</td>\n      <td>136</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.9</td>\n      <td>0.210</td>\n      <td>50</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>474</th>\n      <td>4</td>\n      <td>114</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.9</td>\n      <td>0.126</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>475</th>\n      <td>0</td>\n      <td>137</td>\n      <td>84</td>\n      <td>27</td>\n      <td>0</td>\n      <td>27.3</td>\n      <td>0.231</td>\n      <td>59</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>476</th>\n      <td>2</td>\n      <td>105</td>\n      <td>80</td>\n      <td>45</td>\n      <td>191</td>\n      <td>33.7</td>\n      <td>0.711</td>\n      <td>29</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>477</th>\n      <td>7</td>\n      <td>114</td>\n      <td>76</td>\n      <td>17</td>\n      <td>110</td>\n      <td>23.8</td>\n      <td>0.466</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>478</th>\n      <td>8</td>\n      <td>126</td>\n      <td>74</td>\n      <td>38</td>\n      <td>75</td>\n      <td>25.9</td>\n      <td>0.162</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>479</th>\n      <td>4</td>\n      <td>132</td>\n      <td>86</td>\n      <td>31</td>\n      <td>0</td>\n      <td>28.0</td>\n      <td>0.419</td>\n      <td>63</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>480</th>\n      <td>3</td>\n      <td>158</td>\n      <td>70</td>\n      <td>30</td>\n      <td>328</td>\n      <td>35.5</td>\n      <td>0.344</td>\n      <td>35</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>481</th>\n      <td>0</td>\n      <td>123</td>\n      <td>88</td>\n      <td>37</td>\n      <td>0</td>\n      <td>35.2</td>\n      <td>0.197</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>482</th>\n      <td>4</td>\n      <td>85</td>\n      <td>58</td>\n      <td>22</td>\n      <td>49</td>\n      <td>27.8</td>\n      <td>0.306</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>483</th>\n      <td>0</td>\n      <td>84</td>\n      <td>82</td>\n      <td>31</td>\n      <td>125</td>\n      <td>38.2</td>\n      <td>0.233</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>484</th>\n      <td>0</td>\n      <td>145</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>44.2</td>\n      <td>0.630</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>485</th>\n      <td>0</td>\n      <td>135</td>\n      <td>68</td>\n      <td>42</td>\n      <td>250</td>\n      <td>42.3</td>\n      <td>0.365</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>486</th>\n      <td>1</td>\n      <td>139</td>\n      <td>62</td>\n      <td>41</td>\n      <td>480</td>\n      <td>40.7</td>\n      <td>0.536</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>487</th>\n      <td>0</td>\n      <td>173</td>\n      <td>78</td>\n      <td>32</td>\n      <td>265</td>\n      <td>46.5</td>\n      <td>1.159</td>\n      <td>58</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>488</th>\n      <td>4</td>\n      <td>99</td>\n      <td>72</td>\n      <td>17</td>\n      <td>0</td>\n      <td>25.6</td>\n      <td>0.294</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>489</th>\n      <td>8</td>\n      <td>194</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.1</td>\n      <td>0.551</td>\n      <td>67</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>490</th>\n      <td>2</td>\n      <td>83</td>\n      <td>65</td>\n      <td>28</td>\n      <td>66</td>\n      <td>36.8</td>\n      <td>0.629</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>491</th>\n      <td>2</td>\n      <td>89</td>\n      <td>90</td>\n      <td>30</td>\n      <td>0</td>\n      <td>33.5</td>\n      <td>0.292</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>492</th>\n      <td>4</td>\n      <td>99</td>\n      <td>68</td>\n      <td>38</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.145</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>493</th>\n      <td>4</td>\n      <td>125</td>\n      <td>70</td>\n      <td>18</td>\n      <td>122</td>\n      <td>28.9</td>\n      <td>1.144</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>494</th>\n      <td>3</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.174</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>495</th>\n      <td>6</td>\n      <td>166</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.6</td>\n      <td>0.304</td>\n      <td>66</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>496</th>\n      <td>5</td>\n      <td>110</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.0</td>\n      <td>0.292</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>497</th>\n      <td>2</td>\n      <td>81</td>\n      <td>72</td>\n      <td>15</td>\n      <td>76</td>\n      <td>30.1</td>\n      <td>0.547</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>498</th>\n      <td>7</td>\n      <td>195</td>\n      <td>70</td>\n      <td>33</td>\n      <td>145</td>\n      <td>25.1</td>\n      <td>0.163</td>\n      <td>55</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>499</th>\n      <td>6</td>\n      <td>154</td>\n      <td>74</td>\n      <td>32</td>\n      <td>193</td>\n      <td>29.3</td>\n      <td>0.839</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>500</th>\n      <td>2</td>\n      <td>117</td>\n      <td>90</td>\n      <td>19</td>\n      <td>71</td>\n      <td>25.2</td>\n      <td>0.313</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>501</th>\n      <td>3</td>\n      <td>84</td>\n      <td>72</td>\n      <td>32</td>\n      <td>0</td>\n      <td>37.2</td>\n      <td>0.267</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>502</th>\n      <td>6</td>\n      <td>0</td>\n      <td>68</td>\n      <td>41</td>\n      <td>0</td>\n      <td>39.0</td>\n      <td>0.727</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>503</th>\n      <td>7</td>\n      <td>94</td>\n      <td>64</td>\n      <td>25</td>\n      <td>79</td>\n      <td>33.3</td>\n      <td>0.738</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>504</th>\n      <td>3</td>\n      <td>96</td>\n      <td>78</td>\n      <td>39</td>\n      <td>0</td>\n      <td>37.3</td>\n      <td>0.238</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>505</th>\n      <td>10</td>\n      <td>75</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.3</td>\n      <td>0.263</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>506</th>\n      <td>0</td>\n      <td>180</td>\n      <td>90</td>\n      <td>26</td>\n      <td>90</td>\n      <td>36.5</td>\n      <td>0.314</td>\n      <td>35</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>507</th>\n      <td>1</td>\n      <td>130</td>\n      <td>60</td>\n      <td>23</td>\n      <td>170</td>\n      <td>28.6</td>\n      <td>0.692</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>508</th>\n      <td>2</td>\n      <td>84</td>\n      <td>50</td>\n      <td>23</td>\n      <td>76</td>\n      <td>30.4</td>\n      <td>0.968</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>509</th>\n      <td>8</td>\n      <td>120</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.0</td>\n      <td>0.409</td>\n      <td>64</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>510</th>\n      <td>12</td>\n      <td>84</td>\n      <td>72</td>\n      <td>31</td>\n      <td>0</td>\n      <td>29.7</td>\n      <td>0.297</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>511</th>\n      <td>0</td>\n      <td>139</td>\n      <td>62</td>\n      <td>17</td>\n      <td>210</td>\n      <td>22.1</td>\n      <td>0.207</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>512</th>\n      <td>9</td>\n      <td>91</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.2</td>\n      <td>0.200</td>\n      <td>58</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>513</th>\n      <td>2</td>\n      <td>91</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.3</td>\n      <td>0.525</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>514</th>\n      <td>3</td>\n      <td>99</td>\n      <td>54</td>\n      <td>19</td>\n      <td>86</td>\n      <td>25.6</td>\n      <td>0.154</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>515</th>\n      <td>3</td>\n      <td>163</td>\n      <td>70</td>\n      <td>18</td>\n      <td>105</td>\n      <td>31.6</td>\n      <td>0.268</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>516</th>\n      <td>9</td>\n      <td>145</td>\n      <td>88</td>\n      <td>34</td>\n      <td>165</td>\n      <td>30.3</td>\n      <td>0.771</td>\n      <td>53</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>517</th>\n      <td>7</td>\n      <td>125</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.6</td>\n      <td>0.304</td>\n      <td>51</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>518</th>\n      <td>13</td>\n      <td>76</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.180</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>519</th>\n      <td>6</td>\n      <td>129</td>\n      <td>90</td>\n      <td>7</td>\n      <td>326</td>\n      <td>19.6</td>\n      <td>0.582</td>\n      <td>60</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>520</th>\n      <td>2</td>\n      <td>68</td>\n      <td>70</td>\n      <td>32</td>\n      <td>66</td>\n      <td>25.0</td>\n      <td>0.187</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>521</th>\n      <td>3</td>\n      <td>124</td>\n      <td>80</td>\n      <td>33</td>\n      <td>130</td>\n      <td>33.2</td>\n      <td>0.305</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>522</th>\n      <td>6</td>\n      <td>114</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.189</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>523</th>\n      <td>9</td>\n      <td>130</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.2</td>\n      <td>0.652</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>524</th>\n      <td>3</td>\n      <td>125</td>\n      <td>58</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.6</td>\n      <td>0.151</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>525</th>\n      <td>3</td>\n      <td>87</td>\n      <td>60</td>\n      <td>18</td>\n      <td>0</td>\n      <td>21.8</td>\n      <td>0.444</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>526</th>\n      <td>1</td>\n      <td>97</td>\n      <td>64</td>\n      <td>19</td>\n      <td>82</td>\n      <td>18.2</td>\n      <td>0.299</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>527</th>\n      <td>3</td>\n      <td>116</td>\n      <td>74</td>\n      <td>15</td>\n      <td>105</td>\n      <td>26.3</td>\n      <td>0.107</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>528</th>\n      <td>0</td>\n      <td>117</td>\n      <td>66</td>\n      <td>31</td>\n      <td>188</td>\n      <td>30.8</td>\n      <td>0.493</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>529</th>\n      <td>0</td>\n      <td>111</td>\n      <td>65</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.6</td>\n      <td>0.660</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>530</th>\n      <td>2</td>\n      <td>122</td>\n      <td>60</td>\n      <td>18</td>\n      <td>106</td>\n      <td>29.8</td>\n      <td>0.717</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>531</th>\n      <td>0</td>\n      <td>107</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>45.3</td>\n      <td>0.686</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>532</th>\n      <td>1</td>\n      <td>86</td>\n      <td>66</td>\n      <td>52</td>\n      <td>65</td>\n      <td>41.3</td>\n      <td>0.917</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>533</th>\n      <td>6</td>\n      <td>91</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.8</td>\n      <td>0.501</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>534</th>\n      <td>1</td>\n      <td>77</td>\n      <td>56</td>\n      <td>30</td>\n      <td>56</td>\n      <td>33.3</td>\n      <td>1.251</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>535</th>\n      <td>4</td>\n      <td>132</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.9</td>\n      <td>0.302</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>536</th>\n      <td>0</td>\n      <td>105</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.6</td>\n      <td>0.197</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>537</th>\n      <td>0</td>\n      <td>57</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.7</td>\n      <td>0.735</td>\n      <td>67</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>538</th>\n      <td>0</td>\n      <td>127</td>\n      <td>80</td>\n      <td>37</td>\n      <td>210</td>\n      <td>36.3</td>\n      <td>0.804</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>539</th>\n      <td>3</td>\n      <td>129</td>\n      <td>92</td>\n      <td>49</td>\n      <td>155</td>\n      <td>36.4</td>\n      <td>0.968</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>540</th>\n      <td>8</td>\n      <td>100</td>\n      <td>74</td>\n      <td>40</td>\n      <td>215</td>\n      <td>39.4</td>\n      <td>0.661</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>541</th>\n      <td>3</td>\n      <td>128</td>\n      <td>72</td>\n      <td>25</td>\n      <td>190</td>\n      <td>32.4</td>\n      <td>0.549</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>542</th>\n      <td>10</td>\n      <td>90</td>\n      <td>85</td>\n      <td>32</td>\n      <td>0</td>\n      <td>34.9</td>\n      <td>0.825</td>\n      <td>56</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>543</th>\n      <td>4</td>\n      <td>84</td>\n      <td>90</td>\n      <td>23</td>\n      <td>56</td>\n      <td>39.5</td>\n      <td>0.159</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>544</th>\n      <td>1</td>\n      <td>88</td>\n      <td>78</td>\n      <td>29</td>\n      <td>76</td>\n      <td>32.0</td>\n      <td>0.365</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>545</th>\n      <td>8</td>\n      <td>186</td>\n      <td>90</td>\n      <td>35</td>\n      <td>225</td>\n      <td>34.5</td>\n      <td>0.423</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>546</th>\n      <td>5</td>\n      <td>187</td>\n      <td>76</td>\n      <td>27</td>\n      <td>207</td>\n      <td>43.6</td>\n      <td>1.034</td>\n      <td>53</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>547</th>\n      <td>4</td>\n      <td>131</td>\n      <td>68</td>\n      <td>21</td>\n      <td>166</td>\n      <td>33.1</td>\n      <td>0.160</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>548</th>\n      <td>1</td>\n      <td>164</td>\n      <td>82</td>\n      <td>43</td>\n      <td>67</td>\n      <td>32.8</td>\n      <td>0.341</td>\n      <td>50</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>549</th>\n      <td>4</td>\n      <td>189</td>\n      <td>110</td>\n      <td>31</td>\n      <td>0</td>\n      <td>28.5</td>\n      <td>0.680</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>550</th>\n      <td>1</td>\n      <td>116</td>\n      <td>70</td>\n      <td>28</td>\n      <td>0</td>\n      <td>27.4</td>\n      <td>0.204</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>551</th>\n      <td>3</td>\n      <td>84</td>\n      <td>68</td>\n      <td>30</td>\n      <td>106</td>\n      <td>31.9</td>\n      <td>0.591</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>552</th>\n      <td>6</td>\n      <td>114</td>\n      <td>88</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.8</td>\n      <td>0.247</td>\n      <td>66</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>553</th>\n      <td>1</td>\n      <td>88</td>\n      <td>62</td>\n      <td>24</td>\n      <td>44</td>\n      <td>29.9</td>\n      <td>0.422</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>554</th>\n      <td>1</td>\n      <td>84</td>\n      <td>64</td>\n      <td>23</td>\n      <td>115</td>\n      <td>36.9</td>\n      <td>0.471</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>555</th>\n      <td>7</td>\n      <td>124</td>\n      <td>70</td>\n      <td>33</td>\n      <td>215</td>\n      <td>25.5</td>\n      <td>0.161</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>556</th>\n      <td>1</td>\n      <td>97</td>\n      <td>70</td>\n      <td>40</td>\n      <td>0</td>\n      <td>38.1</td>\n      <td>0.218</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>557</th>\n      <td>8</td>\n      <td>110</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.8</td>\n      <td>0.237</td>\n      <td>58</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>558</th>\n      <td>11</td>\n      <td>103</td>\n      <td>68</td>\n      <td>40</td>\n      <td>0</td>\n      <td>46.2</td>\n      <td>0.126</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>559</th>\n      <td>11</td>\n      <td>85</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.1</td>\n      <td>0.300</td>\n      <td>35</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>560</th>\n      <td>6</td>\n      <td>125</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>33.8</td>\n      <td>0.121</td>\n      <td>54</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>561</th>\n      <td>0</td>\n      <td>198</td>\n      <td>66</td>\n      <td>32</td>\n      <td>274</td>\n      <td>41.3</td>\n      <td>0.502</td>\n      <td>28</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>562</th>\n      <td>1</td>\n      <td>87</td>\n      <td>68</td>\n      <td>34</td>\n      <td>77</td>\n      <td>37.6</td>\n      <td>0.401</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>563</th>\n      <td>6</td>\n      <td>99</td>\n      <td>60</td>\n      <td>19</td>\n      <td>54</td>\n      <td>26.9</td>\n      <td>0.497</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>564</th>\n      <td>0</td>\n      <td>91</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.601</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>565</th>\n      <td>2</td>\n      <td>95</td>\n      <td>54</td>\n      <td>14</td>\n      <td>88</td>\n      <td>26.1</td>\n      <td>0.748</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>566</th>\n      <td>1</td>\n      <td>99</td>\n      <td>72</td>\n      <td>30</td>\n      <td>18</td>\n      <td>38.6</td>\n      <td>0.412</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>567</th>\n      <td>6</td>\n      <td>92</td>\n      <td>62</td>\n      <td>32</td>\n      <td>126</td>\n      <td>32.0</td>\n      <td>0.085</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>568</th>\n      <td>4</td>\n      <td>154</td>\n      <td>72</td>\n      <td>29</td>\n      <td>126</td>\n      <td>31.3</td>\n      <td>0.338</td>\n      <td>37</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>569</th>\n      <td>0</td>\n      <td>121</td>\n      <td>66</td>\n      <td>30</td>\n      <td>165</td>\n      <td>34.3</td>\n      <td>0.203</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>570</th>\n      <td>3</td>\n      <td>78</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.5</td>\n      <td>0.270</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>571</th>\n      <td>2</td>\n      <td>130</td>\n      <td>96</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.6</td>\n      <td>0.268</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>572</th>\n      <td>3</td>\n      <td>111</td>\n      <td>58</td>\n      <td>31</td>\n      <td>44</td>\n      <td>29.5</td>\n      <td>0.430</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>573</th>\n      <td>2</td>\n      <td>98</td>\n      <td>60</td>\n      <td>17</td>\n      <td>120</td>\n      <td>34.7</td>\n      <td>0.198</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>574</th>\n      <td>1</td>\n      <td>143</td>\n      <td>86</td>\n      <td>30</td>\n      <td>330</td>\n      <td>30.1</td>\n      <td>0.892</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>575</th>\n      <td>1</td>\n      <td>119</td>\n      <td>44</td>\n      <td>47</td>\n      <td>63</td>\n      <td>35.5</td>\n      <td>0.280</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>576</th>\n      <td>6</td>\n      <td>108</td>\n      <td>44</td>\n      <td>20</td>\n      <td>130</td>\n      <td>24.0</td>\n      <td>0.813</td>\n      <td>35</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>577</th>\n      <td>2</td>\n      <td>118</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.9</td>\n      <td>0.693</td>\n      <td>21</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>578</th>\n      <td>10</td>\n      <td>133</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.0</td>\n      <td>0.245</td>\n      <td>36</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>579</th>\n      <td>2</td>\n      <td>197</td>\n      <td>70</td>\n      <td>99</td>\n      <td>0</td>\n      <td>34.7</td>\n      <td>0.575</td>\n      <td>62</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>580</th>\n      <td>0</td>\n      <td>151</td>\n      <td>90</td>\n      <td>46</td>\n      <td>0</td>\n      <td>42.1</td>\n      <td>0.371</td>\n      <td>21</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>581</th>\n      <td>6</td>\n      <td>109</td>\n      <td>60</td>\n      <td>27</td>\n      <td>0</td>\n      <td>25.0</td>\n      <td>0.206</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>582</th>\n      <td>12</td>\n      <td>121</td>\n      <td>78</td>\n      <td>17</td>\n      <td>0</td>\n      <td>26.5</td>\n      <td>0.259</td>\n      <td>62</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>583</th>\n      <td>8</td>\n      <td>100</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>38.7</td>\n      <td>0.190</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>584</th>\n      <td>8</td>\n      <td>124</td>\n      <td>76</td>\n      <td>24</td>\n      <td>600</td>\n      <td>28.7</td>\n      <td>0.687</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>585</th>\n      <td>1</td>\n      <td>93</td>\n      <td>56</td>\n      <td>11</td>\n      <td>0</td>\n      <td>22.5</td>\n      <td>0.417</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>586</th>\n      <td>8</td>\n      <td>143</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.9</td>\n      <td>0.129</td>\n      <td>41</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>587</th>\n      <td>6</td>\n      <td>103</td>\n      <td>66</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.3</td>\n      <td>0.249</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>588</th>\n      <td>3</td>\n      <td>176</td>\n      <td>86</td>\n      <td>27</td>\n      <td>156</td>\n      <td>33.3</td>\n      <td>1.154</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>589</th>\n      <td>0</td>\n      <td>73</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>21.1</td>\n      <td>0.342</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>590</th>\n      <td>11</td>\n      <td>111</td>\n      <td>84</td>\n      <td>40</td>\n      <td>0</td>\n      <td>46.8</td>\n      <td>0.925</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>591</th>\n      <td>2</td>\n      <td>112</td>\n      <td>78</td>\n      <td>50</td>\n      <td>140</td>\n      <td>39.4</td>\n      <td>0.175</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>592</th>\n      <td>3</td>\n      <td>132</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.4</td>\n      <td>0.402</td>\n      <td>44</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>593</th>\n      <td>2</td>\n      <td>82</td>\n      <td>52</td>\n      <td>22</td>\n      <td>115</td>\n      <td>28.5</td>\n      <td>1.699</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>594</th>\n      <td>6</td>\n      <td>123</td>\n      <td>72</td>\n      <td>45</td>\n      <td>230</td>\n      <td>33.6</td>\n      <td>0.733</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>595</th>\n      <td>0</td>\n      <td>188</td>\n      <td>82</td>\n      <td>14</td>\n      <td>185</td>\n      <td>32.0</td>\n      <td>0.682</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>596</th>\n      <td>0</td>\n      <td>67</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>45.3</td>\n      <td>0.194</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>597</th>\n      <td>1</td>\n      <td>89</td>\n      <td>24</td>\n      <td>19</td>\n      <td>25</td>\n      <td>27.8</td>\n      <td>0.559</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>598</th>\n      <td>1</td>\n      <td>173</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.8</td>\n      <td>0.088</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>599</th>\n      <td>1</td>\n      <td>109</td>\n      <td>38</td>\n      <td>18</td>\n      <td>120</td>\n      <td>23.1</td>\n      <td>0.407</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>600</th>\n      <td>1</td>\n      <td>108</td>\n      <td>88</td>\n      <td>19</td>\n      <td>0</td>\n      <td>27.1</td>\n      <td>0.400</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>601</th>\n      <td>6</td>\n      <td>96</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.7</td>\n      <td>0.190</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>602</th>\n      <td>1</td>\n      <td>124</td>\n      <td>74</td>\n      <td>36</td>\n      <td>0</td>\n      <td>27.8</td>\n      <td>0.100</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>603</th>\n      <td>7</td>\n      <td>150</td>\n      <td>78</td>\n      <td>29</td>\n      <td>126</td>\n      <td>35.2</td>\n      <td>0.692</td>\n      <td>54</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>604</th>\n      <td>4</td>\n      <td>183</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.4</td>\n      <td>0.212</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>605</th>\n      <td>1</td>\n      <td>124</td>\n      <td>60</td>\n      <td>32</td>\n      <td>0</td>\n      <td>35.8</td>\n      <td>0.514</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>606</th>\n      <td>1</td>\n      <td>181</td>\n      <td>78</td>\n      <td>42</td>\n      <td>293</td>\n      <td>40.0</td>\n      <td>1.258</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>607</th>\n      <td>1</td>\n      <td>92</td>\n      <td>62</td>\n      <td>25</td>\n      <td>41</td>\n      <td>19.5</td>\n      <td>0.482</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>608</th>\n      <td>0</td>\n      <td>152</td>\n      <td>82</td>\n      <td>39</td>\n      <td>272</td>\n      <td>41.5</td>\n      <td>0.270</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>609</th>\n      <td>1</td>\n      <td>111</td>\n      <td>62</td>\n      <td>13</td>\n      <td>182</td>\n      <td>24.0</td>\n      <td>0.138</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>610</th>\n      <td>3</td>\n      <td>106</td>\n      <td>54</td>\n      <td>21</td>\n      <td>158</td>\n      <td>30.9</td>\n      <td>0.292</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>611</th>\n      <td>3</td>\n      <td>174</td>\n      <td>58</td>\n      <td>22</td>\n      <td>194</td>\n      <td>32.9</td>\n      <td>0.593</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>612</th>\n      <td>7</td>\n      <td>168</td>\n      <td>88</td>\n      <td>42</td>\n      <td>321</td>\n      <td>38.2</td>\n      <td>0.787</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>613</th>\n      <td>6</td>\n      <td>105</td>\n      <td>80</td>\n      <td>28</td>\n      <td>0</td>\n      <td>32.5</td>\n      <td>0.878</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>614</th>\n      <td>11</td>\n      <td>138</td>\n      <td>74</td>\n      <td>26</td>\n      <td>144</td>\n      <td>36.1</td>\n      <td>0.557</td>\n      <td>50</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>615</th>\n      <td>3</td>\n      <td>106</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.8</td>\n      <td>0.207</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>616</th>\n      <td>6</td>\n      <td>117</td>\n      <td>96</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.7</td>\n      <td>0.157</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>617</th>\n      <td>2</td>\n      <td>68</td>\n      <td>62</td>\n      <td>13</td>\n      <td>15</td>\n      <td>20.1</td>\n      <td>0.257</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>618</th>\n      <td>9</td>\n      <td>112</td>\n      <td>82</td>\n      <td>24</td>\n      <td>0</td>\n      <td>28.2</td>\n      <td>1.282</td>\n      <td>50</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>619</th>\n      <td>0</td>\n      <td>119</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.141</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>620</th>\n      <td>2</td>\n      <td>112</td>\n      <td>86</td>\n      <td>42</td>\n      <td>160</td>\n      <td>38.4</td>\n      <td>0.246</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>621</th>\n      <td>2</td>\n      <td>92</td>\n      <td>76</td>\n      <td>20</td>\n      <td>0</td>\n      <td>24.2</td>\n      <td>1.698</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>622</th>\n      <td>6</td>\n      <td>183</td>\n      <td>94</td>\n      <td>0</td>\n      <td>0</td>\n      <td>40.8</td>\n      <td>1.461</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>623</th>\n      <td>0</td>\n      <td>94</td>\n      <td>70</td>\n      <td>27</td>\n      <td>115</td>\n      <td>43.5</td>\n      <td>0.347</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>624</th>\n      <td>2</td>\n      <td>108</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.8</td>\n      <td>0.158</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>625</th>\n      <td>4</td>\n      <td>90</td>\n      <td>88</td>\n      <td>47</td>\n      <td>54</td>\n      <td>37.7</td>\n      <td>0.362</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>626</th>\n      <td>0</td>\n      <td>125</td>\n      <td>68</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.7</td>\n      <td>0.206</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>627</th>\n      <td>0</td>\n      <td>132</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.393</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>628</th>\n      <td>5</td>\n      <td>128</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.6</td>\n      <td>0.144</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>629</th>\n      <td>4</td>\n      <td>94</td>\n      <td>65</td>\n      <td>22</td>\n      <td>0</td>\n      <td>24.7</td>\n      <td>0.148</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>630</th>\n      <td>7</td>\n      <td>114</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.4</td>\n      <td>0.732</td>\n      <td>34</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>631</th>\n      <td>0</td>\n      <td>102</td>\n      <td>78</td>\n      <td>40</td>\n      <td>90</td>\n      <td>34.5</td>\n      <td>0.238</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>632</th>\n      <td>2</td>\n      <td>111</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.2</td>\n      <td>0.343</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>633</th>\n      <td>1</td>\n      <td>128</td>\n      <td>82</td>\n      <td>17</td>\n      <td>183</td>\n      <td>27.5</td>\n      <td>0.115</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>634</th>\n      <td>10</td>\n      <td>92</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.9</td>\n      <td>0.167</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>635</th>\n      <td>13</td>\n      <td>104</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>0.465</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>636</th>\n      <td>5</td>\n      <td>104</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.8</td>\n      <td>0.153</td>\n      <td>48</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>637</th>\n      <td>2</td>\n      <td>94</td>\n      <td>76</td>\n      <td>18</td>\n      <td>66</td>\n      <td>31.6</td>\n      <td>0.649</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>638</th>\n      <td>7</td>\n      <td>97</td>\n      <td>76</td>\n      <td>32</td>\n      <td>91</td>\n      <td>40.9</td>\n      <td>0.871</td>\n      <td>32</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>639</th>\n      <td>1</td>\n      <td>100</td>\n      <td>74</td>\n      <td>12</td>\n      <td>46</td>\n      <td>19.5</td>\n      <td>0.149</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>640</th>\n      <td>0</td>\n      <td>102</td>\n      <td>86</td>\n      <td>17</td>\n      <td>105</td>\n      <td>29.3</td>\n      <td>0.695</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>641</th>\n      <td>4</td>\n      <td>128</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>34.3</td>\n      <td>0.303</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>642</th>\n      <td>6</td>\n      <td>147</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.5</td>\n      <td>0.178</td>\n      <td>50</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>643</th>\n      <td>4</td>\n      <td>90</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.0</td>\n      <td>0.610</td>\n      <td>31</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>644</th>\n      <td>3</td>\n      <td>103</td>\n      <td>72</td>\n      <td>30</td>\n      <td>152</td>\n      <td>27.6</td>\n      <td>0.730</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>645</th>\n      <td>2</td>\n      <td>157</td>\n      <td>74</td>\n      <td>35</td>\n      <td>440</td>\n      <td>39.4</td>\n      <td>0.134</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>646</th>\n      <td>1</td>\n      <td>167</td>\n      <td>74</td>\n      <td>17</td>\n      <td>144</td>\n      <td>23.4</td>\n      <td>0.447</td>\n      <td>33</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>647</th>\n      <td>0</td>\n      <td>179</td>\n      <td>50</td>\n      <td>36</td>\n      <td>159</td>\n      <td>37.8</td>\n      <td>0.455</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>648</th>\n      <td>11</td>\n      <td>136</td>\n      <td>84</td>\n      <td>35</td>\n      <td>130</td>\n      <td>28.3</td>\n      <td>0.260</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>649</th>\n      <td>0</td>\n      <td>107</td>\n      <td>60</td>\n      <td>25</td>\n      <td>0</td>\n      <td>26.4</td>\n      <td>0.133</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>650</th>\n      <td>1</td>\n      <td>91</td>\n      <td>54</td>\n      <td>25</td>\n      <td>100</td>\n      <td>25.2</td>\n      <td>0.234</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>651</th>\n      <td>1</td>\n      <td>117</td>\n      <td>60</td>\n      <td>23</td>\n      <td>106</td>\n      <td>33.8</td>\n      <td>0.466</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>652</th>\n      <td>5</td>\n      <td>123</td>\n      <td>74</td>\n      <td>40</td>\n      <td>77</td>\n      <td>34.1</td>\n      <td>0.269</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>653</th>\n      <td>2</td>\n      <td>120</td>\n      <td>54</td>\n      <td>0</td>\n      <td>0</td>\n      <td>26.8</td>\n      <td>0.455</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>654</th>\n      <td>1</td>\n      <td>106</td>\n      <td>70</td>\n      <td>28</td>\n      <td>135</td>\n      <td>34.2</td>\n      <td>0.142</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>655</th>\n      <td>2</td>\n      <td>155</td>\n      <td>52</td>\n      <td>27</td>\n      <td>540</td>\n      <td>38.7</td>\n      <td>0.240</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>656</th>\n      <td>2</td>\n      <td>101</td>\n      <td>58</td>\n      <td>35</td>\n      <td>90</td>\n      <td>21.8</td>\n      <td>0.155</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>657</th>\n      <td>1</td>\n      <td>120</td>\n      <td>80</td>\n      <td>48</td>\n      <td>200</td>\n      <td>38.9</td>\n      <td>1.162</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>658</th>\n      <td>11</td>\n      <td>127</td>\n      <td>106</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.0</td>\n      <td>0.190</td>\n      <td>51</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>659</th>\n      <td>3</td>\n      <td>80</td>\n      <td>82</td>\n      <td>31</td>\n      <td>70</td>\n      <td>34.2</td>\n      <td>1.292</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>660</th>\n      <td>10</td>\n      <td>162</td>\n      <td>84</td>\n      <td>0</td>\n      <td>0</td>\n      <td>27.7</td>\n      <td>0.182</td>\n      <td>54</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>661</th>\n      <td>1</td>\n      <td>199</td>\n      <td>76</td>\n      <td>43</td>\n      <td>0</td>\n      <td>42.9</td>\n      <td>1.394</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>662</th>\n      <td>8</td>\n      <td>167</td>\n      <td>106</td>\n      <td>46</td>\n      <td>231</td>\n      <td>37.6</td>\n      <td>0.165</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>663</th>\n      <td>9</td>\n      <td>145</td>\n      <td>80</td>\n      <td>46</td>\n      <td>130</td>\n      <td>37.9</td>\n      <td>0.637</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>664</th>\n      <td>6</td>\n      <td>115</td>\n      <td>60</td>\n      <td>39</td>\n      <td>0</td>\n      <td>33.7</td>\n      <td>0.245</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>665</th>\n      <td>1</td>\n      <td>112</td>\n      <td>80</td>\n      <td>45</td>\n      <td>132</td>\n      <td>34.8</td>\n      <td>0.217</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>666</th>\n      <td>4</td>\n      <td>145</td>\n      <td>82</td>\n      <td>18</td>\n      <td>0</td>\n      <td>32.5</td>\n      <td>0.235</td>\n      <td>70</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>667</th>\n      <td>10</td>\n      <td>111</td>\n      <td>70</td>\n      <td>27</td>\n      <td>0</td>\n      <td>27.5</td>\n      <td>0.141</td>\n      <td>40</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>668</th>\n      <td>6</td>\n      <td>98</td>\n      <td>58</td>\n      <td>33</td>\n      <td>190</td>\n      <td>34.0</td>\n      <td>0.430</td>\n      <td>43</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>669</th>\n      <td>9</td>\n      <td>154</td>\n      <td>78</td>\n      <td>30</td>\n      <td>100</td>\n      <td>30.9</td>\n      <td>0.164</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>670</th>\n      <td>6</td>\n      <td>165</td>\n      <td>68</td>\n      <td>26</td>\n      <td>168</td>\n      <td>33.6</td>\n      <td>0.631</td>\n      <td>49</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>671</th>\n      <td>1</td>\n      <td>99</td>\n      <td>58</td>\n      <td>10</td>\n      <td>0</td>\n      <td>25.4</td>\n      <td>0.551</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>672</th>\n      <td>10</td>\n      <td>68</td>\n      <td>106</td>\n      <td>23</td>\n      <td>49</td>\n      <td>35.5</td>\n      <td>0.285</td>\n      <td>47</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>673</th>\n      <td>3</td>\n      <td>123</td>\n      <td>100</td>\n      <td>35</td>\n      <td>240</td>\n      <td>57.3</td>\n      <td>0.880</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>674</th>\n      <td>8</td>\n      <td>91</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.6</td>\n      <td>0.587</td>\n      <td>68</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>675</th>\n      <td>6</td>\n      <td>195</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.9</td>\n      <td>0.328</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>676</th>\n      <td>9</td>\n      <td>156</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.8</td>\n      <td>0.230</td>\n      <td>53</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>677</th>\n      <td>0</td>\n      <td>93</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.3</td>\n      <td>0.263</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>678</th>\n      <td>3</td>\n      <td>121</td>\n      <td>52</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.0</td>\n      <td>0.127</td>\n      <td>25</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>679</th>\n      <td>2</td>\n      <td>101</td>\n      <td>58</td>\n      <td>17</td>\n      <td>265</td>\n      <td>24.2</td>\n      <td>0.614</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>680</th>\n      <td>2</td>\n      <td>56</td>\n      <td>56</td>\n      <td>28</td>\n      <td>45</td>\n      <td>24.2</td>\n      <td>0.332</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>681</th>\n      <td>0</td>\n      <td>162</td>\n      <td>76</td>\n      <td>36</td>\n      <td>0</td>\n      <td>49.6</td>\n      <td>0.364</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>682</th>\n      <td>0</td>\n      <td>95</td>\n      <td>64</td>\n      <td>39</td>\n      <td>105</td>\n      <td>44.6</td>\n      <td>0.366</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>683</th>\n      <td>4</td>\n      <td>125</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.3</td>\n      <td>0.536</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>684</th>\n      <td>5</td>\n      <td>136</td>\n      <td>82</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.640</td>\n      <td>69</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>685</th>\n      <td>2</td>\n      <td>129</td>\n      <td>74</td>\n      <td>26</td>\n      <td>205</td>\n      <td>33.2</td>\n      <td>0.591</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>686</th>\n      <td>3</td>\n      <td>130</td>\n      <td>64</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.1</td>\n      <td>0.314</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>687</th>\n      <td>1</td>\n      <td>107</td>\n      <td>50</td>\n      <td>19</td>\n      <td>0</td>\n      <td>28.3</td>\n      <td>0.181</td>\n      <td>29</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>688</th>\n      <td>1</td>\n      <td>140</td>\n      <td>74</td>\n      <td>26</td>\n      <td>180</td>\n      <td>24.1</td>\n      <td>0.828</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>689</th>\n      <td>1</td>\n      <td>144</td>\n      <td>82</td>\n      <td>46</td>\n      <td>180</td>\n      <td>46.1</td>\n      <td>0.335</td>\n      <td>46</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>690</th>\n      <td>8</td>\n      <td>107</td>\n      <td>80</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.6</td>\n      <td>0.856</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>691</th>\n      <td>13</td>\n      <td>158</td>\n      <td>114</td>\n      <td>0</td>\n      <td>0</td>\n      <td>42.3</td>\n      <td>0.257</td>\n      <td>44</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>692</th>\n      <td>2</td>\n      <td>121</td>\n      <td>70</td>\n      <td>32</td>\n      <td>95</td>\n      <td>39.1</td>\n      <td>0.886</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>693</th>\n      <td>7</td>\n      <td>129</td>\n      <td>68</td>\n      <td>49</td>\n      <td>125</td>\n      <td>38.5</td>\n      <td>0.439</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>694</th>\n      <td>2</td>\n      <td>90</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.5</td>\n      <td>0.191</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>695</th>\n      <td>7</td>\n      <td>142</td>\n      <td>90</td>\n      <td>24</td>\n      <td>480</td>\n      <td>30.4</td>\n      <td>0.128</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>696</th>\n      <td>3</td>\n      <td>169</td>\n      <td>74</td>\n      <td>19</td>\n      <td>125</td>\n      <td>29.9</td>\n      <td>0.268</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>697</th>\n      <td>0</td>\n      <td>99</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>25.0</td>\n      <td>0.253</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>698</th>\n      <td>4</td>\n      <td>127</td>\n      <td>88</td>\n      <td>11</td>\n      <td>155</td>\n      <td>34.5</td>\n      <td>0.598</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>699</th>\n      <td>4</td>\n      <td>118</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>44.5</td>\n      <td>0.904</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>700</th>\n      <td>2</td>\n      <td>122</td>\n      <td>76</td>\n      <td>27</td>\n      <td>200</td>\n      <td>35.9</td>\n      <td>0.483</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>701</th>\n      <td>6</td>\n      <td>125</td>\n      <td>78</td>\n      <td>31</td>\n      <td>0</td>\n      <td>27.6</td>\n      <td>0.565</td>\n      <td>49</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>702</th>\n      <td>1</td>\n      <td>168</td>\n      <td>88</td>\n      <td>29</td>\n      <td>0</td>\n      <td>35.0</td>\n      <td>0.905</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>703</th>\n      <td>2</td>\n      <td>129</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>38.5</td>\n      <td>0.304</td>\n      <td>41</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>704</th>\n      <td>4</td>\n      <td>110</td>\n      <td>76</td>\n      <td>20</td>\n      <td>100</td>\n      <td>28.4</td>\n      <td>0.118</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>705</th>\n      <td>6</td>\n      <td>80</td>\n      <td>80</td>\n      <td>36</td>\n      <td>0</td>\n      <td>39.8</td>\n      <td>0.177</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>706</th>\n      <td>10</td>\n      <td>115</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>0.0</td>\n      <td>0.261</td>\n      <td>30</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>707</th>\n      <td>2</td>\n      <td>127</td>\n      <td>46</td>\n      <td>21</td>\n      <td>335</td>\n      <td>34.4</td>\n      <td>0.176</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>708</th>\n      <td>9</td>\n      <td>164</td>\n      <td>78</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.148</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>709</th>\n      <td>2</td>\n      <td>93</td>\n      <td>64</td>\n      <td>32</td>\n      <td>160</td>\n      <td>38.0</td>\n      <td>0.674</td>\n      <td>23</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>710</th>\n      <td>3</td>\n      <td>158</td>\n      <td>64</td>\n      <td>13</td>\n      <td>387</td>\n      <td>31.2</td>\n      <td>0.295</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>711</th>\n      <td>5</td>\n      <td>126</td>\n      <td>78</td>\n      <td>27</td>\n      <td>22</td>\n      <td>29.6</td>\n      <td>0.439</td>\n      <td>40</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>712</th>\n      <td>10</td>\n      <td>129</td>\n      <td>62</td>\n      <td>36</td>\n      <td>0</td>\n      <td>41.2</td>\n      <td>0.441</td>\n      <td>38</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>713</th>\n      <td>0</td>\n      <td>134</td>\n      <td>58</td>\n      <td>20</td>\n      <td>291</td>\n      <td>26.4</td>\n      <td>0.352</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>714</th>\n      <td>3</td>\n      <td>102</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>29.5</td>\n      <td>0.121</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>715</th>\n      <td>7</td>\n      <td>187</td>\n      <td>50</td>\n      <td>33</td>\n      <td>392</td>\n      <td>33.9</td>\n      <td>0.826</td>\n      <td>34</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>716</th>\n      <td>3</td>\n      <td>173</td>\n      <td>78</td>\n      <td>39</td>\n      <td>185</td>\n      <td>33.8</td>\n      <td>0.970</td>\n      <td>31</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>717</th>\n      <td>10</td>\n      <td>94</td>\n      <td>72</td>\n      <td>18</td>\n      <td>0</td>\n      <td>23.1</td>\n      <td>0.595</td>\n      <td>56</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>718</th>\n      <td>1</td>\n      <td>108</td>\n      <td>60</td>\n      <td>46</td>\n      <td>178</td>\n      <td>35.5</td>\n      <td>0.415</td>\n      <td>24</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>719</th>\n      <td>5</td>\n      <td>97</td>\n      <td>76</td>\n      <td>27</td>\n      <td>0</td>\n      <td>35.6</td>\n      <td>0.378</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>720</th>\n      <td>4</td>\n      <td>83</td>\n      <td>86</td>\n      <td>19</td>\n      <td>0</td>\n      <td>29.3</td>\n      <td>0.317</td>\n      <td>34</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>721</th>\n      <td>1</td>\n      <td>114</td>\n      <td>66</td>\n      <td>36</td>\n      <td>200</td>\n      <td>38.1</td>\n      <td>0.289</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>722</th>\n      <td>1</td>\n      <td>149</td>\n      <td>68</td>\n      <td>29</td>\n      <td>127</td>\n      <td>29.3</td>\n      <td>0.349</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>723</th>\n      <td>5</td>\n      <td>117</td>\n      <td>86</td>\n      <td>30</td>\n      <td>105</td>\n      <td>39.1</td>\n      <td>0.251</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>724</th>\n      <td>1</td>\n      <td>111</td>\n      <td>94</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.8</td>\n      <td>0.265</td>\n      <td>45</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>725</th>\n      <td>4</td>\n      <td>112</td>\n      <td>78</td>\n      <td>40</td>\n      <td>0</td>\n      <td>39.4</td>\n      <td>0.236</td>\n      <td>38</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>726</th>\n      <td>1</td>\n      <td>116</td>\n      <td>78</td>\n      <td>29</td>\n      <td>180</td>\n      <td>36.1</td>\n      <td>0.496</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>727</th>\n      <td>0</td>\n      <td>141</td>\n      <td>84</td>\n      <td>26</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.433</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>728</th>\n      <td>2</td>\n      <td>175</td>\n      <td>88</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.9</td>\n      <td>0.326</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>729</th>\n      <td>2</td>\n      <td>92</td>\n      <td>52</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.1</td>\n      <td>0.141</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>730</th>\n      <td>3</td>\n      <td>130</td>\n      <td>78</td>\n      <td>23</td>\n      <td>79</td>\n      <td>28.4</td>\n      <td>0.323</td>\n      <td>34</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>731</th>\n      <td>8</td>\n      <td>120</td>\n      <td>86</td>\n      <td>0</td>\n      <td>0</td>\n      <td>28.4</td>\n      <td>0.259</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>732</th>\n      <td>2</td>\n      <td>174</td>\n      <td>88</td>\n      <td>37</td>\n      <td>120</td>\n      <td>44.5</td>\n      <td>0.646</td>\n      <td>24</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>733</th>\n      <td>2</td>\n      <td>106</td>\n      <td>56</td>\n      <td>27</td>\n      <td>165</td>\n      <td>29.0</td>\n      <td>0.426</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>734</th>\n      <td>2</td>\n      <td>105</td>\n      <td>75</td>\n      <td>0</td>\n      <td>0</td>\n      <td>23.3</td>\n      <td>0.560</td>\n      <td>53</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>735</th>\n      <td>4</td>\n      <td>95</td>\n      <td>60</td>\n      <td>32</td>\n      <td>0</td>\n      <td>35.4</td>\n      <td>0.284</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>736</th>\n      <td>0</td>\n      <td>126</td>\n      <td>86</td>\n      <td>27</td>\n      <td>120</td>\n      <td>27.4</td>\n      <td>0.515</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>737</th>\n      <td>8</td>\n      <td>65</td>\n      <td>72</td>\n      <td>23</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.600</td>\n      <td>42</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>738</th>\n      <td>2</td>\n      <td>99</td>\n      <td>60</td>\n      <td>17</td>\n      <td>160</td>\n      <td>36.6</td>\n      <td>0.453</td>\n      <td>21</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>739</th>\n      <td>1</td>\n      <td>102</td>\n      <td>74</td>\n      <td>0</td>\n      <td>0</td>\n      <td>39.5</td>\n      <td>0.293</td>\n      <td>42</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>740</th>\n      <td>11</td>\n      <td>120</td>\n      <td>80</td>\n      <td>37</td>\n      <td>150</td>\n      <td>42.3</td>\n      <td>0.785</td>\n      <td>48</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>741</th>\n      <td>3</td>\n      <td>102</td>\n      <td>44</td>\n      <td>20</td>\n      <td>94</td>\n      <td>30.8</td>\n      <td>0.400</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>742</th>\n      <td>1</td>\n      <td>109</td>\n      <td>58</td>\n      <td>18</td>\n      <td>116</td>\n      <td>28.5</td>\n      <td>0.219</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>743</th>\n      <td>9</td>\n      <td>140</td>\n      <td>94</td>\n      <td>0</td>\n      <td>0</td>\n      <td>32.7</td>\n      <td>0.734</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>744</th>\n      <td>13</td>\n      <td>153</td>\n      <td>88</td>\n      <td>37</td>\n      <td>140</td>\n      <td>40.6</td>\n      <td>1.174</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>745</th>\n      <td>12</td>\n      <td>100</td>\n      <td>84</td>\n      <td>33</td>\n      <td>105</td>\n      <td>30.0</td>\n      <td>0.488</td>\n      <td>46</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>746</th>\n      <td>1</td>\n      <td>147</td>\n      <td>94</td>\n      <td>41</td>\n      <td>0</td>\n      <td>49.3</td>\n      <td>0.358</td>\n      <td>27</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>747</th>\n      <td>1</td>\n      <td>81</td>\n      <td>74</td>\n      <td>41</td>\n      <td>57</td>\n      <td>46.3</td>\n      <td>1.096</td>\n      <td>32</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>748</th>\n      <td>3</td>\n      <td>187</td>\n      <td>70</td>\n      <td>22</td>\n      <td>200</td>\n      <td>36.4</td>\n      <td>0.408</td>\n      <td>36</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>749</th>\n      <td>6</td>\n      <td>162</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>24.3</td>\n      <td>0.178</td>\n      <td>50</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>750</th>\n      <td>4</td>\n      <td>136</td>\n      <td>70</td>\n      <td>0</td>\n      <td>0</td>\n      <td>31.2</td>\n      <td>1.182</td>\n      <td>22</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>751</th>\n      <td>1</td>\n      <td>121</td>\n      <td>78</td>\n      <td>39</td>\n      <td>74</td>\n      <td>39.0</td>\n      <td>0.261</td>\n      <td>28</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>752</th>\n      <td>3</td>\n      <td>108</td>\n      <td>62</td>\n      <td>24</td>\n      <td>0</td>\n      <td>26.0</td>\n      <td>0.223</td>\n      <td>25</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>753</th>\n      <td>0</td>\n      <td>181</td>\n      <td>88</td>\n      <td>44</td>\n      <td>510</td>\n      <td>43.3</td>\n      <td>0.222</td>\n      <td>26</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>754</th>\n      <td>8</td>\n      <td>154</td>\n      <td>78</td>\n      <td>32</td>\n      <td>0</td>\n      <td>32.4</td>\n      <td>0.443</td>\n      <td>45</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>755</th>\n      <td>1</td>\n      <td>128</td>\n      <td>88</td>\n      <td>39</td>\n      <td>110</td>\n      <td>36.5</td>\n      <td>1.057</td>\n      <td>37</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>756</th>\n      <td>7</td>\n      <td>137</td>\n      <td>90</td>\n      <td>41</td>\n      <td>0</td>\n      <td>32.0</td>\n      <td>0.391</td>\n      <td>39</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>757</th>\n      <td>0</td>\n      <td>123</td>\n      <td>72</td>\n      <td>0</td>\n      <td>0</td>\n      <td>36.3</td>\n      <td>0.258</td>\n      <td>52</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>758</th>\n      <td>1</td>\n      <td>106</td>\n      <td>76</td>\n      <td>0</td>\n      <td>0</td>\n      <td>37.5</td>\n      <td>0.197</td>\n      <td>26</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>759</th>\n      <td>6</td>\n      <td>190</td>\n      <td>92</td>\n      <td>0</td>\n      <td>0</td>\n      <td>35.5</td>\n      <td>0.278</td>\n      <td>66</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>760</th>\n      <td>2</td>\n      <td>88</td>\n      <td>58</td>\n      <td>26</td>\n      <td>16</td>\n      <td>28.4</td>\n      <td>0.766</td>\n      <td>22</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>761</th>\n      <td>9</td>\n      <td>170</td>\n      <td>74</td>\n      <td>31</td>\n      <td>0</td>\n      <td>44.0</td>\n      <td>0.403</td>\n      <td>43</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>762</th>\n      <td>9</td>\n      <td>89</td>\n      <td>62</td>\n      <td>0</td>\n      <td>0</td>\n      <td>22.5</td>\n      <td>0.142</td>\n      <td>33</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>763</th>\n      <td>10</td>\n      <td>101</td>\n      <td>76</td>\n      <td>48</td>\n      <td>180</td>\n      <td>32.9</td>\n      <td>0.171</td>\n      <td>63</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>764</th>\n      <td>2</td>\n      <td>122</td>\n      <td>70</td>\n      <td>27</td>\n      <td>0</td>\n      <td>36.8</td>\n      <td>0.340</td>\n      <td>27</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>765</th>\n      <td>5</td>\n      <td>121</td>\n      <td>72</td>\n      <td>23</td>\n      <td>112</td>\n      <td>26.2</td>\n      <td>0.245</td>\n      <td>30</td>\n      <td>0</td>\n    </tr>\n    <tr>\n      <th>766</th>\n      <td>1</td>\n      <td>126</td>\n      <td>60</td>\n      <td>0</td>\n      <td>0</td>\n      <td>30.1</td>\n      <td>0.349</td>\n      <td>47</td>\n      <td>1</td>\n    </tr>\n    <tr>\n      <th>767</th>\n      <td>1</td>\n      <td>93</td>\n      <td>70</td>\n      <td>31</td>\n      <td>0</td>\n      <td>30.4</td>\n      <td>0.315</td>\n      <td>23</td>\n      <td>0</td>\n    </tr>\n  </tbody>
`
  var table = document.getElementById("myTable");
  for (i = 0; i < table.rows.length; i++) {
  table.rows[i].deleteCell(table.rows[i].cells[0]);
}

}
function to_python_format(){
var the_headers= document.querySelectorAll('[name="header"]');
var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value} else {
document.getElementById("myTable").rows[i].cells[j].innerText=document.getElementById("myTable").rows[i].cells[j].children[0].innerText;}

}}
 document.getElementById('grouped').value=document.getElementById('myTable').outerHTML;
 var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
    var num_cols=document.getElementById('myTable').rows[0].cells.length;
    for(i=0;i<num_rows;i++){
    for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerHTML='<td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>';
    document.getElementById("myTable").rows[i].cells[j].children[0].value=the_headers[j].value;}else{document.getElementById("myTable").rows[i].cells[j].innerHTML=`<td><div style="height:25px" contenteditable></div></td>`}

    }}
}
function to_python_format_2(){
var the_headers= document.querySelectorAll('[name="header"]');
var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value} else {
document.getElementById("myTable").rows[i].cells[j].innerText=document.getElementById("myTable").rows[i].cells[j].children[0].innerText;}

}}
 document.getElementById('cross').value=document.getElementById('myTable').outerHTML;
}
function to_python_format_3(){
var the_headers= document.querySelectorAll('[name="header"]');
var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value} else {
document.getElementById("myTable").rows[i].cells[j].innerText=document.getElementById("myTable").rows[i].cells[j].children[0].innerText;}

}}
 document.getElementById('ML_df').value=document.getElementById('myTable').outerHTML;
}
function to_python_format_4(){
var the_headers= document.querySelectorAll('[name="header"]');
var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value} else {
document.getElementById("myTable").rows[i].cells[j].innerText=document.getElementById("myTable").rows[i].cells[j].children[0].innerText;}

}}
 document.getElementById('pca_df').value=document.getElementById('myTable').outerHTML;
}
function to_python_format_5(){

var the_headers= document.querySelectorAll('[name="header"]');
var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value} else {
document.getElementById("myTable").rows[i].cells[j].innerText=document.getElementById("myTable").rows[i].cells[j].children[0].innerText;}

}}
 document.getElementById('regr').value=document.getElementById('myTable').outerHTML;
}

var did_sud=false;
var did_mine=false;
var that_old_table='';

function did_they(){
if(did_sud==false){did_sud=true;
that_old_table = document.getElementById('myTable').innerHTML;
}
if(did_mine==false){did_mine=true;
that_old_table = document.getElementById('myTable').innerHTML;
}}
function corr(){
var c=[];
var cc=[];
var table = document.getElementById("myTable");
var row = table.insertRow(table.rows.length-1);
for(ii=0;ii<(table.rows[1].cells.length);ii++){
var cell = row.insertCell(ii);
cell.innerHTML = "<td><div contenteditable></div></td>";
}

var num_rows=document.getElementById('myTable').rows.length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_cols;i++){
for(j=0;j<num_cols;j++){
c=[];
cc=[];
for(cf=1;cf<num_rows-2;cf++){
c.push(parseInt(document.getElementById('myTable').rows[cf].cells[i].innerText));
cc.push(parseInt(document.getElementById('myTable').rows[cf].cells[j].innerText));
}
c.pop();
cc.pop();
document.getElementById('the_new_tab').rows[0].cells[i].innerHTML+='<b>'+
table.rows[0].cells[j].children[0].value+'</b>: '+ss.sampleCorrelation(c,cc).toFixed(2)+'<br>'

}

}

document.getElementById('the_new_tab').style.height=200;
}

function two(){
var c=[];
var cc=[];
var table = document.getElementById("myTable");
var row = table.insertRow(table.rows.length-1);
for(ii=0;ii<(table.rows[1].cells.length);ii++){
var cell = row.insertCell(ii);
cell.innerHTML = "<td><div contenteditable></div></td>";
}

var num_rows=document.getElementById('myTable').rows.length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_cols;i++){
for(j=0;j<num_cols;j++){
c=[];
cc=[];
for(cf=1;cf<num_rows-2;cf++){
c.push(parseInt(document.getElementById('myTable').rows[cf].cells[i].innerText));
cc.push(parseInt(document.getElementById('myTable').rows[cf].cells[j].innerText));
}
c.pop();
cc.pop();
document.getElementById('the_new_tab').rows[0].cells[i].innerHTML+='<b>'+
table.rows[0].cells[j].children[0].value+'</b>: '+ss.tTestTwoSample(c,cc).toFixed(2)+'<br>'

}

}

document.getElementById('the_new_tab').style.height=200;
}


function maps(){
    if(document.getElementById('mapper').value==='USA'){
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }

for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_locations').value){
    var the_locations=cs[i+1];
  }
}
for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_map_values').value){
    var the_map_values=cs[i+1];
  }
}
for(hj=0;hj<the_map_values.length;hj++){
the_map_values[hj]=parseInt(the_map_values[hj]);
}
tt=[];//NJ,[],NY,[]...

for(i=0;i<the_locations.length;i++){
if(!tt.includes(the_locations[i])){
tt.push(the_locations[i],[]);
}
}
for(i=0;i<tt.length;i++){
for(j=0;j<the_locations.length;j++){
if(tt[i]===the_locations[j]){
tt[i+1].push(the_map_values[j]);}
}
}
for(u=1;u<tt.length;u+=2){

tt[u]=Math.round((tt[u].reduce((a, b) => a + b))/tt[u].length);

}

var new_loc=[];
var new_vals=[];
for(ui=1;ui<tt.length;ui+=2){
new_vals.push(tt[ui])
}
for(uy=0;uy<tt.length;uy+=2){
new_loc.push(tt[uy])
}
var data = [{
          type: 'choropleth',
          locationmode: 'USA-states',
          locations: new_loc,
          z:new_vals,
          text: new_loc,
          colorscale: [
              [0, 'rgb(242,240,247)'], [0.2, 'rgb(218,218,235)'],
              [0.4, 'rgb(188,189,220)'], [0.6, 'rgb(158,154,200)'],
              [0.8, 'rgb(117,107,177)'], [1, 'rgb(84,39,143)']
          ],
          colorbar: {

              thickness: 0.2
          },
          marker: {
              line:{
                  color: 'rgb(255,255,255)',
                  width: 2
              }
          }
      }];


      var layout = {

          geo:{
              scope: 'usa',
              showlakes: true,
              lakecolor: 'rgb(255,255,255)'
          }
      };

      Plotly.newPlot("myDiv", data, layout, {showLink: false});

}else{
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }

for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_locations').value){
    var the_locations=cs[i+1];
  }
}
for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_map_values').value){
    var the_map_values=cs[i+1];
  }
}
for(hj=0;hj<the_map_values.length;hj++){
the_map_values[hj]=parseInt(the_map_values[hj]);
}
tt=[];//NJ,[],NY,[]...

for(i=0;i<the_locations.length;i++){
if(!tt.includes(the_locations[i])){
tt.push(the_locations[i],[]);
}
}
for(i=0;i<tt.length;i++){
for(j=0;j<the_locations.length;j++){
if(tt[i]===the_locations[j]){
tt[i+1].push(the_map_values[j]);}
}
}
for(u=1;u<tt.length;u+=2){

tt[u]=Math.round((tt[u].reduce((a, b) => a + b))/tt[u].length);

}

var new_loc=[];
var new_vals=[];
for(ui=1;ui<tt.length;ui+=2){
new_vals.push(tt[ui])
}
for(uy=0;uy<tt.length;uy+=2){
new_loc.push(tt[uy])
}
var data = [{
          type: 'choropleth',
          locationmode: 'country names',
          locations: new_loc,
          z:new_vals,
          text: new_loc,
          colorscale: [
              [0, 'rgb(242,240,247)'], [0.2, 'rgb(218,218,235)'],
              [0.4, 'rgb(188,189,220)'], [0.6, 'rgb(158,154,200)'],
              [0.8, 'rgb(117,107,177)'], [1, 'rgb(84,39,143)']
          ],
          colorbar: {

              thickness: 0.2
          },
          marker: {
              line:{
                  color: 'rgb(255,255,255)',
                  width: 2
              }
          }
      }];


      var layout = {

          geo: {
          projection: {
              type: 'robinson'
          }
      }
      };

      Plotly.newPlot("myDiv", data, layout, {showLink: false})

}
}
function time(){
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }

for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_time_variable').value){
    var the_y_variable=cs[i+1];
  }
}
for(i=0;i<cs.length;i++){
  if(cs[i]===document.getElementById('the_time').value){
    var that_date=cs[i+1];
  }
}
var data = [
  {
    x: that_date,
    y: the_y_variable,
    type: 'scatter'
  }
];
Plotly.newPlot('myDiv', data);

}
  </script>
  <script>
function box(){
let x="that"
let y="this"
tab=document.getElementById("myTable");
var cs=[];
var pass_counter=0;
for(i=0;i<tab.rows[0].cells.length;i++){
if(isNaN(tab.rows[1].cells[i].innerText)===false){
  if(pass_counter!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  pass_counter++;
  }
  }


var trace1 = {
  name: cs[0],
  y: cs[1],
  type: 'violin'
};

var trace2 = {
  name:cs[2],
  y: cs[3],
  type: 'violin'
};
var trace3 = {
  name:cs[4],
  y: cs[5],
  type: 'violin'
};
var trace4 = {
  name:cs[6],
  y: cs[7],
  type: 'violin'
};
var trace5 = {
  name:cs[8],
  y: cs[9],
  type: 'violin'
};
var trace6 = {
  name:cs[10],
  y: cs[11],
  type: 'violin'
};
var trace7 = {
  name:cs[12],
  y: cs[13],
  type: 'violin'
};
var trace8 = {
  name:cs[14],
  y: cs[15],
  type: 'violin'
};
var trace9 = {
  name:cs[16],
  y: cs[17],
  type: 'violin'
};
var trace10 = {
  name:cs[18],
  y: cs[19],
  type: 'violin'
};
var trace11 = {
  name:cs[20],
  y: cs[21],
  type: 'violin'
};
var trace12 = {
  name:cs[22],
  y: cs[23],
  type: 'violin'
};

var data = [trace1, trace2,trace3,trace4,trace5,trace6,trace7,trace8,trace9,trace10,trace11,trace12];

Plotly.newPlot('myDiv_2', data);}

function histogram(){
let x="that"
let y="this"
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(isNaN(tab.rows[1].cells[i].innerText)===false){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }}

var trace1 = {
  name: cs[0],
  opacity: 0.75,
  x: cs[1],
  type: 'histogram',
  autobinx: true
};

var trace2 = {
  name:cs[2],
  opacity: 0.75,
  x: cs[3],
  type: 'histogram',
  autobinx: true
};
var trace3 = {
  name:cs[4],
  opacity: 0.75,
  x: cs[5],
  type: 'histogram',
  autobinx: true
};
var trace4 = {
  name:cs[6],
  opacity: 0.75,
  x: cs[7],
  type: 'histogram',
  autobinx: true
};
var trace5 = {
  name:cs[8],
  opacity: 0.75,
  x: cs[9],
  type: 'histogram',
  autobinx: true
};
var trace6 = {
  name:cs[10],
  opacity: 0.75,
  x: cs[11],
  type: 'histogram',
  autobinx: true
};
var trace7 = {
  name:cs[12],
  opacity: 0.75,
  x: cs[13],
  type: 'histogram'
};
var trace8 = {
  name:cs[14],
  opacity: 0.75,
  x: cs[15],
  type: 'histogram'
};
var trace9 = {
  name:cs[16],
  opacity: 0.75,
  x: cs[17],
  type: 'histogram'
};
var trace10 = {
  name:cs[18],
  opacity: 0.75,
  x: cs[19],
  type: 'histogram'
};
var trace11 = {
  name:cs[20],
  opacity: 0.75,
  x: cs[21],
  type: 'histogram'
};
var trace12 = {
  name:cs[22],
  opacity: 0.75,
  x: cs[23],
  type: 'histogram'
};

var data = [trace1, trace2,trace3,trace4,trace5,trace6,trace7,trace8,trace9,trace10,trace11,trace12];
var layout={barmode:'overlay',xaxis: {title: ""},
  yaxis: {title: ""}};
Plotly.newPlot('myDiv', data,layout);}

function catogram(){
let x="that"
let y="this"
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(isNaN(tab.rows[1].cells[i].innerText)===true){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];

 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }

  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }}

var trace1 = {
  name: cs[0],
  opacity: 0.75,
  y: cs[1],
  orientation:'h',
  type: 'bar',
  autobinx: true
};

var trace2 = {
  name:cs[2],
  opacity: 0.75,
  y: cs[3],
  orientation:'h',
  type: 'bar',
  autobinx: true
};
var trace3 = {
  name:cs[4],
  opacity: 0.75,
  y: cs[5],
  orientation:'h',
  type: 'bar',
  autobinx: true
};
var trace4 = {
  name:cs[6],
  opacity: 0.75,
  y: cs[7],
  orientation:'h',
  type: 'bar',
  autobinx: true
};
var trace5 = {
  name:cs[8],
  opacity: 0.75,
  y: cs[9],
  orientation:'h',
  type: 'bar',
  autobinx: true
};
var trace6 = {
  name:cs[10],
  opacity: 0.75,
  y: cs[11],
  orientation:'h',
  type: 'bar',
  autobinx: true
};
var trace7 = {
  name:cs[12],
  opacity: 0.75,
  y: cs[13],
  orientation:'h',
  type: 'bar'
};
var trace8 = {
  name:cs[14],
  opacity: 0.75,
  y: cs[15],
  orientation:'h',
  type: 'bar'
};
var trace9 = {
  name:cs[16],
  opacity: 0.75,
  y: cs[17],
  orientation:'h',
  type: 'bar'
};
var trace10 = {
  name:cs[18],
  opacity: 0.75,
  y: cs[19],
  orientation:'h',
  type: 'bar'
};
var trace11 = {
  name:cs[20],
  opacity: 0.75,
  y: cs[21],
  orientation:'h',
  type: 'bar'
};
var trace12 = {
  name:cs[22],
  opacity: 0.75,
  y: cs[23],
  orientation:'h',
  type: 'bar'
};

var data = [trace1, trace2,trace3,trace4,trace5,trace6,trace7,trace8,trace9,trace10,trace11,trace12];
var layout={barmode:'stacked',xaxis: {title: ""},
  yaxis: {title: "Count"}};
Plotly.newPlot('myDiv', data,layout);}

function venndiagramo(){
var tab=document.getElementById('myTable');
var counter=0;
var that_sub_counter=0;
var that_sub2_counter=0;
var header_one=document.getElementById('first_ven').value;
var header_two=document.getElementById('second_ven').value;
var that_sub=document.getElementById('first_venn').value;
var that_sub2=document.getElementById('second_venn').value;
for(i=1;i<tab.rows.length;i++){
  for(j=0;j<tab.rows[0].cells.length;j++){
    if((tab.rows[i].cells[j].innerText===that_sub)&&(tab.rows[0].cells[j].querySelector('input').value===header_one)){ for(jj=0;jj<tab.rows[0].cells.length;jj++){if((tab.rows[i].cells[jj].innerText===that_sub2)&&(tab.rows[0].cells[jj].querySelector('input').value===header_two)){
    counter++;}}}
 if((tab.rows[i].cells[j].innerText===that_sub)&&(tab.rows[0].cells[j].querySelector('input').value===header_one)){that_sub_counter++;}
 if((tab.rows[i].cells[j].innerText===that_sub2)&&(tab.rows[0].cells[j].querySelector('input').value===header_two)){that_sub2_counter++;}
    }}
that_sub_counter=that_sub_counter-counter;
that_sub2_counter=that_sub2_counter-counter;
var trace1 = {
  x: [1, 1.75, 2.5],
  y: [1, 1, 1],
  type: 'scatter',
  mode: 'text',
  text: [that_sub+":"+that_sub_counter, counter, that_sub2+":"+that_sub2_counter],
  textfont: {
    color: 'black',
    size: 18,
    family: 'Arial'
  }
};
var layout = {
  title: '',
  xaxis: {
    showticklabels: false,
    autotick: false,
    showgrid: false,
    zeroline: false
  },
  yaxis: {
    showticklabels: false,
    autotick: false,
    showgrid: false,
    zeroline: false
  },
  shapes: [{
    opacity: 0.3,
    xref: 'x',
    yref: 'y',
    fillcolor: 'blue',
    x0: 0,
    y0: 0,
    x1: 2,
    y1: 2,
    type: 'circle',
    line: {
      color: 'blue'
    }
  }, {
    opacity: 0.3,
    xref: 'x',
    yref: 'y',
    fillcolor: 'green',
    x0: 1.5,
    y0: 0,
    x1: 3.5,
    y1: 2,
    type: 'circle',
    line: {
      color: 'green'
    }
  }],
  margin: {
    l: 20,
    r: 20,
    b: 100
  },
  height: 500,
  width: 500
};
var data = [trace1];
Plotly.newPlot('myDiv', data, layout);
}

function graph(){
tab=document.getElementById("myTable");
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
  if(i!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];
 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }
  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  }
if(tab.rows[0].cells.length==2){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},]
}];}
else if(tab.rows[0].cells.length==3){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]}]
}];}
else if(tab.rows[0].cells.length==4){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]}]
}];}
else if(tab.rows[0].cells.length==5){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]}]
}];}
else if(tab.rows[0].cells.length==6){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]}]
}];}
if(tab.rows[0].cells.length==7){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]}]
}];}
if(tab.rows[0].cells.length==8){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]}]
}];}
if(tab.rows[0].cells.length==9){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]}]
}];}
if(tab.rows[0].cells.length==10){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]}]
}];}
if(tab.rows[0].cells.length==11){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]},
      {label: cs[20],
     values: cs[21]}]
}];}
if(tab.rows[0].cells.length>=12){
var data = [ {
  type: 'splom',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]},
      {label: cs[20],
     values: cs[21]},
      {label: cs[22],
     values: cs[23]}]
}];}
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
 var layout = {
 height: 400,
 width: 400,
 autosize: false,
 hovermode:'closest',
 dragmode:'select',
 plot_bgcolor:'rgba(240,240,240, 0.95)',
}
}else{var layout = {
 height: 800,
 width: 800,
 autosize: false,
 hovermode:'closest',
 dragmode:'select',
 plot_bgcolor:'rgba(240,240,240, 0.95)',
}}


Plotly.newPlot('myDiv', data, layout);

}
function catgraph(){
tab=document.getElementById("myTable");
var pass_counter=0;
var cs=[];

for(i=0;i<tab.rows[0].cells.length;i++){
if(isNaN(tab.rows[1].cells[i].innerText)===true){
  if(pass_counter!=0){
  cs[cs.length]=(cs_vals);}
  cs[cs.length]=tab.rows[0].cells[i].querySelector('input').value;
  var cs_vals=[];
 for(j=0;j<tab.rows.length;j++){
 	if(j!=0){
  cs_vals[cs_vals.length]=tab.rows[j].cells[i].innerText;}
  }
  if(i==tab.rows[0].cells.length-1){
  cs[cs.length]=(cs_vals);}
  pass_counter++;}}
if(tab.rows[0].cells.length==2){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},],
     line: {

         shape: 'hspline'},
}];}
else if(tab.rows[0].cells.length==3){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]}],
     line: {

         shape: 'hspline'},
}];}
else if(tab.rows[0].cells.length==4){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]}],
     line: {

         shape: 'hspline'},
}];}
else if(tab.rows[0].cells.length==5){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]}],
     line: {

         shape: 'hspline'},
}];}
else if(tab.rows[0].cells.length==6){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length==7){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length==8){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length==9){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length==10){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length==11){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]},
      {label: cs[20],
     values: cs[21]}],
     line: {

         shape: 'hspline'},
}];}
if(tab.rows[0].cells.length>=12){
var data = [ {
  type: 'parcats',
  dimensions: [
    {label: cs[0],
     values: cs[1]},
    {label: cs[2],
     values: cs[3]},
     {label: cs[4],
     values: cs[5]},
     {label: cs[6],
     values: cs[7]},
     {label: cs[8],
     values: cs[9]},
      {label: cs[10],
     values: cs[11]},
       {label: cs[12],
     values: cs[13]},
     {label: cs[14],
     values: cs[15]},
      {label: cs[16],
     values: cs[17]},
     {label: cs[18],
     values: cs[19]},
      {label: cs[20],
     values: cs[21]},
      {label: cs[22],
     values: cs[23]}],
     line: {

         shape: 'hspline'},
}];}
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
 var layout = {
 height: 400,
 width: 400,
 autosize: false,
 hovermode:'closest',
 dragmode:'select',
 plot_bgcolor:'rgba(240,240,240, 0.95)',
}
}else{var layout = {
 height: 800,
 width: 800,
 autosize: false,
 hovermode:'closest',
 dragmode:'select',
 plot_bgcolor:'rgba(240,240,240, 0.95)',
}}

Plotly.newPlot('myDiv', data, layout);

}
function sudo(){
document.getElementById('div1').innerHTML=`
<div id="div1">
<table style="background-color:#FFFFF0" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="ninth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>


</table></div>
`
let n1=[5,3,4,6,7,8,9,1,2]
let n2=[6,7,2,1,9,5,3,4,8]
let n3=[1,9,8,3,4,2,5,6,7]
let n4=[8,5,9,7,6,1,4,2,3]
let n5=[4,2,6,8,5,3,7,9,1]
let n6=[7,1,3,9,2,4,8,5,6]
let n7=[9,6,1,5,3,7,2,8,4]
let n8=[2,8,7,4,1,9,6,3,5]
let n9=[3,4,5,2,8,6,1,7,9]

var ns_1=[n1,n2,n3]
var ns_2=[n4,n5,n6]
var ns_3=[n7,n8,n9]

const rand1 = Math.floor(Math.random() * 3);
if (rand1==2){
var rows1= [ns_1[2],ns_1[1],ns_1[0]];}
else if (rand1==1){
var rows1= [ns_1[1],ns_1[0],ns_1[2]];}
else{var rows1= [ns_1[0],ns_1[2],ns_1[1]];}

const rand2 = Math.floor(Math.random() * 3);
if (rand2==2){
var rows2= [ns_2[2],ns_2[1],ns_2[0]];}
else if (rand2==1){
var rows2= [ns_2[1],ns_2[0],ns_2[2]];}
else{var rows2= [ns_2[0],ns_2[2],ns_2[1]];}

const rand3 = Math.floor(Math.random() * 3);
if (rand3==2){
var rows3= [ns_3[2],ns_3[1],ns_3[0]];}
else if (rand3==1){
var rows3= [ns_3[1],ns_3[0],ns_3[2]];}
else{var rows3= [ns_3[0],ns_3[2],ns_3[1]];}

const rand4 = Math.floor(Math.random() * 3);
if (rand4==2){
var ns_c= [rows2,rows1,rows3];}
else if (rand4==1){
var ns_c= [rows3,rows2,rows1];}
else{var ns_c= [rows3,rows1,rows2];}


var ns = [].concat.apply([], ns_c); //flat

var c1=[];//transpose then rinse and repeat
var c2=[];
var c3=[];
var c4=[];
var c5=[];
var c6=[];
var c7=[];
var c8=[];
var c9=[];

c1.push(ns[0][0],ns[1][0],ns[2][0],ns[3][0],ns[4][0],ns[5][0],ns[6][0],ns[7][0],ns[8][0]);
c2.push(ns[0][1],ns[1][1],ns[2][1],ns[3][1],ns[4][1],ns[5][1],ns[6][1],ns[7][1],ns[8][1]);
c3.push(ns[0][2],ns[1][2],ns[2][2],ns[3][2],ns[4][2],ns[5][2],ns[6][2],ns[7][2],ns[8][2]);
c4.push(ns[0][3],ns[1][3],ns[2][3],ns[3][3],ns[4][3],ns[5][3],ns[6][3],ns[7][3],ns[8][3]);
c5.push(ns[0][4],ns[1][4],ns[2][4],ns[3][4],ns[4][4],ns[5][4],ns[6][4],ns[7][4],ns[8][4]);
c6.push(ns[0][5],ns[1][5],ns[2][5],ns[3][5],ns[4][5],ns[5][5],ns[6][5],ns[7][5],ns[8][5]);
c7.push(ns[0][6],ns[1][6],ns[2][6],ns[3][6],ns[4][6],ns[5][6],ns[6][6],ns[7][6],ns[8][6]);
c8.push(ns[0][7],ns[1][7],ns[2][7],ns[3][7],ns[4][7],ns[5][7],ns[6][7],ns[7][7],ns[8][7]);
c9.push(ns[0][8],ns[1][8],ns[2][8],ns[3][8],ns[4][8],ns[5][8],ns[6][8],ns[7][8],ns[8][8]);

var cs_1=[c1,c2,c3]
var cs_2=[c4,c5,c6]
var cs_3=[c7,c8,c9]

const rand1_2 = Math.floor(Math.random() * 3);
if (rand1_2==2){
var rows1c= [cs_1[2],cs_1[1],cs_1[0]];}
else if (rand1_2==1){
var rows1c= [cs_1[1],cs_1[0],cs_1[2]];}
else{var rows1c= [cs_1[0],cs_1[2],cs_1[1]];}

const rand2_2 = Math.floor(Math.random() * 3);
if (rand2_2==2){
var rows2c= [cs_2[2],cs_2[1],cs_2[0]];}
else if (rand2_2==1){
var rows2c= [cs_2[1],cs_2[0],cs_2[2]];}
else{var rows2c= [cs_2[0],cs_2[2],cs_2[1]];}

const rand3_2 = Math.floor(Math.random() * 3);
if (rand3_2==2){
var rows3c= [cs_3[2],cs_3[1],cs_3[0]];}
else if (rand3_2==1){
var rows3c= [cs_3[1],cs_3[0],cs_3[2]];}
else{var rows3c= [cs_3[0],cs_3[2],cs_3[1]];}

const rand4_2 = Math.floor(Math.random() * 3);
if (rand4_2==2){
var ns_c_2= [rows2c,rows1c,rows3c];}
else if (rand4_2==1){
var ns_c_2= [rows3c,rows2c,rows1c];}
else{var ns_c_2= [rows3c,rows1c,rows2c];}

var ns = [].concat.apply([], ns_c_2); //flat

for(i=0;i<9;i++){
for(j=0;j<9;j++){
if(!((i==0&&j==3)||(i==0&&j==4)||(i==0&&j==5)||(i==1&&j==3)||(i==1&&j==4)||(i==1&&j==5)||(i==2&&j==3)||(i==2&&j==4)||(i==2&&j==5)||(i==3&&j==0)||(i==3&&j==1)||(i==3&&j==2)||(i==4&&j==0)||(i==4&&j==1)||(i==4&&j==2)||(i==5&&j==0)||(i==5&&j==1)||(i==5&&j==2)||(i==3&&j==6)||(i==3&&j==7)||(i==3&&j==8)||(i==4&&j==6)||(i==4&&j==7)||(i==4&&j==8)||(i==5&&j==6)||(i==5&&j==7)||(i==5&&j==8)||(i==6&&j==3)||(i==6&&j==4)||(i==6&&j==5)||(i==7&&j==3)||(i==7&&j==4)||(i==7&&j==5)||(i==8&&j==3)||(i==8&&j==4)||(i==8&&j==5))){document.getElementById("myTable").rows[i].cells[j].style="background-color: lightblue"}
const rando_last = Math.floor(Math.random() * 3);
if(rando_last!=2 && rando_last!=1){
document.getElementById("myTable").rows[i].cells[j].innerHTML=ns[i][j]+'&nbsp;&nbsp;&nbsp;';}else{
document.getElementById("myTable").rows[i].cells[j].innerHTML="<td><div contenteditable></div></td>";}

}}


}
function addRow() {
  let table = document.getElementById("myTable");
  let row = table.insertRow(table.rows.length-1);
  for(i=0;i<(table.rows[1].cells.length);i++){
  let cell = row.insertCell(i);
  cell.innerHTML = "<td><div style='height:25px' contenteditable></div></td>";
}}
function deleteRow() {
  let table = document.getElementById("myTable");
  if(table.rows.length!=1){
  table.deleteRow(table.rows.length-1);}
}

function addColumn() {
  var table = document.getElementById("myTable");
  for (i = 0; i < table.rows.length; i++) {
  let x = table.rows[i].insertCell(table.rows[i].cells.length);
  if(i==0){
  x.innerHTML = '<td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>';}else{
  x.innerHTML = "<td><div style='height:25px' contenteditable></div></td>";}
  }

  var table = document.getElementById("the_new_tab");
  for (i = 0; i < table.rows.length; i++) {
  let x = table.rows[i].insertCell(table.rows[i].cells.length);
  x.innerHTML = "<td><div style='height:25px' contenteditable></div></td>";
  }
  }
function deleteColumn() {
  var table = document.getElementById("myTable");
  for (i = 0; i < table.rows.length; i++) {
  table.rows[i].deleteCell(table.rows[i].cells.length-1);
}}
function sumation(){
let table = document.getElementById("myTable");
let row = table.insertRow(table.rows.length-1);
for(i=0;i<(table.rows[1].cells.length);i++){
let cell = row.insertCell(i);
cell.innerHTML = "<td><div contenteditable>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</div></td>";
}
var reducer = (accumulator, currentValue) => +accumulator + +currentValue;
var num_rows=document.getElementById('myTable').rows.length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_cols;i++){
var column=[];
for(j=0;j<num_rows;j++){
if (j!=0 && document.getElementById('myTable').rows[j].cells[i].innerText!=''){
column.push(document.getElementById('myTable').rows[j].cells[i].innerText)};
}


document.getElementById('the_new_tab').rows[0].cells[i].innerHTML="<b>"+column.reduce(reducer)+"</b>&thinsp;&thinsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&thinsp;";}
}
function mean(){
let table = document.getElementById("myTable");
var num_rows=document.getElementById('myTable').rows.length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_cols;i++){
var column=[];
for(j=0;j<num_rows;j++){
if (j!=0 && document.getElementById('myTable').rows[j].cells[i].innerText!=''){
column.push(parseInt(document.getElementById('myTable').rows[j].cells[i].innerText))};
}
let mean=ss.mean(column);
let std=ss.sampleStandardDeviation(column);
let n = Math.sqrt(column.length);
document.getElementById('the_new_tab').rows[0].cells[i].innerHTML="&thinsp;&nbsp;&nbsp;<b>"+mean+"+/-"+Math.round((1.96*std)/n)+"</b>&nbsp;&thinsp;&thinsp;";}
}
//download function inspired by stackoverflow
function download_csv(csv, filename) {
    var the_csvFile = new Blob([csv], {type: "text/csv"});
    var downloadLink = document.createElement("a");
    downloadLink.download = filename;
    downloadLink.href = window.URL.createObjectURL(the_csvFile);
    downloadLink.style.display = "none";
    document.body.appendChild(downloadLink);
    downloadLink.click();
}

function export_table_to_csv(html, filename) {
	var the_csv = [];
	var rows = document.querySelectorAll("table tr");
    for (var i = 0; i < rows.length; i++) {
		var row = [], cols = rows[i].querySelectorAll("td, th");
        for (var j = 0; j < cols.length; j++)
            row.push(cols[j].innerText);
		the_csv.push(row.join(","));
	}
    download_csv(the_csv.join("\n"), filename);
}

document.getElementById("thistest").addEventListener("click", function () {
    var the_headers= document.querySelectorAll('[name="header"]');
    var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
    var num_cols=document.getElementById('myTable').rows[0].cells.length;
    for(i=0;i<num_rows;i++){
    for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerText=the_headers[j].value;}}}
    var html = document.querySelector("table").outerHTML;
	export_table_to_csv(html, "table.csv");
    var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
    var num_cols=document.getElementById('myTable').rows[0].cells.length;
    for(i=0;i<num_rows;i++){
    for(j=0;j<num_cols;j++){
    if(i==0){document.getElementById("myTable").rows[i].cells[j].innerHTML='<td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>';
    document.getElementById("myTable").rows[i].cells[j].children[0].value=the_headers[j].value;}}}

});
</script>
<script>

var bad_ids=[];

function math_again(){
    if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {

    document.getElementById('div1').innerHTML=`
    <div id="div1">
<table style="height:200px;border-top: 2px solid black;
border-bottom: 2px solid black;
border-left: 2px solid black;
border-right: 2px solid black;
overflow-y:scroll;
overflow-x:scroll;
height:250px;
width:570px;
display:block;background-color: rgba(255,255,255,0.5);" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

</table></div>`;}else{
if ((did_sud===true)||(did_mine===true)){
document.getElementById('myTable').style.width=570;
document.getElementById('myTable').innerHTML=that_old_table;}else{
if(! /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
document.getElementById('div1').innerHTML=`
<div id="div1">
<table style="border-top: 2px solid black;
border-bottom: 2px solid black;
border-left: 2px solid black;
border-right: 2px solid black;
overflow-y:scroll;
overflow-x:scroll;
height:250px;
width:570px;
display:block;background-color: rgba(255,255,255,0.5);" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="ninth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="tens_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

</table></div>
`;
document.getElementById('the_new_table').innerHTML=`<div id='the_new_table'><table style="height:57px;background-color: rgba(255,255,255,0.7);"id='the_new_tab'>
<tr><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td>
<td><div style="height:25px;width:57px" contenteditable></div></td></tr>
</table></div>`;
} else {
document.getElementById('myTable').style.width=160;
    document.getElementById('div1').innerHTML=`
    <div id="div1">
<table style="background-color: rgba(255,255,255,0.7)" id="myTable">
  <tr id="first_row">
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>
    <td><input name="header" placeholder="Edit" style="width:57px;border:0px;background-color:#f5f2d0;"></td>

  </tr>
  <tr id="second_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
    <tr id="third_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fourth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="fifth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

  <tr id="sixth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="seventh_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>
  <tr id="eighth_row">
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>
    <td><div style="height:25px" contenteditable></div></td>

  </tr>

</table></div>`;
document.getElementById('the_new_table').innerHTML=`<table style="height:57px;background-color: rgba(255,255,255,0.7);"id='the_new_tab'>
<tr><td> <div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td><td><div style="height:25px;width:57px" contenteditable></div></td></tr></table>`;

}
document.getElementById("thistest").style.display = 'block';
Plotly.purge("myDiv");
}
did_sud=false;
did_mine=false;
}}
function Play() {

var num_rows=document.getElementById('myTable').getElementsByTagName('tr').length;
var num_cols=document.getElementById('myTable').rows[0].cells.length;
for(i=0;i<num_rows;i++){
for(j=0;j<num_cols;j++){
document.getElementById("myTable").rows[i].cells[j].style="background-color:#ebf6f5";
  let str1 = i
  let str2 = j
  let i_ids=str1.toString();
  let j_ids=str2.toString();
  let the_id = i_ids.concat(j_ids);
var rand = Math.floor(Math.random() * 5) + 1

if (rand==2&&i<9&&j<9){document.getElementById("myTable").rows[i].cells[j].innerHTML="<input type='button' id=id"+the_id+" onclick='the_butt(this.id)' oncontextmenu='prevent_menu();flag(this.id)' value='&#8196;&nbsp;&nbsp;'>";} else {
document.getElementById("myTable").rows[i].cells[j].innerHTML="<input type='button' id=id"+the_id+" onclick='the_butt(this.id)' oncontextmenu='prevent_menu();flag(this.id)' value='&nbsp;&nbsp;&nbsp;'>";}

if (i>9||j>8){(window.bad_ids).push("id"+the_id)}
}
}

}
function prevent_menu(){
document.addEventListener('contextmenu', event => event.preventDefault());
}

function the_butt(clicked_id){
var numb = clicked_id.match(/\d/g);
var numb = numb.join("");
if(clicked_id.length>4||numb.endsWith(9)){for(x=0;x<bad_ids.length;x++){document.getElementById(bad_ids[x]).style.borderStyle = "inset";document.getElementById(bad_ids[x]).style.backgroundColor="darkgrey";}} else {

if(document.getElementById(clicked_id).value===String.fromCharCode(0x2004,160,160)){
document.getElementById(clicked_id).value="💥";

}
if(document.getElementById(clicked_id).value===String.fromCharCode(160,160,160)){
var numb = clicked_id.match(/\d/g);
var numb = numb.join("");

if(numb=="00"){
var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num+11;
var test_trap3 = real_num+1;

var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap3_str).value=="🚩"||document.getElementById("id0"+test_trap3_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;}

else if(numb=="10"){
var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num-9;
var test_trap3 = real_num+1;
var test_trap4 = real_num-10;
var test_trap5 = real_num+11;

var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();
var test_trap5_str = test_trap5.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap2_str).value=="🚩"||document.getElementById("id0"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap4_str).value=="🚩"||document.getElementById("id0"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap5_str).value=="🚩"||document.getElementById("id"+test_trap5_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;}

else if(numb.startsWith(document.getElementById("myTable").rows.length-1)&&numb.endsWith("0")){
var real_num = parseInt(numb,10);

var test_trap2 = real_num-9;
var test_trap3 = real_num+1;
var test_trap4 = real_num-10;

var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();

var counter = 0;

if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}

document.getElementById(clicked_id).value=" "+counter;}

else if(numb.startsWith(document.getElementById("myTable").rows.length-1)&&(numb.endsWith(document.getElementById('myTable').rows[0].cells.length-1))){
var real_num = parseInt(numb,10);

var test_trap2 = real_num-11;
var test_trap3 = real_num-1;
var test_trap4 = real_num-10;

var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();

var counter = 0;

if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}

document.getElementById(clicked_id).value=" "+counter;}


else if((numb.startsWith("1")) && (numb.endsWith(document.getElementById('myTable').rows[0].cells.length-1))){
var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num+9;
var test_trap3 = real_num-1;
var test_trap4 = real_num-10;
var test_trap5 = real_num-11;
var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();
var test_trap5_str = test_trap5.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap4_str).value=="🚩"||document.getElementById("id0"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap5_str).value=="🚩"||document.getElementById("id0"+test_trap5_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;}

else if ((numb.startsWith("0")) && (numb.endsWith(document.getElementById('myTable').rows[0].cells.length-1))){
var real_num = parseInt(numb,10);
var test_trap4 = real_num-1;
var test_trap1 = real_num+10;
var test_trap7 = real_num+9;

var test_trap1_str = test_trap1.toString();
var test_trap7_str = test_trap7.toString();
var test_trap4_str = test_trap4.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap7_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap7_str).value=="🚩"||document.getElementById("id"+test_trap7_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap4_str).value=="🚩"||document.getElementById("id0"+test_trap4_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;
}

else if(document.getElementById(clicked_id).value===String.fromCharCode(160,160,160)&& (!numb.startsWith("0"))&&(!numb.startsWith("1"))&&(!numb.endsWith("0"))&&(!numb.endsWith((document.getElementById('myTable').rows[0].cells.length-1).toString()))&&(!numb.startsWith(document.getElementById("myTable").rows.length-1))){
var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num-10;
var test_trap3 = real_num+1;
var test_trap4 = real_num-1;
var test_trap5 = real_num-9;
var test_trap6 = real_num-11;
var test_trap7 = real_num+9;
var test_trap8 = real_num+11;
var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();
var test_trap5_str = test_trap5.toString();
var test_trap6_str = test_trap6.toString();
var test_trap7_str = test_trap7.toString();
var test_trap8_str = test_trap8.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap5_str).value=="🚩"||document.getElementById("id"+test_trap5_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap6_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap6_str).value=="🚩"||document.getElementById("id"+test_trap6_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap7_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap7_str).value=="🚩"||document.getElementById("id"+test_trap7_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap8_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap8_str).value=="🚩"||document.getElementById("id"+test_trap8_str).value=="💥"){counter++;}

document.getElementById(clicked_id).value=" "+counter;}

else if (document.getElementById(clicked_id).value===String.fromCharCode(160,160,160)){
if (numb.startsWith("0")){
var real_num = parseInt(numb,10);
var test_trap3 = real_num+1;
var test_trap4 = real_num-1;
var test_trap1 = real_num+10;
var test_trap7 = real_num+9;
var test_trap8 = real_num+11;
var test_trap1_str = test_trap1.toString();
var test_trap7_str = test_trap7.toString();
var test_trap8_str = test_trap8.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap7_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap7_str).value=="🚩"||document.getElementById("id"+test_trap7_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap8_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap8_str).value=="🚩"||document.getElementById("id"+test_trap8_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap3_str).value=="🚩"||document.getElementById("id0"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap4_str).value=="🚩"||document.getElementById("id0"+test_trap4_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;}

else if(numb.startsWith("1") && (!numb.endsWith("0"))){
var real_num = parseInt(numb,10);
var test_trap3 = real_num+1;
var test_trap5 = real_num-9;
var test_trap6 = real_num-11;
var test_trap4 = real_num-1;
var test_trap2 = real_num-10;
var test_trap1 = real_num+10;
var test_trap7 = real_num+9;
var test_trap8 = real_num+11;
var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap5_str = test_trap5.toString();
var test_trap6_str = test_trap6.toString();
var test_trap7_str = test_trap7.toString();
var test_trap8_str = test_trap8.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap7_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap7_str).value=="🚩"||document.getElementById("id"+test_trap7_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap8_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap8_str).value=="🚩"||document.getElementById("id"+test_trap8_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap5_str).value=="🚩"||document.getElementById("id0"+test_trap5_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap6_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap6_str).value=="🚩"||document.getElementById("id0"+test_trap6_str).value=="💥"){counter++;}
if(document.getElementById("id0"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id0"+test_trap2_str).value=="🚩"||document.getElementById("id0"+test_trap2_str).value=="💥"){counter++;}
document.getElementById(clicked_id).value=" "+counter;}

else if(numb.endsWith("0")){var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num-10;
var test_trap3 = real_num+1;
var test_trap5 = real_num-9;
var test_trap8 = real_num+11;
var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap5_str = test_trap5.toString();
var test_trap8_str = test_trap8.toString();

var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap5_str).value=="🚩"||document.getElementById("id"+test_trap5_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap8_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap8_str).value=="🚩"||document.getElementById("id"+test_trap8_str).value=="💥"){counter++;}

document.getElementById(clicked_id).value=" "+counter;}

else if (numb.endsWith((document.getElementById('myTable').rows[0].cells.length-1).toString())){
var real_num = parseInt(numb,10);
var test_trap1 = real_num+10;
var test_trap2 = real_num-10;

var test_trap4 = real_num-1;

var test_trap6 = real_num-11;
var test_trap7 = real_num+9;

var test_trap1_str = test_trap1.toString();
var test_trap2_str = test_trap2.toString();

var test_trap4_str = test_trap4.toString();

var test_trap6_str = test_trap6.toString();
var test_trap7_str = test_trap7.toString();


var counter = 0;

if(document.getElementById("id"+test_trap1_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap1_str).value=="🚩"||document.getElementById("id"+test_trap1_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap6_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap6_str).value=="🚩"||document.getElementById("id"+test_trap6_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap7_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap7_str).value=="🚩"||document.getElementById("id"+test_trap7_str).value=="💥"){counter++;}


document.getElementById(clicked_id).value=" "+counter;}
else if (numb.startsWith(document.getElementById("myTable").rows.length-1)){var real_num = parseInt(numb,10);

var test_trap2 = real_num-10;
var test_trap3 = real_num+1;
var test_trap4 = real_num-1;
var test_trap5 = real_num-9;
var test_trap6 = real_num-11;

var test_trap2_str = test_trap2.toString();
var test_trap3_str = test_trap3.toString();
var test_trap4_str = test_trap4.toString();
var test_trap5_str = test_trap5.toString();
var test_trap6_str = test_trap6.toString();


var counter = 0;


if(document.getElementById("id"+test_trap2_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap2_str).value=="🚩"||document.getElementById("id"+test_trap2_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap3_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap3_str).value=="🚩"||document.getElementById("id"+test_trap3_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap4_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap4_str).value=="🚩"||document.getElementById("id"+test_trap4_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap5_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap5_str).value=="🚩"||document.getElementById("id"+test_trap5_str).value=="💥"){counter++;}
if(document.getElementById("id"+test_trap6_str).value===String.fromCharCode(0x2004,160,160)||document.getElementById("id"+test_trap6_str).value=="🚩"||document.getElementById("id"+test_trap6_str).value=="💥"){counter++;}


document.getElementById(clicked_id).value=" "+counter;}
}}}}


  function flag(clicked_id){
if(document.getElementById(clicked_id).value===String.fromCharCode(160,160,160)){
document.getElementById(clicked_id).value="❌";
}
else if(document.getElementById(clicked_id).value===String.fromCharCode(0x2004,160,160)){
document.getElementById(clicked_id).value="🚩";

}}
//have to add &#x1F6A9; or \u1F6A9\u1F6A9
</script>

<hr style="height:1px; visibility:hidden;">
<hr style="height:1px; visibility:hidden;">
<hr style="height:1px; visibility:hidden;">

<style>
.footer {
   display:flex;
   left: 0;
   bottom: 0;
   position: fixed;
   padding: 0px;
   width: 100%;
   height: 25px;
   line-height: 0%;
   background-color: rgba(0,0,0,0.3);
   color: lightgrey;
  align-items:center;
  text-align:center;
  justify-content:center;
}
</style>

<div id="the_footer" class="footer">

<p>

  <button onclick="document.getElementById('the_footer').style.display='none'" id="hide_p"style="border-radius:20px;background-color:#6fad61">Accept</button>&nbsp;&nbsp;&nbsp;&nbsp;
This site uses cookies to run effectively.  See: <a href="privacy"style="color:lightgrey">Privacy and Cookie Policy</a>

</p>
</div>

</fieldset>

</body>
</html>
