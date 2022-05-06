---
title: जावा के माध्यम से जेएसओएन प्रारूप को एपीएनजी में कनवर्ट करें
description: Microsoft PowerPoint का उपयोग किए बिना जावा में JSON को JPEG2000 में पार्स करें
url_ignore: /hi/java/conversion/json-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: PSD SVGZ TGA WMZ IMAGE JPEG2000 DICOM DXF EMZ WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से जेएसओएन प्रारूप को एपीएनजी में कनवर्ट करें" h2="जावा एपीआई किसी भी जावा J2SE, J2EE, J2ME अनुप्रयोगों के भीतर JSON प्रारूप को JPEG2000 में पार्स करने के लिए" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके, आप दो आसान चरणों में किसी भी जावा एप्लिकेशन में JSON प्रारूप को JPEG2000 में बदल सकते हैं। सबसे पहले, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप JSON को JPEG में पार्स कर सकते हैं। उसके बाद, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) का उपयोग करके, आप JPEG को JPEG2000 में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से जेएसओएन प्रारूप को एपीएनजी में कनवर्ट करें" %}}
1. एक नया [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) ऑब्जेक्ट बनाएं और JSON फाइल खोलें
2. [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) का उपयोग करके JSON को JPEG के रूप में सेव करें। ) तरीका
3. [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) वर्ग का उपयोग करके JPEG दस्तावेज़ लोड करें
4. [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase का उपयोग करके दस्तावेज़ को JPEG2000 प्रारूप में सहेजें-) तरीका
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
इसके अलावा, एपीआई आपको निर्दिष्ट लेआउट विकल्पों के साथ JSON को JPEG2000 में पार्स करने की अनुमति देता है। लेआउट विकल्पों को निर्दिष्ट करने के लिए, आप [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) वर्ग का उपयोग कर सकते हैं। यह आपको एक सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में बदलने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से लेआउट सेट करें और JSON फॉर्मेट को JPEG2000 में बदलें" %}}
एपीआई का उपयोग करके, आप अपने एपीएनजी दस्तावेज़ में वॉटरमार्क के साथ JSON को JPEG2000 में भी बदल सकते हैं। वॉटरमार्क जोड़ने के लिए आप पहले JSON को JPEG में बदल सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) क्लास का इस्तेमाल करके इमेज फ़ाइल लोड करें, [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) क्लास और इमेज ऑब्जेक्ट के साथ इसे इनिशियलाइज़ करें, एक नया बनाएं [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) ऑब्जेक्ट और अनुवाद और रूपांतरण को वांछित कोण पर सेट करें और [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics.drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) विधि। अपनी छवि में वॉटरमार्क जोड़ने के बाद, आप JPEG को JPEG2000 प्रारूप के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-jpeg2000/" name="JSON सेवा JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-emz/" name="JSON सेवा EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-psd/" name="JSON सेवा PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-wmf/" name="JSON सेवा WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-wmz/" name="JSON सेवा WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dxf/" name="JSON सेवा DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-image/" name="JSON सेवा IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-svgz/" name="JSON सेवा SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dicom/" name="JSON सेवा DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-tga/" name="JSON सेवा TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}