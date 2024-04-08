---
title: Elimine la anotación DOC en línea o administre anotaciones a través de C++
description: elimine comentarios del archivo DOC a través de la aplicación en línea de forma gratuita. Código API C++ para gestionar comentarios de archivos DOC.

family: total
platformtag: cpp
feature: Annotate
informat: DOC
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Borrar comentarios del documento DOC en línea o administrar mediante C++" h2="Desarrolle una poderosa aplicación de utilidad de anotación de documentos DOC basada en C++. Código listado para administrar comentarios del archivo DOC a través de C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eliminar anotaciones DOC en línea" %}}

1. Importe el archivo DOC para eliminar comentarios subiéndolo
1. Hágalo haciendo clic dentro del área de colocación arrastrando y soltando la aplicación de anotación
1. Dependiendo del tamaño del archivo DOC y la velocidad de Internet, espere unos segundos
1. Haga clic en el botón 'Eliminar' para borrar los comentarios.
1. Descarga el archivo al instante

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Eliminar comentarios de documentos DOC a través de C++" %}}

1. Agregar referencia de biblioteca al proyecto C++
1. Cargar archivo DOC
1. Obtenga todos los nodos utilizando GetChildNodes que tenga NodeType::Comment como parámetro
1. Llame a NodeCollection.Clear en la recopilación de comentarios

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código C++: eliminar comentarios del archivo DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Agregar comentarios a través de C++" %}}

1. Crear objeto de clase Document y DocumentBuilder
1. O cargar el documento
1. Utilice la clase Comentario para agregar el comentario.
1. Utilice el método AppendChild con el comentario obj como parámetro
1. Utilice un método relevante como get_Paragraphs()->Add
1. O la otra forma es utilizar las clases CommentRangeStart y CommentRangeEnd.
1. Llame al método de guardar para guardar el archivo con comentarios agregados.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Extraer todos los comentarios" %}}

1. Cargar documento a través del objeto de clase de documento
1. Obtenga todos los GetChildNodes en NodeCollection
1. Iterar a través de cada colección y recopilar información sobre ellas.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código C++: agregar comentario al archivo DOC" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Extraer todos los comentarios" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desarrollar una aplicación de anotación de documentos DOC a través de C++</h2>

¿Necesita desarrollar una aplicación o utilidad de anotación DOC para proporcionar comentarios, hacer sugerencias o colaborar con otros en el documento?Dado que [Aspose.Words for C++](https://products.aspose.com/words/cpp/) es una API secundaria de [Aspose.Total for C++](https://products.aspose.com/total/es/cpp/), cualquier desarrollador de C++ puede integrar el código API anterior en su aplicación de anotación de documentos.La potente biblioteca C++ permite programar cualquier solución de anotación de documentos.Además, puede admitir muchos formatos populares, incluido el formato DOC.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca C++ para anotar archivos DOC" %}}

Hay tres opciones para instalar Aspose.Words para C++ en su entorno de desarrollador.Elija uno que se adapte a sus necesidades y siga las instrucciones paso a paso:<br /><br />

- Install a [Paquete NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Documentación](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Instale la biblioteca usando [Consola del administrador de paquetes](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) dentro de Visual Studio IDE
- Instale la biblioteca a mano usando [instalador de ventanas](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}
Puede utilizar esta biblioteca de C++ para desarrollar software en los sistemas operativos Microsoft Windows, Linux y macOS:<br /><br />

- GCC >= 6.3.0 y Clang >= 3.9.1 son necesarios para Linux
- Xcode >= 12.5.1, Clang y libc++ son necesarios para macOS

<br /><br />
Si desarrolla software para Linux o macOS, consulte la información sobre dependencias de bibliotecas adicionales (paquetes de código abierto fontconfig y mesa-glu) en [Documentación del producto](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Preguntas frecuentes" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Preguntas frecuentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Puedo usar el código C++ anterior en mi aplicación?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sí, puede descargar este código y utilizarlo con el fin de desarrollar una aplicación de anotación de documentos basada en C++.Este código puede servir como un recurso valioso para mejorar la funcionalidad y las capacidades de sus proyectos en el dominio del procesamiento y manipulación de documentos backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Esta aplicación de anotación de documentos en línea funciona solo en Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Tiene la flexibilidad de iniciar la anotación de documentos para eliminar comentarios en cualquier dispositivo, independientemente del sistema operativo en el que se ejecute, ya sea Windows, Linux, Mac OS o Android. Todo lo que se requiere es un navegador web moderno y una conexión a Internet activa.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro utilizar la aplicación en línea para anotar documentos DOC?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Los archivos de salida generados a través de nuestro servicio se eliminarán de forma segura y automática de nuestros servidores en un plazo de 24 horas.Como resultado, los enlaces de visualización asociados con estos archivos dejarán de funcionar después de este período.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debería utilizar la aplicación?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede utilizar cualquier navegador web moderno como Google Chrome, Firefox, Opera o Safari para realizar anotaciones en documentos DOC en línea.Sin embargo, si está desarrollando una aplicación de escritorio, le recomendamos utilizar la API de procesamiento de documentos Aspose.Total para una gestión eficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}