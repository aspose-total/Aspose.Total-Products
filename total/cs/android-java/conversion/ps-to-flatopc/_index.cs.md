---
title: Android API pro vykreslení PS do FLATOPC
description: Transformujte PS na FLATOPC přes Android přes Java API

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: FLAT_OPC
otherformats: OTT DOCM MARKDOWN DOT WORDML XAMLFLOW DOTX DOTM MHTML PCL ODT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslete PS do FLATOPC na Androidu přes Java" h2="Převeďte PS na FLATOPC v mobilních aplikacích bez instalace jakéhokoli softwaru" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu PS na FLATOPC můžete integrovat do svých mobilních aplikací pomocí dvou rozhraní API balíčku [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Nejprve musíte převést soubor PS na DOC pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Za druhé, pomocí rozhraní API pro zpracování textu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) můžete vykreslit DOC do FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte PS na FLATOPC na Androidu přes Java" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte PS na DOC pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu FLATOPC pomocí metody [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte FLATOPC jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte informace o souborech PS na Androidu prostřednictvím Java" %}}
Před převodem PS na FLATOPC možná budete potřebovat informace o dokumentu včetně autora, data vytvoření, klíčových slov, data úpravy, předmětu a názvu. Tyto informace jsou užitečné pro rozhodování o procesu konverze. Pomocí výkonného [Aspose.PDF pro Android přes Java](https://docs.aspose.com/pdf/androidjava/) API můžete získat vše. Chcete-li získat specifické informace o souboru PS, nejprve získejte objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) pomocí [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Jakmile je objekt DocumentInfo načten, můžete získat hodnoty jednotlivých vlastností.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS document
Document doc = new Document("template.ps");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vložte vysvětlivky do dokumentu FLATOPC v systému Android přes Java" %}}
Kromě převodu dokumentů můžete do aplikací pro Android přidat také spoustu dalších funkcí pomocí [Aspose.Words pro Android přes Java](https://products.aspose.com/words/androidjava/) API. Jednou z těchto funkcí je vkládání vysvětlivek a číslování do dokumentu FLATOPC. Pokud chcete vložit poznámku pod čarou nebo vysvětlivku do dokumentu FLATOPC, použijte metodu DocumentBuilder.InsertFootnote. Tato metoda vloží do dokumentu poznámku pod čarou nebo vysvětlivku. Třídy EndnoteOptions a FootnoteOptions představují možnosti číslování poznámek pod čarou a vysvětlivky.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-ott/" name="PS Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-flatopc/" name="PS Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-markdown/" name="PS Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-dot/" name="PS Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-wordml/" name="PS Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-xamlflow/" name="PS Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-dotx/" name="PS Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-dotm/" name="PS Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-mhtml/" name="PS Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-pcl/" name="PS Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-odt/" name="PS Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/ps-to-rtf/" name="PS Na RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}