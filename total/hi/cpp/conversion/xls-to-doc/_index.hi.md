---
title: C++ के साथ XLS को DOC में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: C++ अनुप्रयोगों के भीतर XLS को DOC में बदलें या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।

family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOC
otherformats: POWERPOINT WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ के माध्यम से XLS को DOC में बदलें या ऑनलाइन" h2="एक्सेल निर्यात करें&reg; पूर्ण-कार्यात्मक सी ++ अनुप्रयोगों के भीतर सीएसवी से डीओसी तक" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी++ पर सीएसवी से डीओसी रूपांतरण" %}}
1. [Factory](https://reference.aspose.com/cells) के सदस्य फ़ंक्शन [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) का उपयोग करके XLS फ़ाइल खोलें /cpp/class/aspose.cells.factory) वर्ग संदर्भ
2. XLS को PDF में बदलें और SaveFormat को Pdf में सेट करें
3. परिवर्तित पीडीएफ फाइल को [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को DOC प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");
// save XLS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>बीएमपी से जीआईएफ के लिए ऑनलाइन कन्वर्टर</h3>

<iframe title="doc से xls रूपांतरण ऑनलाइन टूल" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xls" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xls-to-doc/">बीएमपी से जीआईएफ रूपांतरण के लिए हमारा मुफ्त ऐप आज़माएं</a></p>
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
                          <span itemprop="text">बीएमपी रूपांतरण के लिए ऑनलाइन ऐप ऊपर एकीकृत है। बीएमपी से जीआईएफ रूपांतरण प्रक्रिया शुरू करने के लिए, बस अपनी बीएमपी फ़ाइल को निर्दिष्ट क्षेत्र में खींचकर और छोड़ कर या फ़ाइल आयात करने के लिए सफेद बॉक्स के अंदर क्लिक करके जोड़ें। फ़ाइल आयात हो जाने के बाद, रूपांतरण प्रक्रिया शुरू करने के लिए "कन्वर्ट" बटन पर क्लिक करें। बीएमपी से जीआईएफ रूपांतरण पूरा होने के बाद, आप अपनी नई रूपांतरित जीआईएफ फ़ाइल को केवल एक क्लिक के साथ तुरंत डाउनलोड कर सकते हैं।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी को परिवर्तित करने में कितना समय लगता है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">इस ऑनलाइन कन्वर्टर की गति काफी हद तक बीएमपी फ़ाइल के आकार पर निर्भर करती है। छोटी बीएमपी फाइलों को कुछ ही सेकंड में जीआईएफ में बदला जा सकता है। इसके अतिरिक्त, रूपांतरण प्रक्रिया की दक्षता इस आधार पर अलग-अलग होगी कि आपने अपने एप्लिकेशन को कैसे अनुकूलित किया है यदि आपने रूपांतरण कोड को C++ एप्लिकेशन के भीतर एकीकृत किया है।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या मुक्त Aspose.Total कन्वर्टर का उपयोग करके XLS को DOC में बदलना सुरक्षित है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बिल्कुल! बीएमपी से जीआईएफ रूपांतरण पूरा होने के बाद, आप प्रदान की गई डाउनलोड लिंक के माध्यम से अपनी परिवर्तित फ़ाइल को तुरंत डाउनलोड कर पाएंगे। हम अपलोड की गई फ़ाइलों को 24 घंटों के बाद हटा देते हैं, और इस समयावधि के बाद डाउनलोड लिंक काम नहीं करेंगे। आपको आश्वस्त किया जा सकता है कि फ़ाइल रूपांतरण, बीएमपी सहित, पूरी तरह से सुरक्षित और सुरक्षित है, क्योंकि आपकी फ़ाइलों तक किसी की पहुंच नहीं है। नि: शुल्क ऐप को परीक्षण उद्देश्यों के लिए ऊपर एकीकृत किया गया है, जिससे आप कोड को एकीकृत करने से पहले परिणामों की जांच कर सकते हैं।</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी कन्वर्ट करने के लिए मुझे किस ब्राउजर का इस्तेमाल करना चाहिए?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">आप किसी भी आधुनिक वेब ब्राउज़र जैसे Google Chrome, Firefox, Opera, या Safari का उपयोग करके इस ऑनलाइन कन्वर्टर तक पहुँच सकते हैं। हालाँकि, यदि आप डेस्कटॉप एप्लिकेशन पर काम कर रहे हैं, तो Aspose.Total XLS रूपांतरण API एक सहज समाधान प्रदान करता है।</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}