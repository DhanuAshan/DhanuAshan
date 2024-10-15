this is the css file of flex box that is to create a various dimensions with 9 portions and 1 grid is 2 grids width and the 2 is 2 grids widht and 2 rows in height, and the 3 grid is 2 grids width adn2grids height,and grid
4 and 5 is under the 2grid, and al the 6,7,8,9 are at the last row...... 
1122
3322
3345
6789



the html code wiht css code as follows...
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>grid layout</title>
<style>
	.grid-container{
		display:grid;
		grid-template-columns:auto auto auto auto;
		background-color:red;
		padding:10px;
		column-gap:10px;
		row-gap:10px;

	}
	.grid-item{
		background-color:blue;
		padding:15px;
		font-size:50px;
		border:1px solid black;
	}

.grid-item-1{
	grid-column-start:1;
	grid-column-end:3;
	padding:30px;
}

.grid-item-2{
	grid-column-start:3;
	grid-column-end:5;
	grid-row-start:1;
	grid-row-end:4;
	height:200px;

}
.grid-item-3{
	grid-column-start:1;
	grid-column-end:3;
	grid-row-start:2;
	grid-row-end:5;
	padding:5px;
}

.grid-item-4{
		grid-column-start:3;
	grid-column-end:4;
	grid-row-start:4;
	grid-row-end:5;
	padding:5px;
	
}

	
.grid-item-5{
	grid-column-start:4;
	grid-column-end:4;
	grid-row-start:4;
	grid-row-end:5;
	padding:5px;


	

	}

.grid-item-6{
	grid-column-start:1;
	grid-column-end:2;
	grid-row-start:5;
	grid-row-end:5;
	padding:100px;


	

	}

.grid-item-7{
	grid-column-start:2;
	grid-column-end:3;
	grid-row-start:5;
	grid-row-end:5;
	padding:100px;


	

	}
.grid-item-8{
	grid-column-start:3;
	grid-column-end:4;
	grid-row-start:5;
	grid-row-end:5;
	padding:100px;


	

	}

.grid-item-9{
	grid-column-start:4;
	grid-column-end:5;
	grid-row-start:5;
	grid-row-end:5;
	padding:100px;


	

	}







</style></head>
<body>
<div class="grid-container">
	<div class="grid-item grid-item-1">1</div>

	<div class="grid-item grid-item-2">2</div>

	<div class="grid-item grid-item-3">3</div>
	<div class="grid-item grid-item-4">4</div>

	<div class="grid-item grid-item-5">5</div>

	<div class="grid-item grid-item-6">6</div>
	<div class="grid-item grid-item-7">7</div>

	<div class="grid-item grid-item-8">8</div>

	<div class="grid-item grid-item-9">9</div>

</body>
</html>
<!---
DhanuAshan/DhanuAshan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
