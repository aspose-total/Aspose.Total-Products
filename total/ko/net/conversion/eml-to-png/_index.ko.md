---
title: EML을 PNG로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EML을 PNG로 변환
url_ignore: /ko/net/conversion/eml-to-png/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EPUB TIFF MD EMF ODT PDF DOTX JPEG PCL DOCX FLATOPC PS DOT DOCM TEXT WORDML OTT RTF GIF SVG XPS DOC DOTM PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 PNG로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EML을 PNG로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EML을 PNG로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EML 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 PNG로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML을 PNG로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 클래스를 사용하여 EML 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EML을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 PNG 형식으로 저장하고 Png를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EML 파일 구문 분석" %}}
EML을 PNG로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EML 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/eml)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 PNG 문서 편집 제한" %}}
EML에서 PNG로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EML 파일을 PNG로 변환: 사용 사례" %}}
이메일 마크업 언어 (EML) 파일은 이메일 기반의 정보를 저장하기 위해 사용되는 텍스트 기반 파일로, 메시지를 보내기와 받는 데 적합합니다. 그러나 시각적 콘텐츠를 다루어야 할 때, PNG 형식 같은 이미지 파일이 그래픽과 일러스트를 표현하는 데 필수적입니다.

이메일 마크업 언어 (EML) 파일을 PNG 형식으로 변환하는 것은 시각적 콘텐츠 표현 능력의 완전성을 이끄는 데 있어 必요합니다. 이 변환은 다음을 달성하기 위해 사용됩니다:

**사용 사례:**

*   **소셜 미디어 그래픽**: EML 파일을 PNG으로 변환하여 아름다운 소셜 미디어 그래픽, 광고, 및 홍보 자료를 만들 수 있습니다.
*   **이메일 마케팅 캠페ーン**: PNG을 사용하여 이메일 마케팅 캠페ーン을 시각적으로 표현하고 디자인을 최적화하며 참여율을 측정할 수 있습니다.
*   **웹페이지 그래픽**: EML 파일을 PNG으로 변환하여 인터랙티브한 웹페이지 그래픽을 만들며 사용자 경험을 모사할 수 있습니다.
*   **블로그 포스트 일러스트**: PNG을 사용하여 블로그 포스트의 일러스트를 시각적으로 표현하고 독자를 끌어올리실 수 있습니다.
*   **presentation 자료**: EML 파일을 PNG으로 변환하여 프로페셔널한 presentation 자료를 만들며 데이터 비주화, 차트, 및 그래프를 효과적으로 표현할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}