<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Hormas
    
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img.ajuste___img_component(
        :style="{'background-image': `url(${require('@/assets/curso/temas/img15.svg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Cuando hablamos de “horma”, nos referimos a un molde con la forma estilizada del pie humano cuya función principal es servir de referencia y soporte durante la construcción del calzado. Las hormas definen la forma, volumen, curva y silueta del zapato, convirtiéndose en una herramienta fundamental en todo proceso de fabricación.

    <!-- BLOQUE 1 -->
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Partes de la horma
    
    .row.mb-5.align-items-center.m-0(data-aos="fade-right")
      .col-xl.estilo___caja_12
        p Aunque pueda parecer una estructura simple, la horma está compuesta por múltiples partes, cada una con una función técnica específica. A continuación, se describen las partes principales que pueden variar según el tipo de horma:
        <ul class="fa-ul estilo___ul">
          <li class="mb-4"><span class="fa-li"><i class="fas fa-cut color___fa-cut"></i></span><strong>Lado medial</strong>: corresponde a la parte interior del pie. Es donde se ubican el dedo gordo y el arco plantar.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___fa-cut"></i></span><strong>Lado lateral</strong>: se refiere al lado externo del pie, donde se encuentra el dedo meñique.</li>
        </ul>
      .col-xl-auto(data-aos="fade-left").espacio___movil_4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2. 
          span Vista inferior de la horma con línea de referencia del punto de quiebre
        figure(data-aos="fade-left")
          img.mb-2(src="@/assets/curso/temas/img16.png", alt="Vista lateral superior de una horma de calzado de madera con una línea roja horizontal que atraviesa el centro, marcando la alineación longitudinal de la horma.").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Zonas estructurales de la horma
    
    .row.mb-5.align-items-center.m-0
      .col-xl-auto(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 3. 
          span Vista lateral de la horma con línea del frente del tacón
        figure
          img.mb-2(src="@/assets/curso/temas/img17.png", alt="Vista lateral de una horma de calzado de madera con una línea vertical roja que indica la ubicación del punto de apoyo más alto del empeine.").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
      .col-xl.estilo___caja_13.m-0(data-aos="fade-left")
        p Estas secciones definen el diseño anatómico básico de la horma:
        <ul class="fa-ul">
          <li class="mb-4"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Parte delantera</strong>: inicia a partir de la línea de perímetro de la bola del pie o zona de articulación (metatarsos).</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Parte trasera</strong>: comprende desde la línea de articulación hasta el extremo del talón.</li>
        </ul>
      
    p.mb-4 A continuación se presentan los elementos más representativos de una horma, los cuales cumplen funciones específicas en el proceso de fabricación del calzado:

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 4. 
            span Vista superior de la horma con partes funcionales señaladas
          figure
            img.ajuste__espacio_1(src="@/assets/curso/temas/img18.png", alt="Vista superior de una horma de calzado de madera con etiquetas que señalan partes clave: cono (zona delantera), bisagra (unión móvil), apertura (ranura central), talla (marca de medida), tubo (perforación central) y mesa (base trasera)." ).m-auto
          figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
        .col-xl.espacio___movil_3
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Cono").ajuste-cajaAcordion
              p.mb-0 Comienza en la parte más alta y se extiende hasta el empeine, coincidiendo con el punto más prominente del pie.
            .row(titulo="Bisagra").ajuste-cajaAcordion
              p.mb-0 Pieza funcional que permite abrir o articular la horma. 
            .row(titulo="Apertura").ajuste-cajaAcordion
              p.mb-0 Sección recortada de la horma que incorpora la bisagra. Tiene cara delantera y trasera. No todas las hormas incluyen este mecanismo.
            .row(titulo="Talla").ajuste-cajaAcordion
              p.mb-0 Número o referencia grabada en la horma. Debe ser legible incluso con el corte montado.
            .row(titulo="Tubo").ajuste-cajaAcordion
              p.mb-0 Orificio ubicado en la parte superior de la horma, con medidas estándar de 10,5 mm de diámetro y 38 mm de profundidad. Sirve para fijar la horma en equipos o estanterías.
            .row(titulo="Mesa").ajuste-cajaAcordion
              p.mb-0 Superficie plana donde se localizan tanto el tubo como la talla.

    .row.align-items-center.mb-5.m-0.espacio___movil_2
      .col-lg.estilo___caja_14(data-aos="fade-right")
        p.mb-4.ajustes___movil-1 Además de las partes principales, existen componentes que cumplen funciones específicas en el diseño y la funcionalidad de la horma:
        <ul class="fa-ul">
          <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___fa-cut"></i></span><strong>Perfil de la puntera</strong>: superficie curva que va desde el empeine hasta el canto a la altura del dedo gordo.</li>
          <li class="mb-3"><span class="fa-li"><i class="fas fa-cut color___fa-cut"></i></span><strong>Talón (cuboide)</strong>: zona más ancha de la parte posterior de la horma, ubicada por encima del canto.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___fa-cut"></i></span><strong>Orificios</strong>: ubicados en los laterales, permiten fijar piezas metálicas que sujetan la bisagra.</li>
        </ul>
      .col-xl-auto(data-aos="fade-left").espacio___movil_4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 5. 
          span Perfil lateral de la horma con elementos constructivos
        figure
          img.mb-2(src="@/assets/curso/temas/img19.png", alt="Vista lateral de una horma de madera que destaca elementos estructurales clave: perfil de la puntera, cono, orificios, apertura y talón. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
    
    p.mb-4 Estos elementos aportan soporte, protección y facilitan el proceso de fabricación del calzado:

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 6. 
            span Vista inferior de horma con componentes de montaje
          figure
            img.mb-2(src="@/assets/curso/temas/img20.png", alt="Vista inferior de una horma antigua de madera donde se identifican elementos funcionales del montaje: placa para montar, canto, enfranque, agujero para tachuelas o clavos y taco.").m-auto
          figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
        .col-xl.espacio___movil_4
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Placa para montar").ajuste-cajaAcordion
              p.mb-0 Lámina metálica ubicada en la parte inferior para proteger la horma. Puede cubrir puntera, talón o toda la base. Se encuentra en hormas de madera y plástico.
            .row(titulo="Canto (o dima)").ajuste-cajaAcordion
              p.mb-0 Es la esquina donde se unen la pared y la planta de la horma. Puede ser redondeado o tener un ángulo de 90°.
            .row(titulo="Enfranque").ajuste-cajaAcordion
              p.mb-0 Parte inferior media de la horma, entre el talón y la parte delantera.
            .row(titulo="Agujero para tachuelas o clavos").ajuste-cajaAcordion
              p.mb-0 Orificio en la placa que permite fijar temporalmente piezas como la palmilla.
            .row(titulo="Taco").ajuste-cajaAcordion
              p.mb-0 Inserto de caucho o plástico flexible ubicado en el agujero de tachuela, que reemplaza material más duro para permitir clavado o grapas.
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Horma de tacón alto

    p.mb-5.espacio___movil_1 Aunque las hormas para calzado de mujer comparten los mismos componentes básicos, sus proporciones y diseño varían significativamente en comparación con las hormas masculinas. Algunas partes específicas de este tipo de hormas son:

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl.espacio___movil_1
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-right")
            .row(titulo="Punto de quiebre").ajuste-cajaAcordion
              p.mb-0 Ubicado en la parte inferior de la horma, justo debajo de la línea del perímetro de articulación. Marca la división entre la parte delantera y el enfranque.
            .row(titulo="Enfranque").ajuste-cajaAcordion
              p.mb-0 Zona central de la parte inferior de la horma, ubicada entre la delantera y la talonera.
            .row(titulo="Ángulo del asiento del talón").ajuste-cajaAcordion
              p.mb-0 Cambia según la altura del tacón. Un tacón de 1 cm tiene un ángulo de 0º; uno de 1,3 cm tiene 1º, y este aumenta 1º por cada 3 mm. Por ejemplo, un tacón de 5 cm genera un ángulo de 16º; uno de 6,35 cm (2.5") llega a 27º.
            .row(titulo="Curvatura del talón").ajuste-cajaAcordion
              p.mb-0 Radio de la curvatura del contorno de la talonera. En hormas femeninas, suele ser de 90 mm; en masculinas, entre 105 mm y 115 mm.
        .col-xl-auto(data-aos="fade-left").espacio___movil_4
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 7. 
            span Zonas técnicas de inclinación y soporte de la horma
          figure
            img.mb-2(src="@/assets/curso/temas/img21.png", alt="Imagen lateral de una horma verde que identifica partes esenciales: cono, punto de quiebre, enfranque, ángulo del asiento del talón y curva del talón.").m-auto
          figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    p.mb-5 Estos elementos permiten identificar límites, zonas de contacto y proporciones clave en la estructura de la horma:

    .bg--img_03
      .row.h-100.align-items-center
        .col-xl-auto(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 8. 
            span Referencias geométricas principales en la base de la horma
          figure
            img.mb-2(src="@/assets/curso/temas/img22.png", alt="Vista inferior de una horma verde donde se señalan referencias clave para el diseño del calzado: puntera, delantera, punto y línea de enfranque, línea del frente del tacón, canto plano del tacón y talonera. ").m-auto
          figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
        .col-xl.espacio___movil_4
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Puntera").ajuste-cajaAcordion
              p.mb-0 Punta visible en el borde o canto de la horma.
            .row(titulo="Delantera").ajuste-cajaAcordion
              p.mb-0 Parte de la horma que precede la zona de contacto con el suelo.
            .row(titulo="Línea de enfraque").ajuste-cajaAcordion
              p.mb-0 Punto donde el enfranque comienza a elevarse del suelo.
            .row(titulo="Línea del frente del tacón").ajuste-cajaAcordion
              p.mb-0 Se ubica a un 25 % de la longitud total de la horma, desde la parte trasera.
            .row(titulo="Canto del plano del tacón").ajuste-cajaAcordion
              p.mb-0 Línea inferior que divide la talonera del enfranque.
            .row(titulo="Talonera (asiento del tacón)").ajuste-cajaAcordion
              p.mb-0 Zona plana en la parte posterior inferior donde reposa el talón.

    <!-- BLOQUE 2 -->
    Separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Dimensiones de la horma
    
    .row.align-items-center.mb-5
      .col-xl
        p.mb-4 La horma tiene una silueta tridimensional compleja. Para fabricarla correctamente, es necesario seguir normas específicas y realizar mediciones precisas. Conocer las dimensiones de la horma permite comunicar cambios técnicos, identificar errores estructurales y garantizar un calce adecuado. 
        .row.align-items-center.estilo___caja_15(data-aos="fade-right")
          .col-xl-auto
            figure.d-none.d-xl-block
              img(src="@/assets/curso/temas/img23.svg", alt="" style="max-width: 90px").m-auto
          .col-xl
            p.mb-0 Las dimensiones estándar se dividen en medidas de longitud, ancho, circunferencia y volumen. En la zapatería comercial, se usan principalmente largo y ancho para establecer la talla. Sin embargo, en el diseño a medida y el desarrollo técnico de calzado, se requieren mediciones más detalladas y especializadas.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img24.svg", alt="" style="max-width: 500px").m-auto

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Medidas longitudinales

    p.mb-4 Estas medidas determinan el largo total y parcial de la horma, base para desarrollar patrones y definir la talla del calzado.

    .row.mb-5
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img25.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Largo de horma
          p.mb-0 También llamado longitud de calce o S.S.L en inglés. Se mide desde la talonera hasta la punta con una cinta métrica sobre la superficie.
      .col-sm-6.col-lg-3.mb-4.mb-lg-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img25.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Longitud de calce
          p.mb-0 Se mide desde la puntera hasta la curva del talón, como si dos planos verticales tocaran ambos extremos mientras la horma está apoyada en una superficie plana.
      .col-sm-6.col-lg-3.mb-4.mb-sm-0(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img25.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Longitud plantar
          p.mb-0 Medida entre los extremos inferiores de la horma, siguiendo el eje principal.
      .col-sm-6.col-lg-3(data-aos="zoom-in")
        .tarjeta--boton.color-primario.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src="@/assets/curso/temas/img25.svg", alt="" style="max-width: 100px").m-auto
          h3.text-center Longitud de mesa
          p.mb-0 Se mide desde el borde frontal hasta la parte trasera de la superficie plana superior de la horma (mesa).

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Medidas de circunferencia y volumen

    p.mb-4 Estas dimensiones son esenciales para determinar el volumen interno del calzado y permiten ajustar el diseño a las características del pie humano.

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto(data-aos="fade-right")
          .titulo-sexto.color-acento-contenido.mb-3
            h5 Figura 9. 
            span Medición de perímetros y longitud de la horma
          figure
            img.mb-2(src="@/assets/curso/temas/img26.png", alt="Imagen lateral de una horma verde con cintas amarillas marcando tres medidas clave: perímetro de la bola, perímetro de retención, perímetro de empeine y longitud de la horma.").m-auto
          figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).
        .col-xl.espacio___movil_4
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Perímetro de la bola").ajuste-cajaAcordion
              p.mb-0 También llamado perímetro de articulación. Se mide alrededor de la parte más ancha del antepié, conectando los puntos de la bola medial, la bola lateral y el punto de bridaje. Este punto se encuentra al 65 % de la longitud plantar.
            .row(titulo="Perímetro de retención").ajuste-cajaAcordion
              p.mb-0 Se mide desde el punto medio entre el perímetro de articulación y el perímetro de empeine hasta la mitad del cono. Se toma a 25 mm desde el punto de bridaje en el cono y 25 mm desde la línea de ancho de bola en la planta.
            .row(titulo="Perímetro de empeine").ajuste-cajaAcordion
              p.mb-0 Se mide desde el enfranque hasta la parte superior del cono. Se toma 25 mm por encima del perímetro de retención y 25 mm por detrás de este en la planta.
            .row(titulo="Perímetro talón-cuñas").ajuste-cajaAcordion
              p.mb-0 Medición que va desde el canto del talón, pasando por el cuboide, hasta el cruce del perímetro del empeine con el eje principal. Determina el tamaño de la abertura del zapato. En un zapato sin cordones talla 9 US de hombre, puede variar entre 360 mm y 378 mm.
            .row(titulo="Perímetro talonera-empeine").ajuste-cajaAcordion
              p.mb-0 También llamado perímetro de entrada. Se mide desde el punto del talón, pasando por el cuboide, hasta el punto de bridaje sobre el eje principal.

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Medidas verticales y de apoyo

    .row.align-items-center.mb-5
      .col-lg.estilo___caja_16(data-aos="fade-up")
        p.mb-4 Estas medidas determinan la altura, elevación y perfil del zapato.
        <ul class="fa-ul">
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Altura de la puntera</strong>: volumen de la horma en la zona del dedo gordo.</li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Salida o quebrante de la punta</strong>: se refiere a la distancia entre el plano del suelo y el extremo de la puntera. Puede ser inexistente en zapatillas planas o superior a 10 mm en botas de senderismo.</li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Altura de tacón</strong>: distancia entre la talonera y el suelo. Varía desde 0 mm en calzado plano hasta 100 mm o más en tacones altos.</li>
        </ul>
      .col-xl-auto(data-aos="fade-left").espacio___movil_4
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 10. 
          span Medidas verticales y de perímetro desde vista lateral
        figure(data-aos="fade-left")
          img.mb-2(src="@/assets/curso/temas/img27.png", alt="Imagen lateral de una horma verde que presenta medidas clave para el diseño de calzado: perímetro talón-empeine, perímetro talón-cuello, altura del tacón, longitud de calce, salida y altura de la puntera. ").m-auto
        figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Medidas de ancho y base

    p.mb-4 Estas dimensiones establecen el soporte y la base del calzado, fundamentales para la estabilidad y confort.

    .bg--img_03.mb-5
      .row.h-100.align-items-center
        .col-xl-auto(data-aos="fade-right").d-none.d-xl-block
          figure
            img(src="@/assets/curso/temas/img28.svg", alt="" style="width: 400px").m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Ancho de flancos").ajuste-cajaAcordion
              p.mb-0 Se mide transversalmente en la parte delantera de la horma, uniendo el punto de la bola medial con el de la bola lateral.
            .row(titulo="Anchura plantar").ajuste-cajaAcordion
              p.mb-0 Se mide en la planta de la horma, 25 mm detrás del ancho de la bola.
            .row(titulo="Anchura de la cintura").ajuste-cajaAcordion
              p.mb-0 Se toma 25 mm detrás de la anchura plantar, en la parte media inferior de la horma.
            .row(titulo="Anchura del talón").ajuste-cajaAcordion
              p.mb-0 Se mide en la base trasera, justo por delante de la talonera, a una distancia del 25 % de la longitud plantar.
            .row(titulo="Ancho de talón (cuboides)").ajuste-cajaAcordion
              p.mb-0 Corresponde al punto más ancho de la parte trasera de la horma.
            .row(titulo="Ancho de mesa").ajuste-cajaAcordion
              p.mb-0 Se toma transversalmente en la parte superior de la horma, sobre la placa superior, desde el lado medial hasta el lateral.
    
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
      h5 Figura 11. 
      span Vista posterior y superior de la horma con medidas clave

    figure.estilo___caja_4.mb-2
      img(data-aos="zoom-in")(src="@/assets/curso/temas/img29.png", alt="Vista inferior y frontal de una horma verde que ilustra las principales medidas plantares utilizadas en el diseño de calzado: longitud plantar, ancho de flancos, anchura plantar, anchura de la cintura y anchura del talón. " style="width: 500px").m-auto
    figcaption Nota. Imagen tomada de  Motawi, W. M., & Motawi, A. M. (2021).

    <!-- BLOQUE 3 -->
    Separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Clasificación de las hormas
    
    .row.mb-5.align-items-center
      .col-xl
        p.mb-0 Las hormas se pueden clasificar de diversas maneras, según el usuario, la tipología del calzado, el sistema de extracción y la altura del tacón. Estas clasificaciones permiten seleccionar la horma adecuada de acuerdo con la funcionalidad, el diseño y las necesidades específicas de cada calzado.
      .col-xl-auto(data-aos="fade-left")
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img30.svg", alt="" style="max-width: 294px").m-auto
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Según el usuario
    
    p.mb-4 Esta clasificación considera las características fisiológicas y las necesidades particulares del usuario.

    TabsC.color-acento-contenido.mb-5(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Según el género y la edad")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img31.svg', alt='').img400.m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Según el género y la edad
            <ul class="fa-ul estilo___ul">
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma para dama</strong>: con formas más estilizadas, menor volumen en el empeine y el talón.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma para caballero</strong>: más ancha y robusta, con mayor soporte en la planta del pie.</li>
              <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma infantil</strong>: adaptada a pies en crecimiento, flexible y con refuerzo en el arco.</li>
            </ul>
      .py-3.py-md-4(titulo="Según el tipo de piel")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img32.svg', alt='').img400.m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Según el tipo de piel
            <ul class="fa-ul estilo___ul">
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma estándar (normal)</strong>: para pies con proporciones promedio; utilizada en calzado convencional.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma para pie ancho</strong>: con mayor espacio en la parte delantera y lateral, ideal para pies voluminosos.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma para pie delgado</strong>: más ajustada en metatarso y talón, evita deslizamientos dentro del zapato.</li>
              <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma ortopédica</strong>: proporciona soporte específico en el arco, estabilidad y comodidad para pies con requerimientos especiales.</li>
            </ul>
      .py-3.py-md-4(titulo="Según la aplicación o uso")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure.d-none.d-xl-block
              img(src='@/assets/curso/temas/img33.svg', alt='').img400.m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura.mb-4 Según la aplicación o uso
            <ul class="fa-ul estilo___ul">
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma deportiva</strong>: optimizada para rendimiento, con buena flexibilidad y soporte.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma de seguridad</strong>: más ancha, resistente, y con espacio para punteras protectoras.</li>
              <li class="mb-3"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma de moda</strong>: estilizada, con formas innovadoras centradas en la estética.</li>
              <li class="mb-0"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Horma confort</strong>: diseñada para uso prolongado, con materiales acolchados y mayor espacio interior.</li>
            </ul>
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Según la familia de calzado a la que pertenezca

    .row.mb-5.align-items-center(data-aos="zoom-in")
      .col-xl.estilo___caja_17
        p.mb-3 Las hormas varían según el tipo de zapato que se desea fabricar. Algunas de las más comunes incluyen:
        <ul class="fa-ul">
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Tubular.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Mocasín.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Calzado de dama clásico (con diferentes alturas de tacón).</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Calzado de hombre clásico.</strong></li>
          <li class="mb-2"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Deportivos.</strong></li>
          <li class="mb-0"><span class="fa-li"><i class="fas fa-cut color___fa-cut_1"></i></span><strong>Botas y botines.</strong></li>
        </ul>
      .col-xl-auto
        figure.d-none.d-xl-block
          img(src="@/assets/curso/temas/img34.jpg" style="max-width: 550px")

    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Según el sistema de extracción

    p.mb-5 Esta clasificación se refiere al mecanismo que permite retirar la horma del interior del calzado durante la fabricación:

    .fondo___slider.mb-5
      .px-5
        .ajuste-slider(data-aos="zoom-in")
          SlyderA(tipo="b")
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img36.svg', alt='' style="max-width: 400px").m-auto
              .col-xl-6.mb-4.col-xs-12
                h4.mb-4 Horma entera
                p.mb-0 Horma completa, sin divisiones ni mecanismos. Usada en sandalias, zapatos de salón y zapatos con diseño abierto que permiten deshormado sin dificultad.
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img37.svg', alt='' style="max-width: 400px").m-auto
              .col-xl-6.mb-4.col-xs-12
                h4.mb-4 Horma con cuña
                p.mb-0 Incorpora una pieza divisible en la zona del empeine que se separa para facilitar el deshormado. Indicada para zapatos abotinados o botines. Muy utilizada en botas y zapatos abotinados.
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img38.svg', alt='' style="max-width: 400px").m-auto
              .col-xl-6.mb-4.col-xs-12
                h4.mb-4 Horma con articulado Alfa (V)
                p.mb-0 Tiene una bisagra que permite la reducción y apertura de la horma.
            .row.h-100.justify-content-center.align-items-center
              .col-xl-6
                figure.d-none.d-xl-block
                  img(src='@/assets/curso/temas/img39.svg', alt='' style="max-width: 400px").m-auto
              .col-xl-6.mb-4.col-xs-12
                h4.mb-4 Horma con articulado Tendo (Kiowa)
                p.mb-0 El talón se desliza hacia arriba sin torsionar el calzado. Reduce la horma durante la extracción. Ideal para calzado plano y botas de baja altura.
    
    .caja-titulos-tercer-nivel.mb-5(data-aos="fade-right")
      .col-lg-auto
        figure
          img(src="@/assets/curso/temas/img2.svg" style="max-width: 70px").m-auto
      .col
        h3 Según la altura del tacón
    
    p.mb-4 La inclinación de la horma influye directamente en el diseño del calzado y en el tipo de soporte que brinda al pie. Se clasifica de la siguiente manera:

    .row.mb-5
      .col-xl-auto
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
          h5 Tabla 4. 
          span Clasificación de hormas según altura del tacón
        .tabla-a.mb-4.ajuste--text.ajuste___tabla_4(data-aos="fade-up")
          table
            thead
              tr
                th.ajuste-border-tabla Clasificación
                th.ajuste-border-tabla Altura del tacón
                th.ajuste-border-tabla Características
                th Ejemplos de calzado
            tbody
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma plana
                td.ajuste-border-tabla 0 - 1 cm
                td.ajuste-border-tabla.texto-left Ofrece máxima estabilidad y comodidad. Ideal para uso prolongado.
                td.texto-left Zapatillas deportivas, zapatos de seguridad, sandalias planas.
              tr
                td.ajuste-border-tabla Horma baja
                td.ajuste-border-tabla 1.5 - 3.5 cm
                td.ajuste-border-tabla.texto-left Mejora la postura sin comprometer la comodidad.
                td.texto-left Mocasines, zapatos escolares, botas bajas.
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma media
                td.ajuste-border-tabla 3.5 - 6.5 cm
                td.ajuste-border-tabla.texto-left Equilibrio entre estilo y confort. Inclinación moderada.
                td.texto-left Zapatos de oficina, botines, tacones medianos.
              tr
                td.ajuste-border-tabla Horma alta
                td.ajuste-border-tabla 6.5 - 9.5 cm
                td.ajuste-border-tabla.texto-left Estiliza la figura. Requiere materiales de soporte.
                td.texto-left Tacones de vestir, sandalias elegantes, botas altas.
              tr.ajuste-color-tabla
                td.ajuste-border-tabla Horma extra alta
                td.ajuste-border-tabla Más de 9 cm
                td.ajuste-border-tabla.texto-left Máxima inclinación. Menor comodidad para uso prolongado.
                td.texto-left <em>Stilettos</em>, plataformas, calzado de pasarela.
    
    p.mb-5.espacio___movil_1 A medida que la talla aumenta, también lo hace la altura necesaria del tacón para mantener la misma proporción ergonómica y estética en el diseño del calzado.
    
 
    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade-right")
      h5 Figura 12. 
      span Relación entre la talla y la altura del tacón

    figure.estilo___caja_18
      img(data-aos="zoom-in")(src="@/assets/curso/temas/img40.png", alt="Ilustración de varias hormas de calzado representadas por curvas superpuestas, cada una correspondiente a una talla distinta, desde la 1½ hasta la 8½." style="max-width: 1100px").m-auto

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

<style lang="sass"></style>
