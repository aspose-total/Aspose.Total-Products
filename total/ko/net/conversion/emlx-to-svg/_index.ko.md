---
title: EMLX을 SVG로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMLX을 SVG로 변환
url_ignore: /ko/net/conversion/emlx-to-svg/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: SVG
otherformats: SVG ODT JPEG DOC WORDML DOTM EMF DOCX DOTX OTT FLATOPC RTF PS XPS GIF PNG MD PCL DOCM TEXT TIFF PDF DOT EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 SVG로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMLX을 SVG로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMLX을 SVG로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMLX 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 SVG로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX을 SVG로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMLX 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMLX을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 SVG 형식으로 저장하고 Svg를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMLX 파일 구문 분석" %}}
EMLX을 SVG로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMLX 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

```cs// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 SVG 문서 편집 제한" %}}
EMLX에서 SVG로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMLX 파일을 SVG로 변환: 사용 사례" %}}
**EMLX Conversion: Unlocking the Potential of Interactive Visualizations**

EMLX (이메일 메시지 포맷) 파일은 구조화된 데이터를 저장하기 위해 사용됩니다. 이 파일들은 정적 정보와 문서로만 활용할 수 있지만, 동적 시각화를 위한 SVG (Scalable Vector Graphics) 형식은 인터랙티브한 그래픽과 일러스트션을 만들기 위해 필수적입니다.

EMLX 파일들을 SVG 형식으로 전환하는 것은 당신의 시각화와 상호작용 가능성을 fullest로 활용할 수 있도록 합니다. 이 전환은 다음 기능을 사용할 수 있도록 합니다:

**Use Cases:**

*   **웹사이트 인터랙티브니스**: EMLX 파일을 SVG로 전환하여 动态적인 웹사이트 요소,如 호버 효과, 애니메이션, 및 인터렉티브한 지도 등을 만들 수 있습니다.
*   **소셜 미디어 앱게이트먼트**: SVG를 통해 소셜 미디어 데이터를 시각화하여_engaging한 인포그래픽과 인터랙티브한 스토리 등을 만듭니다.
*   **마케팅 컬래터럴**: EMLX 파일을 SVG로 전환하여_interactive한 마케팅 자료,如 브로셔, 플라이어, 및 프레젠테이션 등을 만들 수 있습니다.
*   **데이터 스토리텔링**: SVG를 통해 복잡한 데이터를 시각화하여_compelling한 스토리를 만드는 데 사용할 수 있습니다.
*   **게밍과 시물레이션**: EMLX 파일을 SVG로 전환하여_이머시브한 게밍 경험과 시물레이션을 만들 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}