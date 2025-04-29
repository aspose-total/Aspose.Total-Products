---
title: EML을 JPEG로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EML을 JPEG로 변환
url_ignore: /ko/net/conversion/eml-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: JPEG
otherformats: FLATOPC DOTX DOC PDF EPUB DOCM DOTM JPEG TEXT PCL PS OTT DOCX GIF MD XPS RTF SVG PNG WORDML DOT EMF TIFF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 JPEG로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EML을 JPEG로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EML을 JPEG로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EML 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 JPEG로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML을 JPEG로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 클래스를 사용하여 EML 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EML을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 JPEG 형식으로 저장하고 Jpeg를 SaveFormat으로 설정합니다.
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
EML을 JPEG로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EML 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/eml)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 JPEG 문서 편집 제한" %}}
EML에서 JPEG로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EML 파일을 JPEG로 변환: 사용 사례" %}}
EML (电子邮件) 文件用于存储基于文本的消息，因此它们是创建简单视觉化的邮件内容预览或摘录的理想选择。然而，当涉及到具有吸引眼球的图形和多媒体元素时，JPEG（联合摄影专家组）图片成为分享和展示数据的重要工具。

将 EML 文件转换为 JPEG 格式是必要的，以充分发挥您在数据呈现和共享方面的能力。这种转换使您能够：

**用途：**

* **电子邮件营销活动**：将 EML 文件转换为可视化的电子邮件活动，包括图片预览、社交媒体帖子和内容摘录。
* **新闻简报和博客**：使用 JPEG 展示电子邮件新闻简报和博客文章，使其对读者更具吸引力。
* **社交媒体分享**：将 EML 文件转换为在 Twitter、Facebook 或 LinkedIn 等社交平台上分享电子邮件内容，带有可视化图片。
* **电子邮件客户集成**：将 EML 文件转换以创建具有可视化界面和用户体验的定制电子邮件客户端。
* **数据呈现和报告**：使用 JPEG 以更吸引人的方式呈现数据，使利益相关者更容易理解复杂信息。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}