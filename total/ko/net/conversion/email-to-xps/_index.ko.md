---
title: EMAIL을 XPS로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMAIL을 XPS로 변환
url_ignore: /ko/net/conversion/email-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: ODT DOTM DOCX PDF JPEG TEXT DOCM WORDML RTF PS PNG TIFF DOTX EMF XPS GIF MD DOC OTT DOT SVG PCL EPUB FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 XPS로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMAIL을 XPS로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMAIL을 XPS로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMAIL 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 XPS로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL을 XPS로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMAIL 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMAIL을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 XPS 형식으로 저장하고 Xps를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMAIL 파일 구문 분석" %}}
EMAIL을 XPS로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMAIL 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 XPS 문서 편집 제한" %}}
EMAIL에서 XPS로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMAIL 파일을 XPS로 변환: 사용 사례" %}}
이메일에서 엾스 파일로 변환하기: 시각적 콘텐츠의 잠재력을 깨워보세요.

이메일은 통신 수단으로서 중요한 역할을 하지만, 시각적 콘텐츠와 같은 자료를 전송할 때는 한계가 있습니다. 다른 포맷，如 PDF나 엾스 파일처럼 원본 그래픽과 레이아웃을 그대로保전하는 데 비해, 이메일은 이미지 품질과 포맷ting이 전송 과정에서 손실될 수 있습니다.

그렇기 때문에 변환이 필요합니다. 이메일을 엾스 파일로 변换하기는 간단한 과정이며, 다음을 달성할 수 있습니다:

**사용 사례:**

* **시각적 콘텐츠 보호:** 이메일을 엾스 파일로 변환하여 시각적 콘텐츠가 전송或存档될 때 손실되지 않게 보장합니다.
* **인쇄 дружoso 통신:** 엾스 파일을 활용하여 인쇄할 수 있는 이메일 버전을 만들 수 있습니다. 이는 발표, 보고서, 기타 공식 통신에 적합한 자료입니다.
* **보안 및 규제 준수:** 중요한 시각적 콘텐츠를 보호하기 위해 규제 요구사항을 만족하고 보안을 강화할 수 있습니다.
* **아카이브 및 보존:** 엾스 파일로 저장하여 이메일附件과 이미지에 대한 후속 참조나 규제 목표 달성에 도움이 됩니다.
* **접근성 및包容性:** 시각적으로 장애 있는 사용자에게 대안적인 포맷을 제공하여 접근성을 향상시킬 수 있습니다.

이메일을 엾스 파일로 변환하면, 시각적 콘텐츠의 모든 잠재력을 전부 발휘할 수 있습니다. 그 콘텐츠가 활기차 있게 보존되고 있을 것입니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}