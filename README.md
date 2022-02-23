# Go_Design97
/*
 * Globals
 */

/* Links */
a,
a:focus,
a:hover {
  color: #fff;
}

/* Custom default button */
.btn-secondary,
.btn-secondary:hover,
.btn-secondary:focus {
  color: #333;
  text-shadow: none; /* Prevent inheritance from `body` */
  background-color: #fff;
  border: .05rem solid #fff;
}


/*
 * Base structure
 */
.emoge h1 p {
  display: inline-block;
  text-align: center;
}

}
html,
body {
  height: 100%;
  background-color: #333;
}

body {
  display: -ms-flexbox;
  display: flex;
  color: #fff;
  text-shadow: 0 .05rem .1rem rgba(0, 0, 0, .5);
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
}
.balloons {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
} 

.balloon_01  {
 float: left;
 position:relative;
 margin: 50px;
 width:100px;
 vertical-align: middle;
 color: black;
 line-height:50px;
 height:50px;
  background: white;
  border-radius: 10px;
}
.balloon_01 : after {
 border-top:0px solid transparent; 
 border-left: 10px solid transparent; 
 border-right: 10px solid transparent; 
 border-bottom: 10px solid pink; 
 content:""; 
 position:absolute;
 top:-10px;
 left:200px;  
}
.balloon {  
 position:relative; 
 margin: 50px;
 width:400px; 
 height:50px;
  background:pink; 
  border-radius: 10px;
}
.balloon:after { 
 border-top:0px solid transparent; 
 border-left: 10px solid transparent; 
 border-right: 10px solid transparent; 
 border-bottom: 10px solid pink; 
 content:""; 
 position:absolute;
 top:-10px;
 left:200px;  
}
 

.balloon_02  {
  float: left;
  background: white;
  color: black;
   vertical-align: middle;
 line-height:50px;
 height:50px;
 position:relative;
 margin: 50px;
 width:100px;
 height:50px;
  
  border-radius: 10px;
}
.balloon_02 :after {
 border-top:0px solid transparent;
 border-left: 10px solid transparent;
 border-right: 10px solid transparent;
 border-bottom: 10px solid blue;
 content:"";
 position:absolute;
 top:-10px;
 left:200px;
}


.balloon_03 {
 float: left;
 color: black;
 background: white;
 float: left;
 vertical-align: middle;
 line-height:50px;
 height:50px;
 position:relative;
 margin: 50px;
 width:100px;
 height:50px;
 border-radius: 10px;
}

.balloon_03 :after {
  color: black;
 background: white;
 border-top:15px solid #333333;
 border-left: 15px solid transparent;
 border-right: 0px solid transparent;
 border-bottom: 0px solid transparent;
 content:"";
 position:absolute;
 top:10px;
 left:-15px;
}
 
 


.cover-container {
  max-width: 42em;
}


/*
 * Header
 */
.masthead {
  margin-bottom: 2rem;
}

.masthead-brand {
  margin-bottom: 0;
}

.nav-masthead .nav-link {
  padding: .25rem 0;
  font-weight: 700;
  color: rgba(255, 255, 255, .5);
  background-color: transparent;
  border-bottom: .25rem solid transparent;
}

.nav-masthead .nav-link:hover,
.nav-masthead .nav-link:focus {
  border-bottom-color: rgba(255, 255, 255, .25);
}

.nav-masthead .nav-link + .nav-link {
  margin-left: 1rem;
}

.nav-masthead .active {
  color: #fff;
  border-bottom-color: #fff;
}

@media (min-width: 48em) {
  .masthead-brand {
    float: left;
  }
  .nav-masthead {
    float: right;
  }
}


/*
 * Cover
 */
.cover {
  padding: 0 1.5rem;
}
.cover .btn-lg {
  padding: .75rem 1.25rem;
  font-weight: 700;
}


/*
 * Footer
 */
.mastfoot {
  color: rgba(255, 255, 255, .5);
}
