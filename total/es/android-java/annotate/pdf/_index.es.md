---
title: Elimine la anotación PDF en línea o administre anotaciones mediante aplicaciones móviles de Android
description: elimine comentarios del archivo PDF a través de la aplicación en línea de forma gratuita.Código API de Android para gestionar comentarios de archivos PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Borrar comentarios del documento PDF en línea o administrar a través de aplicaciones de Android" h2="Desarrolle una potente aplicación de utilidad de anotación de documentos PDF basada en Android.Código listado para gestionar comentarios del archivo PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eliminar anotaciones PDF en línea" %}}

1. Importe el archivo PDF para eliminar comentarios subiéndolo
1. Hágalo haciendo clic dentro del área de colocación arrastrando y soltando la aplicación de anotación
1. Dependiendo del tamaño del archivo PDF y la velocidad de Internet, espere unos segundos
1. Haga clic en el botón 'Eliminar' para borrar los comentarios.
1. Descarga el archivo al instante

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Eliminar comentarios de documentos PDF a través de la API de la aplicación de Android" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Cargar documento a través del objeto de clase de documento
1. Seleccione la página específica a través de getPages().get_Item(Index)
1. Utilice AnnotationSelector y obtenga todas las anotaciones de texto a través de annotationSelector.getSelected()
1. Repita cada anotación y llame al método de eliminación para eliminarla.
1. Llame al método save para guardar el archivo.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Eliminar comentarios del archivo PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Agregar anotaciones a través de la API de la aplicación de Android" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Crear objeto de clase de documento
1. Agregue la nueva página y el contenido usando getPages().add()
1. Utilice getPages().get_Item(Index) de la clase TextAnnotation
1. Establezca las anotaciones relevantes como título, tema, contenido, etc.
1. Utilice getAnnotations().add para agregar las anotaciones.
1. Llame al método de guardar para guardar el archivo con comentarios agregados.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Agregar anotación PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desarrollar una aplicación para Android de anotación de documentos PDF</h2>

¿Necesita desarrollar una aplicación o utilidad móvil de anotación PDF para proporcionar comentarios, hacer sugerencias o colaborar con otros en el documento?Con [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/es/android-java/), una API secundaria de [Aspose.Total for Android via Java](https://products.aspose.com/total/es/android-java/), cualquier desarrollador de Android puede integrar el código API anterior dentro de su aplicación de anotación de documentos.La potente biblioteca de Android permite programar cualquier solución de anotación de documentos.Además, puede admitir muchos formatos populares, incluido el formato PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca de Android para anotar archivos PDF" %}}

- Alojamos nuestros paquetes Java en [Repositorios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java es un archivo JAR común que contiene código de bytes.
- Siga el [instrucciones paso a paso](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) sobre cómo instalar Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

- API de Android 31 y 32
- Android 4.0 y superior
- Herramientas de Android Studio y SDK

<br />
Para obtener más detalles sobre las dependencias de paquetes opcionales, como JogAmp JOGL, el motor de fuentes Harfbuzz, Java Advanced Imaging JAI, consulte [Documentación del producto](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}