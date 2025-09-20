---
title: Convierta el formato JSON a WMF a través de Java
description: Analizar JSON a WMF en Java sin usar Microsoft PowerPoint
url_ignore: /es/java/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: TGA DICOM JPEG2000 WMZ EMZ PSD WMF DXF SVGZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a WMF a través de Java" h2="API de Java para analizar el formato JSON a WMF dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/), puede convertir el formato JSON a WMF dentro de cualquier aplicación Java en dos simples pasos. En primer lugar, al usar [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede analizar JSON a JPEG. Después de eso, usando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), puede convertir JPEG a WMF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a WMF a través de Java" %}}
1. Cree un nuevo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y abra el archivo JSON
2. Guarde JSON como JPEG usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
3. Cargue el documento JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Guarde el documento en formato WMF usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Además, la API le permite analizar JSON a WMF con opciones de diseño específicas. Para especificar las opciones de diseño, puede usar la clase [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Le permite procesar una matriz como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir una cadena en un número o fecha, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a WMF a través de Java" %}}
Usando la API, también puede convertir JSON a WMF con marca de agua en su documento WMF. Para agregarle una marca de agua, primero puede convertir JSON a JPEG y agregarle una marca de agua. Para agregar una marca de agua, cargue un archivo de imagen usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), cree un objeto de [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialícela con el objeto Image, cree una nueva [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) y configure la traducción y transformación al ángulo deseado y agregue una marca de agua usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# método drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Después de agregar la marca de agua en su imagen, puede guardar el JPEG como formato WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
Convertir **JSON a WMF** es esencial para producir **gráficos de Windows Metafile a partir de datos estructurados**. Los archivos WMF proporcionan gráficos vectoriales escalables compatibles con aplicaciones heredadas de Windows y documentos de Office. Al transformar JSON en WMF, las organizaciones pueden automatizar la creación de diagramas, gráficos e ilustraciones técnicas, asegurando consistencia y compatibilidad en los flujos de trabajo empresariales.  

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}

- **Aplicaciones heredadas de Windows** – Mantener la compatibilidad con software antiguo que requiere gráficos WMF.  
- **Diagramas escalables** – Generar diagramas basados en vectores que escalan sin pérdida de calidad.  
- **Integración en documentos de Office** – Incrustar gráficos WMF directamente en archivos de Word, PowerPoint y Excel.  
- **Gráficos empresariales** – Automatizar la generación de gráficos a partir de conjuntos de datos estructurados para informes corporativos.  
- **Ilustraciones técnicas** – Crear ilustraciones precisas y basadas en datos para manuales y documentos de ingeniería.  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}

- **Tuberías de JSON a WMF** – Automatizar la conversión de datos estructurados en gráficos vectoriales WMF.  
- **Generación automatizada de gráficos vectoriales** – Reducir la creación manual de diagramas e ilustraciones.  
- **Renderizado de gráficos basado en JSON** – Poblar gráficos y visuales directamente desde conjuntos de datos.  
- **Flujos de trabajo de ilustración a nivel empresarial** – Integrar la generación de WMF en los flujos de documentación corporativa.  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}