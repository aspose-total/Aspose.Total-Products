---
title: Elimine la anotación DOCX en línea o administre anotaciones mediante aplicaciones móviles de Android
description: elimine comentarios del archivo DOCX a través de la aplicación en línea de forma gratuita.Código API de Android para gestionar comentarios de archivos DOCX.

family: total
platformtag: Android
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Borrar comentarios del documento DOCX en línea o administrar a través de aplicaciones de Android" h2="Desarrolle una potente aplicación de utilidad de anotación de documentos DOCX basada en Android.Código listado para gestionar comentarios del archivo DOCX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eliminar anotaciones DOCX en línea" %}}

1. Importe el archivo DOCX para eliminar comentarios subiéndolo
1. Hágalo haciendo clic dentro del área de colocación arrastrando y soltando la aplicación de anotación
1. Dependiendo del tamaño del archivo DOCX y la velocidad de Internet, espere unos segundos
1. Haga clic en el botón 'Eliminar' para borrar los comentarios.
1. Descarga el archivo al instante

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Eliminar comentarios de documentos DOCX a través de la aplicación de Android" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Cargar documento a través del objeto de clase de documento
1. Obtenga todos los comentarios de todos los nodos utilizando [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) y NodeType.COMMENT
1. Invoca el método [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) para eliminar todos los comentarios.
1. Llame al método save para guardar el archivo.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Eliminar comentarios del archivo DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eliminar y agregar respuesta al comentario DOCX" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Cargar documento a través del objeto de clase de documento
1. Obtener comentarios usando getChild
1. Utilice [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) para eliminar la respuesta especificada a este comentario
1. Utilice [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) para agregar cualquier respuesta a este comentario.
1. Llame al método de guardar para guardar el archivo.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Agregar comentarios a través de la aplicación de Android" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Crear objeto de clase de documento
1. Utilice [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) para crear el comentario.
1. Utilice getParagraphs().add y getFirstParagraph().getRuns().add
1. Llame al método de guardar para guardar el archivo. with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Eliminar y agregar respuesta de comentario del archivo DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Código: Agregar comentarios" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desarrollar una aplicación para Android de anotación de documentos DOCX</h2>

¿Necesita desarrollar una aplicación o utilidad móvil de anotación DOCX para proporcionar comentarios, hacer sugerencias o colaborar con otros en el documento?Con [Aspose.Words for Android via Java](https://products.aspose.com/words/es/android-java/), una API secundaria de [Aspose.Total for Android via Java](https://products.aspose.com/total/es/android-java/), cualquier desarrollador de Android puede integrar el código API anterior dentro de su aplicación de anotación de documentos.La potente biblioteca de Android permite programar cualquier solución de anotación de documentos.Además, puede admitir muchos formatos populares, incluido el formato DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca de Android para anotar archivos DOCX" %}}

- Alojamos nuestros paquetes Java en [Repositorios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java es un archivo JAR común que contiene código de bytes.
- Siga el [instrucciones paso a paso](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) sobre cómo instalar Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

- Se admite Java SE 7 y versiones de Java más recientes.
- Paquete separado para Java SE 6 en caso de que uno esté obligado a utilizar JRE obsoleto.
- El paquete Java es multiplataforma y se ejecuta en todos los sistemas operativos con implementación JVM.
- Los sistemas operativos incluyen Microsoft Windows, Linux, macOS, Android e iOS.

<br />
Para obtener más detalles sobre las dependencias de paquetes opcionales, como JogAmp JOGL, el motor de fuentes Harfbuzz, Java Advanced Imaging JAI, consulte [Documentación del producto](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}