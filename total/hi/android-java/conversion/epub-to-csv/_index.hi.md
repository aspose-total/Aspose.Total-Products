---
title: जावा के माध्यम से एंड्रॉइड में सीजीएम को सीएसवी में कनवर्ट करें
description: माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना जावा एपीआई के माध्यम से एंड्रॉइड में सीएसवी को सीजीएम प्रस्तुत करें

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: CSV
otherformats: TSV XLT ODS FODS XLTX SXC TXT XLTM EXCEL DIF XLAM XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड में सीएसवी को सीजीएम प्रस्तुत करें" h2="Microsoft<sup>&reg;</sup> Excel या Adobe<sup>&reg;</sup> Acrobat Reader की आवश्यकता के बिना Android अनुप्रयोगों में EPUB को CSV में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप दो चरणों की प्रक्रिया में अपने एंड्रॉइड एप्लिकेशन के भीतर सीजीएम से सीएसवी रूपांतरण सुविधा को एकीकृत कर सकते हैं। सबसे पहले, [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) का उपयोग करके आप EPUB को XLSX में गुप्त कर सकते हैं। दूसरे, आप पावरफुल स्प्रेडशीट प्रोसेसिंग एपीआई [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) का इस्तेमाल करके XLSX को CSV में बदल सकते हैं। दोनों API [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) उत्पाद परिवार के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीएसवी को सीजीएम प्रस्तुत करने के लिए एंड्रॉइड एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) का उपयोग करके EPUB को XLSX में बदलें। ) तरीका
3. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके XLSX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) का उपयोग करके दस्तावेज़ को CSV प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) और [Aspose.Cells for Android via Java](https://docs.aspose.com/cells) इंस्टॉल करें /java/aspose-cells-for-android-via-java-installation/) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में EPUB फ़ाइल का XMP मेटाडेटा प्राप्त करें" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) आपको EPUB फ़ाइल के XMP मेटाडेटा तक पहुंचने की अनुमति देता है। मेटाडेटा प्राप्त करने के लिए, एक [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) ऑब्जेक्ट बनाएं और इनपुट EPUB फ़ाइल खोलें और [getMetadata()] का उपयोग करें (https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) संपत्ति मेटाडेटा प्राप्त करने के लिए।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में CSV दस्तावेज़ को सुरक्षित रखें" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) आपकी ज़रूरतों के आधार पर आपकी CSV फ़ाइल की सुरक्षा का समर्थन करता है। अपने दस्तावेज़ की सुरक्षा के लिए आप [workbook] की [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) विधि का उपयोग कर सकते हैं। https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) वर्ग।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-csv.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-tsv/" name="EPUB प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xlt/" name="EPUB प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-ods/" name="EPUB प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-fods/" name="EPUB प्रति FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xltx/" name="EPUB प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-sxc/" name="EPUB प्रति SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-txt/" name="EPUB प्रति TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xltm/" name="EPUB प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-excel/" name="EPUB प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-dif/" name="EPUB प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xlam/" name="EPUB प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xlsb/" name="EPUB प्रति XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}