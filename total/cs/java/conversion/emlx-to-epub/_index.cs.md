---
title: Export EMLX do EPUB přes Java
description: Java API pro převod EMLX do EPUB bez použití Microsoft Word nebo Outlook
url_ignore: /cs/java/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: PNG XPS FLATOPC MD TIFF DOTX EMF PDF DOTM EPUB RTF DOCM GIF TEXT SVG JPEG WORDML PS DOC DOT ODT OTT PCL DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro vykreslení EMLX do EPUB" h2="Exportujte EMLX do EPUB pomocí on premise Java API bez použití jakýchkoli závislostí třetích stran" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailová konverze je výkonná funkce, kterou mohou vývojáři Java integrovat do jakékoli Java J2SE, J2EE, J2ME aplikace prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/). Pomocí dvou rozhraní API v rámci balíčku můžete převést e-mailovou adresu EMLX na EPUB bez jakýchkoli závislostí třetích stran. Za prvé, můžete použít Emlx Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) k převodu formátu souboru EMLX do HTML. Za druhé, můžete vykreslit HTML do EPUB pomocí Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést EMLX na EPUB" %}}
1. Otevřete soubor EMLX pomocí třídy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Převeďte EMLX na HTML pomocí [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu EPUB pomocí [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte EPUB jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Musíte použít Aspose.Total pro Javu přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}