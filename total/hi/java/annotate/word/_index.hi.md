---
title: Word एनोटेशन ऑनलाइन निकालें या जावा के माध्यम से एनोटेशन प्रबंधित करें
description: ऑनलाइन ऐप के माध्यम से Word फ़ाइल से टिप्पणियाँ निःशुल्क हटाएँ। Word फ़ाइलों की टिप्पणियों को प्रबंधित करने के लिए जावा एपीआई कोड।

family: total
platformtag: Java
feature: Annotate
informat: Word
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Word दस्तावेज़ से टिप्पणियाँ ऑनलाइन साफ़ करें या जावा के माध्यम से प्रबंधित करें" h2="शक्तिशाली जावा आधारित Word दस्तावेज़ एनोटेशन उपयोगिता एप्लिकेशन विकसित करें।जावा के माध्यम से Word फ़ाइल की टिप्पणियों को प्रबंधित करने के लिए कोड सूचीबद्ध है।" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word एनोटेशन ऑनलाइन निकालें" %}}

1. टिप्पणियों को अपलोड करके हटाने के लिए Word फ़ाइल आयात करें
1. एनोटेशन ऐप के ड्रैग और ड्रॉप के माध्यम से ड्रॉप क्षेत्र के अंदर क्लिक करके ऐसा करें
1. Word फ़ाइल के आकार और इंटरनेट स्पीड के आधार पर कुछ सेकंड प्रतीक्षा करें
1. टिप्पणियाँ साफ़ करने के लिए 'निकालें' बटन पर क्लिक करें
1. फ़ाइल तुरंत डाउनलोड करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से Word दस्तावेज़ टिप्पणियाँ हटाएँ" %}}

1. जावा प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) और NodeType.COMMENT का उपयोग करके सभी नोड्स से सभी टिप्पणियाँ प्राप्त करें
1. सभी टिप्पणियों को हटाने के लिए [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) विधि लागू करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Word फ़ाइल से टिप्पणियाँ हटाने के लिए जावा में कोड उदाहरण" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word टिप्पणी उत्तर हटाएँ और जोड़ें" %}}

1. जावा प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट के माध्यम से दस्तावेज़ लोड करें
1. GetChild का उपयोग करके टिप्पणी प्राप्त करें
1. इस टिप्पणी के निर्दिष्ट उत्तर को हटाने के लिए [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) का उपयोग करें
1. इस टिप्पणी में कोई भी उत्तर जोड़ने के लिए [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से टिप्पणियाँ जोड़ें" %}}

1. जावा प्रोजेक्ट में लाइब्रेरी संदर्भ जोड़ें
1. दस्तावेज़ वर्ग ऑब्जेक्ट बनाएँ
1. टिप्पणी बनाने के लिए [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) का उपयोग करें
1. getParagraphs().add और getFirstParagraph().getRuns().add का उपयोग करें
1. फ़ाइल को सहेजने के लिए सेव विधि को कॉल करें with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Word फ़ाइल से टिप्पणी उत्तर हटाने और जोड़ने के लिए जावा कोड" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="जावा कोड: टिप्पणियाँ जोड़ना" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>जावा के माध्यम से Word दस्तावेज़ एनोटेशन एप्लिकेशन विकसित करें</h2>

क्या आपको फीडबैक देने, सुझाव देने या दस्तावेज़ पर दूसरों के साथ सहयोग करने के लिए Word एनोटेशन ऐप या उपयोगिता विकसित करने की आवश्यकता है?[Aspose.Words for Java](https://products.aspose.com/words/java/), [Aspose.Total for Java](https://products.aspose.com/total/java/) के चाइल्ड एपीआई के साथ, कोई भी जावा डेवलपर उपरोक्त एपीआई कोड को अपने दस्तावेज़ एनोटेशन एप्लिकेशन में एकीकृत कर सकता है।शक्तिशाली जावा लाइब्रेरी किसी भी दस्तावेज़ एनोटेशन समाधान को प्रोग्रामिंग करने की अनुमति देती है। इसके अलावा यह Word प्रारूप सहित कई लोकप्रिय प्रारूपों का समर्थन कर सकता है।<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Word फ़ाइलों को एनोटेट करने के लिए जावा लाइब्रेरी" %}}
आपके सिस्टम पर "[Aspose.Words for Java](https://products.aspose.com/words/java/)" या "[Aspose.Total for Java](https://products.aspose.com/total/java/)" इंस्टॉल करने के लिए वैकल्पिक विकल्प हैं।हमारा जावा पैकेज क्रॉस-प्लेटफ़ॉर्म होने के लिए डिज़ाइन किया गया है, जो माइक्रोसॉफ्ट विंडोज, लिनक्स, मैकओएस, एंड्रॉइड और आईओएस जैसे विभिन्न ऑपरेटिंग सिस्टम पर जेवीएम कार्यान्वयन के साथ संगत है। कृपया वह चुनें जो आपकी आवश्यकताओं से मेल खाता हो और चरण-दर-चरण निर्देशों का पालन करें:<br />

- [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) इंस्टॉल करें
- या [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) से
- चरण दर चरण [निर्देश](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

- जावा एसई 7 या हाल के जावा संस्करण
- यदि आपके पास यह पुराना जेआरई है तो जावा एसई 6 के लिए अलग पैकेज।

<br />
जोगएम्प जेओजीएल, हार्फबज फ़ॉन्ट इंजन और जावा एडवांस्ड इमेजिंग जेएआई विवरण के लिए कृपया जेपीजी1 देखें।

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
                          <span itemprop="name"><b>क्या मैं अपने एप्लिकेशन में उपरोक्त जावा कोड का उपयोग कर सकता हूं?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">हां, इस कोड को डाउनलोड करने और जावा-आधारित दस्तावेज़ एनोटेशन एप्लिकेशन को विकसित करने के उद्देश्य से इसका उपयोग करने के लिए आपका स्वागत है।यह कोड बैकएंड दस्तावेज़ प्रसंस्करण और हेरफेर के क्षेत्र में आपकी परियोजनाओं की कार्यक्षमता और क्षमताओं को बढ़ाने के लिए एक मूल्यवान संसाधन के रूप में काम कर सकता है।</span>
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
                          <span itemprop="name"><b>क्या Word दस्तावेज़ को एनोटेट करने के लिए ऑनलाइन ऐप का उपयोग करना सुरक्षित है?</b></span>
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
                          <span itemprop="text">आप ऑनलाइन Word दस्तावेज़ एनोटेशन के लिए Google Chrome, फ़ायरफ़ॉक्स, ओपेरा, या Safari जैसे किसी भी आधुनिक वेब ब्राउज़र का उपयोग कर सकते हैं।हालाँकि, यदि आप एक डेस्कटॉप एप्लिकेशन विकसित कर रहे हैं, तो हम कुशल प्रबंधन के लिए Aspose.Total दस्तावेज़ प्रोसेसिंग एपीआई का उपयोग करने की सलाह देते हैं।</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}