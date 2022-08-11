---
title: C++를 통해 이메일을 DOCM로 내보내기
description: Microsoft Word 또는 Outlook을 사용하지 않고 EMLX을 DOCM로 변환하는 C++ API
url: /ko/cpp/conversion/emlx-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOCM
otherformats: WORDML GIF DOCX MD TEXT RTF BMP DOTM SVG FLATOPC EMF ODT OTT JPEG XPS PNG TIFF DOTX PS EPUB PCL DOC PDF DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EMLX을 DOCM로 내보내기 위한 C++ API" h2="Microsoft Word 또는 Outlook 없이 C++ 애플리케이션 내에서 EMLX을 DOCM로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 이메일 변환 기능을 추가하려는 C++ 개발자입니까? [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/)를 사용하여 EMLX 파일 형식을 HTML로 변환할 수 있습니다. 그 후 [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API를 사용하여 HTML을 DOCM로 내보낼 수 있습니다. 두 API 모두 [C++용 Aspose.Total](https://products.aspose.com/total/cpp/) 패키지에 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX을 DOCM로 변환하는 C++ API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) 클래스 참조를 사용하여 EMLX 파일을 엽니다.
2. [저장](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) 멤버 함수를 사용하여 EMLX을 HTML로 변환
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스를 사용하여 HTML 로드
4. [저장](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 방법을 사용하여 문서를 DOCM 형식으로 저장하고 Docm를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docm as save format
doc->Save(u"convertedFile.Docm");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 EMLX 파일 구문 분석" %}}
EMLX을 DOCM로 변환할 수 있을 뿐만 아니라 EMLX 문서를 읽고, 조작하고, 구문 분석할 수 있습니다. [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API의 MapiMessage 클래스를 이용하여 이메일의 제목, 주소, 본문, 수신자 정보를 얻을 수 있습니다. 예를 들어 get_SenderEmlxAddress() 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DOCM 파일 형식 편집을 제한하는 C++ API" %}}
EMLX에서 DOCM로 문서를 내보내는 동안 앱에 문서 보호 기능을 추가할 수도 있습니다. 문서에 보호 기능을 추가하는 것은 문서에 보호 방법을 적용하기만 하면 되므로 간단한 프로세스입니다. 보호 유형을 읽기 전용으로 설정하여 사용자가 문서를 편집하도록 제한할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docm");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-wordml/" name="EMLX 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-gif/" name="EMLX 에게 GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-docx/" name="EMLX 에게 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-md/" name="EMLX 에게 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-text/" name="EMLX 에게 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-rtf/" name="EMLX 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-docm/" name="EMLX 에게 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-dotm/" name="EMLX 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-svg/" name="EMLX 에게 SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-flatopc/" name="EMLX 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-emf/" name="EMLX 에게 EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-odt/" name="EMLX 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-ott/" name="EMLX 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-jpeg/" name="EMLX 에게 JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-xps/" name="EMLX 에게 XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-png/" name="EMLX 에게 PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-tiff/" name="EMLX 에게 TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-dotx/" name="EMLX 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-ps/" name="EMLX 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-epub/" name="EMLX 에게 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-pcl/" name="EMLX 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-doc/" name="EMLX 에게 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-pdf/" name="EMLX 에게 PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/emlx-to-dot/" name="EMLX 에게 DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}