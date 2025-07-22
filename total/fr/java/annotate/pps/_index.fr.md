---
title: Supprimer l'annotation PPS en ligne ou gérer les annotations via Java
description: supprimez gratuitement les commentaires du fichier PPS via l'application en ligne.Code API Java pour gérer les commentaires des fichiers PPS.

family: total
platformtag: Java
feature: Annotate
informat: PPS
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Effacer les commentaires de la présentation PPS en ligne ou gérer via Java" h2="Développez une puissante application utilitaire d’annotation de présentation PPS basée sur Java.Code répertorié pour la gestion des commentaires du fichier PPS via Java." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer les annotations PPS en ligne" %}}

1. Importez le fichier PPS pour supprimer les commentaires en le téléchargeant
1. Faites-le en cliquant dans la zone de dépôt via glisser-déposer de l'application d'annotation
1. En fonction de la taille du fichier PPS et de la vitesse d'Internet, attendez quelques secondes
1. Cliquez sur le bouton "Supprimer" pour effacer les commentaires
1. Téléchargez le fichier instantanément

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Supprimer les commentaires de présentation PPS via Java" %}}

1. Ajouter une référence de bibliothèque au projet Java
1. Charger PPS via un objet de classe Présentation
1. Parcourez chaque auteur via la collection [Presentation.getCommentAuthors()](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#getCommentAuthors--)
1. Invoquer la méthode [clear()](https://reference.aspose.com/slides/java/com.aspose.slides/icommentcollection/#clear--) pour supprimer son commentaire
1. Enfin, appelez [getCommentAuthors().clear()](https://reference.aspose.com/slides/java/com.aspose.slides/commentauthorcollection/#clear--) pour supprimer tous les auteurs
1. Appelez la méthode save pour enregistrer le fichier
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Exemple de code en Java pour supprimer les commentaires et les auteurs de PPS Présentation" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Ajouter des commentaires de présentation PPS via Java" %}}

1. Ajouter une référence de bibliothèque au projet Java
1. Charger PPS via un objet de classe Présentation
1. Invoquez [Presentation.getCommentAuthors().addAuthor(String, String)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentAuthorCollection#addAuthor-java.lang.String-java.lang.String-) pour ajouter les auteurs
1. Utilisez [ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)](https://reference.aspose.com/slides/java/com.aspose.slides/ICommentCollection#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) pour l'ajout de commentaires
1. Appelez la méthode save pour enregistrer le fichier with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code Java : ajout de commentaires" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Développer une application d'annotation de documents PPS via Java</h2>

Besoin de développer une application ou un utilitaire d'annotation PPS pour fournir des commentaires, faire des suggestions ou collaborer avec d'autres sur le document ?Avec [Aspose.Slides for Java](https://products.aspose.com/slides/java/), une API enfant de [Aspose.Total for Java](https://products.aspose.com/total/java/), tout développeur Java peut intégrer le code API ci-dessus dans son application d'annotation de documents.La puissante bibliothèque Java permet de programmer n'importe quelle solution d'annotation de documents.De plus, il peut prendre en charge de nombreux formats populaires, notamment le format PPS.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque Java pour annoter les fichiers PPS" %}}
Il existe d'autres options pour installer "[Aspose.Slides for Java](https://products.aspose.com/slides/java/)" ou "[Aspose.Total for Java](https://products.aspose.com/total/java/)" sur votre système. Notre package Java est conçu pour être multiplateforme, compatible avec les implémentations JVM sur divers systèmes d'exploitation tels que Microsoft Windows, Linux, macOS, Android et iOS.Veuillez en choisir un qui correspond à vos besoins et suivre les instructions étape par étape :<br />

- Installer [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/)
- Ou depuis [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/)
- Étape par étape [Instructions](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

- J2SE 6.0 (Java 1.6) et supérieur

<br />
Pour plus de détails, veuillez vous référer à [Documentation produit](https://docs.aspose.com/slides/java/system-requirements/#optional-dependencies).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}
```
<h2> 📝 Pourquoi annoter les fichiers PPS : Améliorer les diaporamas autonomes, les présentations en kiosque et les présentations lors de salons</h2>

L'annotation des fichiers **PPS (PowerPoint Show)** est importante pour les entreprises qui créent des présentations autonomes pour des événements, des kiosques et des présentations générales de l'entreprise. Ajouter des commentaires et des annotations aide les équipes à peaufiner la synchronisation des diapositives, à approuver le contenu et à maintenir la cohérence de la marque sur les affichages publics.

## ✅ Cas d'utilisation clés

- **Présentations générales de l'entreprise autonomes :** Annoter les fichiers PPS pour peaufiner les séquences de diapositives, ajouter des notes de synchronisation et mettre en évidence les mises à jour pour les présentations en lecture automatique.
- **Présentations en kiosque :** Utilisez des commentaires pour ajuster les visuels, garantir un message clair et marquer les sections nécessitant des ajustements de conception pour les affichages interactifs ou non surveillés.
- **Diaporamas lors de salons :** Ajouter des annotations pour mettre à jour les points forts des produits, approuver les modifications de diapositives et aligner le message sur les campagnes actuelles.

## ⚙️ Avantages de l'automatisation

- **Révisions de synchronisation des diapositives :** Automatisez les annotations pour vérifier les durées des diapositives, les transitions et la boucle pour une lecture fluide.
- **Approbation de contenu :** Utilisez des workflows automatisés pour recueillir des commentaires, suivre les révisions et finaliser les présentations PPS avant le déploiement.
- **Audits de l'image de marque de la présentation :** Intégrez des vérifications automatisées pour vérifier que toutes les diapositives respectent les directives de la marque, les logos et les visuels approuvés.
```
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
                          <span itemprop="name"><b>Puis-je utiliser le code Java ci-dessus dans mon application ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Oui, vous pouvez télécharger ce code et l'utiliser dans le but de développer une application d'annotation de documents basée sur Java.Ce code peut servir de ressource précieuse pour améliorer les fonctionnalités et les capacités de vos projets dans le domaine du traitement et de la manipulation de documents backend.</span>
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
                          <span itemprop="name"><b>Est-il sécuritaire d'utiliser l'application en ligne pour annoter un document PPS ?</b></span>
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
                          <span itemprop="text">Vous pouvez utiliser n'importe quel navigateur Web moderne comme Google Chrome, Firefox, Opera ou Safari pour l'annotation de documents PPS en ligne.Toutefois, si vous développez une application de bureau, nous vous recommandons d'utiliser l'API de traitement de documents Aspose.Total pour une gestion efficace.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}