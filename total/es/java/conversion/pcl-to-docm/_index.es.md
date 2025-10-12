---
title: Conversión de PCL a DOCM en línea o desarrollo de una aplicación basada en Java para convertir archivos PCL
description: Aplicación gratuita en línea para convertir archivos PCL a DOCM. Código de biblioteca de conversión Java para documentos PCL. 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: DOCM
otherformats: DOT XAMLFLOW DOTX PS OTT ODT MHTML DOTM FLATOPC MARKDOWN WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicación de conversión de PCL a DOCM en línea y código Java para convertir archivos PCL" h2="Desarrollar una potente aplicación de conversión y exportación PCL basada en Java. Convierta archivos PCL individuales o múltiples a DOCM y otros formatos a través de la API de automatización de Java. Convierta libremente archivos PCL en línea a través de la aplicación con descarga instantánea." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicación gratuita de conversión de PCL a DOCM en línea" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=docm&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierte archivos PCL a DOCM en línea usando la aplicación" %}}

1. Subir archivos PCL para convertir
1. Espere unos segundos o más según el tamaño de PCL
1. Esté atento a la barra de estado de carga
1. Haga clic en el botón "Convertir"
1. PCL se convertirá en un documento DOCM
1. Descargue el archivo DOCM convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir PCL a DOCM mediante la API de automatización de Java" %}}


1. Abra el archivo PCL usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta PCL a DOC usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el archivo DOC usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Guarde el documento en formato DOCM usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) y configure DOCM como Guardar formato



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "bfec283bb7a30344c355fa8754a3e3a7" "convert-pcl-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Algunos casos más para guardar PCL en DOCM con otras funciones como Requisitos de conversión, Abrir documento PCL protegido con contraseña a través de Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.pcl", "password");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Desarrollar una aplicación de conversión de archivos PCL utilizando Java</h2>

¿Necesita desarrollar una aplicación de software basada en Java para guardar y exportar fácilmente archivos PCL a documentos DOCM? Con [Aspose.Total for Java](https://products.aspose.com/total/es/java/), cualquier desarrollador Java puede integrar el código API anterior para programar la aplicación de conversión en una variedad de formatos, incluidos Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, archivos de correo electrónico, imágenes (JPG, PNG, BMP, GIF) y otros formatos. Potente biblioteca Java para conversión de documentos, admite muchos formatos populares, incluido el formato PCL. Al exportar y renderizar documentos a otros formatos, los programadores pueden utilizar las API secundarias Aspose.Total for Java, incluidas [Aspose.Words for Java](https://products.aspose.com/words/es/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/es/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/es/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/es/java/) y más.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca de conversión PCL para Java" %}}

Existen opciones alternativas para integrar Aspose.Total for Java en su sistema. Elija uno que se asemeje a sus necesidades y siga las instrucciones paso a paso:<br /><br />

- Utilice Aspose.Total for Java directamente desde un proyecto basado en Maven e incluya la API secundaria relevante en pom.xml.
- Alternativamente, se puede obtener un archivo ZIP de [Descargas](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de la aplicación para guardar PCL en DOCM" %}}

Cualquier sistema operativo que pueda ejecutar Java Runtime Environment (JRE) puede ejecutar Aspose.Total for Java. A continuación se enumeran la mayoría de los sistemas operativos compatibles, pero no todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS y otros
- macOS: 10.9 (Mavericks) y posteriores
- Móvil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Convertir **PCL a DOCM** permite la transformación de las salidas de **Printer Command Language** en documentos de Word habilitados para macros, lo que permite la automatización, actualizaciones dinámicas y capacidades avanzadas de formato directamente desde archivos basados en impresión.

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}

* Incrustar macros en documentos de Word convertidos para automatización
* Reutilizar datos impresos en informes editables y programables
* Crear plantillas empresariales interactivas a partir de impresiones PCL
* Mejorar flujos de trabajo productivos utilizando documentos habilitados para macros

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}

* Conversión por lotes de archivos PCL a DOCM para informes dinámicos
* Integrar salidas de impresión en flujos de trabajo automatizados basados en Word
* Generar documentos habilitados para macros a partir de flujos de impresión en tiempo real

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}