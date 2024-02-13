---
title: DOTX एनोटेशन ऑनलाइन निकालें या .NET के माध्यम से एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से DOTX फ़ाइल से टिप्पणियाँ निःशुल्क हटाएँ।DOTX फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए .NET API कोड।

family: total
platformtag: net
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="DOTX दस्तावेज़ से टिप्पणियाँ ऑनलाइन साफ़ करें या .NET के माध्यम से प्रबंधित करें" h2="शक्तिशाली .NET आधारित DOTX दस्तावेज़ एनोटेशन उपयोगिता एप्लिकेशन विकसित करें।.NET के माध्यम से DOTX फ़ाइल की टिप्पणियों को प्रबंधित करने के लिए सूचीबद्ध कोड।" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX एनोटेशन ऑनलाइन निकालें" %}}

1. टिप्पणियों को अपलोड करके हटाने के लिए DOTX फ़ाइल आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. DOTX फ़ाइल के आकार और इंटरनेट स्पीड के आधार पर कुछ सेकंड प्रतीक्षा करें
1. टिप्पणियाँ साफ़ करने के लिए 'निकालें' बटन पर क्लिक करें
1. फ़ाइल तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title=".NET के माध्यम से विशिष्ट लेखक DOTX दस्तावेज़ टिप्पणियाँ हटाएँ" %}}

1. .NET प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. NodeType.Comment वाले GetChildNodes का उपयोग करके सभी नोड्स टिप्पणियाँ प्राप्त करें
1. सभी टिप्पणियों को दोहराएँ और लेखक के नाम का मिलान करें
1. विशिष्ट लेखक टिप्पणी को हटाने के लिए निकालें विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# कोड: DOTX फ़ाइल से विशिष्ट लेखक टिप्पणियाँ हटाएँ" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET के माध्यम से टिप्पणियाँ जोड़ें" %}}

1. दस्तावेज़ वर्ग ऑब्जेक्ट बनाएँ
1. टिप्पणी वर्ग का प्रयोग करें
1. Paragraphs.Add का उपयोग करके नया पैराग्राफ जोड़ें
1. FirstParagraph.Runs.Add का उपयोग करें, टिप्पणी जोड़ें
1. या दूसरा तरीका CommentRangeStart और CommentRangeEnd कक्षाओं का उपयोग करना है
1. अतिरिक्त टिप्पणियों के साथ फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सभी टिप्पणियाँ निकालें" %}}

1. दस्तावेज़ वर्ग ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. एक ArrayList ऑब्जेक्ट बनाएं
1. NodeCollection में सभी GetChildNodes प्राप्त करें
1. प्रत्येक संग्रह को दोहराएँ और ArrayList में टिप्पणियाँ जोड़ें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET कोड: DOTX फ़ाइल से टिप्पणी जोड़ें" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: सभी टिप्पणियाँ निकालें" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>.NET के माध्यम से DOTX दस्तावेज़ एनोटेशन एप्लिकेशन विकसित करें</h2>

क्या आपको फीडबैक देने, सुझाव देने या दस्तावेज़ पर दूसरों के साथ सहयोग करने के लिए DOTX एनोटेशन ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Words for .NET](https://products.aspose.com/words/net/), [Aspose.Total for .NET](https://products.aspose.com/total/net/) के चाइल्ड एपीआई के साथ, कोई भी .NET डेवलपर उपरोक्त एपीआई कोड को अपने दस्तावेज़ एनोटेशन एप्लिकेशन में एकीकृत कर सकता है।शक्तिशाली .NET लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है।इसके अलावा यह DOTX प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX फ़ाइलों को एनोटेट करने के लिए .NET लाइब्रेरी" %}}

आपके सिस्टम पर "Aspose.Words for .NET" या "Aspose.Total for .NET" स्थापित करने के लिए तीन वैकल्पिक विकल्प हैं।कृपया वह चुनें जो आपकी आवश्यकताओं से मेल खाता हो और चरण-दर-चरण निर्देशों का पालन करें:<br /><br />

- [NuGet Package](https://www.nuget.org/packages/Aspose.Words/) इंस्टॉल करें. [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget) देखें
- विजुअल स्टूडियो आईडीई के भीतर [Package Manager Console](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) का उपयोग करके लाइब्रेरी स्थापित करें
- [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer) का उपयोग करके लाइब्रेरी को हाथ से इंस्टॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

हमारा उत्पाद पूरी तरह से क्रॉस-प्लेटफ़ॉर्म है और '.NET मानक 2.0' विनिर्देश के बाद सभी प्रमुख .NET कार्यान्वयन का समर्थन करता है:<br /><br />

- माइक्रोसॉफ्ट .NET फ्रेमवर्क, शुरुआती 2.0 संस्करण से शुरू होकर नवीनतम '.NET फ्रेमवर्क 4.8' पर समाप्त होता है।
- .NET कोर, शुरुआती 2.0 से शुरू होकर नवीनतम '.NET 6' पर समाप्त होता है
- मोनो >= 2.6.7
<br /><br />
चूंकि .NET कोड अंतर्निहित हार्डवेयर या ऑपरेटिंग सिस्टम पर निर्भर नहीं करता है, बल्कि केवल वर्चुअल मशीन पर निर्भर करता है, इसलिए आप विंडोज, मैकओएस, एंड्रॉइड, आईओएस और लिनक्स के लिए किसी भी प्रकार का सॉफ्टवेयर विकसित करने के लिए स्वतंत्र हैं।बस सुनिश्चित करें कि आपने .NET Framework, .NET Core, Windows Azure, Mono या Xamarin का संबंधित संस्करण स्थापित किया है।<br /><br />
हम C#, F#, VB.NET एप्लिकेशन बनाने के लिए Microsoft Visual Studio, Xamarin और MonoDevelop IDE का उपयोग करने की अनुशंसा करते हैं।
<br /><br />
अधिक जानकारी के लिए कृपया [Product Documentation](https://docs.aspose.com/words/net/system-requirements/) देखें।

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
                          <span itemprop="name"><b>क्या मैं अपने एप्लिकेशन में उपरोक्त .NET कोड का उपयोग कर सकता हूँ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">हां, इस कोड को डाउनलोड करने और .NET-आधारित दस्तावेज़ एनोटेशन एप्लिकेशन को विकसित करने के उद्देश्य से इसका उपयोग करने के लिए आपका स्वागत है।यह कोड बैकएंड दस्तावेज़ प्रसंस्करण और हेरफेर के क्षेत्र में आपकी परियोजनाओं की कार्यक्षमता और क्षमताओं को बढ़ाने के लिए एक मूल्यवान संसाधन के रूप में काम कर सकता है।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या यह ऑनलाइन दस्तावेज़ एनोटेशन ऐप केवल विंडोज़ पर काम करता है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">आपके पास किसी भी डिवाइस पर टिप्पणियों को हटाने के लिए दस्तावेज़ एनोटेशन शुरू करने की सुविधा है, चाहे वह किसी भी ऑपरेटिंग सिस्टम पर चलता हो, चाहे वह विंडोज, लिनक्स, मैक ओएस या एंड्रॉइड हो।बस एक समकालीन वेब ब्राउज़र और एक सक्रिय इंटरनेट कनेक्शन की आवश्यकता है।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या DOTX दस्तावेज़ को एनोटेट करने के लिए ऑनलाइन ऐप का उपयोग करना सुरक्षित है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बिल्कुल! हमारी सेवा के माध्यम से उत्पन्न आउटपुट फ़ाइलें 24 घंटे की समय सीमा के भीतर हमारे सर्वर से सुरक्षित रूप से और स्वचालित रूप से हटा दी जाएंगी।परिणामस्वरूप, इस अवधि के बाद इन फ़ाइलों से जुड़े डिस्प्ले लिंक काम करना बंद कर देंगे।</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ऐप का उपयोग करने के लिए कौन सा ब्राउज़र चाहिए?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">आप ऑनलाइन DOTX दस्तावेज़ एनोटेशन के लिए Google Chrome, फ़ायरफ़ॉक्स, ओपेरा, या Safari जैसे किसी भी आधुनिक वेब ब्राउज़र का उपयोग कर सकते हैं।हालाँकि, यदि आप एक डेस्कटॉप एप्लिकेशन विकसित कर रहे हैं, तो हम कुशल प्रबंधन के लिए Aspose.Total दस्तावेज़ प्रोसेसिंग एपीआई का उपयोग करने की सलाह देते हैं।</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}