---
title: EML을 PDF로 내보내는 C# API
description: .NET에서 Microsoft Word 또는 Outlook을 사용하지 않고 EML을 PDF로 변환
url_ignore: /ko/net/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOCX DOC SVG FLATOPC WORDML MD PNG TIFF DOTM DOT XPS TEXT EPUB DOCM JPEG GIF PS DOTX RTF PDF OTT EMF ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 이메일을 PDF로 내보내기" h2="Word 또는 Outlook을 사용하지 않고 Windows, macOS 및 Linux에서 EML을 PDF로 렌더링하는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
애플리케이션 내부에 EML을 PDF로 변환 기능을 추가하려는 .NET 개발자라면 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 파일 형식 조작 API를 사용하는 것이 좋습니다. 앞으로. [Aspose.Email for .NET](https://products.aspose.com/email/net/)을 사용하여 EML 파일 형식을 HTML로 변환할 수 있습니다. 그런 다음 [Aspose.Words for .NET](https://products.aspose.com/words/net/)을 사용하여 HTML을 PDF로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML을 PDF로 변환하는 C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) 클래스를 사용하여 EML 파일을 엽니다.
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) 방법을 사용하여 EML을 HTML로 변환합니다.
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

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 EML 파일 구문 분석" %}}
EML을 PDF로 변환하기 전에 올바른 이메일을 변환하고 있는지 확인하려면 EML 문서를 로드하고 구문 분석한 다음 원하는 속성을 살펴보세요. [Aspose.Email for .NET](https://products.aspose.com/eml)의 [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) 클래스를 사용하여 /net/) API를 사용하여 발신자 및 수신자 정보를 얻을 수 있습니다. 예를 들어 [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) 속성을 사용하여 변환할 특정 발신자 이메일을 확인할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통한 PDF 문서 편집 제한" %}}
EML에서 PDF로 문서를 저장하는 동안 출력 문서를 보호해야 할 수 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. 이는 다른 사람이 문서에서 민감한 기밀 정보를 편집하는 것을 방지하는 데 유용할 수 있습니다. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하면 [ProtectionType](https://apireference.aspose.net)을 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. com/words/net/aspose.words/protectiontype) 열거 매개변수. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EML 파일을 PDF로 변환: 사용 사례" %}}
EML (전자 메일) 파일은 텍스트 기반 메시지를 저장하기 위해 사용되는 파일로, 이메일을 보내고 받는 데 적합한 것입니다. 그러나 프로페셔널한 문서로 보이도록 만들기 위해 PDF가 필요한 경우가 있습니다. PDF는 프린트 온 디맨드, 전자 서명, 그리고 디지털 아카이브에 있어서 필수적인 파일 형식입니다.

EML 파일을 PDF로 변환하는 것은 이 파일의 풀潜력을 unlocks하고, 문서 액세스성 기능을 활성화하는 데 기여합니다. 이 변환은 다음을 달성할 수 있도록 합니다:

**사용 사례:**

* **프로페셔널한 문서**: EML 파일을 PDF로 변换하여 제안서, 계약서, 그리고 발표 자료를 만들 수 있습니다.
* **전자 서명과 디지털 아카이브**: PDF를 통해 안전한 전자 서명을 지원하고, 중요한 문서를 디지털 아카이브에 저장할 수 있습니다. 이 과정은 법규적 요구사항에 부합하는 것을 보장합니다.
* **프린트 온 디맨드**: EML 파일을 PDF로 변환하여 고품질의 인쇄 자료를 생산할 수 있습니다. 이러한 자료는 마케팅 캠페ーン과 이벤트에 활용될 수 있습니다.
* **액세스성과包容性**: PDF를 통해 장애인에게도 문서를 읽을 수 있도록 스캔 또는 형식화된 텍스트 포맷으로 변환할 수 있습니다.
* **디지털 배포와 협업**: EML 파일을 PDF로 변换하여 이메일이나 온라인 협업 플랫폼을 통해 안전하게 문서를 공유하고, 워크플로우를 개선하고 생산성을 높일 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}