---
title: PS을 ODT으로 내보내기 위한 C# API
description: Microsoft Word를 사용하지 않고 PS을 ODT으로 변환
url_ignore: /ko/net/conversion/ps-to-odt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODT
otherformats: RTF WORDML DOTM ODT OTT DOTX XAMLFLOW FLATOPC DOT MHTML PCL MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 PS을 ODT으로 렌더링" h2="Microsoft Word를 사용하지 않고 Windows, macOS 및 Linux에서 PS을 ODT으로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)은 .NET 애플리케이션 내부에 문서 조작 및 변환 기능을 추가하는 강력한 API입니다. 고급 PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 PS 파일 형식을 DOC로 변환할 수 있습니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)를 사용하여 DOC를 ODT으로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PS을 ODT으로 변환하는 C# API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 PS 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 PS을 문서로 변환
3. Aspose.Words의 [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 Doc 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 ODT 형식으로 저장하고 Odt을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 소유자 암호를 사용하여 PS 파일 암호 해독" %}}
PS을 ODT으로 변환하기 전에 문서의 암호를 해독하려면 API를 사용하면 됩니다. PDF 파일을 복호화하기 위해서는 먼저 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 객체를 생성하고 소유자의 비밀번호로 PS을 열어야 합니다. 이후 Document 객체의 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 메소드를 호출해야 합니다. 마지막으로 Document 개체의 Save 메서드를 사용하여 업데이트된 파일을 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 ODT 파일 만들기" %}}
ODT이 편집되지 않도록 보호하고 다른 사람이 문서에서 민감한 기밀 정보를 편집하지 못하도록 하기 위해 API를 사용하여 문서 보호를 설정할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용할 수 있습니다. 이는 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하여 수행할 수 있습니다. [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 PS 파일을 ODT로 변환: 사용 사례" %}}
PS (포트ABLE 닌텍 포맷) 파일들은 문서를 저장하기 위해 이상적인 정적 문서와 출판물에 사용됩니다. 그러나 동적 데이터를 작업할 때, 스페레드시트들처럼 OpenDocument Text (ODT)가 문서 편집과 협업에 필수적인 것입니다.

OpenDocument Text로 PS 파일들을 변환하는 것은您的 문서 편집과 협업 기능을 전면 활용을 가능하게 합니다. 이 변환은以下 목표를 달성할 수 있도록 도와줍니다:

**사용목적:**

*   **학术 연구**: 학术 논문, 석사论文, 博士논문을 편집하고 협업을 진행하며 연구 결과를 공유할 수 있습니다.
*   **기술 문서 작성**: OpenDocument Text를 사용하여 기술 문서를 만들고 편집할 수 있습니다. 예를 들어 소프트웨어 응용 프로그램, 하드웨어 장치, 그리고 엔지니어링 과정에 대한 사용자 매뉴얼, 안내서, 및 지침을 작성할 수 있습니다.
*   **비즈니스 발표**: PS 파일들을 통해 유용한 발표 자료를 만드는 데 도움이 됩니다. OpenDocument Text를 활용하여 기업 내의 커뮤니케이션, 비즈니스 미팅, 및 산업 행사를 위한 보고서, 제안서, 및 발표자료를 만들 수 있습니다.
*   **출판과 매체**: 기사, 이야기, 기타 콘텐츠를 편집하고 출판물에 올리실 수 있습니다. OpenDocument Text를 사용하여 웹사이트, 온라인 메ディア 플랫� 등에서 게시할 수 있는 콘텐츠를 만듭니다.
*   **개인적인 프로젝트**: 맞춤형 문서를 만들고 개인적인 용도로 사용할 수 있습니다. 예를 들어 이력서, 자격증, 편지 등을 OpenDocument Text로 만들 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}