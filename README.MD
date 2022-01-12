# Cabeceras:
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6
---

# UNDERLINES 
Underline 1
-----------
Underline 2
===========

# Formatos de enfasis
- formato italica de la *primera* forma
- formato italica de la _segunda_ forma
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~

# Listas 
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Esto es un Link</a>
- [Esto es un link en Markdown](http://www.google.es)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Emblem.png)

# Code Snippets
Codigo en HTML 
```HTML
<form action="#" method="get">
        <input type="button" value="Enviar">
        <input type="number" name="firstname" id="name">
        <input type="text" name="lastname" id="lastname">
        <input type="text" name="age" id="age">
        <input type="date" name="birthday" id="birth">
        <img src="#" alt="Test Img">
        <video src="video/cat.mp4"></video>
```

Codigo en JS 
```JavaScript
$(function(){
    $(document).on('click', '#gettotalarticles', function(e){
        e.preventDefault();

        $.ajax({
            type: 'POST',
            headers: {"cache-control" : "no-cache"},
            url: baseAdminDir + 'index.php?' + new Date().getTime(),
            async: true,
            dataType: 'json',
            data:  {
                controller: 'AdminIntegratorConfiguration',
                action: 'getTotalArticles'
            },
            success: function(json){
                console.log(jsnon.total_articles)
                alert(json.total_articles)
            }
        });
    });
});
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| MAXI   | Jimenez  | DASDA     |
| MAXI   | Perez    | ADSAS     |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Es otro texto que no se relaciona con la cita anterior.
>Otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de Línea

Esto es nuestro primer parrafo. 
Esto es nuestro segundo parrafo. 
Esto es nuestro tercer parrafo. 
