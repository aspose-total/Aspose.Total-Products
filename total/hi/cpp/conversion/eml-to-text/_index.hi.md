---
title: C++ के माध्यम से EML को TEXT में निर्यात करें
description: सी ++ एपीआई माइक्रोसॉफ्ट वर्ड या आउटलुक का उपयोग किए बिना ईमेल को बीएमपी में कनवर्ट करने के लिए

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: TEXT
otherformats: EMF JPEG OTT XPS DOTX PNG BMP SVG EPUB DOT FLATOPC PS GIF MD PCL DOCX DOC ODT PDF TIFF DOTM WORDML RTF DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ईमेल को बीएमपी में निर्यात करने के लिए सी++ एपीआई" h2="Microsoft Word या Outlook की आवश्यकता के बिना C++ एप्लिकेशन के भीतर EML को TEXT में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
क्या आप एक C++ डेवलपर हैं जो आपके एप्लिकेशन के अंदर ईमेल रूपांतरण सुविधाओं को जोड़ना चाहते हैं? [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) का उपयोग करके आप EML फ़ाइल स्वरूप को HTML में बदल सकते हैं। उसके बाद, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API का उपयोग करके, आप HTML को TEXT में निर्यात कर सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई ईमेल को बीएमपी में कनवर्ट करने के लिए" %}}
1. [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) वर्ग संदर्भ का उपयोग करके EML फ़ाइल खोलें
2. [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) सदस्य फ़ंक्शन का उपयोग करके EML को HTML में बदलें
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग का उपयोग करके HTML लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) विधि का उपयोग करके दस्तावेज़ को TEXT प्रारूप में सहेजें और Text को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Text as save format
doc->Save(u"convertedFile.Text");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ के माध्यम से ईमेल फ़ाइल को पार्स करें" %}}
आप न केवल अपने EML को TEXT में बदल सकते हैं, बल्कि आप EML दस्तावेज़ को पढ़ सकते हैं, उसमें हेरफेर कर सकते हैं और उसका विश्लेषण कर सकते हैं। आप [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API के MapiMessage वर्ग का उपयोग करके ईमेल के विषय, पता, मुख्य भाग, प्राप्तकर्ताओं की जानकारी प्राप्त कर सकते हैं। उदाहरण के लिए, आप get_SenderEmlAddress() प्रॉपर्टी का उपयोग करके रूपांतरण के लिए एक विशिष्ट प्रेषक ईमेल की जांच कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ एपीआई बीएमपी फ़ाइल प्रारूप संपादन को प्रतिबंधित करने के लिए" %}}
दस्तावेज़ को EML से TEXT में निर्यात करते समय आप अपने ऐप में दस्तावेज़ सुरक्षा सुविधाएँ भी जोड़ सकते हैं। अपने दस्तावेज़ में सुरक्षा जोड़ना एक सरल प्रक्रिया है, क्योंकि आपको केवल अपने दस्तावेज़ में सुरक्षा पद्धति लागू करने की आवश्यकता है। दस्तावेज़ को संपादित करने के लिए उपयोगकर्ता को प्रतिबंधित करने के लिए आप सुरक्षा प्रकार को केवल पढ़ने के लिए सेट कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Text");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}