---
title: API de C++ para exportar PDF a WORDML
description: Convierta PDF a WORDML dentro de aplicaciones C++.
url: /es/cpp/conversion/pdf-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: WORDML
otherformats: DOTM MHTML ODT DOT PS XAMLFLOW DOCM PCL OTT DOTX FLATOPC RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar PDF a WORDML" h2="Renderice PDF a WORDML dentro de aplicaciones C++ sin necesidad de ninguna aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) las bibliotecas de automatización de formato de archivo permiten al desarrollador de C++ convertir PDF a WORDML en dos simples pasos. En primer lugar, puede usar la API [Aspose.PDF para C++](https://products.aspose.com/pdf/cpp/) para convertir el formato de archivo PDF a DOC. En segundo lugar, al utilizar la API avanzada de procesamiento de documentos de Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar DOC a WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para renderizar PDF a WORDML" %}}
1. Abra el archivo PDF usando la referencia de clase [Documento](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convierta PDF a DOC usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Cargue el archivo DOC utilizando la referencia de clase [Documento](https://reference.aspose.com/words/cpp/class/aspose.words.document) de Aspose.Words API
4. Guarde el documento en formato WORDML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as WordML
wordDoc->Save(u"output.WordML");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cambiar la contraseña del documento PDF a través de C++" %}}
En el proceso de renderizar PDF a WORDML, puede abrir un PDF protegido con contraseña y también cambiar su contraseña. Para cambiar la contraseña de un archivo PDF, debe conocer la contraseña del propietario de ese documento. Puede cargar un documento PDF protegido con contraseña con [Aspose.PDF para C++](https://products.aspose.com/pdf/cpp/) especificando su contraseña de propietario y usando el método ChangePasswords para cambiar la contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de archivos WORDML a través de C++" %}}
También puede restringir la edición de archivos WORDML mediante la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. La API le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). El siguiente ejemplo de código muestra cómo restringir la edición en un documento para que solo sea posible editar en los campos de formulario.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.WordML");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-dotm/" name="PDF A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-mhtml/" name="PDF A MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-odt/" name="PDF A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-dot/" name="PDF A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-ps/" name="PDF A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xamlflow/" name="PDF A XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-wordml/" name="PDF A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-pcl/" name="PDF A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-ott/" name="PDF A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-dotx/" name="PDF A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-flatopc/" name="PDF A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-rtf/" name="PDF A RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}