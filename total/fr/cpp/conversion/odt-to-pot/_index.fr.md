---
title: Convertir ODT en POT via C++
description: Exportez ODT vers POT dans vos applications C++ sans utiliser Microsoft Word ou PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: POT
otherformats: PPTM POTM POTX PPSM ODP PPTX PPSX POWERPOINT PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour convertir ODT en POT" h2="Exportez ODT vers POT dans vos applications C++ sans utiliser Microsoft Word® ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) se compose de puissantes API d'automatisation de fichiers qui permettent d'automatiser la conversion ODT en POT tout en utilisant deux de ses API. Chargez votre ODT en utilisant [Aspose.Words for C++](https://products.aspose.com/words/cpp/) et convertissez-le en HTML, puis chargez le HTML via l'API C++ de manipulation PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour créer une nouvelle présentation et enregistrez-la sous POT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversion ODT en POT sur C++" %}}
1. Ouvrez le fichier ODT à l'aide de la référence de classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
2. Convertir ODT en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions)
3. Initialisez un nouvel objet [Présentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Ajoutez une forme automatique dans votre diapositive et ajoutez-y AddTextFrame
5. Chargez le contenu HTML et écrivez-le dans votre fichier de présentation
6. Enregistrez le odtument au format POT à l'aide de la méthode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Pot comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load ODT file with an instance of Odtument
Odtument odtument = new Odtument("template.odt");
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"sourceFile.odt");
// save the odtument in HTML file format
odt->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Charger un odtument ODT protégé par mot de passe via C++" %}}
Outre la conversion de odtuments, l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) offre des tonnes de fonctionnalités de manipulation de odtuments aux développeurs C++. Si votre format de fichier Microsoft Word ODT est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API. Pour charger le odtument chiffré, vous pouvez utiliser une surcharge de constructeur spéciale, qui accepte un objet [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Cet objet contient la propriété Password, qui spécifie la chaîne de mot de passe.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected odtument, the password is passed to the odtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"odtPassword");
// load the odtument from the local file system by filename:
SharedPtr<Odtument> odt = MakeObject<Odtument>(u"Encrypted.odt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ajouter des commentaires dans le odtument POT via C++" %}}
Lors de l'enregistrement du ODT au format POT, vous pouvez également utiliser [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour ajouter d'autres fonctionnalités dans votre odtument POT. Par exemple, vous pouvez ajouter des commentaires dans votre présentation. Le commentaire de la diapositive de présentation est associé à un auteur particulier. La classe Presentation contient la collection d'auteurs dans ICommentAuthorCollection qui sont responsables de l'ajout de commentaires de diapositive. Pour chaque auteur, il existe une collection de commentaires dans ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-pptm/" name="ODT À PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-potm/" name="ODT À POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-potx/" name="ODT À POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-ppsm/" name="ODT À PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-pot/" name="ODT À POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-pptx/" name="ODT À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-ppsx/" name="ODT À PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-powerpoint/" name="ODT À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-ppt/" name="ODT À PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/odt-to-pps/" name="ODT À PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}