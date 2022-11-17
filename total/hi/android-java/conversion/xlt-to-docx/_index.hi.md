---
title: Android में XLT को DOCX में निर्यात करें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना सीएसवी को डीओसी में कनवर्ट करने के लिए एंड्रॉइड एपीआई

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOCX
otherformats: WORD POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड पर सीएसवी को डीओसी को प्रस्तुत करें" h2="Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना अपने Android एप्लिकेशन में XLT को DOCX में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) शक्तिशाली फाइल ऑटोमेशन एपीआई का एक पैकेज है। इसके दो एपीआई का उपयोग करके, आप अपने एंड्रॉइड एप्लिकेशन के अंदर सीएसवी को डीओसी रूपांतरण सुविधा में एकीकृत कर सकते हैं। पहले चरण में आप [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) का उपयोग करके PDF में XLT निर्यात कर सकते हैं। उसके बाद, [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) का उपयोग करके, आप PDF को DOCX में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीएसवी को डीओसी में निर्यात करने के लिए एंड्रॉइड एपीआई" %}}
1. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके XLT फ़ाइल खोलें
2. XLT को PDF में बदलें और SaveFormat को AUTO पर सेट करें
3. रूपांतरित पीडीएफ फाइल को [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके लोड करें
4. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions का उपयोग करके दस्तावेज़ को DOCX प्रारूप में सहेजें -) तरीका
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) और [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells) इंस्टॉल करें /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) आपके अनुप्रयोगों में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में XLT फ़ाइल से कस्टम गुण निकालें" %}}Document
दस्तावेज़ रूपांतरण के अलावा, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) कई अन्य सुविधाएं भी प्रदान करता है। रूपांतरण प्रक्रिया से पहले, आप XLT दस्तावेज़ के कस्टम गुण निकाल सकते हैं। कस्टम गुण निकालने के लिए, [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) विधि को कॉल करें और इसका नाम दें दस्तावेज़ संपत्ति को हटाया जाना है।
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/xlt-to-word/" name="XLT प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/xlt-to-powerpoint/" name="XLT प्रति POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/xlt-to-pptx/" name="XLT प्रति PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/xlt-to-docx/" name="XLT प्रति DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}