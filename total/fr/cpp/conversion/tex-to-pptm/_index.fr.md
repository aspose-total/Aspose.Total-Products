---
title: API C++ pour convertir TEX en PPTM
description: Convertir TEX en PPTM via C++ sans utiliser Microsoft Word ou Adobe Acrobat Reader
url: /fr/cpp/conversion/tex-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PPTM
otherformats: PPSM POT POWERPOINT XAML OTP PPSX PPS SWF ODP PPT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre TEX en PPTM dans les applications C++" h2="Convertissez TEX en PPTM dans vos applications C++ sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à intégrer la fonction de conversion TEX vers PPTM dans vos applications C++ ? Vous pouvez le faire en deux étapes simples. Vous pouvez exporter TEX vers PPTX en utilisant [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Deuxièmement, en utilisant [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vous pouvez convertir PPTX en PPTM. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour exporter TEX vers PPTM" %}}
1. Ouvrez le fichier TEX à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convertissez TEX en PPTX en utilisant la fonction de méthode [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Chargez le document PPTX en utilisant la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Enregistrez le document au format PPTM à l'aide de la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez `Pptm` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class
auto doc = MakeObject<Document>(u"template.tex");
// save TEX as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pptm format
prs->Save(u"output.pptm", Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Changer le mot de passe du document TEX via C++" %}}
Lors du processus de conversion de TEX en PPTM, vous pouvez ouvrir un TEX protégé par mot de passe et également modifier son mot de passe. Pour changer le mot de passe d'un fichier TEX, vous devez connaître le mot de passe du propriétaire de ce document. Vous pouvez charger un document PDF protégé par mot de passe avec [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) en spécifiant son mot de passe propriétaire et en utilisant la méthode ChangePasswords pour changer le mot de passe.
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

{{% blocks/products/pf/feature-page-section  h2="Ajouter des images à partir du Web dans un fichier PPTM via C++" %}}
Après avoir converti TEX en PPTM, vous pouvez également ajouter des images du Web à votre document de sortie. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) prend en charge les opérations avec des images dans ces formats populaires : JPEG, PNG, BMP, GIF et autres. Vous pouvez ajouter une ou plusieurs images de votre ordinateur sur une diapositive d'une présentation. Cet exemple de code en C++ vous montre comment ajouter une image à un fichier PPTM
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPTM file
auto pres = System::MakeObject<Presentation>("output.pptm");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.pptm", SaveFormat::Pptm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-ppsm/" name="TEX À PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-pot/" name="TEX À POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-powerpoint/" name="TEX À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-xaml/" name="TEX À XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-otp/" name="TEX À OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-ppsx/" name="TEX À PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-pps/" name="TEX À PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-swf/" name="TEX À SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-pptm/" name="TEX À PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-ppt/" name="TEX À PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-potx/" name="TEX À POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tex-to-potm/" name="TEX À POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}