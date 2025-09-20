---
title: Convierta EPUB a PPSX a través de la API de Java
description: API de Java para convertir EPUB a PPSX sin usar Microsoft Word
url_ignore: /es/java/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: POWERPOINT XAML PPTM PPT PPSM OTP PPS POT POTM POTX SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar EPUB a PPSX" h2="Exporte EPUB a PPSX a través de la API Java local sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) puede convertir fácilmente EPUB a PPSX dentro de cualquier aplicación Java J2SE, J2EE, J2ME. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puede exportar EPUB a PPTX. Después de eso, al usar [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de procesamiento de PowerPoint, puede convertir PPTX a PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir EPUB a PPSX" %}}
1. Abra el archivo EPUB usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta EPUB a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPSX usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Ppsx` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Al cargar el formato de archivo EPUB, su documento puede estar protegido con contraseña. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir archivo EPUB cifrado a través de Java" %}}
Después de convertir EPUB a PPSX, también puede agregar un tipo de vista predefinido para su presentación. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) proporciona una función para establecer el tipo de vista para la presentación generada cuando se abre en PowerPoint a través de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) clase. La propiedad [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se usa para establecer el tipo de vista mediante [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerador. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
Convertir **EPUB a PPSX (PowerPoint Open XML Show)** es esencial para generar **archivos de presentación modernos** a partir de libros electrónicos. Los archivos PPSX proporcionan un formato basado en XML abierto para presentaciones de diapositivas que se inician directamente en modo de presentación, garantizando compatibilidad y una visualización profesional. Al transformar EPUB en PPSX, educadores, editores y empresas pueden entregar de manera eficiente presentaciones pulidas, optimizar el intercambio de contenido y mantener la coherencia en pantallas digitales y en vivo.

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}
- **Vistas previas de publicación** – Mostrar contenido de libros electrónicos como diapositivas interactivas para clientes o lectores.
- **Conferencias académicas** – Convertir contenido de libros de texto en diapositivas de conferencias listas para reproducir.
- **Presentaciones de trabajos de investigación** – Presentar diapositivas estructuradas para conferencias y seminarios.
- **Presentaciones empresariales** – Presentar materiales corporativos en un formato de presentación de diapositivas profesional y moderno.
- **Sesiones de capacitación** – Crear diapositivas instructivas para talleres y programas de aprendizaje electrónico.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}
- **Flujos de trabajo EPUB a PPSX automatizados** – Automatizar la conversión de libros electrónicos en archivos de presentación de diapositivas modernos.
- **Generación automatizada de presentaciones de diapositivas** – Producir diapositivas listas para reproducir directamente desde publicaciones digitales.
- **Conversión masiva de libros electrónicos a PowerPoint** – Convertir múltiples libros electrónicos en presentaciones de manera eficiente.
- **Flujos de trabajo de publicación a nivel empresarial** – Integrar la generación de PPSX en sistemas de distribución de presentaciones a gran escala y gestión de contenido.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}