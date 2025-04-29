---
title: MSG을 EMF로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 MSG을 EMF로 변환
url_ignore: /ko/net/conversion/msg-to-emf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EMF
otherformats: DOTX JPEG PCL OTT SVG PS ODT DOCX DOT DOCM EPUB XPS WORDML PNG MD TIFF TEXT DOC RTF EMF PDF FLATOPC DOTM GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 EMF로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 MSG을 EMF로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 MSG을 EMF로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 MSG 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 EMF로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSG을 EMF로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) 클래스를 사용하여 MSG 파일을 엽니다.
2. [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) 방법을 사용하여 MSG을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 EMF 형식으로 저장하고 Emf를 SaveFormat으로 설정합니다.
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

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 MSG 파일 구문 분석" %}}
MSG을 EMF로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 MSG 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/msg)의 [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 EMF 문서 편집 제한" %}}
MSG에서 EMF로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 MSG 파일을 EMF로 변환: 사용 사례" %}}
MSG 파일을 EMF 형식으로 변환하는 것은 이미지 편집 기능을 완전히 활용할 수 있도록 합니다. 이_conversion_은_이미지_편집_사능성을_완전히_활용할_수_있게_합니다.

**Use Cases:**

*   **그래픽_디자인_및_일러스트레이션**: MSG 파일을 EMF 형식으로 변환하여 정적 그래픽, 일러스트레이션, 및 예술작업을 생성할 수 있습니다.
*   **디지털_아트_보존**: EMF 형식으로 변환된 파일을 통해 디지털 아트를 보존하고, 호환성 문제 해결하고, 이미지의完整성을 유지할 수 있습니다.
*   **기술_스케치_및_CAD**: MSG 파일을 EMF 형식으로 변환하여 기술 스케치, CAD(컴퓨터_Aided_Design), 및 엔지니어링 애플리케이션을 지원할 수 있습니다.
*   **스크린_캡처_및_라스터화**: EMF 형식으로 변换된 파일을 통해 스크린 캡처를 진행하고, 래스터 그래픽스를 벡터 형식으로 전환하며, 스크린 렌더링 품질을 개선할 수 있습니다.
*   **디지털_시계_및_광고**: MSG 파일을 EMF 형식으로 변换하여 디지털 시계, 광고 자료, 및 인터랙티브 디스플레이를 생성할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}