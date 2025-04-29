---
title: EMLX을 PDF로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EMLX을 PDF로 변환
url_ignore: /ko/net/conversion/emlx-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PDF
otherformats: MD XPS SVG TEXT WORDML DOT DOTX FLATOPC TIFF DOCX EMF OTT ODT DOC EPUB DOTM JPEG PS PNG GIF DOCM PCL PDF RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 PDF로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EMLX을 PDF로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EMLX을 PDF로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EMLX 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 PDF로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX을 PDF로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) 클래스를 사용하여 EMLX 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EMLX을 HTML로 변환합니다.
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 HTML 로드
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 PDF 형식으로 저장하고 Pdf를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EMLX 파일 구문 분석" %}}
EMLX을 PDF로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EMLX 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/email)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 PDF 문서 편집 제한" %}}
EMLX에서 PDF로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EMLX 파일을 PDF로 변환: 사용 사례" %}}
이메일 교환 파일(EMLX)은 이메일 기반의 정보를 저장하기 위해 사용되는 파일로, 이를 통해 과거의通信을 영원히 보존할 수 있는 디지털 아카이브를 만들기에 적합합니다. 그러나 시각적 콘텐츠를 공유하고 보존할 때, PDF 형식은 문서를 전달하고-long-term preservation-에 가장 적합한 파일 형식입니다.

EMLX 파일을 PDF로 변환하는 것은 당신의 디지털 아카이브功能을 최대한 활용할 수 있도록 합니다. 이 변환은 다음을 달성하기 위해 사용됩니다:

**사용 사례:**

* **디지털 아카이브:** 과거의 이메일 대화, 첨부 파일, 발신자 정보를 영원히 기록하여 저장하고 있습니다.
* **문서 보존:** 계약, 협약, 모임 기록 등 중요한 문서를 법적 목표로-long-term reference-에 보존할 수 있도록 합니다.
* **전자 상거래 주문 추踪:** 배송 정보, 결제记录, 고객 대화 등을 추적하기 위해 EMLX 파일을 PDF로 변환합니다.
* **기술 지원 문서화:** 기술 매뉴얼, 가이드, 문제 해결 자료를 지원 팀에게 제공하여 사용할 수 있습니다.
* **법规 준수 보고서:** 이메일 파일을 통해_AUDIT TRAIL, 사건 로그, 보안 위험 등을 보고하기 위해 PDF로 변환합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}