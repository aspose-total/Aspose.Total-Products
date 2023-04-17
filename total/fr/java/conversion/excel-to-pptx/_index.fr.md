---
title: Convertir EXCEL en PPTX en utilisant Java ou avec le convertisseur en ligne gratuit
description: API Java pour exporter EXCEL vers PPTX ou en ligne en utilisant Excel ou Word ou en ligne. Testez rapidement le convertisseur en ligne CSV vers DOC gratuit avant d'intégrer le code.
url_ignore: /fr/java/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: PPTX
otherformats: WORD PPTX POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour exporter EXCEL vers PPTX ou en ligne" h2="API Java sur site pour exporter EXCEL vers PPTX sans dépendre de Microsoft Excel®" >}}
{{% blocks/products/pf/feature-page-summary %}}
Le rendu EXCEL en PPTX est un processus en deux étapes. Vous utiliserez d'abord l'API [Aspose.Cells for Java](https://products.aspose.com/cells/java) pour convertir le document EXCEL donné en PDF, puis en utilisant [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, vous pouvez facilement convertir votre document PDF en PPTX. Les deux API font partie de la collection de bibliothèques d'automatisation de format de fichier [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EXCEL en PPTX via l'API Java" %}}
1. Ouvrez le fichier EXCEL à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Convertissez EXCEL en PDF et définissez SaveFormat sur AUTO
3. Chargez le fichier PDF converti à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Enregistrez le document au format PPTX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) méthode et définissez Pptx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertisseur en ligne pour EXCEL en PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">Essayez notre application gratuite pour la conversion EXCEL en PPTX</a></p>
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
                          <span itemprop="name"><b>Comment puis-je convertir EXCEL en PPTX en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'application en ligne pour la conversion EXCEL est intégrée ci-dessus. Le processus de conversion consiste à ajouter votre fichier EXCEL soit en le faisant glisser et en le déposant dans la zone blanche, soit en cliquant à l'intérieur de la zone pour importer le fichier. Une fois le fichier ajouté, cliquez simplement sur le bouton Convertir pour démarrer le processus de conversion. Une fois terminé, vous pouvez télécharger votre fichier PPTX nouvellement converti en un seul clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir EXCEL ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La vitesse de ce convertisseur en ligne est largement déterminée par la taille du fichier EXCEL à convertir. Les fichiers EXCEL plus petits peuvent être convertis en PPTX en quelques secondes seulement. De plus, si vous avez incorporé le code de conversion dans une application Java, l'efficacité de l'application influencera également le processus de conversion.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir EXCEL en PPTX en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Une fois le processus de conversion terminé, un lien de téléchargement pour le fichier PPTX sera mis à disposition immédiatement. Les fichiers téléchargés sont automatiquement supprimés après 24 heures et les liens de téléchargement ne seront plus actifs au-delà de ce délai. Vous pouvez être assuré que vos fichiers sont en sécurité et que la conversion des fichiers, y compris EXCEL, est entièrement sécurisée. L'application gratuite a été intégrée principalement à des fins de test, vous permettant de vérifier les résultats avant d'intégrer le code dans votre projet.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir EXCEL ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Pour la conversion en ligne, vous pouvez utiliser n'importe quel navigateur Web moderne tel que Google Chrome, Firefox, Opera ou Safari. Cependant, si vous développez une application de bureau, l'API Aspose.Total EXCEL Conversion est un excellent choix car elle est conçue pour fonctionner de manière transparente dans de tels environnements.</span>
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