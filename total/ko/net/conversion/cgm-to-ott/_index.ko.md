---
title: CGM을 OTT으로 내보내기 위한 C# API
description: Microsoft Word를 사용하지 않고 CGM을 OTT으로 변환
url_ignore: /ko/net/conversion/cgm-to-ott/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTT
otherformats: OTT XAMLFLOW FLATOPC DOTX MHTML ODT DOTM PS WORDML RTF MARKDOWN DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 CGM을 OTT으로 렌더링" h2="Microsoft Word를 사용하지 않고 Windows, macOS 및 Linux에서 CGM을 OTT으로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)은 .NET 애플리케이션 내부에 문서 조작 및 변환 기능을 추가하는 강력한 API입니다. 고급 PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 CGM 파일 형식을 DOC로 변환할 수 있습니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)를 사용하여 DOC를 OTT으로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 OTT으로 변환하는 C# API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 문서로 변환
3. Aspose.Words의 [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 Doc 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 OTT 형식으로 저장하고 Ott을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 소유자 암호를 사용하여 CGM 파일 암호 해독" %}}
CGM을 OTT으로 변환하기 전에 문서의 암호를 해독하려면 API를 사용하면 됩니다. PDF 파일을 복호화하기 위해서는 먼저 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다. 이후 Document 객체의 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 메소드를 호출해야 합니다. 마지막으로 Document 개체의 Save 메서드를 사용하여 업데이트된 파일을 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 OTT 파일 만들기" %}}
OTT이 편집되지 않도록 보호하고 다른 사람이 문서에서 민감한 기밀 정보를 편집하지 못하도록 하기 위해 API를 사용하여 문서 보호를 설정할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용할 수 있습니다. 이는 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하여 수행할 수 있습니다. [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 OTT로 변환: 사용 사례" %}}
CGM (Computer Graphics Metafile) 파일을 오타입 텍스트 포맷으로 변환하는 것은, 원본의 텍스트 기반 데이터 시각화와 분석 기능을 최대한 활용할 수 있도록 합니다. 이 변환은以下用途에 적용할 수 있습니다:

**사용 사례:**

*   **로고 디자인**: CGM 파일을 오타입 텍스트 포맷으로 변환하여, 다양한 매체에서 깨끗하고清爽한 타이포그래피를 확보할 수 있습니다.
*   **폰트 특성 분석**: 오타입 텍스트 포맷을 통해 폰트의 특성을 분석하고, 사용 패턴을追跡하며 폰트 트렌드를 식별할 수 있습니다.
*   **브랜드링과 아이덴티티 개발**: CGM 파일을 통해 브랜드 아이덴티티를 확립하는 데 도움을 받을 수 있습니다. 이는 로고, 타이포그래피, 컬러 스키마까지 모두 포함한 통합적인 브랜드 이미지를 창출할 수 있습니다.
*   **프린트 디자인과 퍼블리싱**: CGM 파일을 통해 프로페셔널한 프린트 자료를 만들 수 있습니다. 예를 들어 브로셔, 플라이어, 포스터 등에 사용할 수 있습니다.
*   **데이터 리포팅과 다시보드 제작**: CGM 파일을 오타입 텍스트 포맷으로 변환하여, 스태업에서 인터랙티브한 داش보드를 만들고 데이터를 시각화할 수 있습니다. 이는 스테케홀러에게 더 나은 결정을 내릴 수 있도록 도와줍니다.

CGM 파일을 오타입 텍스트 포맷으로 변환하는 것은, 원본의 텍스트 기반 데이터 시각화와 분석 기능을 최대한 활용할 수 있도록 합니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}