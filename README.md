# Practica Git

## Practica Markdown
Los ficheros readme se utilizan para documentar los proyectos o repositorios en GitHub. 

### Utilidades readme
Desde el readme puedes **usar negrita**  _cursiva_ ~~o palabras tachadas~~

### Uso de tablas
Dentro de los readme tambien se puede añadir tablas 
| Primer encabezado | Segundo encabezado |
| ------------- | ------------- |
| Contenido de la celda  | Contenido de la celda  |
| Contenido de la celda  | Contenido de la celda  |

### Imagenes
Dentro del readme tambien se pueden usar imagenes.
![Image text](https://github.com/A21Manuel/PracticaGit/blob/main/github.jpeg)
Tambien se puede añadir un GIF
![Image text](https://github.com/A21Manuel/PracticaGit/blob/main/nyan-cat.gif)

### Listas
Este es un ejemplo de texto que da entrada a una lista genérica de elementos:
- Elemento 1
  - Elemento anidado
- Elemento 2
  1. Tambien se puede anidar con listas numeradas
  2. Prueba de anidacion de lista numerada
- Elemento 3

- Este es un ejemplo de texto que da entrada a una lista numerada:
1. Elemento 1
2. Elemento 2
3. Elemento 3

### Enlaces
Ejemplo de enlace a otra página [GitHub Page](https://manuelvazquezcasti.github.io/Portfolio/).

### Código 
Ejemplo de código dentro de readme

Ejemplo código html
```
<ul class="Navigation">
  <li><a href="index.html">Home</a></li>
  <li><a href="#AboutMe">About me</a></li>
  <li><a href="#projects">Projects</a></li>
  <li><a href="#Skills">Skills</a></li>
  <li><a href="contact.html">Contact</a></li>
  <li><button onclick="myFunction()" class="btn"><img src="img/darkmode.png" width="40" height="40"/></button></li>
</ul>
```

Ejemplo código JAVA
```
public static boolean esPrimo(int número) {
		boolean esPrimo=false;
		for(int i=1;i<=número;i++)
			if (número%i == 0) {
				esPrimo = false;
			}
			else esPrimo = true;
		return esPrimo;
	}
```

### Mencionar
Para mencionar a una persona o equipo se utiliza @ 
@ManuelVazquezCasti
>Tambien se pueden añadir citas 
