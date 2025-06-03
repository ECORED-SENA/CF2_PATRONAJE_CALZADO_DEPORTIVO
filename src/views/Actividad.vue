<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Fundamentos del Patronaje de Calzado Deportivo',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> Evaluar la comprensión de los conceptos clave relacionados con las medidas del pie, las hormas y el proceso de enmascarado en el patronaje de calzado deportivo.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!..',
      titulo_reprobado: 'VUELVA A INTENTARLO..',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es la principal función de la horma en la fabricación del calzado?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Diseñar el estilo visual del zapato.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Servir como molde tridimensional para su construcción.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Controlar la temperatura durante el proceso de producción.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reducir el peso del calzado terminado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto: 'El sistema Mondopoint mide:',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La anchura del pie en pulgadas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La altura del tacón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'La longitud del pie en milímetros.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'La circunferencia del empeine.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Qué herramienta se utiliza para trazar ejes sobre la cinta en el enmascarado?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Tijeras.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cuchilla de corte.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Esfero.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Compás de precisión.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Cuál es la fórmula más común para calcular el ancho base metatarsiano?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Largo del pie x 2.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Largo del pie ÷ 6.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Largo del pie x 3/4.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Largo del pie x 5/6.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Cuál de las siguientes es una clasificación de hormas según el tipo de pie?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Horma ortopédica.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Horma tubular.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Horma con cuña.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Horma media.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Qué componente de la horma permite abrirla durante el proceso?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Mesa.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Bisagra.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Tubo.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Canto.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto: '¿Cuál es la secuencia correcta para iniciar el enmascarado?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Colocar cinta lateral, marcar bordes, cortar eje.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto:
                'Colocar cinta en el empeine y talón, luego reforzar con cinta en línea de profundidad.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Cubrir con papel, trazar eje, colocar cinta final.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Trazar patrón, cubrir con cinta, recortar bordes.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            'El tipo de pisada en el que el pie se inclina hacia adentro es:',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pisada supinadora.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Pisada neutra.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Pisada pronadora.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Pisada elevada.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué zona de la horma se encuentra entre el talón y la parte delantera?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Mesa.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Enfranque.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Taco.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Puntera.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es el perímetro que se mide desde el talón pasando por el cuboide hasta el eje principal?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Perímetro talonera-empeine.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Perímetro de retención.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Perímetro de la bola.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Perímetro de empeine.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'La horma con cuña permite una extracción más fácil del calzado terminado.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'El enmascarado solo se realiza en la cara interna de la horma para mayor precisión.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto: 'El pie cavo tiene un arco plantar muy pronunciado.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: 'El sistema europeo de tallas es el mismo que el inglés.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto: 'El ancho de mesa se mide en la base trasera de la horma.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
