---
title: Android API pro vykreslení CGM do DOT
description: Transformujte CGM na DOT přes Android přes Java API

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: DOT
otherformats: MHTML XAMLFLOW ODT DOTM MARKDOWN RTF PS DOCM PCL OTT FLATOPC WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslete CGM do DOT na Androidu přes Java" h2="Převeďte CGM na DOT v mobilních aplikacích bez instalace jakéhokoli softwaru" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu CGM na DOT můžete integrovat do svých mobilních aplikací pomocí dvou rozhraní API balíčku [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Nejprve musíte převést soubor CGM na DOC pomocí [Aspose.PDF pro Android přes Java](https://products.aspose.com/pdf/android-java/). Za druhé, pomocí rozhraní API pro zpracování textu [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) můžete vykreslit DOC do DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte CGM na DOT na Androidu přes Java" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte CGM na DOC pomocí [uložit](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metoda
3. Načtěte soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) třídy Aspose.Words
4. Uložte dokument do formátu DOT pomocí metody [uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) a nastavte DOT jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat přes Javu přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) a [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ve vašich aplikacích.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOT
outputDocument.save("output.dot", SaveFormat.DOT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte informace o souborech CGM na Androidu prostřednictvím Java" %}}
Před převodem CGM na DOT možná budete potřebovat informace o dokumentu včetně autora, data vytvoření, klíčových slov, data úpravy, předmětu a názvu. Tyto informace jsou užitečné pro rozhodování o procesu konverze. Pomocí výkonného [Aspose.PDF pro Android přes Java](https://docs.aspose.com/pdf/androidjava/) API můžete získat vše. Chcete-li získat specifické informace o souboru CGM, nejprve získejte objekt [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) pomocí [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--). Jakmile je objekt DocumentInfo načten, můžete získat hodnoty jednotlivých vlastností.
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM document
Document doc = new Document("template.cgm");
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

{{% blocks/products/pf/feature-page-section  h2="Vložte vysvětlivky do dokumentu DOT v systému Android přes Java" %}}
Kromě převodu dokumentů můžete do aplikací pro Android přidat také spoustu dalších funkcí pomocí [Aspose.Words pro Android přes Java](https://products.aspose.com/words/androidjava/) API. Jednou z těchto funkcí je vkládání vysvětlivek a číslování do dokumentu DOT. Pokud chcete vložit poznámku pod čarou nebo vysvětlivku do dokumentu DOT, použijte metodu DocumentBuilder.InsertFootnote. Tato metoda vloží do dokumentu poznámku pod čarou nebo vysvětlivku. Třídy EndnoteOptions a FootnoteOptions představují možnosti číslování poznámek pod čarou a vysvětlivky.
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
doc.save("output.dot", SaveFormat.DOT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-mhtml/" name="CGM Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-xamlflow/" name="CGM Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-odt/" name="CGM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-dotm/" name="CGM Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-markdown/" name="CGM Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-rtf/" name="CGM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-ps/" name="CGM Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-dot/" name="CGM Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-pcl/" name="CGM Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-ott/" name="CGM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-flatopc/" name="CGM Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/cgm-to-wordml/" name="CGM Na WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}