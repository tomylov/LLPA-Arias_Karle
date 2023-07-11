# LPPA-Arias_Karle

change readme
sintaxis: reglas de escritura
semantica: lo que escribo

1. styles
2. inline style: es tirar estilos dentro de la linea (h1 style=";") no utilizar ya que son los mas pesados
3. stylesheet: archivo css. hoja de estilos en cascada
selectores:
- elementos
- etiqueta (h1,h2,etc.)
- class (.clase)
- id (#id)
- atributo
- pseudoclases
- operadores ej: p>li esta mal ya que no hereda un li de p

nodo elemento <> nodo texto
div: elemento de bloque que no tiene conocimiento semantico
span: elemento de linea que no tiene conocimiento semantico

ul li a{} //todos los a que sean hijos de un li
elemento hermano: que esta dentro de la misma linea de codigo ej: un p y span adentro de un div

p.negrita todos los p con la clase negrita
p .negrita la clase negrita que sea hijo de un elemento p

todos los navegadores tienen estilos precargados por ende se utiliza un reset

CSS specificity: mientras mas pesado mas prioridad tiene para ser leido

tipos de dispositivos:
xs- celular
small- table
m- notebook
l- teles

layout <> responsive

viewport: parte visible del documento

responsive:
- flexible: se hace con float o tablas o flexbox o grid
- breackpoint: mediaquery (mide ancho y alto de vw)

DOM
document object model.
Manipular el html desde js a traves de eventos.
insertAdjacentElement: insertar html.
innerHTML: tomar un html.

1) Lograr que la secuencia recuerde los valores que elige(array secuencia).
2) La secuencia repite estados e incrementa en un nuevo estado aleatorio. setintervar()
3) La secuencia es incremental y se incrementa con el click(idea anterior pero se dispara con un click)
4) boton play y reset
5) Imprimir los numeros del 1 al 10 cada 1 segundo.
