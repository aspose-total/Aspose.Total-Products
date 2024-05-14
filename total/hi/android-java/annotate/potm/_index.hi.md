---
title: POTM एनोटेशन को ऑनलाइन हटाएं या Android मोबाइल ऐप्स का उपयोग करके एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से POTM फ़ाइल से टिप्पणियां निःशुल्क हटाएं।POTM फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए Android API कोड.

family: total
platformtag: Android
feature: Annotate
informat: POTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="POTM प्रस्तुति से टिप्पणियाँ ऑनलाइन साफ़ करें या Android ऐप्स के माध्यम से प्रबंधित करें" h2="शक्तिशाली एंड्रॉयड आधारित POTM प्रस्तुति एनोटेशन उपयोगिता अनुप्रयोग विकसित करें।POTM फ़ाइल की टिप्पणियों के प्रबंधन के लिए सूचीबद्ध कोड." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM एनोटेशन ऑनलाइन हटाएं" %}}

1. POTM फ़ाइल को अपलोड करके टिप्पणियाँ हटाने के लिए आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. POTM फ़ाइल के आकार और इंटरनेट की गति के आधार पर कुछ सेकंड तक प्रतीक्षा करें
1. टिप्पणियाँ हटाने के लिए 'हटाएँ' बटन पर क्लिक करें
1. फ़ाइल को तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप के माध्यम से POTM प्रस्तुति टिप्पणियाँ हटाएँ" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. प्रेजेंटेशन क्लास ऑब्जेक्ट के माध्यम से POTM लोड करें
1. Presentation.getCommentAuthors() संग्रह के माध्यम से प्रत्येक लेखक के माध्यम से पुनरावृति करें
1. इसकी टिप्पणी को हटाने के लिए clear() विधि का प्रयोग करें
1. अंत में सभी लेखकों को हटाने के लिए getCommentAuthors().clear() को कॉल करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड : POTM प्रस्तुति से टिप्पणियाँ और लेखक हटाएँ" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Android ऐप के माध्यम से POTM प्रस्तुति टिप्पणियाँ जोड़ें" %}}

1. एंड्रॉइड प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. प्रेजेंटेशन क्लास ऑब्जेक्ट के माध्यम से POTM लोड करें
1. लेखकों को जोड़ने के लिए Presentation.getCommentAuthors().addAuthor(String, String) का प्रयोग करें
1. टिप्पणियाँ जोड़ने के लिए ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="कोड: टिप्पणियाँ जोड़ना" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>POTM दस्तावेज़ एनोटेशन Android ऐप विकसित करें</h2>

क्या आपको दस्तावेज़ पर प्रतिक्रिया देने, सुझाव देने या दूसरों के साथ सहयोग करने के लिए POTM एनोटेशन मोबाइल ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Total for Android via Java](https://products.aspose.com/total/hi/android-java/) के चाइल्ड API [Aspose.Slides for Android via Java](https://products.aspose.com/slides/hi/android-java/) के साथ, कोई भी एंड्रॉयड डेवलपर अपने दस्तावेज़ एनोटेशन एप्लिकेशन के भीतर उपरोक्त API कोड को एकीकृत कर सकता है।शक्तिशाली एंड्रॉइड लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है।इसके अलावा यह POTM प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM फ़ाइलों को एनोटेट करने के लिए एंड्रॉइड लाइब्रेरी" %}}

- हम अपने जावा पैकेजों को [मावेन रिपॉजिटरी](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/) में होस्ट करते हैं। 
- Aspose.Slides for Java एक सामान्य JAR फ़ाइल है जिसमें बाइट-कोड होता है।
- Aspose.Slides for Android via Java को स्थापित करने के लिए [चरण दर चरण निर्देश](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) का अनुसरण करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

- J2SE 6.0 (जावा 1.6) और उच्चतर
- जावा पैकेज क्रॉस-प्लेटफॉर्म है और JVM कार्यान्वयन के साथ सभी ऑपरेटिंग सिस्टम पर चलता है।

<br />
अधिक जानकारी के लिए कृपया [उत्पाद दस्तावेज़ीकरण](https://docs.aspose.com/slides/java/system-requirements/) देखें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}