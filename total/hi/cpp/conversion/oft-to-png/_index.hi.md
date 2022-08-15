---
title: C++ के माध्यम से OFT को PNG में निर्यात करें
description: सी ++ एपीआई माइक्रोसॉफ्ट वर्ड या आउटलुक का उपयोग किए बिना ईमेल को बीएमपी में कनवर्ट करने के लिए
url: /hi/cpp/conversion/oft-to-png/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PNG
otherformats: DOTX DOT DOCM PDF MD DOTM DOCX SVG XPS PCL GIF EPUB TIFF RTF JPEG DOC WORDML OTT PS TEXT ODT EMF BMP FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="ईमेल को बीएमपी में निर्यात करने के लिए सी++ एपीआई" h2="Microsoft Word या Outlook की आवश्यकता के बिना C++ एप्लिकेशन के भीतर OFT को PNG में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
क्या आप एक C++ डेवलपर हैं जो आपके एप्लिकेशन के अंदर ईमेल रूपांतरण सुविधाओं को जोड़ना चाहते हैं? [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) का उपयोग करके आप OFT फ़ाइल स्वरूप को HTML में बदल सकते हैं। उसके बाद, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API का उपयोग करके, आप HTML को PNG में निर्यात कर सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई ईमेल को बीएमपी में कनवर्ट करने के लिए" %}}
1. [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) वर्ग संदर्भ का उपयोग करके OFT फ़ाइल खोलें
2. [सहेजें](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) सदस्य फ़ंक्शन का उपयोग करके OFT को HTML में बदलें
3. [दस्तावेज़](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग का उपयोग करके HTML लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) विधि का उपयोग करके दस्तावेज़ को PNG प्रारूप में सहेजें और Png को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ के माध्यम से ईमेल फ़ाइल को पार्स करें" %}}
आप न केवल अपने OFT को PNG में बदल सकते हैं, बल्कि आप OFT दस्तावेज़ को पढ़ सकते हैं, उसमें हेरफेर कर सकते हैं और उसका विश्लेषण कर सकते हैं। आप [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API के MapiMessage वर्ग का उपयोग करके ईमेल के विषय, पता, मुख्य भाग, प्राप्तकर्ताओं की जानकारी प्राप्त कर सकते हैं। उदाहरण के लिए, आप get_SenderOftAddress() प्रॉपर्टी का उपयोग करके रूपांतरण के लिए एक विशिष्ट प्रेषक ईमेल की जांच कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ एपीआई बीएमपी फ़ाइल प्रारूप संपादन को प्रतिबंधित करने के लिए" %}}
दस्तावेज़ को OFT से PNG में निर्यात करते समय आप अपने ऐप में दस्तावेज़ सुरक्षा सुविधाएँ भी जोड़ सकते हैं। अपने दस्तावेज़ में सुरक्षा जोड़ना एक सरल प्रक्रिया है, क्योंकि आपको केवल अपने दस्तावेज़ में सुरक्षा पद्धति लागू करने की आवश्यकता है। दस्तावेज़ को संपादित करने के लिए उपयोगकर्ता को प्रतिबंधित करने के लिए आप सुरक्षा प्रकार को केवल पढ़ने के लिए सेट कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-dotx/" name="OFT प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-dot/" name="OFT प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-docm/" name="OFT प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-pdf/" name="OFT प्रति PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-md/" name="OFT प्रति MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-dotm/" name="OFT प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-docx/" name="OFT प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-svg/" name="OFT प्रति SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-xps/" name="OFT प्रति XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-pcl/" name="OFT प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-gif/" name="OFT प्रति GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-epub/" name="OFT प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-tiff/" name="OFT प्रति TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-rtf/" name="OFT प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-jpeg/" name="OFT प्रति JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-doc/" name="OFT प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-wordml/" name="OFT प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-ott/" name="OFT प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-ps/" name="OFT प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-text/" name="OFT प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-odt/" name="OFT प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-emf/" name="OFT प्रति EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-png/" name="OFT प्रति PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/oft-to-flatopc/" name="OFT प्रति FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}