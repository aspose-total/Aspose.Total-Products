---
title: Export EML do PDF přes Java
description: Java API pro převod EML do PDF bez použití Microsoft Word nebo Outlook
url_ignore: /cs/java/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOTM EMF MD PCL RTF EPUB OTT PS ODT SVG GIF DOCM TIFF XPS FLATOPC DOT TEXT DOC PDF WORDML DOCX PNG JPEG DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro vykreslení EML do PDF" h2="Exportujte EML do PDF pomocí on premise Java API bez použití jakýchkoli závislostí třetích stran" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailová konverze je výkonná funkce, kterou mohou vývojáři Java integrovat do jakékoli Java J2SE, J2EE, J2ME aplikace prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/). Pomocí dvou rozhraní API v rámci balíčku můžete převést e-mailovou adresu EML na PDF bez jakýchkoli závislostí třetích stran. Za prvé, můžete použít Eml Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) k převodu formátu souboru EML do HTML. Za druhé, můžete vykreslit HTML do PDF pomocí Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést EML na PDF" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu PDF pomocí [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte PDF jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-pdf.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
**PDF** je nejuniverzálnější formát dokumentu. Převod **EML na PDF** zachovává rozložení, přílohy a formátování pro snadné sdílení.

## ✅ Klíčové použití
- Archivace e-mailů jako univerzálně přístupných PDF.
- Ukládání e-mailů připravených pro dodržování předpisů.
- Bezpečné sdílení obchodní korespondence.

## ⚙️ Scénáře automatizace
- Automatizovaná archivace PDF pro firemní e-maily.
- Převod podpůrných tiketů z e-mailu do PDF.
- Hromadná migrace záloh e-mailů do repozitářů PDF.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}