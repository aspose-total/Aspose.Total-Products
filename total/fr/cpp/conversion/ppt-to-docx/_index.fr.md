---
title: API C++ pour convertir PPT en DOCX ou avec le convertisseur en ligne gratuit
description: Exportez PPT vers DOCX dans vos applications C++ ou en ligne. Testez rapidement le convertisseur en ligne PPT vers DOCX gratuit avant d'intégrer le code.

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCX
otherformats: DOC FLATOPC OTT RTF DOT DOTM TEXT WORDML ODT DOCM WORD DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ pour rendre PPT en DOCX ou application en ligne" h2="Exportez PPT vers DOCX dans des applications C++ sans aucune dépendance Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) est un package complet de bibliothèques d'automatisation du format de fichier C++. En utilisant les fonctionnalités riches des API disponibles dans le package, nous pouvons facilement convertir PowerPoint PPT en Word DOCX. Pour effectuer la conversion, vous pouvez d'abord utiliser l'API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) pour convertir PPT en HTML. Après cela, en utilisant l'API de traitement de texte riche en fonctionnalités [Aspose.Words for C++](https://products.aspose.com/words/cpp/), vous pouvez convertir le HTML en DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir PPT en DOCX" %}}
1. Chargez le fichier PPT à l'aide de la référence de classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Rendez PPT en HTML en utilisant la fonction membre [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOCX en utilisant la fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOCX format
docx->Save(u"output.docx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertisseur en ligne gratuit pour PPT en DOCX</h3>

<iframe title="Outil en ligne de conversion docx en ppt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=docx&from=ppt" id="child-iframe" width="80%"></iframe>

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
              <h2>Questions fréquemment posées</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Comment puis-je convertir PPT en DOCX en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'application en ligne pour la conversion PPT est intégrée ci-dessus. Pour convertir votre fichier PPT en DOCX à l'aide de cet outil en ligne, vous pouvez soit faire glisser et déposer le fichier PPT dans la zone désignée, soit cliquer à l'intérieur de la zone blanche pour sélectionner le fichier sur votre appareil. Une fois le fichier PPT sélectionné, cliquez sur le bouton Convertir. Une fois la conversion PPT en DOCX terminée, vous pouvez télécharger votre fichier DOCX converti en un seul clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir PPT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La vitesse de conversion PPT en DOCX à l'aide de ce convertisseur en ligne dépend en grande partie de la taille du fichier PPT. Les fichiers PPT plus petits peuvent être convertis en DOCX en quelques secondes seulement. De plus, si vous avez intégré le code de conversion dans votre application C++, la vitesse de conversion dépendra de la façon dont vous avez optimisé votre application pour le processus de conversion.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir PPT en DOCX en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Après le processus de conversion, le lien de téléchargement des fichiers DOCX sera disponible instantanément. Pour garantir votre confidentialité, les fichiers téléchargés sont supprimés après 24 heures et les liens de téléchargement cesseront de fonctionner après cette période. Soyez assuré que la conversion de fichiers, y compris la conversion PPT, est entièrement sécurisée et privée. L'application gratuite est principalement intégrée à des fins de test, vous permettant de vérifier le résultat avant d'intégrer le code.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir PPT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Le convertisseur PPT en DOCX en ligne est compatible avec tous les navigateurs Web modernes, y compris Google Chrome, Firefox, Opera et Safari, entre autres. Toutefois, si vous travaillez sur une application de bureau, vous pouvez envisager d'utiliser l'API Aspose.Total PPT Conversion, spécialement conçue pour une intégration transparente avec les applications C++. Cette API offre une conversion à grande vitesse et des fonctionnalités avancées qui peuvent améliorer les performances de votre application. De plus, il prend en charge une large gamme de formats de fichiers, ce qui en fait une solution polyvalente pour tous vos besoins de conversion. Que vous choisissiez d'utiliser le convertisseur en ligne ou l'API, vous pouvez être assuré que vos fichiers sont en sécurité tout au long du processus de conversion.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}