---
title: API Java pour exporter CGM vers MHTML
description: Convertir CGM en MHTML à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: XAMLFLOW DOTX WORDML OTT FLATOPC DOTM PCL ODT PS MHTML MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez CGM en MHTML via Java" h2="API Java sur site pour rendre CGM en MHTML sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir CGM en MHTML en utilisant deux étapes simples. Vous devez d'abord rendre le fichier CGM au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en MHTML. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir CGM en MHTML" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format MHTML à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez MHTML en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de CGM en MHTML, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le CGM à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document CGM protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier MHTML, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre MHTML dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertir les fichiers **Computer Graphics Metafile (CGM)** au format **MHTML (MIME HTML)** est essentiel pour préserver des documents d'ingénierie et techniques complexes avec des graphiques intégrés dans un seul fichier autonome. Dans les systèmes d'archivage web basés sur Java, cette conversion permet aux organisations de stocker des documents complets, y compris des visuels CGM, des styles et des ressources, dans une archive portable adaptée à la visualisation hors ligne et au déploiement en intranet. MHTML garantit que les spécifications de conception, les rapports et les dessins restent intacts pour une accessibilité et une distribution à long terme.

---

## ✅ Cas d'utilisation clés

- **Regroupement de documents d'ingénierie avec des graphiques intégrés**  
  Regroupez des diagrammes CGM et des contenus connexes dans MHTML pour des enregistrements techniques cohérents et autonomes.

- **Visualisation hors ligne dans les portails intranet**  
  Fournissez des documents améliorés par CGM au format MHTML pour un accès hors ligne fluide à travers les réseaux d'entreprise.

- **Archivage des spécifications de conception**  
  Stockez des versions MHTML des spécifications basées sur CGM pour la conformité, la référence et la documentation de projet.

---

## ⚙️ Scénarios d'automatisation

- **Bibliothèques Java avec prise en charge de MHTML**  
  Utilisez des API comme **Aspose.Words for Java** ou des exportateurs Java personnalisés pour générer des fichiers MHTML à partir de documents basés sur CGM.

- **Outils d'exportation basés sur le web**  
  Intégrez la conversion de CGM en MHTML dans des applications web Java pour un regroupement instantané de fichiers.

- **Flux de travail de conversion basés sur Servlet**  
  Déployez des servlets Java qui traitent les entrées CGM et produisent des archives MHTML pour une distribution sécurisée.

- **Pipelines d'archivage automatisés**  
  Incluez des étapes de conversion de CGM en MHTML dans des systèmes de gestion de documents ou d'ETL pilotés par Java pour des archivages planifiés.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}