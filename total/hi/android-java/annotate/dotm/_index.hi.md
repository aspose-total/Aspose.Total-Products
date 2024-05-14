---
title: DOTM एनोटेशन को ऑनलाइन हटाएं या Android मोबाइल ऐप्स का उपयोग करके एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से DOTM फ़ाइल से टिप्पणियां निःशुल्क हटाएं।DOTM फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए Android API कोड.

family: total
platformtag: Android
feature: Annotate
informat: DOTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOTM दस्तावेज़ से टिप्पणियाँ ऑनलाइन साफ़ करें या Android ऐप्स के माध्यम से प्रबंधित करें" h2="शक्तिशाली एंड्रॉइड आधारित DOTM दस्तावेज़ एनोटेशन उपयोगिता अनुप्रयोग विकसित करें।DOTM फ़ाइल की टिप्पणियों के प्रबंधन के लिए सूचीबद्ध कोड." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM एनोटेशन ऑनलाइन हटाएं" %}}

1. DOTM फ़ाइल को अपलोड करके टिप्पणियाँ हटाने के लिए आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. DOTM फ़ाइल के आकार और इंटरनेट की गति के आधार पर कुछ सेकंड तक प्रतीक्षा करें
1. टिप्पणियाँ हटाने के लिए 'हटाएँ' बटन पर क्लिक करें
1. फ़ाइल को तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप के माध्यम से DOTM दस्तावेज़ टिप्पणियाँ हटाएँ" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. डॉक्यूमेंट क्लास ऑब्जेक्ट के माध्यम से डॉक्यूमेंट लोड करें
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) और NodeType.COMMENT का उपयोग करके सभी नोड्स से सभी टिप्पणियाँ प्राप्त करें
1. सभी टिप्पणियाँ हटाने के लिए [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) विधि लागू करें
1. फ़ाइल को सहेजने के लिए save विधि को कॉल करें.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : DOTM फ़ाइल से टिप्पणियाँ हटाएँ" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM हटाएँ और जोड़ें टिप्पणी उत्तर दें" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. डॉक्यूमेंट क्लास ऑब्जेक्ट के माध्यम से डॉक्यूमेंट लोड करें
1. getChild का उपयोग करके टिप्पणी प्राप्त करें
1. इस टिप्पणी के निर्दिष्ट उत्तर को हटाने के लिए [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) का उपयोग करें
1. इस टिप्पणी पर कोई भी उत्तर जोड़ने के लिए [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="एंड्रॉयड ऐप के माध्यम से टिप्पणियाँ जोड़ें" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट बनाएँ
1. टिप्पणी बनाने के लिए [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) का उपयोग करें
1. getParagraphs().add और getFirstParagraph().getRuns().add का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड: DOTM फ़ाइल से टिप्पणी उत्तर हटाएँ और जोड़ें" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="कोड: टिप्पणियाँ जोड़ना" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>DOTM दस्तावेज़ एनोटेशन Android ऐप विकसित करें</h2>

क्या आपको दस्तावेज़ पर प्रतिक्रिया देने, सुझाव देने या दूसरों के साथ सहयोग करने के लिए DOTM एनोटेशन मोबाइल ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Total for Android via Java](https://products.aspose.com/total/hi/android-java/) के चाइल्ड API [Aspose.Words for Android via Java](https://products.aspose.com/words/hi/android-java/) के साथ, कोई भी एंड्रॉयड डेवलपर अपने दस्तावेज़ एनोटेशन एप्लिकेशन के भीतर उपरोक्त API कोड को एकीकृत कर सकता है।शक्तिशाली एंड्रॉइड लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है।इसके अलावा यह DOTM प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTM फ़ाइलों को एनोटेट करने के लिए एंड्रॉइड लाइब्रेरी" %}}

- हम अपने जावा पैकेजों को [मावेन रिपॉजिटरी](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) में होस्ट करते हैं। 
- Aspose.Words for Java एक सामान्य JAR फ़ाइल है जिसमें बाइट-कोड होता है।
- Aspose.Words for Android via Java को स्थापित करने के लिए [चरण दर चरण निर्देश](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) का अनुसरण करें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

- जावा SE 7 और नवीनतम जावा संस्करण समर्थित हैं।
- यदि किसी को पुराने JRE का उपयोग करना पड़े तो Java SE 6 के लिए अलग पैकेज।
- जावा पैकेज क्रॉस-प्लेटफॉर्म है और JVM कार्यान्वयन के साथ सभी ऑपरेटिंग सिस्टम पर चलता है।
- ऑपरेटिंग सिस्टम में माइक्रोसॉफ्ट विंडोज, लिनक्स, मैकओएस, एंड्रॉइड और आईओएस शामिल हैं।

<br />
वैकल्पिक पैकेज निर्भरताओं, जैसे कि जोगएम्प जेओजीएल, हार्फबज़ फ़ॉन्ट इंजन, जावा एडवांस्ड इमेजिंग जेएआई, के बारे में अधिक जानकारी के लिए कृपया [उत्पाद दस्तावेज़ीकरण](https://docs.aspose.com/words/java/system-requirements/) देखें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}