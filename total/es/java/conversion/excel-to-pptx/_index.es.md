---
title: Convierta EXCEL a PPTX usando Java o con el convertidor en línea gratuito
description: API de Java para exportar EXCEL a PPTX o en línea con Excel o Word o en línea. Pruebe el convertidor en línea gratuito de CSV a DOC rápidamente antes de integrar el código.
url_ignore: /es/java/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: PPTX
otherformats: WORD PPTX POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar EXCEL a PPTX o en línea" h2="API de Java local para exportar EXCEL a PPTX sin depender de Microsoft Excel<sup>&reg;</sup>" >}}
{{% blocks/products/pf/feature-page-summary %}}
Renderizar EXCEL a PPTX es un proceso de dos pasos. Primero usará [Aspose.Cells for Java](https://products.aspose.com/cells/java) API para convertir el documento EXCEL dado a PDF, y luego usará [Aspose.PDF for Java](https://products.aspose.com/pdf/java), puede convertir fácilmente su documento PDF a PPTX. Ambas API pertenecen a la colección de bibliotecas de automatización de formato de archivo [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir EXCEL a PPTX a través de la API de Java" %}}
1. Abra el archivo EXCEL usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convierta EXCEL a PDF y configure SaveFormat en AUTO
3. Cargue el archivo PDF convertido usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Guarde el documento en formato PPTX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método y establecer Pptx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertidor en línea de EXCEL a PPTX</h3>

<iframe title="Herramienta de conversión de pptx a xlsx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">Pruebe nuestra aplicación gratuita para la conversión de EXCEL a PPTX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Preguntas frecuentes</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cómo puedo convertir EXCEL a PPTX en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La aplicación en línea para la conversión de EXCEL está integrada arriba. El proceso de conversión implica agregar su archivo EXCEL, ya sea arrastrándolo y soltándolo en el área blanca o haciendo clic dentro del área para importar el archivo. Una vez que se agrega el archivo, simplemente haga clic en el botón Convertir para iniciar el proceso de conversión. Una vez completado, puede descargar su archivo PPTX recién convertido con solo un clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir EXCEL?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La velocidad de este convertidor en línea está determinada en gran medida por el tamaño del archivo EXCEL que se convierte. Los archivos EXCEL más pequeños se pueden convertir a PPTX en solo unos segundos. Además, si ha incorporado el código de conversión dentro de una aplicación Java, la eficiencia de la aplicación también influirá en el proceso de conversión.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir EXCEL a PPTX usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! Una vez que se complete el proceso de conversión, un enlace de descarga para el archivo PPTX estará disponible de inmediato. Los archivos cargados se eliminan automáticamente después de 24 horas y los enlaces de descarga ya no estarán activos más allá de ese período de tiempo. Puede estar seguro de que sus archivos están seguros y que la conversión de archivos, incluido EXCEL, es completamente segura. La aplicación gratuita se ha integrado principalmente con fines de prueba, lo que le permite verificar los resultados antes de integrar el código en su proyecto.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir EXCEL?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Para la conversión en línea, puede usar cualquier navegador web moderno como Google Chrome, Firefox, Opera o Safari. Sin embargo, si está desarrollando una aplicación de escritorio, la API de conversión de EXCEL de Aspose.Total es una excelente opción, ya que está diseñada para funcionar sin problemas en dichos entornos.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}