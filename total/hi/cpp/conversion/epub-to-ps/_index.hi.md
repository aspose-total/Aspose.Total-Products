---
title: डीओसीएम को सीजीएम निर्यात करने के लिए सी ++ एपीआई
description: सी ++ अनुप्रयोगों के भीतर सीजीएम को डीओसीएम में कनवर्ट करें।

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PS
otherformats: MHTML OTT RTF PCL DOTX XAMLFLOW FLATOPC DOT DOCM DOTM ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="डीओसीएम को सीजीएम निर्यात करने के लिए सी ++ एपीआई" h2="किसी तीसरे पक्ष के आवेदन की आवश्यकता के बिना सी ++ अनुप्रयोगों के भीतर डीओसीएम को सीजीएम प्रस्तुत करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी C++ डेवलपर को दो आसान चरणों में EPUB को PS में बदलने की अनुमति देती है। सबसे पहले, आप EPUB फ़ाइल स्वरूप को DOC में बदलने के लिए [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API का उपयोग कर सकते हैं। दूसरे, उन्नत वर्ड डॉक्यूमेंट प्रोसेसिंग एपीआई [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके, आप PS को DOC निर्यात कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="डीओसीएम को सीजीएम प्रस्तुत करने के लिए सी ++ एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) सदस्य फ़ंक्शन का उपयोग करके EPUB को DOC में बदलें
3. Aspose.Words API के [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग संदर्भ का उपयोग करके DOC फ़ाइल लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को PS प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Ps
wordDoc->Save(u"output.Ps");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से EPUB दस्तावेज़ का पासवर्ड बदलें" %}}
डीओसीएम को सीजीएम प्रदान करने की प्रक्रिया में, आप पासवर्ड से सुरक्षित सीजीएम खोल सकते हैं और उसका पासवर्ड भी बदल सकते हैं। EPUB फ़ाइल का पासवर्ड बदलने के लिए, आपको उस दस्तावेज़ के स्वामी का पासवर्ड पता होना चाहिए। आप पासवर्ड से सुरक्षित PDF दस्तावेज़ को [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) के साथ लोड कर सकते हैं और पासवर्ड बदलने के लिए ChangePasswords पद्धति का उपयोग कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से PS फ़ाइल संपादन को प्रतिबंधित करें" %}}
आप [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API का उपयोग करके PS फ़ाइल संपादन को प्रतिबंधित भी कर सकते हैं। कभी-कभी आपको किसी दस्तावेज़ को संपादित करने की क्षमता को सीमित करना पड़ सकता है और इसके साथ केवल कुछ क्रियाओं की अनुमति देनी पड़ सकती है। API आपको [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) एन्यूमरेशन पैरामीटर का उपयोग करके सामग्री को प्रतिबंधित करने के तरीके को नियंत्रित करने में सक्षम बनाता है। निम्न कोड उदाहरण दर्शाता है कि किसी दस्तावेज़ में संपादन को कैसे प्रतिबंधित किया जाए ताकि केवल प्रपत्र फ़ील्ड में संपादन संभव हो।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Ps");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}