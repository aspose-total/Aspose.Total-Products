---
title: Supprimez l'annotation DOT en ligne ou gérez les annotations via .NET
description: supprimez gratuitement les commentaires du fichier DOT via l'application en ligne.Code API .NET pour gérer les commentaires des fichiers DOT.

family: total
platformtag: net
feature: Annotate
informat: DOT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Effacer les commentaires du document DOT en ligne ou gérer via .NET" h2="Développez une puissante application utilitaire d’annotation de documents DOT basée sur .NET.Code répertorié pour la gestion des commentaires du fichier DOT via .NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer les annotations DOT en ligne" %}}

1. Importez le fichier DOT pour supprimer les commentaires en le téléchargeant
1. Faites-le en cliquant dans la zone de dépôt via glisser-déposer de l'application d'annotation
1. En fonction de la taille du fichier DOT et de la vitesse d'Internet, attendez quelques secondes
1. Cliquez sur le bouton "Supprimer" pour effacer les commentaires
1. Téléchargez le fichier instantanément

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Supprimer les commentaires du document DOT d'un auteur spécifique via .NET" %}}

1. Ajouter une référence de bibliothèque au projet .NET
1. Charger un document via un objet de classe Document
1. Obtenez tous les commentaires des nœuds en utilisant GetChildNodes ayant NodeType.Comment
1. Parcourez tous les commentaires et faites correspondre le nom de l'auteur
1. Appelez la méthode Remove pour supprimer le commentaire d'auteur spécifique

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code C# : supprimer les commentaires d'auteur spécifiques du fichier DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Ajouter des commentaires via .NET" %}}

1. Créer un objet de classe Document
1. Utiliser la classe Commentaire
1. Ajoutez le nouveau paragraphe en utilisant Paragraphs.Add
1. Utilisez FirstParagraph.Runs.Add et ajoutez le commentaire
1. Ou l'autre façon est d'utiliser les classes CommentRangeStart et CommentRangeEnd
1. Appelez la méthode save pour enregistrer le fichier avec les commentaires ajoutés

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Extraire tous les commentaires" %}}

1. Charger un document via un objet de classe Document
1. Créer un objet ArrayList
1. Obtenez tous les GetChildNodes dans NodeCollection
1. Parcourez chaque collection et ajoutez des commentaires dans ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code .NET : Ajouter un commentaire à partir du fichier DOT" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Extraire tous les commentaires" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Développer une application d'annotation de documents DOT via .NET</h2>

Besoin de développer une application ou un utilitaire d'annotation DOT pour fournir des commentaires, faire des suggestions ou collaborer avec d'autres sur le document ?Avec [Aspose.Words for .NET](https://products.aspose.com/words/net/), une API enfant de [Aspose.Total for .NET](https://products.aspose.com/total/net/), tout développeur .NET peut intégrer le code API ci-dessus dans son application d'annotation de documents.La puissante bibliothèque .NET permet de programmer n'importe quelle solution d'annotation de documents.De plus, il peut prendre en charge de nombreux formats populaires, notamment le format DOT.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque .NET pour annoter les fichiers DOT" %}}

Il existe trois options alternatives pour installer "Aspose.Words for .NET" ou "Aspose.Total for .NET" sur votre système.Veuillez en choisir un qui correspond à vos besoins et suivre les instructions étape par étape :<br /><br />

- Installez un [Paquet NuGet](https://www.nuget.org/packages/Aspose.Words/). Voir [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Installez la bibliothèque à l'aide de [Console du gestionnaire de packages](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) dans Visual Studio IDE
- Installez la bibliothèque à la main en utilisant [Programme d'installation de Windows](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

Notre produit est entièrement multiplateforme et prend en charge toutes les principales implémentations .NET suivant la spécification « .NET Standard 2.0 » :<br /><br />

- Microsoft .NET Framework, depuis la première version 2.0 jusqu'à la dernière version « .NET Framework 4.8 »
- .NET Core, depuis la première version 2.0 jusqu'à la dernière version « .NET 6 »
- Mono >= 2.6.7
<br /><br />
Comme le code .NET ne repose pas sur le matériel ou le système d'exploitation sous-jacent, mais uniquement sur une machine virtuelle, vous êtes donc libre de développer tout type de logiciel pour Windows, macOS, Android, iOS et Linux.Assurez-vous simplement d'avoir installé la version correspondante de .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.<br /><br />
Nous vous recommandons d'utiliser Microsoft Visual Studio, Xamarin et MonoDevelop IDE pour créer des applications C#, F# et VB.NET.
<br /><br />
Pour plus de détails, veuillez vous référer à [Documentation produit](https://docs.aspose.com/words/net/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
**Fichiers DOT (modèles de documents Word 97–2003)**  
Les fichiers DOT définissent des structures de documents réutilisables. Les annotations dans ces fichiers aident à préciser l'objectif des modèles, les instructions d'utilisation et les notes de personnalisation pour les utilisateurs.

#### Utilisations des Annotations dans les Fichiers DOT :

- **Guidance pour la personnalisation des modèles**  
  Les annotations sont utilisées pour indiquer aux utilisateurs comment et où insérer le contenu.

- **Instructions de flux**  
  Les commentaires expliquent les comportements automatisés, les macro ou la mise en forme conditionnelle intégrées dans le modèle.

- **Évaluations de marquage et de style**  
  Les zones doivent être mis en conformité avec les directives de marque d'entreprise ou les normes de documents.

- **Collecte de retours des utilisateurs**  
  Facilitez les améliorations itératives en permettant aux utilisateurs d'insérer des commentaires sur l'utilisabilité du modèle.

- **Modèles conformément aux réglementations**  
  Fournir des notes liées aux réglementations directement dans le modèle pour les processus de documentation légale.
{{% /blocks/products/pf/feature-page-summary %}}
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
                          <span itemprop="name"><b>Puis-je utiliser le code .NET ci-dessus dans mon application ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Oui, vous pouvez télécharger ce code et l'utiliser dans le but de développer une application d'annotation de documents basée sur .NET.Ce code peut servir de ressource précieuse pour améliorer les fonctionnalités et les capacités de vos projets dans le domaine du traitement et de la manipulation de documents backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Cette application d'annotation de documents en ligne fonctionne-t-elle uniquement sous Windows ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous avez la possibilité de lancer l'annotation de documents pour la suppression des commentaires sur n'importe quel appareil, quel que soit le système d'exploitation sur lequel il s'exécute, qu'il s'agisse de Windows, Linux, Mac OS ou Android.Tout ce dont vous avez besoin est un navigateur Web contemporain et une connexion Internet active.</span>
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