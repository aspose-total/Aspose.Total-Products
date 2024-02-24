---
title: API .NET para Convertir Word a Excel o Utilizar el Conversor en Línea Gratuito
description: Utilice nuestra API de C# para convertir documentos de Word a Excel sin depender de Microsoft Excel o Adobe Reader. ¡Pruebe nuestro conversor en línea gratuito de Word a Excel antes de integrar el código en su aplicación y ahorre tiempo! 
url_ignore: /es/net/conversion/word-to-excel/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: EXCEL
otherformats: SXC ODS XLSX XLAM XLT XLSM XLTX TSV XLTM FODS XLSB XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para Convertir Documentos de Word a Excel o Aplicación en Línea" h2="Exportar Word a Excel con C# sin necesidad de Microsoft<sup>®</sup> Word ni Microsoft<sup>®</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Por qué convertir documentos de Word a formatos de Excel?</h2>

Algunas personas pueden querer convertir archivos de Word a formatos de Excel utilizando código .NET por varias razones. Excel es una herramienta ampliamente utilizada para el análisis y la organización de datos, por lo que la conversión permite un manejo más eficiente de la información contenida en los documentos de Word. Esto puede ser especialmente útil cuando se trabaja con tablas, listas o datos estructurados que se desean manipular, filtrar o analizar en una hoja de cálculo. La automatización a través de código .NET simplifica el proceso y ahorra tiempo al permitir una conversión rápida y precisa de documentos, lo que facilita la integración de datos de Word en flujos de trabajo y aplicaciones que requieren el formato de Excel.

<h2 class="heading-border">Cómo Aspose.Total puede ayudar en la conversión de Word a Excel?</h2>

Con [Aspose.Total para .NET](https://products.aspose.com/total/net/), puedes incorporar la capacidad de convertir de Word a Excel en cualquier aplicación .NET, ya sea en C#, ASP.NET o VB.NET, en solo dos pasos. En primer lugar, utilizando Aspose.Words for .NET, puedes exportar documentos de Word a HTML. Luego, empleando la API de Aspose.Cells for .NET para hojas de cálculo, puedes convertir el HTML en un formato Excel. Esto facilita la automatización del proceso de conversión y permite a los desarrolladores integrar con eficiencia la funcionalidad de conversión de Word a Excel en sus aplicaciones.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir Word a Excel" %}}
1. Abra el archivo Word usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Convierta Word a HTML usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Cargue el documento HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato Excel usando el método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Excel` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertidor en línea gratuito para Word a Excel</h3>

<iframe title="Herramienta de conversión de xlsx a docx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlsx&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Cargar documento Word desde Stream a través de C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) también le permite cargar documentos Word a través de la transmisión. Para abrir un documento desde una secuencia, simplemente pase un objeto de secuencia que contenga el documento al constructor [Document](https://reference.aspose.com/words/net/aspose.words/document). El siguiente ejemplo de código muestra cómo abrir un documento desde una secuencia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregue propiedades personalizadas en un archivo Excel a través de C#" %}}
Al convertir Word a Excel, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) le permite agregar propiedades personalizadas en sus documentos Excel. Para agregar una propiedad personalizada, puede usar el método [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) para la [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) clase. El método Add agrega la propiedad al archivo de Excel y devuelve una referencia para la propiedad del nuevo documento como [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>¿Cómo puedo convertir Word a Excel en línea?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La aplicación en línea para la conversión de Word está integrada arriba. En primer lugar, debe agregar el archivo Word para la conversión arrastrando y amp; suelte o haga clic dentro del área blanca para importar el documento. Luego haga clic en el botón Convertir. Cuando se completa la conversión de Word a Excel, puede descargar su archivo convertido. Entonces obtendrá archivos Excel de salida con solo un clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Cuánto tiempo lleva convertir Word?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Este convertidor en línea funciona rápido pero depende principalmente del tamaño del archivo Word. Puede convertir archivos Word de tamaño pequeño a Excel en unos segundos. Además, si ha integrado el código de conversión dentro de la aplicación .NET, depende de cómo haya optimizado su aplicación para el proceso de conversión.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Es seguro convertir Word a Excel usando el convertidor gratuito Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">¡Por supuesto! El enlace de descarga de archivos Excel estará disponible instantáneamente después de la conversión. Eliminamos los archivos cargados después de 24 horas y los enlaces de descarga dejarán de funcionar después de este período de tiempo. Nadie tiene acceso a sus archivos. La conversión de archivos (incluyendo Word) es absolutamente segura. La aplicación principalmente gratuita está integrada con el propósito de probar para que uno pueda verificar el resultado antes de integrar el código.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>¿Qué navegador debo usar para convertir Word?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puede usar cualquier navegador moderno para esta conversión en línea, por ejemplo, Google Chrome, Firefox, Opera, Safari. Pero en caso de que estés desarrollando una aplicación de escritorio. La API de conversión de Aspose.Total Word funcionará sin problemas.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}