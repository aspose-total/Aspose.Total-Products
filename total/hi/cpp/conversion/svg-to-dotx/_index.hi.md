---
title: डीओसीएम को सीजीएम निर्यात करने के लिए सी ++ एपीआई
description: सी ++ अनुप्रयोगों के भीतर सीजीएम को डीओसीएम में कनवर्ट करें।

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOTX
otherformats: PCL WORDML ODT OTT DOCM RTF PS XAMLFLOW MARKDOWN DOTM FLATOPC MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="डीओसीएम को सीजीएम निर्यात करने के लिए सी ++ एपीआई" h2="किसी तीसरे पक्ष के आवेदन की आवश्यकता के बिना सी ++ अनुप्रयोगों के भीतर डीओसीएम को सीजीएम प्रस्तुत करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी C++ डेवलपर को दो आसान चरणों में SVG को DOTX में बदलने की अनुमति देती है। सबसे पहले, आप SVG फ़ाइल स्वरूप को DOC में बदलने के लिए [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API का उपयोग कर सकते हैं। दूसरे, उन्नत वर्ड डॉक्यूमेंट प्रोसेसिंग एपीआई [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके, आप DOTX को DOC निर्यात कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="डीओसीएम को सीजीएम प्रस्तुत करने के लिए सी ++ एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) सदस्य फ़ंक्शन का उपयोग करके SVG को DOC में बदलें
3. Aspose.Words API के [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग संदर्भ का उपयोग करके DOC फ़ाइल लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को DOTX प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotx
wordDoc->Save(u"output.Dotx");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से SVG दस्तावेज़ का पासवर्ड बदलें" %}}
डीओसीएम को सीजीएम प्रदान करने की प्रक्रिया में, आप पासवर्ड से सुरक्षित सीजीएम खोल सकते हैं और उसका पासवर्ड भी बदल सकते हैं। SVG फ़ाइल का पासवर्ड बदलने के लिए, आपको उस दस्तावेज़ के स्वामी का पासवर्ड पता होना चाहिए। आप पासवर्ड से सुरक्षित PDF दस्तावेज़ को [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) के साथ लोड कर सकते हैं और पासवर्ड बदलने के लिए ChangePasswords पद्धति का उपयोग कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से DOTX फ़ाइल संपादन को प्रतिबंधित करें" %}}
आप [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API का उपयोग करके DOTX फ़ाइल संपादन को प्रतिबंधित भी कर सकते हैं। कभी-कभी आपको किसी दस्तावेज़ को संपादित करने की क्षमता को सीमित करना पड़ सकता है और इसके साथ केवल कुछ क्रियाओं की अनुमति देनी पड़ सकती है। API आपको [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) एन्यूमरेशन पैरामीटर का उपयोग करके सामग्री को प्रतिबंधित करने के तरीके को नियंत्रित करने में सक्षम बनाता है। निम्न कोड उदाहरण दर्शाता है कि किसी दस्तावेज़ में संपादन को कैसे प्रतिबंधित किया जाए ताकि केवल प्रपत्र फ़ील्ड में संपादन संभव हो।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotx");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-pcl/" name="SVG प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-wordml/" name="SVG प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-odt/" name="SVG प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-ott/" name="SVG प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-dotx/" name="SVG प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-rtf/" name="SVG प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-ps/" name="SVG प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-xamlflow/" name="SVG प्रति XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-markdown/" name="SVG प्रति MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-dotm/" name="SVG प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-flatopc/" name="SVG प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-mhtml/" name="SVG प्रति MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}