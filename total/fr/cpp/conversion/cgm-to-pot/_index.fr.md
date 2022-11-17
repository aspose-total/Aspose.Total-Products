---
title: API C++ pour convertir CGM en POT
description: Convertir CGM en POT via C++ sans utiliser Microsoft Word ou Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POT
otherformats: SWF POWERPOINT POTM PPSM OTP XAML PPTM PPSX PPS POTX ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre CGM en POT dans les applications C++" h2="Convertissez CGM en POT dans vos applications C++ sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Êtes-vous un développeur C++ cherchant à intégrer la fonction de conversion CGM vers POT dans vos applications C++ ? Vous pouvez le faire en deux étapes simples. Vous pouvez exporter CGM vers PPTX en utilisant [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Deuxièmement, en utilisant [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vous pouvez convertir PPTX en POT. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour exporter CGM vers POT" %}}
1. Ouvrez le fichier CGM à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convertissez CGM en PPTX en utilisant la fonction de méthode [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Chargez le document PPTX en utilisant la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Enregistrez le document au format POT à l'aide de la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez `Pot` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pot format
prs->Save(u"output.pot", Aspose::Slides::Export::SaveFormat::Pot);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Changer le mot de passe du document CGM via C++" %}}
Lors du processus de conversion de CGM en POT, vous pouvez ouvrir un CGM protégé par mot de passe et également modifier son mot de passe. Pour changer le mot de passe d'un fichier CGM, vous devez connaître le mot de passe du propriétaire de ce document. Vous pouvez charger un document PDF protégé par mot de passe avec [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) en spécifiant son mot de passe propriétaire et en utilisant la méthode ChangePasswords pour changer le mot de passe.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ajouter des images à partir du Web dans un fichier POT via C++" %}}
Après avoir converti CGM en POT, vous pouvez également ajouter des images du Web à votre document de sortie. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) prend en charge les opérations avec des images dans ces formats populaires : JPEG, PNG, BMP, GIF et autres. Vous pouvez ajouter une ou plusieurs images de votre ordinateur sur une diapositive d'une présentation. Cet exemple de code en C++ vous montre comment ajouter une image à un fichier POT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POT file
auto pres = System::MakeObject<Presentation>("output.pot");
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
pres->Save(u"updated.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-swf/" name="CGM À SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-powerpoint/" name="CGM À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-potm/" name="CGM À POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-ppsm/" name="CGM À PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-otp/" name="CGM À OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-xaml/" name="CGM À XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-pptm/" name="CGM À PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-ppsx/" name="CGM À PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-pps/" name="CGM À PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-potx/" name="CGM À POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-pot/" name="CGM À POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/cgm-to-ppt/" name="CGM À PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}