---
title: API C++ pour exporter XPS vers XAMLFLOW
description: Convertissez XPS en XAMLFLOW dans les applications C++.
url: /fr/cpp/conversion/xps-to-xamlflow/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: XAMLFLOW
otherformats: OTT RTF DOT MHTML WORDML DOTX DOCM PS FLATOPC ODT DOTM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour exporter XPS vers XAMLFLOW" h2="Rendre XPS en XAMLFLOW dans les applications C++ sans nécessiter d'application tierce" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les bibliothèques d'automatisation de format de fichier [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permettent aux développeurs C++ de convertir XPS en XAMLFLOW en deux étapes simples. Tout d'abord, vous pouvez utiliser l'API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) pour convertir le format de fichier XPS en DOC. Deuxièmement, en utilisant l'API avancée de traitement de documents Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez exporter DOC vers XAMLFLOW. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour rendre XPS en XAMLFLOW" %}}
1. Ouvrez le fichier XPS à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convertissez XPS en DOC en utilisant la fonction membre [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Chargez le fichier DOC en utilisant la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) de l'API Aspose.Words
4. Enregistrez le document au format XAMLFLOW à l'aide de la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Xamlflow
wordDoc->Save(u"output.Xamlflow");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Changer le mot de passe du document XPS via C++" %}}
Lors du processus de conversion de XPS en XAMLFLOW, vous pouvez ouvrir un XPS protégé par mot de passe et également modifier son mot de passe. Pour changer le mot de passe d'un fichier XPS, vous devez connaître le mot de passe du propriétaire de ce document. Vous pouvez charger un document PDF protégé par mot de passe avec [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) en spécifiant son mot de passe propriétaire et en utilisant la méthode ChangePasswords pour changer le mot de passe.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restreindre l'édition de fichiers XAMLFLOW via C++" %}}
Vous pouvez également restreindre l'édition de fichiers XAMLFLOW à l'aide de l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Parfois, vous devrez peut-être limiter la possibilité de modifier un document et n'autoriser que certaines actions avec celui-ci. L'API vous permet de contrôler la façon dont vous restreignez le contenu à l'aide du paramètre d'énumération [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). L'exemple de code suivant montre comment limiter la modification dans un document afin que seule la modification dans les champs de formulaire soit possible.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Xamlflow");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-ott/" name="XPS À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-rtf/" name="XPS À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-dot/" name="XPS À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-mhtml/" name="XPS À MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-wordml/" name="XPS À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-dotx/" name="XPS À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-xamlflow/" name="XPS À XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-ps/" name="XPS À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-flatopc/" name="XPS À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-odt/" name="XPS À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-dotm/" name="XPS À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xps-to-pcl/" name="XPS À PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}