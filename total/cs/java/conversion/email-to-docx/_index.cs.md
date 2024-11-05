---
title: Export EMAIL do DOCX přes Java
description: Java API pro převod EMAIL do DOCX bez použití Microsoft Word nebo Outlook
url_ignore: /cs/java/conversion/email-to-docx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: PCL OTT RTF PDF WORDML TIFF DOCX MD EMF JPEG DOTX DOT FLATOPC XPS GIF DOC EPUB TEXT DOTM SVG PNG PS DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro vykreslení EMAIL do DOCX" h2="Exportujte EMAIL do DOCX pomocí on premise Java API bez použití jakýchkoli závislostí třetích stran" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailová konverze je výkonná funkce, kterou mohou vývojáři Java integrovat do jakékoli Java J2SE, J2EE, J2ME aplikace prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/). Pomocí dvou rozhraní API v rámci balíčku můžete převést e-mailovou adresu EMAIL na DOCX bez jakýchkoli závislostí třetích stran. Za prvé, můžete použít Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) k převodu formátu souboru EMAIL do HTML. Za druhé, můžete vykreslit HTML do DOCX pomocí Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést EMAIL na DOCX" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu DOCX pomocí [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte DOCX jako SaveFormat
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