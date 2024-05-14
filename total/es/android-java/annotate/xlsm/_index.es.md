---
title: Elimine la anotación XLSM en línea o administre anotaciones mediante aplicaciones móviles de Android
description: elimine comentarios del archivo XLSM a través de la aplicación en línea de forma gratuita.Código API de Android para gestionar comentarios de archivos XLSM.

family: total
platformtag: Android
feature: Annotate
informat: XLSM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Borrar comentarios del documento XLSM en línea o administrar a través de aplicaciones de Android" h2="Desarrolle una potente aplicación de utilidad de anotación de documentos XLSM basada en Android.Código listado para gestionar comentarios del archivo XLSM." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eliminar anotaciones XLSM en línea" %}}

1. Importe el archivo XLSM para eliminar comentarios subiéndolo
1. Hágalo haciendo clic dentro del área de colocación arrastrando y soltando la aplicación de anotación
1. Dependiendo del tamaño del archivo XLSM y la velocidad de Internet, espere unos segundos
1. Haga clic en el botón 'Eliminar' para borrar los comentarios.
1. Descarga el archivo al instante

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Eliminar comentarios de documentos XLSM a través de la API de la aplicación de Android" %}}

1. Agregar referencia de biblioteca al proyecto de Android
1. Cargar documento a través del objeto de clase Libro de trabajo
1. Seleccione la hoja de trabajo específica
1. Obtenga todos los comentarios del uso de [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. Obtenga todos los comentarios enhebrados a través de getThreadedComments
1. Utilice removeAt para eliminar comentarios y autores respectivamente.
1. Llame al método de guardar para guardar el archivo.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Eliminar comentarios del documento XLSM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Actualizar comentarios XLSM enhebrados" %}}

1. Cargar documento a través del objeto de clase Libro de trabajo
1. Obtenga la hoja de trabajo específica
1. Obtenga el comentario del hilo usando getComments().getThreadedComments(Index).get(Index)
1. Utilice el método setNotes para actualizar el comentario.
1. Llame al método de guardar para guardar el archivo.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Agregar comentarios a través de la API de la aplicación de Android" %}}

1. Crear documento a través del objeto de clase Libro de trabajo
1. Obtenga la hoja de trabajo específica
1. Agregar índice de comentarios a través de getComments().add
1. Utilice el método setNotes para agregar comentarios
1. Llame al método de guardar para guardar el archivo. with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Código: Actualizar comentario enhebrado del archivo XLSM" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Código: Agregar comentarios" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Desarrollar una aplicación para Android de anotación de documentos XLSM</h2>

¿Necesita desarrollar una aplicación o utilidad de anotación XLSM basada en Android para proporcionar comentarios, hacer sugerencias o colaborar con otros en el documento?Con [Aspose.Cells for Android via Java](https://products.aspose.com/cells/es/android-java/), una API secundaria de [Aspose.Total for Android via Java](https://products.aspose.com/total/es/android-java/), cualquier desarrollador de Android puede integrar el código API anterior dentro de su aplicación de anotación de documentos.La potente biblioteca de Android permite programar cualquier solución de anotación de documentos.Además, puede admitir muchos formatos populares, incluido el formato XLSM.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para anotar archivos XLSM" %}}

- Alojamos nuestros paquetes Java en [Repositorios Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java es un archivo JAR común que contiene código de bytes.
- Siga el [instrucciones paso a paso](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) sobre cómo instalar Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

- Sistema operativo Android 2.0 o superior.
- El paquete Java es multiplataforma y se ejecuta en todos los sistemas operativos con implementación JVM.

<br />
Para obtener más detalles, consulte [Documentación del producto](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}