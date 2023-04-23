<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 Programación en Unity3D
    
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-right")
        p.mb-0 El programa Unity es un motor de tipo gráfico; esto quiere decir que contiene muchas funcionalidades que resuelven aspectos en la creación de un videojuego sin que se necesite programar; por ejemplo poner color a un objeto seleccionado, iluminar un plano o cambiar el nivel de una imagen entre otros.
          br
          br
          |Para adicionar algún tipo de comportamiento, componente o atributo que no se pueda hacer desde el menú del programa, lo que se debe hacer es escribir líneas de código o scripts para que le proporcionen estas características. Esto es lo que se llama programación orientada a objetos.

    p.mb-5 <b>La Programación Orientada a Objetos -POO-</b> posee las siguientes características:

    TabsA.color-acento-contenido.mb-5
      .tarjeta.p-4(titulo="Abstracción" style="background-color: #DFF5FA")
        h4 Abstracción
        p Consiste en abstraer o aislar las características o atributos esenciales que definen un objeto y que lo distinguen de los demás con el propósito de que las pueda usar otro objeto. Por ejemplo si el objeto es una puerta las características esenciales es que tenga un marco, bisagras y cerradura sin importar el tamaño, el color y el tipo de material entre otras.
      .tarjeta.p-4(titulo="Herencia" style="background-color: #DFF5FA")
        h4 Herencia
        p Al encapsulamiento de las características de un objeto se le llama clase; que esta conformada por un patrón de atributos que la hacen de orden superior o superclase porque tiene características generales, pero pueden surgir clases hijas o subclases que hereden estas características y se encuentren en orden inferior dentro de la jerarquía. 
          br
          br
          |En el ejemplo de la puerta, las clases hijas que heredan las características son los tipos de puertas que pueden elaborarse como las correderas, plegables, pivotantes, de seguridad, entre otras.
      .tarjeta.p-4(titulo="Polimorfismo" style="background-color: #DFF5FA")
        h4 Polimorfismo
        p Consiste en definir un método con un conjunto de parámetros el cual puede ser aplicado en varios tipos de objetos. El método puede aumentar o disminuir los parámetros dependiendo del objeto al que se aplique. Por ejemplo el método se llama Open y es utilizado para abrir diferentes objetos como: puerta, cuenta bancaria, evento, historia clínica, entre otros. Dependiendo de lo que se abra, el proceso como tal, tiene mas o menos actividades por realizar.
      .tarjeta.p-4(titulo="Pila de producto" style="background-color: #DFF5FA")
        h4 Pila de producto
        p Es el conjunto de características esenciales que han sido separadas de las no esenciales. En el ejemplo de la puerta en el encapsulamiento se encuentra el marco, las bisagras y la cerradura ya que son los atributos principales o generales que hacen que el objeto sea definido como puerta, los demás atributos como el color, el material y el tamaño, hacen parte lo que se consideran características, pues estos son atributos que pueden poseer innumerables tipos de objetos.

    p.mb-5 El lenguaje de programación que se utiliza en Unity para generar las líneas de código o Scripts es C#; el cual se compone de variables, funciones y clases que se explicarán más adelante. Para escribir el código, Unity tiene un editor de texto asociado llamado Visual Studio, aunque el programador puede utilizar simplemente el bloc de notas. El editor (Visual Studio) le ayuda a determinar los errores de sintaxis que se puedan cometer en el desarrollo, por esa razón es recomendable hacer uso de este.   
      br
      br
      |Antes de comenzar a estructurar un programa en Unity, ver la explicación de algunos conceptos básicos en el siguiente enlace:
    
    

    Separador
    .titulo-segundo.color-acento-contenido
      h2#t_2_1 2.1 Conceptos básicos de algoritmo y programa
    
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass">
.tabs-a
  .tabs-a__tab
    background-color: #E8E8E8
    &.tabs-a__tab__selected
      color: white !important
    &:hover
      color: white !important
</style>
