---
title: Supprimez l'annotation DOCX en ligne ou gérez les annotations à l'aide des applications mobiles Android
description: supprimez gratuitement les commentaires du fichier DOCX via l'application en ligne.Code API Android pour gérer les commentaires des fichiers DOCX.

family: total
platformtag: Android
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Effacer les commentaires du document DOCX en ligne ou les gérer via les applications Android" h2="Développez une puissante application utilitaire d’annotation de documents DOCX basée sur Android.Code répertorié pour la gestion des commentaires du fichier DOCX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer les annotations DOCX en ligne" %}}

1. Importez le fichier DOCX pour supprimer les commentaires en le téléchargeant
1. Faites-le en cliquant dans la zone de dépôt via glisser-déposer de l'application d'annotation
1. En fonction de la taille du fichier DOCX et de la vitesse d'Internet, attendez quelques secondes
1. Cliquez sur le bouton "Supprimer" pour effacer les commentaires
1. Téléchargez le fichier instantanément

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Supprimer les commentaires du document DOCX via l'application Android" %}}

1. Ajouter une référence de bibliothèque au projet Android
1. Charger un document via un objet de classe Document
1. Obtenez tous les commentaires de tous les nœuds en utilisant [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) et NodeType.COMMENT
1. Invoquez la méthode [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) pour supprimer tous les commentaires
1. Appelez la méthode save pour enregistrer le fichier.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Supprimer les commentaires du fichier DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Supprimer et ajouter une réponse au commentaire DOCX" %}}

1. Ajouter une référence de bibliothèque au projet Android
1. Charger un document via un objet de classe Document
1. Obtenir des commentaires en utilisant getChild
1. Utilisez [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) pour supprimer la réponse spécifiée à ce commentaire
1. Utilisez [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) pour ajouter une réponse à ce commentaire
1. Appelez la méthode save pour enregistrer le fichier

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ajouter des commentaires via l'application Android" %}}

1. Ajouter une référence de bibliothèque au projet Android
1. Créer un objet de classe Document
1. Utilisez [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) pour créer le commentaire
1. Utilisez getParagraphs().add et getFirstParagraph().getRuns().add
1. Appelez la méthode save pour enregistrer le fichier with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Supprimer et ajouter une réponse au commentaire du fichier DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Code : ajout de commentaires" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Développer l'application Android d'annotation de documents DOCX</h2>

Besoin de développer une application mobile ou un utilitaire d'annotation DOCX pour fournir des commentaires, faire des suggestions ou collaborer avec d'autres sur le document ?Avec [Aspose.Words for Android via Java](https://products.aspose.com/words/fr/android-java/), une API enfant de [Aspose.Total for Android via Java](https://products.aspose.com/total/fr/android-java/), tout développeur Android peut intégrer le code API ci-dessus dans son application d'annotation de documents.La puissante bibliothèque Android permet de programmer n'importe quelle solution d'annotation de documents.De plus, il peut prendre en charge de nombreux formats populaires, notamment le format DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Bibliothèque Android pour annoter les fichiers DOCX" %}}

- Nous hébergeons nos packages Java en [Dépôts Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java est un fichier JAR commun contenant du byte-code.
- Suivez le [instructions étape par étape](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) pour savoir comment installer Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

- Java SE 7 et les versions Java plus récentes sont prises en charge.
- Package séparé pour Java SE 6 au cas où l'on serait obligé d'utiliser un JRE obsolète.
- Le package Java est multiplateforme et fonctionne sur tous les systèmes d'exploitation avec implémentation JVM.
- Les systèmes d'exploitation incluent Microsoft Windows, Linux, macOS, Android et iOS.

<br />
Pour plus de détails sur les dépendances de packages optionnels, telles que JogAmp JOGL, le moteur de polices Harfbuzz, Java Advanced Imaging JAI, veuillez vous référer à [Documentation produit](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}