/*
  If you get stuck, feel free to watch the follow-up videos where I'll show you one solution
*/

/* ================================= 
  Base Element Styles
==================================== */

* {
	box-sizing: border-box;
}

body {
	font-family: 'Varela Round', sans-serif;
	line-height: 1.6;
	color: #3a3a3a;
}

p {
	font-size: .95em;
	margin-bottom: 1.8em; 
}

h2,
h3,
a {
	color: #093a58;
}

h2,
h3 {
	margin-top: 0;
}

a {
	text-decoration: none;
}

img {
	max-width: 100%;
}

/* ================================= 
  Base Layout Styles
==================================== */

/* ---- Navigation ---- */

.name {
	font-size: 1.25em;
  margin: 0;
}

.main-nav {
  margin-top: 5px;
}
.name a,
.main-nav a {
	text-align: center;
  display: block;
  padding; 10px 15px;
}

.main-nav a {
	font-size: .95em;
	color: #3acec2;
	text-transform: uppercase;
}

.main-nav a:hover {
	color: #093a58;
}

/* ---- Layout Containers ---- */

.main-header{
  padding-top: 5em;
  padding-bottom: 5em;
}
.banner,
.main-footer {
  text-align: center;  
}

.banner {
	color: #fff;
	background: #3acec2;
  padding: 3em 0;
  margin-bottom: 60px;
}

.col {
  padding-right: 1em;
  padding-left: 1em;
    
}
.main-footer {
	background: #d9e4ea;
	padding: 2em 0;
	margin-top: 30px;
}

/* ---- Page Elements ---- */

.logo {
	width: 190px;
}
.headline {
  margin-bottom: 0;
}
/* ================================= 
  Media Queries
==================================== */

@media (min-width: 1025px) {
  
  .main-header {
  color: red;
}
  .container {
  width: 80%;
  max-width: 1125px;
}
  .primary {
  width: 40%;
}
  .secondary,
  .tertiary  {
   width: 30%;
 }
}

	/* ---- Float clearfix ---- */

	.clearfix::after {
		content: " ";
		display: table;
		clear: both;
  	}
}
