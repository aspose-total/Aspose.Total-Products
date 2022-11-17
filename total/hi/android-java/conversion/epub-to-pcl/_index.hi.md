---
title: डीओसीएम को सीजीएम प्रस्तुत करने के लिए एंड्रॉइड एपीआई
description: जावा एपीआई के माध्यम से एंड्रॉइड के माध्यम से सीजीएम को डीओसीएम में बदलना

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PCL
otherformats: MHTML DOTX ODT MARKDOWN WORDML DOCM PS FLATOPC DOT XAMLFLOW DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड पर डीओसीएम को सीजीएम प्रस्तुत करें" h2="बिना किसी सॉफ्टवेयर को इंस्टॉल किए मोबाइल ऐप में EPUB को PCL में बदलें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) पैकेज के दो API का उपयोग करके अपने मोबाइल ऐप्स में EPUB को PCL रूपांतरण सुविधा में एकीकृत कर सकते हैं। सबसे पहले आपको [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) का उपयोग करके EPUB फ़ाइल को DOC में कनवर्ट करना होगा। दूसरे, वर्ड प्रोसेसिंग एपीआई [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके, आप PCL को DOC रेंडर कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से एंड्रॉइड पर सीजीएम को डीओसीएम में कनवर्ट करें" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) का उपयोग करके EPUB को DOC में बदलें। ) तरीका
3. Aspose.Words के [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके DOC फ़ाइल लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को PCL प्रारूप में सहेजें और PCL सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) और [Aspose.Words for Android via Java](https://docs.aspose.com/words) इंस्टॉल करें /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PCL
outputDocument.save("output.pcl", SaveFormat.PCL);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android पर EPUB फ़ाइल जानकारी प्राप्त करें" %}}
सीजीएम को डीओसीएम में बदलने से पहले, आपको लेखक, निर्माण तिथि, कीवर्ड, संशोधित तिथि, विषय और शीर्षक सहित दस्तावेज़ के बारे में जानकारी की आवश्यकता हो सकती है। यह जानकारी रूपांतरण प्रक्रिया के लिए निर्णय लेने में सहायक होती है। शक्तिशाली [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API का उपयोग करके, आप यह सब प्राप्त कर सकते हैं। EPUB फ़ाइल के बारे में फ़ाइल-विशिष्ट जानकारी प्राप्त करने के लिए, पहले [getInfo](https:// का उपयोग करके [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) ऑब्जेक्ट प्राप्त करें। Reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) विधि। एक बार DocumentInfo ऑब्जेक्ट पुनर्प्राप्त हो जाने के बाद, आप अलग-अलग गुणों के मान प्राप्त कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB document
Document doc = new Document("template.epub");
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

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में डीओसीएम दस्तावेज़ में एंडनोट्स डालें" %}}
दस्तावेज़ रूपांतरण के अलावा, आप [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API का उपयोग करके अपने Android एप्लिकेशन के अंदर अन्य सुविधाओं का एक समूह भी जोड़ सकते हैं। उस सुविधा में से एक डीओसीएम दस्तावेज़ में एंडनोट्स और नंबरिंग डालना है। यदि आप किसी PCL दस्तावेज़ में फ़ुटनोट या एंडनोट सम्मिलित करना चाहते हैं, तो कृपया DocumentBuilder.InsertFootnote पद्धति का उपयोग करें। यह विधि दस्तावेज़ में एक फुटनोट या एंडनोट सम्मिलित करती है। EndnoteOptions और FootnoteOptions वर्ग फ़ुटनोट और एंडनोट के लिए नंबरिंग विकल्पों का प्रतिनिधित्व करते हैं।
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
doc.save("output.pcl", SaveFormat.PCL);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-mhtml/" name="EPUB प्रति MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-dotx/" name="EPUB प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-odt/" name="EPUB प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-markdown/" name="EPUB प्रति MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-wordml/" name="EPUB प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-pcl/" name="EPUB प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-ps/" name="EPUB प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-flatopc/" name="EPUB प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-dot/" name="EPUB प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xamlflow/" name="EPUB प्रति XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-dotm/" name="EPUB प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-rtf/" name="EPUB प्रति RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}