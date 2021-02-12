# Cabeceras:
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

# Underlines:
Underline 1
-----------
Underline 2
===========

# Formatos de emphasis
- letra *italica* de la primera forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~.
- aquí podemos usar formato *itálico*, pero también **bold** y ~~tachado~~

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item.
3. Esto es un item.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML </a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo GitHub](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código en JavaScript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   |  Burgos  |  2343433  |
| Tomas  |  Tompson |  29989737 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Líneas divisoras
Esto es un texto que será dividido por guiones:

---
Esto es otro texto dividido por asteriscos:

***
Esto es otro texto dividido por subguiones:
___

# Saltos de lineas
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista