# FLox

[Descargar Flox](https://raw.githubusercontent.com/ssaurexd/flox/master/flox.css)
[Descargar Flox Minificado](https://raw.githubusercontent.com/ssaurexd/flox/master/flox.min.css)


_____________________________________

## Grid

![Ejemplo de Grid](./images/ejemplo_grid.png)

```
<main class="container" >
	<div class="row ">
		<div class="col-1">Grid 1 </div>
		<div class="col-1">Grid 2 </div>
		<div class="col-1">Grid 3 </div>
		<div class="col-1">Grid 4 </div>
		<div class="col-1">Grid 5 </div>
		<div class="col-1">Grid 6 </div>
		<div class="col-1">Grid 7 </div>
		<div class="col-1">Grid 8 </div>
		<div class="col-1">Grid 9 </div>
		<div class="col-1">Grid 10 </div>
		<div class="col-1">Grid 11 </div>
		<div class="col-1">Grid 12 </div>
		<div class="col-1">Grid 13 </div>
		<div class="col-1">Grid 14 </div>
		<div class="col-1">Grid 15 </div>
		<div class="col-1">Grid 16 </div>
		<div class="col-1">Grid 17 </div>
		<div class="col-1">Grid 18 </div>
		<div class="col-1">Grid 19 </div>
		<div class="col-1">Grid 20 </div>
		<div class="col-1">Grid 21 </div>
		<div class="col-1">Grid 22 </div>
		<div class="col-1">Grid 23 </div>
		<div class="col-1">Grid 24 </div>
	</div>
</main>
```

### Responsive

De manera responsive se hay 5 tamaños 
	`xs < 576px` 
	`sm > 576px < 768px`
	`md > 768px < 992px`
	`lg > 992px < 1200px`
	`xl >1200px`

[Ejemplo resposive](./images/xl.png)
[Ejemplo resposive](./images/lg.png)
[Ejemplo resposive](./images/md.png)
[Ejemplo resposive](./images/sm.png)
[Ejemplo resposive](./images/xs.png)

	```
	<main class="container">
		<div class="row">
			<div class="xs-24 sm-6 md-12 lg-20 xl-2"> 1 </div>
			<div class="xs-24 sm-18 md-12 lg-4 xl-22"> 2 </div>
		</div>
	</main>
	```

### Ocultar un elemento
	
Para ocultar un elemento en cada tamaño hay `tamaño-none`
Ejemplo `md-none` 

[Ejemplo ocultar 1](./images/hide-lg.png)
[Ejemplo ocultar 2](./images/hide-md.png)

	```
	<main class="container" >
		<div class="row">
			<div class="md-12 lg-20"> 1 </div>
			<div class="md-12 lg-4"> 2 </div>
		</div>
	</main>
	
	<main class="container" >
		<div class="row">
			<div class="md-none lg-20"> 1 </div>
			<div class="md-12 lg-4"> 2 </div>
		</div>
	</main>
	```