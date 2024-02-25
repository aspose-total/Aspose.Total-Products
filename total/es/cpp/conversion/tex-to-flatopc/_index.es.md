---
title: API de C++ para exportar TEX a FLATOPC
description: Convierta TEX a FLATOPC dentro de aplicaciones C++.

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: FLATOPC
otherformats: PS XAMLFLOW OTT DOTM MARKDOWN DOT RTF DOCM MHTML WORDML ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar TEX a FLATOPC" h2="Renderice TEX a FLATOPC dentro de aplicaciones C++ sin necesidad de ninguna aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) las bibliotecas de automatización de formato de archivo permiten al desarrollador de C++ convertir TEX a FLATOPC en dos simples pasos. En primer lugar, puede usar la API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para convertir el formato de archivo TEX a DOC. En segundo lugar, al utilizar la API avanzada de procesamiento de documentos de Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar DOC a FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para renderizar TEX a FLATOPC" %}}
1. Abra el archivo TEX usando la referencia de clase [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convierta TEX a DOC usando la función miembro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Cargue el archivo DOC utilizando la referencia de clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) de Aspose.Words API
4. Guarde el documento en formato FLATOPC usando la función miembro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cambiar la contraseña del documento TEX a través de C++" %}}
En el proceso de renderizar TEX a FLATOPC, puede abrir un TEX protegido con contraseña y también cambiar su contraseña. Para cambiar la contraseña de un archivo TEX, debe conocer la contraseña del propietario de ese documento. Puede cargar un documento PDF protegido con contraseña con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando su contraseña de propietario y usando el método ChangePasswords para cambiar la contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de archivos FLATOPC a través de C++" %}}
También puede restringir la edición de archivos FLATOPC mediante la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. La API le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). El siguiente ejemplo de código muestra cómo restringir la edición en un documento para que solo sea posible editar en los campos de formulario.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}