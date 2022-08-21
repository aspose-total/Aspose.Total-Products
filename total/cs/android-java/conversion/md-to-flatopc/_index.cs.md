---
title: Android API pro vykreslení MD do FLATOPC
description: Transformujte MD na FLATOPC přes Android přes Java API
url: /cs/android-java/conversion/md-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: FLAT_OPC
otherformats: XAMLFLOW OTT DOT DOTX PS WORDML ODT PCL DOCM MARKDOWN DOTM MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslete MD do FLATOPC na Androidu přes Java" h2="Převeďte MD na FLATOPC v mobilních aplikacích bez instalace jakéhokoli softwaru" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu MD na FLATOPC můžete integrovat do svých mobilních aplikací pomocí dvou rozhraní API balíčku [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Nejprve musíte převést soubor MD na DOC pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Za druhé, pomocí rozhraní API pro zpracování textu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) můžete vykreslit DOC do FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte MD na FLATOPC na Androidu přes Java" %}}
1. Otevřete soubor MD pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte MD na DOC pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu FLATOPC pomocí metody [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte FLATOPC jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte informace o souborech MD na Androidu prostřednictvím Java" %}}
Před převodem MD na FLATOPC možná budete potřebovat informace o dokumentu včetně autora, data vytvoření, klíčových slov, data úpravy, předmětu a názvu. Tyto informace jsou užitečné pro rozhodování o procesu konverze. Pomocí výkonného [Aspose.PDF pro Android přes Java](https://docs.aspose.com/pdf/androidjava/) API můžete získat vše. Chcete-li získat specifické informace o souboru MD, nejprve získejte objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) pomocí [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Jakmile je objekt DocumentInfo načten, můžete získat hodnoty jednotlivých vlastností.
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD document
Document doc = new Document("template.md");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-xamlflow/" name="MD Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-ott/" name="MD Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-dot/" name="MD Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-dotx/" name="MD Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-ps/" name="MD Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-wordml/" name="MD Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-odt/" name="MD Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-pcl/" name="MD Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-flatopc/" name="MD Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-markdown/" name="MD Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-dotm/" name="MD Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/md-to-mhtml/" name="MD Na MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}