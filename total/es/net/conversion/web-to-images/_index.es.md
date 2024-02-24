---
title: Convierta páginas web HTML en imágenes usando C#
description: Raspe las páginas web del sitio web y exporte HTML a imágenes. Desarrolle aplicaciones .NET para extraer datos de sitios web en JPEG, PNG, GIF, BMP, etc. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta páginas web en imágenes a través de C#" h2="Extraiga los datos del sitio web de las páginas web HTML. Convierta HTML en imágenes JPG, GIF, PNG, BMP dentro de las aplicaciones .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">¿Por qué convertir páginas web en imágenes?</h2>
<p>La conversión de páginas web a imágenes puede ser útil en una variedad de situaciones. Es un requisito común para muchas aplicaciones. En algunos escenarios, es necesario capturar toda la página web como una imagen, incluidas las partes que no son visibles en la pantalla. Esto puede ser útil para generar vistas previas de sitios web, capturar recibos y facturas o archivar páginas web con fines legales. Se puede utilizar para crear capturas de pantalla de páginas web con fines de documentación o prueba. También se puede usar para crear miniaturas o vistas previas de páginas web para usar en resultados de búsqueda o galerías de imágenes. Ya sea que esté creando una aplicación de escritorio o una aplicación web, hay muchas opciones disponibles para convertir páginas web en imágenes usando C#.</p><br />

<p>La conversión de páginas web en imágenes mediante C# puede proporcionar varios beneficios, entre ellos:</p><br />
<ul>
<li>Accesibilidad mejorada: Las imágenes pueden ser más fáciles de leer y comprender para las personas con discapacidad visual u otras discapacidades.</li>
<li>Mayor portabilidad: Las imágenes se pueden compartir o incrustar fácilmente en otros documentos o aplicaciones.</li>
</ul>
<p>Convertir páginas web en imágenes usando C# también puede presentar algunos desafíos, que incluyen:</p><br />
<ul>
<li>Soporte de formato limitado: Algunas API o herramientas pueden no ser compatibles con todos los formatos de imagen o pueden tener limitaciones en el tamaño o la resolución de las imágenes de salida.</li>
<li>Problemas de compatibilidad: Algunas páginas web pueden no mostrarse correctamente en todos los navegadores o pueden requerir configuraciones o complementos específicos para mostrarse correctamente.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="¿Cómo convertir páginas web en imágenes usando C#?" %}}
Para convertir páginas web en imágenes mediante C#, puede utilizar una API de Aspose.HTML para .NET que proporciona esta funcionalidad para convertir páginas HTML en formatos de imagen, incluidos JPEG, PNG y TIFF.</p>

1. Cargue un documento HTML usando uno de los constructores disponibles en [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Puede cargar HTML desde un archivo, código HTML, una transmisión o una URL.
2. Crear una nueva instancia de [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) y establezca la propiedad ImageFormat en JPEG. De forma predeterminada, la propiedad Formato se establece en PNG.
3. utilizar el [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) de la clase Converter para guardar el documento HTML como un archivo JPEG. Deberá proporcionar HTMLDocument, ImageSaveOptions y la ruta del archivo de salida como parámetros para el método ConvertHTML().
4. El archivo JPEG resultante se guardará en la ruta de archivo especificada.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión de imagen y chatarra web" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o instale directamente desde Package Manager Console de Visual Studio.

Dos [Aspose.Total for .NET](https://products.aspose.com/total/net/) API infantil, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) se integrará.

Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}