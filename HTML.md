<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <title>Ryan Clark's Portfolio</title>
        <link rel="stylesheet" href="bootstrap.css" type="text/css"/>
        <link rel="stylesheet" href="style.css" type="text/css"/>
        <link rel="stylesheet" href="bootstrap.min.css">
        <link rel="stylesheet" href="bootstrap_theme.min.css">
        <script type="text/javascript" src="jquery-1.11.3.min.js"></script>
    </head>
    <body>
        <div class="container">
            <div class="row">
                <div class="col-md-6"><img class="img-responsive2" src="Images/Rebel.png"></div>
                <div class="col-md-6 text-right text-uppercase">
                    <h1 class="name-font">Ryan Clark</h1>
                    <h3>Front-end Jedi</h3>
                </div>
            </div>
            <div class="row background">
                <div class="col-md-12">
                    <img class="img-responsive" src="Images/Fam.jpg" alt="Family">
                </div>
            </div>
            <div class="row background feature">
                <div class="col-md-12">
                    <h2>Featured Work</h2>
                </div>
            </div>
            <div class="row background">
                <div class="col-md-4 modal-fade">
                    <img class="img-responsive3" src="Images/07.jpg" data-toggle="modal" data-target="#Project1">
                    <h3 class="feature text-center">Project 1</h3>
                    <p class="text-center">
                        <a href="http://github.com">Appify</a></p>
               
            </div>
                <div class="col-md-4">
                    <img class="img-responsive3" src="Images/06.jpg">
                    <h3 class="feature text-center">Project 2</h3>
                    <p class="text-center"><a href="http://github.com">Sunflower</a></p>
                </div>
                <div class="col-md-4">
                    <img class="img-responsive3" src="Images/05.jpg">
                    <h3 class="feature text-center">Project 3</h3>
                    <p class="text-center"><a href="http://github.com">Bokeh</a></p>       
                </div>
            </div>
        </div>
 <!-- Modal -->
<div class="modal-fade" id="Project1" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
        <h4 class="modal-title" id="myModalLabel">Favorite App Page</h4>
      </div>
      <div class="modal-body">
        <img class="img-responsive3" src="images/07.jpg">
        This was my first project in Web Development. 
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
    </body>
</html>
