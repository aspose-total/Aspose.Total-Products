---
title: Word फ़ाइल से ऑनलाइन और C++ का उपयोग करके टेक्स्ट और छवियाँ निकालें
description: ऑनलाइन Word फ़ाइल पार्सर ऐप। Word दस्तावेज़ से छवियों और पाठ सामग्री को निकालने के लिए C++ API कोड।

family: total
platformtag: cpp
feature: Parse
informat: Word
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Word फ़ाइल को ऑनलाइन तथा C++ के माध्यम से पार्स करें" h2="शक्तिशाली C++ आधारित Word दस्तावेज़ पार्सर उपयोगिता अनुप्रयोग विकसित करें।Word दस्तावेज़ पाठ निष्कर्षण के लिए सूचीबद्ध C++ कोड।" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ऑनलाइन ऐप के माध्यम से Word दस्तावेज़ पार्स करें" %}}

1. Word फ़ाइल को अपलोड करके पार्स करने के लिए आयात करें।
1. पार्सर ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें।
1. Word फ़ाइल के आकार और इंटरनेट की गति के आधार पर कुछ सेकंड तक प्रतीक्षा करें।
1. दस्तावेज़ को पार्स करने के लिए 'अभी पार्स करें' बटन पर क्लिक करें।
1. तुरन्त देखने के लिए पार्स की गई फ़ाइलें डाउनलोड करें।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="C++ के माध्यम से Word फ़ाइल को पार्स करें" %}}

1. C++ प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. Word फ़ाइल लोड करें
1. GetChildNodes का उपयोग करके सभी चाइल्ड नोड्स प्राप्त करें
1. NodeType::Shape को पैरामीटर के रूप में उपयोग करें
1. प्रत्येक नोड के माध्यम से पुनरावृति करें और छवि को सहेजें
1. आकार->get_ImageData()->Save विधि का उपयोग करके निकाली गई फ़ाइल को सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ कोड: Word दस्तावेज़ छवि निष्कर्षण" offSpacer="" %}}

{{< gist "aspose-com-gists" "0916cd11f2eb51ded9c1c14a8a1a3f68" "parse-word-document-by-extracting-images.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>C++ के माध्यम से Word फ़ाइल पार्सर अनुप्रयोग विकसित करें</h2>

क्या आपको Word पार्सर एप्लिकेशन या सॉफ्टवेयर विकसित करने की आवश्यकता है?[Aspose.Total for C++](https://products.aspose.com/total/hi/cpp/) के चाइल्ड API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) के साथ, कोई भी C++ डेवलपर अपने दस्तावेज़ पार्सर अनुप्रयोग में उपरोक्त API कोड को एकीकृत कर सकता है।शक्तिशाली C++ लाइब्रेरी किसी भी दस्तावेज़ पार्सिंग समाधान को छवियों के साथ-साथ पाठ निकालने के लिए प्रोग्रामिंग की अनुमति देती है।इसके अलावा यह Word प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पार्सर अनुप्रयोग के लिए Word फ़ाइल को संसाधित करने हेतु C++ उपयोगिता" %}}

आपके डेवलपर परिवेश में Aspose.Words for C++ या Aspose.Total for C++ को स्थापित करने के लिए तीन विकल्प हैं।कृपया अपनी आवश्यकताओं के अनुरूप एक विकल्प चुनें और चरण-दर-चरण निर्देशों का पालन करें:<br /><br />

- [NuGet पैकेज](https://www.nuget.org/packages/Aspose.Words.Cpp/) स्थापित करें. [प्रलेखन](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget) देखें
- Visual Studio IDE में [पैकेज प्रबंधक कंसोल](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) का उपयोग करके लाइब्रेरी स्थापित करें
- [विंडोज इंस्टालर](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand) का उपयोग करके लाइब्रेरी को हाथ से स्थापित करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}
आप Microsoft Windows, Linux और macOS ऑपरेटिंग सिस्टम पर सॉफ़्टवेयर विकसित करने के लिए इस C++ लाइब्रेरी का उपयोग कर सकते हैं:<br /><br />

- Linux के लिए GCC >= 6.3.0 और Clang >= 3.9.1 आवश्यक हैं
- Xcode >= 12.5.1, MacOS के लिए Clang और libc++ आवश्यक हैं

<br /><br />
यदि आप लिनक्स या मैकओएस के लिए सॉफ्टवेयर विकसित करते हैं, तो कृपया [उत्पाद दस्तावेज़ीकरण](https://docs.aspose.com/words/cpp/system-requirements/) में अतिरिक्त लाइब्रेरी निर्भरताओं (फॉन्टकॉन्फिग और मेसा-ग्लू ओपन-सोर्स पैकेज) की जानकारी की जांच करें।

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="पूछे जाने वाले प्रश्न" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>पूछे जाने वाले प्रश्न</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या मैं अपने अनुप्रयोग में उपरोक्त C++ कोड का उपयोग कर सकता हूँ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">हां, आप इस कोड को डाउनलोड कर सकते हैं और C++-आधारित दस्तावेज़ पार्सर अनुप्रयोग विकसित करने के उद्देश्य से इसका उपयोग कर सकते हैं।यह कोड बैकएंड दस्तावेज़ प्रसंस्करण के क्षेत्र में आपकी परियोजनाओं की कार्यक्षमता और क्षमताओं को बढ़ाने के लिए एक मूल्यवान संसाधन के रूप में काम कर सकता है, जैसे कि नोड्स को पढ़ना और पाठ और छवियों को निकालने के लिए दस्तावेज़ लोड करना।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या यह ऑनलाइन दस्तावेज़ पार्सर ऐप केवल विंडोज़ पर काम करता है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">आपके पास किसी भी डिवाइस पर दस्तावेजों को पार्स करने की सुविधा है, चाहे वह किसी भी ऑपरेटिंग सिस्टम पर चलता हो, चाहे वह विंडोज, लिनक्स, मैक ओएस या एंड्रॉइड हो।इसके लिए बस एक आधुनिक वेब ब्राउज़र और सक्रिय इंटरनेट कनेक्शन की आवश्यकता है।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या Word दस्तावेज़ को पार्स करने के लिए ऑनलाइन ऐप का उपयोग करना सुरक्षित है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बेशक! हमारी सेवा के माध्यम से उत्पन्न आउटपुट फ़ाइलें 24 घंटे की समय सीमा के भीतर हमारे सर्वर से सुरक्षित और स्वचालित रूप से हटा दी जाएंगी।परिणामस्वरूप, इन फ़ाइलों से जुड़े प्रदर्शन लिंक इस अवधि के बाद कार्यात्मक नहीं रहेंगे।</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ऐप का उपयोग करने के लिए कौन सा ब्राउज़र चाहिए?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">आप ऑनलाइन Word दस्तावेज़ पार्सर के लिए Google क्रोम, फ़ायरफ़ॉक्स, ओपेरा या सफारी जैसे किसी भी आधुनिक वेब ब्राउज़र का उपयोग कर सकते हैं।हालाँकि, यदि आप एक डेस्कटॉप एप्लिकेशन विकसित कर रहे हैं, तो हम कुशल प्रबंधन के लिए Aspose.Total दस्तावेज़ प्रसंस्करण API का उपयोग करने की सलाह देते हैं।</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}