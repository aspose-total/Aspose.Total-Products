---
title: जावा का उपयोग करके FODS को DOCX में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: जावा एपीआई एक्सेल या वर्ड का उपयोग करके सीएसवी को डीओसी में निर्यात करने के लिए या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।
url_ignore: /hi/java/conversion/fods-to-docx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOCX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सीएसवी को डीओसी में निर्यात करने के लिए जावा एपीआई या ऑनलाइन" h2="माइक्रोसॉफ्ट एक्सेल पर भरोसा किए बिना सीएसवी को डीओसी में निर्यात करने के लिए परिसर जावा एपीआई पर&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
सीएसवी को डीओसी को प्रस्तुत करना दो चरणों वाली प्रक्रिया है। दिए गए FODS दस्तावेज़ को PDF में बदलने के लिए आप पहले [Aspose.Cells for Java](https://products.aspose.com/cells/java) API का इस्तेमाल करेंगे और फिर [Aspose.PDF for Java](https) का इस्तेमाल करेंगे ://products.aspose.com/pdf/java) एपीआई, आप आसानी से अपने पीडीएफ दस्तावेज़ को डीओसी में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Java](https://products.aspose.com/total/java/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी के संग्रह में आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा एपीआई के माध्यम से सीएसवी को डीओसी में कैसे बदलें" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके FODS फ़ाइल खोलें
2. FODS को PDF में बदलें और SaveFormat को AUTO पर सेट करें
3. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके परिवर्तित पीडीएफ फाइल को लोड करें
4. दस्तावेज़ को [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions का उपयोग करके DOCX प्रारूप में सहेजें।-) विधि और डॉक को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आपको [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे जावा के लिए Aspose.Total का उपयोग करना होगा। और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>बीएमपी से जीआईएफ के लिए ऑनलाइन कन्वर्टर</h3>

<iframe title="docx से fods रूपांतरण ऑनलाइन टूल" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=fods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/fods-to-docx/">बीएमपी से जीआईएफ रूपांतरण के लिए हमारे मुफ्त ऐप का प्रयास करें</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>अक्सर पूछे जाने वाले प्रश्नों</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>मैं बीएमपी को जीआईएफ में ऑनलाइन कैसे बदल सकता हूं?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बीएमपी रूपांतरण के लिए ऑनलाइन ऐप ऊपर एकीकृत है। रूपांतरण प्रक्रिया में आपकी FODS फ़ाइल को सफेद क्षेत्र में खींचकर और छोड़ कर या फ़ाइल को आयात करने के लिए क्षेत्र के अंदर क्लिक करके जोड़ना शामिल है। फ़ाइल जुड़ जाने के बाद, रूपांतरण प्रक्रिया शुरू करने के लिए बस कन्वर्ट बटन पर क्लिक करें। एक बार पूरा हो जाने के बाद, आप अपनी नई परिवर्तित DOCX फ़ाइल को केवल एक क्लिक से डाउनलोड कर सकते हैं।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी को परिवर्तित करने में कितना समय लगता है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">इस ऑनलाइन कनवर्टर की गति काफी हद तक परिवर्तित की जा रही FODS फ़ाइल के आकार से निर्धारित होती है। छोटी बीएमपी फाइलों को कुछ ही सेकंड में जीआईएफ में बदला जा सकता है। इसके अतिरिक्त, यदि आपने जावा एप्लिकेशन में रूपांतरण कोड शामिल किया है, तो एप्लिकेशन की दक्षता भी रूपांतरण प्रक्रिया को प्रभावित करेगी।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या मुक्त Aspose.Total कन्वर्टर का उपयोग करके FODS को DOCX में बदलना सुरक्षित है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बिल्कुल! रूपांतरण प्रक्रिया पूरी होने के बाद DOCX फ़ाइल के लिए एक डाउनलोड लिंक तुरंत उपलब्ध कराया जाएगा। अपलोड की गई फ़ाइलें 24 घंटों के बाद स्वचालित रूप से हटा दी जाती हैं, और डाउनलोड लिंक उस समय सीमा के बाद सक्रिय नहीं रहेंगे। आप निश्चिंत हो सकते हैं कि आपकी फ़ाइलें सुरक्षित हैं, और FODS सहित फ़ाइल रूपांतरण पूरी तरह से सुरक्षित है। मुफ्त ऐप को मुख्य रूप से परीक्षण उद्देश्यों के लिए एकीकृत किया गया है, जिससे आप अपने प्रोजेक्ट में कोड को एकीकृत करने से पहले परिणामों को सत्यापित कर सकते हैं।</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी कन्वर्ट करने के लिए मुझे किस ब्राउजर का इस्तेमाल करना चाहिए?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ऑनलाइन रूपांतरण के लिए, आप किसी भी आधुनिक वेब ब्राउज़र जैसे Google Chrome, Firefox, Opera, या Safari का उपयोग कर सकते हैं। हालाँकि, यदि आप एक डेस्कटॉप एप्लिकेशन विकसित कर रहे हैं, तो Aspose.Total FODS रूपांतरण API एक उत्कृष्ट विकल्प है क्योंकि इसे ऐसे वातावरण में निर्बाध रूप से काम करने के लिए डिज़ाइन किया गया है।</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}