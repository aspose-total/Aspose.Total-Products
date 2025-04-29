---
title: EMAIL을 EPUB로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMAIL을 EPUB로 변환
url_ignore: /ko/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 EPUB로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMAIL을 EPUB로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMAIL을 EPUB로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMAIL 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 EPUB로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL을 EPUB로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMAIL 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMAIL을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 EPUB 형식으로 저장하고 Epub를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMAIL 파일 구문 분석" %}}
EMAIL을 EPUB로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMAIL 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 EPUB 문서 편집 제한" %}}
EMAIL에서 EPUB로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMAIL 파일을 EPUB로 변환: 사용 사례" %}}
이메일 파일은 텍스트 기반 메시지를 저장하기 위해 사용되는 파일로, 개인화된 커뮤니케이션 및 뉴스레터를 만들기 위한 이상적인 格으로서 활용됩니다. 그러나 멀티미디어 콘텐츠를 작업할 때, EPUB (전자 퍼블리케이션) 포맷은 디지털 퍼블리싱과 책 배포에 필수적이 됩니다.

이메일 파일을 EPUB 포맷으로 변환하는 것은 당신의 디지털 퍼블리싱 능력을 완전히 활용하기 위해 必요합니다. 이 변환은 다음을 위한 방법으로서 사용할 수 있습니다:

**사용 사례:**

* **개인화된 E-뉴스레터:** 이메일 파일을 EPUB 포맷으로 변환하여, 구독자 이름과 관심 분야에 맞춘 유용한 E-뉴스레터를 만들 수 있습니다.
* **디지털 잡지 발행:** EPUB 포맷을 사용하여 잡지, 신문, 주간지를 디지털로 발행하고, 다양한 기기에서 읽기 쉬운 형식으로 배포할 수 있습니다.
* **전자 책 발행:** 이메일 파일을 EPUB 포맷으로 변환하여, 링크, 이미지, 멀티미디어 콘텐츠가 포함된 인터랙티브한 전자 책을 만들 수 있습니다.
* **기업 커뮤니케이션:** EPUB 포맷을 통해 회사 보고서, 정책, 절차를 사원과 이해관계자에게 액세스 가능한 형식으로 배포할 수 있습니다.
* **디지털 콘텐츠 배급:** 이메일 파일을 EPUB 포맷으로 변환하여 블로그 게시물, 기사, 영상을 다양한 플랫�에서 발행하고 배포할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}