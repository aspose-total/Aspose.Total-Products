---
title: Convertir ODT en POTX via C++ ou avec le convertisseur en ligne gratuit
description: Exportez ODT vers POTX dans vos applications C++ sans utiliser Microsoft Word ou PowerPoint ou en ligne. Testez rapidement le convertisseur en ligne ODT vers POTX gratuit avant d'intégrer le code.

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: POTX
otherformats: ODP PPSM PPSX POWERPOINT POTM PPTX PPT POT PPS PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour convertir ODT en POTX ou application en ligne" h2="Exportez ODT vers POTX dans vos applications C++ sans utiliser Microsoft Word® ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) se compose de puissantes API d'automatisation de fichiers qui permettent d'automatiser la conversion ODT en POTX tout en utilisant deux de ses API. Chargez votre ODT en utilisant [Aspose.Words for C++](https://products.aspose.com/words/cpp/) et convertissez-le en HTML, puis chargez le HTML via l'API C++ de manipulation PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour créer une nouvelle présentation et enregistrez-la sous POTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversion ODT en POTX sur C++" %}}
1. Ouvrez le fichier ODT à l'aide de la référence de classe [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
2. Convertir ODT en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions)
3. Initialisez un nouvel objet [Présentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Ajoutez une forme automatique dans votre diapositive et ajoutez-y AddTextFrame
5. Chargez le contenu HTML et écrivez-le dans votre fichier de présentation
6. Enregistrez le odtument au format POTX à l'aide de la méthode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Potx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertisseur en ligne gratuit pour ODT en POTX</h3>

<iframe title="Outil en ligne de conversion potx en odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

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

{{% blocks/products/pf/feature-page-section  h2="Ajouter des commentaires dans le odtument POTX via C++" %}}
Lors de l'enregistrement du ODT au format POTX, vous pouvez également utiliser [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour ajouter d'autres fonctionnalités dans votre odtument POTX. Par exemple, vous pouvez ajouter des commentaires dans votre présentation. Le commentaire de la diapositive de présentation est associé à un auteur particulier. La classe Presentation contient la collection d'auteurs dans ICommentAuthorCollection qui sont responsables de l'ajout de commentaires de diapositive. Pour chaque auteur, il existe une collection de commentaires dans ICommentCollection.
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
```

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
              <h2>Questions fréquemment posées</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Comment puis-je convertir ODT en POTX en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous pouvez trouver l'application en ligne pour la conversion ODT ci-dessus. Pour démarrer le processus de conversion, vous pouvez ajouter le fichier ODT soit en le faisant glisser et en le déposant, soit en cliquant à l'intérieur de la zone blanche pour importer le document. Une fois que vous avez ajouté le fichier, vous pouvez simplement cliquer sur le bouton "Convertir". Une fois la conversion ODT en POTX terminée, vous pouvez télécharger votre fichier converti en un seul clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir ODT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La vitesse de ce convertisseur en ligne dépend en grande partie de la taille du fichier ODT à convertir. Les petits fichiers ODT peuvent être convertis en POTX en quelques secondes seulement. Si vous utilisez le code de conversion dans une application C++, la vitesse de conversion dépendra de la façon dont vous avez optimisé votre application.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir ODT en POTX en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Une fois votre fichier ODT converti en POTX à l'aide de notre convertisseur en ligne, le lien de téléchargement du fichier POTX sera immédiatement disponible. Nous prenons au sérieux la sécurité et la confidentialité de vos fichiers téléchargés et les supprimons 24 heures après la fin du processus de conversion. Rassurez-vous, personne n'aura accès à vos fichiers. Notre processus de conversion, y compris la conversion ODT, est totalement sûr. Nous fournissons une application gratuite à des fins de test afin que vous puissiez vérifier les résultats avant d'intégrer le code.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir ODT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pour la conversion ODT en ligne, vous pouvez utiliser n'importe quel navigateur moderne, tel que Google Chrome, Firefox, Opera ou Safari. Toutefois, si vous développez une application de bureau, l'API Aspose.Total ODT Conversion est recommandée pour des performances fluides.</span>
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