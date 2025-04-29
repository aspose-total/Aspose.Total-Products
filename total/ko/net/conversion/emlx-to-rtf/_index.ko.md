---
title: EMLX을 RTF로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMLX을 RTF로 변환
url_ignore: /ko/net/conversion/emlx-to-rtf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: RTF
otherformats: EMF EPUB TEXT OTT PS PNG GIF DOT DOC DOTM DOTX MD DOCM ODT JPEG XPS DOCX TIFF SVG WORDML PDF FLATOPC RTF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 RTF로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMLX을 RTF로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMLX을 RTF로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMLX 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 RTF로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX을 RTF로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMLX 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMLX을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 RTF 형식으로 저장하고 Rtf를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMLX 파일 구문 분석" %}}
EMLX을 RTF로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMLX 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 RTF 문서 편집 제한" %}}
EMLX에서 RTF로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMLX 파일을 RTF로 변환: 사용 사례" %}}
EMLX (전자메일 확장형) 파일은 텍스트 기반의 이메일 정보를 저장하기 위해 사용되는 파일로, 간단한 이메일 작성과 뉴스레터 등에 적합합니다. 그러나 구조화된 데이터 작업에서는 RTF (리치 텍스트 포맷) 파일이 문서 형식과 레이아웃을 위한 필수적인 도구로 작용합니다.

EMLX 파일에서 RTF 포맷으로의 전환은 문서의 완전한 레이아웃과 스타일 가능성을 풀어주는 데 있어 必요합니다. 이 전환을 통해 다음 기능을 활용할 수 있습니다:

**사용 사례:**

* **비즈니스 커뮤니케이션**:正式한 비즈니스 이메일, 제안서, 보고서 등을 작성하기 위해 폰 스타일, 크기, 색상 등에 대한 정확한 조절을 가능하게 합니다.
* **저널리스트 쓰기**: 기사, 편집논란, 보도稿 등을 포맷팅하여 출판물에서 일관적인 외부를 유지할 수 있습니다.
* **학문적 작성**: 연구보고서, 학位论文 등에 구조화된 문서를 작성하고格式과 레이아웃을 정확하게 조절할 수 있습니다.
* **마케팅 자료**: 브로셔, 플라이어, 카탈로그 등을 포맷팅하여 세부사항과视覚적 매력을 강조합니다.
* **기술 문서**: 사용자 매뉴얼, 인스트루션 가이드, 기술 사양서 등을 작성하고 헤더, 서브헤더, 포맷ting으로清晰한 구조를 만듭니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}