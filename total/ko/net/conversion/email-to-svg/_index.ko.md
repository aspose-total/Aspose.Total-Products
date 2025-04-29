---
title: EMAIL을 SVG로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMAIL을 SVG로 변환
url_ignore: /ko/net/conversion/email-to-svg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: SVG
otherformats: PCL TIFF DOCX FLATOPC DOTX DOTM DOC MD XPS PS ODT RTF EPUB DOT SVG OTT TEXT GIF DOCM PDF WORDML EMF JPEG PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 SVG로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMAIL을 SVG로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMAIL을 SVG로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMAIL 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 SVG로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL을 SVG로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMAIL 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMAIL을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 SVG 형식으로 저장하고 Svg를 SaveFormat으로 설정합니다.
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

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMAIL 파일 구문 분석" %}}
EMAIL을 SVG로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMAIL 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 SVG 문서 편집 제한" %}}
EMAIL에서 SVG로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMAIL 파일을 SVG로 변환: 사용 사례" %}}
이메일 파일은 텍스트 기반 메시지를 저장하기 위해 사용되고, 이는 맞춤형 커뮤니케이션과 뉴스레터를 만들기 위한 이상적인 방법입니다. 그러나 시각적 콘텐츠를 다루는 경우, SVG (Scalable Vector Graphics) 같은 이미지 형식은 효과적인 커뮤니케이션과 브랜드링크에 필수적이 됩니다.

이메일 파일을 SVG 포맷으로 변환하는 것은 당신의 시각적 커뮤니케이션과 브랜드링크의 완전한 잠재력을 끌어내는 데 필요한 것입니다. 이 변환은 다음을 달성하기 위해 도움이 됩니다:

**사용 사례:**

* **브랜드링크 및 로고**: 이메일 템플릿을 SVG 기반으로 변환하여 다양한 매체에서 일관적인 브랜드 아셋을 만들 수 있습니다.
* **인포그래픽 및 시각화**: 데이터를 시각적으로 표현하고, 인터랙티브한 인포그래픽을 만들며, 복잡한 정보를清명하게 전달할 수 있습니다.
* **웹 및 모바일 디자인**: 이메일 뉴스레터를 SVG로 변환하여 반응형 웹과 모바일 디자이너가 다양한 스타일에서 일관적인 디자인을 만드는 데 도움이 됩니다.
* **소셜 미디어 및 마케팅 자료**: 브랜드 일관성을 유지한 SVG 기반의 소셜 아이콘과 그래픽스를 만들 수 있습니다.
* **전자상거래 및 온라인 스토어ーフ트**: 제품 그래픽스를 통해 3D 시물레이션을 시�션하고, 제품 정보를 상세하게 전달할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}