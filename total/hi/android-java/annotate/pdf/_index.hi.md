---
title: PDF एनोटेशन को ऑनलाइन हटाएं या Android मोबाइल ऐप्स का उपयोग करके एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से PDF फ़ाइल से टिप्पणियां निःशुल्क हटाएं।PDF फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए Android API कोड.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="PDF दस्तावेज़ से टिप्पणियाँ ऑनलाइन साफ़ करें या Android ऐप्स के माध्यम से प्रबंधित करें" h2="शक्तिशाली एंड्रॉइड आधारित PDF दस्तावेज़ एनोटेशन उपयोगिता अनुप्रयोग विकसित करें।PDF फ़ाइल की टिप्पणियों के प्रबंधन के लिए सूचीबद्ध कोड." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF एनोटेशन ऑनलाइन हटाएं" %}}

1. PDF फ़ाइल को अपलोड करके टिप्पणियाँ हटाने के लिए आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. PDF फ़ाइल के आकार और इंटरनेट की गति के आधार पर कुछ सेकंड तक प्रतीक्षा करें
1. टिप्पणियाँ हटाने के लिए 'हटाएँ' बटन पर क्लिक करें
1. फ़ाइल को तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप API के माध्यम से PDF दस्तावेज़ टिप्पणियाँ हटाएँ" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. डॉक्यूमेंट क्लास ऑब्जेक्ट के माध्यम से डॉक्यूमेंट लोड करें
1. getPages().get_Item(Index) के माध्यम से विशिष्ट पृष्ठ का चयन करें
1. एनोटेशन चयनकर्ता का उपयोग करें और annotationSelector.getSelected() के माध्यम से सभी पाठ एनोटेशन प्राप्त करें
1. प्रत्येक एनोटेशन को पुनरावृत्त करें और उसे हटाने के लिए डिलीट विधि को कॉल करें।
1. फ़ाइल को सहेजने के लिए save विधि को कॉल करें.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : PDF फ़ाइल से टिप्पणियाँ हटाएँ" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप API के माध्यम से एनोटेशन जोड़ें" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट बनाएँ
1. getPages().add() का उपयोग करके नया पृष्ठ और सामग्री जोड़ें
1. TextAnnotation वर्ग के getPages().get_Item(Index) का उपयोग करें
1. प्रासंगिक एनोटेशन जैसे शीर्षक, विषय, सामग्री आदि सेट करें
1. एनोटेशन जोड़ने के लिए getAnnotations().add का उपयोग करें
1. जोड़े गए टिप्पणियों के साथ फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : PDF एनोटेशन जोड़ें" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>PDF दस्तावेज़ एनोटेशन Android ऐप विकसित करें</h2>

क्या आपको दस्तावेज़ पर प्रतिक्रिया देने, सुझाव देने या दूसरों के साथ सहयोग करने के लिए PDF एनोटेशन मोबाइल ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Total for Android via Java](https://products.aspose.com/total/hi/android-java/) के चाइल्ड API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/hi/android-java/) के साथ, कोई भी एंड्रॉयड डेवलपर अपने दस्तावेज़ एनोटेशन एप्लिकेशन के भीतर उपरोक्त API कोड को एकीकृत कर सकता है।शक्तिशाली एंड्रॉइड लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है।इसके अलावा यह PDF प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF फ़ाइलों को एनोटेट करने के लिए एंड्रॉइड लाइब्रेरी" %}}

- हम अपने जावा पैकेजों को [मावेन रिपॉजिटरीज़](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/) में होस्ट करते हैं। 
- Aspose.PDF for Java एक सामान्य JAR फ़ाइल है जिसमें बाइट-कोड होता है।
- Aspose.PDF for Android via Java को स्थापित करने के लिए [चरण दर चरण निर्देश](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) का अनुसरण करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

- एंड्रॉइड एपीआई 31 और 32
- एंड्रॉइड 4.0 और ऊपर
- Android Studio और SDK उपकरण

<br />
वैकल्पिक पैकेज निर्भरताओं, जैसे कि जोगएम्प जेओजीएल, हार्फबज़ फ़ॉन्ट इंजन, जावा एडवांस्ड इमेजिंग जेएआई, के बारे में अधिक जानकारी के लिए कृपया [उत्पाद दस्तावेज़ीकरण](https://docs.aspose.com/pdf/java/system-requirements/) देखें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}