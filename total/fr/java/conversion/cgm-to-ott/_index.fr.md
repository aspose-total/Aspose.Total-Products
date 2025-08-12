---
title: API Java pour exporter CGM vers OTT
description: Convertir CGM en OTT à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: WORDML RTF ODT DOT DOTM XAMLFLOW PCL MHTML DOTX OTT MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez CGM en OTT via Java" h2="API Java sur site pour rendre CGM en OTT sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir CGM en OTT en utilisant deux étapes simples. Vous devez d'abord rendre le fichier CGM au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en OTT. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir CGM en OTT" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format OTT à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez OTT en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de CGM en OTT, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le CGM à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document CGM protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier OTT, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre OTT dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertissez les fichiers **Computer Graphics Metafile (CGM)** au format **OTT (modèle de texte OpenDocument)** est essentiel pour les organisations utilisant des environnements open source et compatibles avec ODF. Sur les plateformes basées sur **Java**, cette conversion permet d'intégrer des diagrammes CGM et des visuels techniques dans des modèles réutilisables compatibles avec LibreOffice et d'autres éditeurs OpenDocument. Les modèles OTT garantissent une cohérence de conception, facilitent l'édition collaborative et rationalisent la génération de rapports normalisés au sein d'équipes distribuées tout en maintenant des normes ouvertes pour l'interopérabilité.


## ✅ Cas d'utilisation clés

- **Génération de rapports conforme à l'ODF**  
  Créez des rapports basés sur des normes où les visuels CGM s'intègrent parfaitement avec le contenu structuré OpenDocument.

- **Édition collaborative de documents**  
  Stockez des modèles OTT améliorés par des CGM dans des référentiels partagés pour une édition multi-utilisateurs en temps réel sur des plateformes open source.


## ⚙️ Scénarios d'automatisation

- **Automatisation Java via un convertisseur**  
  Utilisez les API Aspose dans les workflows Java pour convertir des fichiers CGM en modèles OTT en vue d'un déploiement automatisé.

- **Intégrations SDK LibreOffice**  
  Exploitez le SDK LibreOffice dans les applications Java pour peupler et personnaliser des modèles OTT basés sur des CGM.

- **Systèmes ETL pour la création de documents en masse**  
  Intégrez la conversion CGM en OTT dans des pipelines ETL basés sur Java pour la génération de documents à grande échelle basée sur des modèles.

- **Plateformes d'entreprise open source**  
  Déployez des modèles OTT avec des diagrammes CGM intégrés dans des systèmes de gestion de contenu et d'automatisation de documents alimentés par Java.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}