---
title: XLSX एनोटेशन को ऑनलाइन हटाएं या Android मोबाइल ऐप्स का उपयोग करके एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से XLSX फ़ाइल से टिप्पणियां निःशुल्क हटाएं।XLSX फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए Android API कोड.

family: total
platformtag: Android
feature: Annotate
informat: XLSX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="XLSX दस्तावेज़ से टिप्पणियाँ ऑनलाइन साफ़ करें या Android ऐप्स के माध्यम से प्रबंधित करें" h2="शक्तिशाली एंड्रॉइड आधारित XLSX दस्तावेज़ एनोटेशन उपयोगिता अनुप्रयोग विकसित करें।XLSX फ़ाइल की टिप्पणियों के प्रबंधन के लिए सूचीबद्ध कोड." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX एनोटेशन ऑनलाइन हटाएं" %}}

1. XLSX फ़ाइल को अपलोड करके टिप्पणियाँ हटाने के लिए आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. XLSX फ़ाइल के आकार और इंटरनेट की गति के आधार पर कुछ सेकंड तक प्रतीक्षा करें
1. टिप्पणियाँ हटाने के लिए 'हटाएँ' बटन पर क्लिक करें
1. फ़ाइल को तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप API के माध्यम से XLSX दस्तावेज़ टिप्पणियाँ हटाएँ" %}}

1. Android प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. वर्कबुक क्लास ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. विशिष्ट वर्कशीट का चयन करें
1. [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--) का उपयोग करके सभी टिप्पणियाँ प्राप्त करें
1. getThreadedComments के माध्यम से सभी थ्रेडेड टिप्पणियाँ प्राप्त करें
1. टिप्पणियों और लेखकों को क्रमशः हटाने के लिए removeAt का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : XLSX दस्तावेज़ से टिप्पणियाँ हटाएँ" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="थ्रेडेड XLSX टिप्पणियाँ अपडेट करें" %}}

1. वर्कबुक क्लास ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. विशिष्ट वर्कशीट प्राप्त करें
1. getComments().getThreadedComments(Index).get(Index) का उपयोग करके थ्रेडेड टिप्पणी प्राप्त करें
1. टिप्पणी को अद्यतन करने के लिए setNotes विधि का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप API के माध्यम से टिप्पणियाँ जोड़ें" %}}

1. वर्कबुक क्लास ऑब्जेक्ट के माध्यम से दस्तावेज़ बनाएँ
1. विशिष्ट वर्कशीट प्राप्त करें
1. getComments().add के माध्यम से टिप्पणी सूचकांक जोड़ें
1. टिप्पणी जोड़ने के लिए setNotes विधि का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : XLSX फ़ाइल की थ्रेडेड टिप्पणी अपडेट करें" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="कोड: टिप्पणियाँ जोड़ना" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>XLSX दस्तावेज़ एनोटेशन Android ऐप विकसित करें</h2>

क्या आपको फीडबैक देने, सुझाव देने या दस्तावेज़ पर दूसरों के साथ सहयोग करने के लिए एंड्रॉइड आधारित XLSX एनोटेशन ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Total for Android via Java](https://products.aspose.com/total/hi/android-java/) के चाइल्ड API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/hi/android-java/) के साथ, कोई भी एंड्रॉयड डेवलपर अपने दस्तावेज़ एनोटेशन एप्लिकेशन के भीतर उपरोक्त API कोड को एकीकृत कर सकता है।शक्तिशाली एंड्रॉइड लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है।इसके अलावा यह XLSX प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX फ़ाइलों को एनोटेट करने के लिए Android API" %}}

- हम अपने जावा पैकेजों को [मावेन रिपॉजिटरीज़](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) में होस्ट करते हैं। 
- Aspose.Cells for Java एक सामान्य JAR फ़ाइल है जिसमें बाइट-कोड होता है।
- Aspose.Cells for Android via Java को स्थापित करने के लिए [चरण दर चरण निर्देश](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) का अनुसरण करें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

- एंड्रॉयड ओएस 2.0 या उससे ऊपर.
- जावा पैकेज क्रॉस-प्लेटफॉर्म है और JVM कार्यान्वयन के साथ सभी ऑपरेटिंग सिस्टम पर चलता है।

<br />
अधिक जानकारी के लिए कृपया [उत्पाद दस्तावेज़ीकरण](https://docs.aspose.com/cells/java/system-requirements/) देखें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}