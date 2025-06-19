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
            '¿Qué sistema de tallas mide la longitud del pie en milímetros?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: '<em>Mondopoint</em>.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Sistema métrico - <em>Mondopoint</em>.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Sistema inglés.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Sistema americano.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué parte de la horma se encuentra en la parte superior y sirve para fijarla en equipos?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Puntera.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Tubo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Mesa.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Enfranque.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto: '¿Cuál es el propósito del enmascarado en el patronaje?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Crear el diseño de suela.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Transferir el diseño tridimensional a un plano bidimensional.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Medir la altura del tacón.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Cortar la palmilla.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué tipo de pie presenta una curvatura muy pronunciada en el arco plantar?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pie plano.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Pie cavo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Pie neutro.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Pie pronador.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto:
            '¿Qué instrumento se utiliza para marcar líneas con alta precisión sobre la horma?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Compás de puntas secas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Borrador.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Cinta métrica.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Cuchilla.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            '¿Cómo se llama la parte más ancha de la parte posterior de la horma?',
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
              texto: 'Cuboide.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Tacón.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Enfranque.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Cuál es la unidad de medida usada en la fórmula “Ancho base metatarsiano = 5/6 del largo del pie”?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Milímetros.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Centímetros.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Proporción.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Grados.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto:
            '¿Qué tipo de horma se recomienda para pies con necesidades especiales y soporte específico?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Horma ortopédica.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Horma deportiva.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Horma de moda.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Horma plana.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto: '¿Qué parte de la horma representa el punto de quiebre?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Zona de división entre delantera y enfranque.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Línea del tacón.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Canto.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Tubo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es la herramienta esencial para cortar el enmascarado final?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Regla.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Tijeras.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Compás.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Metro de calzado.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'El sistema europeo de tallas también es conocido como Paris <em>Point</em>.',
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
            'La horma de tacón alto tiene el mismo ángulo en el asiento del talón sin importar su altura.',
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
          texto: 'El perímetro del pie se mide sobre el dorso del empeine.',
          imagen: require('@/assets/actividad/imagen1.png'),
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
          id: 14,
          texto:
            'Las hormas para pie delgado evitan el deslizamiento dentro del calzado.',
          imagen: require('@/assets/actividad/imagen2.png'),
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
          id: 15,
          texto:
            'El proceso de enmascarado comienza colocando una cinta de refuerzo sobre el talón.',
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
