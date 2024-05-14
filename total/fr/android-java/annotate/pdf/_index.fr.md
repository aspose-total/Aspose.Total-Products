---
title: Supprimez l'annotation PDF en ligne ou gérez les annotations à l'aide des applications mobiles Android
description: supprimez gratuitement les commentaires du fichier PDF via l'application en ligne.Code API Android pour gérer les commentaires des fichiers PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Effacer les commentaires du document PDF en ligne ou les gérer via les applications Android" h2="Développez une puissante application utilitaire d’annotation de documents PDF basée sur Android.Code répertorié pour la gestion des commentaires du fichier PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer les annotations PDF en ligne" %}}

1. Importez le fichier PDF pour supprimer les commentaires en le téléchargeant
1. Faites-le en cliquant dans la zone de dépôt via glisser-déposer de l'application d'annotation
1. En fonction de la taille du fichier PDF et de la vitesse d'Internet, attendez quelques secondes
1. Cliquez sur le bouton "Supprimer" pour effacer les commentaires
1. Téléchargez le fichier instantanément

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Supprimer les commentaires du document PDF via l'API de l'application Android" %}}

1. Ajouter une référence de bibliothèque au projet Android
1. Charger un document via un objet de classe Document
1. Sélectionnez la page spécifique via getPages().get_Item(Index)
1. Utilisez AnnotationSelector et obtenez toutes les annotations de texte via annotationSelector.getSelected()
1. Parcourez chaque annotation et appelez la méthode delete pour la supprimer.
1. Appelez la méthode save pour enregistrer le fichier.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Supprimer les commentaires du fichier PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Ajouter une annotation via l'API de l'application Android" %}}

1. Ajouter une référence de bibliothèque au projet Android
1. Créer un objet de classe Document
1. Ajoutez la nouvelle page et le contenu en utilisant getPages().add()
1. Utilisez getPages().get_Item(Index) de la classe TextAnnotation
1. Définissez les annotations pertinentes telles que le titre, le sujet, le contenu, etc.
1. Utilisez getAnnotations().add pour ajouter les annotations
1. Appelez la méthode save pour enregistrer le fichier avec les commentaires ajoutés
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Ajouter une annotation PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Développer l'application Android d'annotation de documents PDF</h2>

Besoin de développer une application mobile ou un utilitaire d'annotation PDF pour fournir des commentaires, faire des suggestions ou collaborer avec d'autres sur le document ?Avec [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/fr/android-java/), une API enfant de [Aspose.Total for Android via Java](https://products.aspose.com/total/fr/android-java/), tout développeur Android peut intégrer le code API ci-dessus dans son application d'annotation de documents.La puissante bibliothèque Android permet de programmer n'importe quelle solution d'annotation de documents.De plus, il peut prendre en charge de nombreux formats populaires, notamment le format PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque Android pour annoter les fichiers PDF" %}}

- Nous hébergeons nos packages Java en [Dépôts Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java est un fichier JAR commun contenant du byte-code.
- Suivez le [instructions étape par étape](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) pour savoir comment installer Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

- API Android 31 et 32
- Android 4.0 et supérieur
- Outils Android Studio et SDK

<br />
Pour plus de détails sur les dépendances de packages optionnels, telles que JogAmp JOGL, le moteur de polices Harfbuzz, Java Advanced Imaging JAI, veuillez vous référer à [Documentation produit](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}