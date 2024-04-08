---
title: Supprimez l'annotation DOT en ligne ou gérez les annotations via C++
description: supprimez gratuitement les commentaires du fichier DOT via l'application en ligne. Code API C++ pour gérer les commentaires des fichiers DOT.

family: total
platformtag: cpp
feature: Annotate
informat: DOT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Effacer les commentaires du document DOT en ligne ou gérer via C++" h2="Développez une puissante application utilitaire d’annotation de documents DOT basée sur C++. Code répertorié pour la gestion des commentaires du fichier DOT via C++." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer les annotations DOT en ligne" %}}

1. Importez le fichier DOT pour supprimer les commentaires en le téléchargeant
1. Faites-le en cliquant dans la zone de dépôt via glisser-déposer de l'application d'annotation
1. En fonction de la taille du fichier DOT et de la vitesse d'Internet, attendez quelques secondes
1. Cliquez sur le bouton "Supprimer" pour effacer les commentaires
1. Téléchargez le fichier instantanément

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Supprimer les commentaires du document DOT via C++" %}}

1. Ajouter une référence de bibliothèque au projet C++
1. Charger le fichier DOT
1. Obtenez tous les nœuds en utilisant GetChildNodes ayant NodeType :: Comment comme paramètre
1. Appelez NodeCollection.Clear pour la collecte de commentaires

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code C++ : supprimer les commentaires du fichier DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "remove-word-document-comments.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Ajouter des commentaires via C++" %}}

1. Créer un objet de classe Document et DocumentBuilder
1. Ou Charger le document
1. Utilisez la classe Comment pour ajouter le commentaire
1. Utilisez la méthode AppendChild avec le commentaire obj comme paramètre
1. Utilisez une méthode pertinente comme get_Paragraphs()->Add
1. Ou l'autre façon est d'utiliser les classes CommentRangeStart et CommentRangeEnd
1. Appelez la méthode save pour enregistrer le fichier avec les commentaires ajoutés

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Extraire tous les commentaires" %}}

1. Charger un document via un objet de classe Document
1. Obtenez tous les GetChildNodes dans NodeCollection
1. Parcourez chaque collection et collectez des informations à leur sujet

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code C++ : Ajouter un commentaire au fichier DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "word-document-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ Code: Extraire tous les commentaires" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Développer une application d'annotation de documents DOT via C++</h2>

Besoin de développer une application ou un utilitaire d'annotation DOT pour fournir des commentaires, faire des suggestions ou collaborer avec d'autres sur le document ?Avec [Aspose.Words for C++](https://products.aspose.com/words/cpp/), une API enfant de [Aspose.Total for C++](https://products.aspose.com/total/fr/cpp/), tout développeur C++ peut intégrer le code API ci-dessus dans son application d'annotation de documents.La puissante bibliothèque C++ permet de programmer n'importe quelle solution d'annotation de documents.De plus, il peut prendre en charge de nombreux formats populaires, notamment le format DOT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque C++ pour annoter les fichiers DOT" %}}

Il existe trois options pour installer Aspose.Words for C++ dans votre environnement de développeur.Veuillez en choisir un qui correspond à vos besoins et suivre les instructions étape par étape :<br /><br />

- Install a [Paquet NuGet](https://www.nuget.org/packages/Aspose.Words.Cpp/). See [Documentation](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- Installez la bibliothèque à l'aide de [Console du gestionnaire de packages](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) dans Visual Studio IDE
- Installez la bibliothèque à la main en utilisant [Programme d'installation de Windows](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}
Vous pouvez utiliser cette bibliothèque C++ pour développer des logiciels sur les systèmes d'exploitation Microsoft Windows, Linux et macOS :<br /><br />

- GCC >= 6.3.0 et Clang >= 3.9.1 sont requis pour Linux
- Xcode >= 12.5.1, Clang et libc++ sont requis pour macOS

<br /><br />
Si vous développez des logiciels pour Linux ou macOS, veuillez vérifier les informations sur les dépendances supplémentaires de la bibliothèque (packages open source fontconfig et mesa-glu) dans [Documentation produit](https://docs.aspose.com/words/cpp/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQ" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>FAQ</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Puis-je utiliser le code C++ ci-dessus dans mon application ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Oui, vous pouvez télécharger ce code et l'utiliser dans le but de développer une application d'annotation de documents basée sur C++.Ce code peut servir de ressource précieuse pour améliorer les fonctionnalités et les capacités de vos projets dans le domaine du traitement et de la manipulation de documents backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Cette application d'annotation de documents en ligne fonctionne-t-elle uniquement sous Windows ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous avez la possibilité de lancer l'annotation de documents pour la suppression des commentaires sur n'importe quel appareil, quel que soit le système d'exploitation sur lequel il s'exécute, qu'il s'agisse de Windows, Linux, Mac OS ou Android. Tout ce dont vous avez besoin est un navigateur Web contemporain et une connexion Internet active.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sécuritaire d'utiliser l'application en ligne pour annoter un document DOT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Les fichiers de sortie générés via notre service seront supprimés de manière sécurisée et automatique de nos serveurs dans un délai de 24 heures.De ce fait, les liens d'affichage associés à ces fichiers cesseront d'être fonctionnels passé ce délai.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur doit utiliser l'application ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous pouvez utiliser n'importe quel navigateur Web moderne comme Google Chrome, Firefox, Opera ou Safari pour l'annotation de documents DOT en ligne.Toutefois, si vous développez une application de bureau, nous vous recommandons d'utiliser l'API de traitement de documents Aspose.Total pour une gestion efficace.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}