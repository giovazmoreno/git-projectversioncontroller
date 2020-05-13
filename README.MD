### Version del curso= v1.2.2

# 1.- Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# 2.- Underlines
Underline 1 -
-
Underline 2 =
=

# 3.- Formatos de enfasis
- formato *italica* de la primera forma *
- formato _italica_ de la segunda forma _
- formato **bold o strong** *
- formato __bold o strong__ __
- formato ~~tachado~~ ~~

- aqui podemos usar ~~***multiples***~~  formatos

# 4.- Listas
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada
1. Esto es un item de lista ordenada

- Esto es un iten de lista desordenada
- Esto es un iten de lista desordenada
- Esto es un iten de lista desordenada





# 5.- Links
- <a href="http://www.google.com">Esto es un link en HTML</a>
- [Esto es un link en markdown](http://www.google.com)

# 6.- Imagenes
![Logo GITHub](https://github.githubassets.com/images/modules/open_graph/github-mark.png)

# 7.- Code snippets

Codigo en JSON
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

 Codigo en javascript
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

# 8.- Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Giovanna | Vazquez | 12345 |
| Eloisa | Moreno | 56789 |
| Allison | Rubi | 34567 |
| Zoe | Cabrera | 78901 |

# 9.- Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.
Esto aun esta en la cita

Esto ya no esta dentro de la cita porque hay un Enter despues de la cita para finalizarla.

# 10.- Lineas horizontales
Esto es un texto dividido

---
Es importante que exista un enter entre texto y los 3 - (guiones medios) 

***
Divisor con tres asteriscos

___
Divisor con 3 _


# 11.- Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.

Es necesario darle  el salto de linea con un enter.
