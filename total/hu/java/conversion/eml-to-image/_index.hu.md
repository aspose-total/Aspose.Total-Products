---
title: Exportálja az EML-t IMAGE-be Java-n keresztül
description: Java API az EML IMAGE-vé konvertálásához Microsoft Word vagy Outlook használata nélkül
url_ignore: /hu/java/conversion/eml-to-image/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: PS PDF MD EPUB TEXT DOTM IMAGE PCL TIFF FLATOPC SVG GIF PNG EMF RTF XPS DOCM ODT DOC DOT WORDML DOCX JPEG DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API az EML rendereléséhez IMAGE-be" h2="Exportálja az EML e-mail-címet IMAGE-be a helyszíni Java API használatával, harmadik féltől származó függőségek használata nélkül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Az e-mail konvertálás egy hatékony funkció, amelyet a Java fejlesztők integrálhatnak bármely Java J2SE, J2EE, J2ME alkalmazásba az [Aspose.Total for Java](https://products.aspose.com/total/java/). A csomagon belüli két API használatával az EML e-mail címet IMAGE-vé alakíthatja harmadik féltől való függőség nélkül. Először is használhatja az Eml Manipulation API-t [Aspose.Email for Java](https://products.aspose.com/email/java/) az EML fájlformátum HTML-lé alakításához. Másodszor, a HTML-t IMAGE-be renderelheti a Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) használatával.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet az EML-t IMAGE-vé konvertálni" %}}
1. Nyissa meg az EML fájlt a [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) osztály használatával
2. Alakítsa át az EML e-mail-címet HTML-vé a [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) segítségével)) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot IMAGE formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) segítségével)) metódust, és állítsa be a IMAGE-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://releases.aspose.com/total/java/) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
Az **EML** átalakítása **általános képformátumokba** (BMP, PNG, JPEG, TIFF stb.) rögzíti az e-mail teljes vizuális reprezentációját egy statikus képként.

## ✅ Fő felhasználási esetek
- **Univerzális megtekintés**: Az e-mail tartalmának megtekintése e-mail kliens nélkül is.
- **Digitális bizonyíték**: Az e-mail pontos másolatának megőrzése jogi és szabályozási célokra.
- **Könnyű megosztás**: Az e-mailek képként történő elküldése üzenetküldőkön vagy közösségi platformokon keresztül.
- **Képzés és dokumentáció**: Teljes e-mail vizuális beillesztése felhasználói kézikönyvekbe.

## ⚙️ Automatizálási forgatókönyvek
- **Több formátumú exportálás**: Egy EML átalakítása több képformátummá automatikusan.
- **E-mail rögzítő rendszerek**: Az összes beérkező e-mail tárolása kép pillanatképek formájában.
- **Nyomozati munkafolyamatok**: Képformátumok szabványosítása nyomozásokhoz.
- **Archiválási csatornák**: Hosszú távú megőrzés automatizálása képtárakban.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}