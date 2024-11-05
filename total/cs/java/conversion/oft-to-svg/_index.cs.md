---
title: Export OFT do SVG přes Java
description: Java API pro převod OFT do SVG bez použití Microsoft Word nebo Outlook
url_ignore: /cs/java/conversion/oft-to-svg/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: SVG
otherformats: DOT WORDML JPEG DOTX EMF TIFF MD DOCM PNG ODT DOCX TEXT OTT GIF DOC EPUB PDF DOTM PS RTF FLATOPC XPS SVG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro vykreslení OFT do SVG" h2="Exportujte OFT do SVG pomocí on premise Java API bez použití jakýchkoli závislostí třetích stran" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-mailová konverze je výkonná funkce, kterou mohou vývojáři Java integrovat do jakékoli Java J2SE, J2EE, J2ME aplikace prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/). Pomocí dvou rozhraní API v rámci balíčku můžete převést e-mailovou adresu OFT na SVG bez jakýchkoli závislostí třetích stran. Za prvé, můžete použít Oft Manipulation API [Aspose.Oft for Java](https://products.aspose.com/email/java/) k převodu formátu souboru OFT do HTML. Za druhé, můžete vykreslit HTML do SVG pomocí Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést OFT na SVG" %}}
1. Otevřete soubor OFT pomocí třídy [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Převeďte OFT na HTML pomocí [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metoda
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu SVG pomocí [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) a nastavte SVG jako SaveFormat
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