---
title: CGM을 DOTX으로 내보내기 위한 C# API
description: Microsoft Word를 사용하지 않고 CGM을 DOTX으로 변환
url_ignore: /ko/net/conversion/cgm-to-dotx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTX
otherformats: ODT RTF MHTML MARKDOWN DOTX PS WORDML DOTM XAMLFLOW OTT FLATOPC PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 CGM을 DOTX으로 렌더링" h2="Microsoft Word를 사용하지 않고 Windows, macOS 및 Linux에서 CGM을 DOTX으로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)은 .NET 애플리케이션 내부에 문서 조작 및 변환 기능을 추가하는 강력한 API입니다. 고급 PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 CGM 파일 형식을 DOC로 변환할 수 있습니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)를 사용하여 DOC를 DOTX으로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 DOTX으로 변환하는 C# API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 CGM을 문서로 변환
3. Aspose.Words의 [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 Doc 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 DOTX 형식으로 저장하고 Dotx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 소유자 암호를 사용하여 CGM 파일 암호 해독" %}}
CGM을 DOTX으로 변환하기 전에 문서의 암호를 해독하려면 API를 사용하면 됩니다. PDF 파일을 복호화하기 위해서는 먼저 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 객체를 생성하고 소유자의 비밀번호로 CGM을 열어야 합니다. 이후 Document 객체의 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 메소드를 호출해야 합니다. 마지막으로 Document 개체의 Save 메서드를 사용하여 업데이트된 파일을 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 DOTX 파일 만들기" %}}
DOTX이 편집되지 않도록 보호하고 다른 사람이 문서에서 민감한 기밀 정보를 편집하지 못하도록 하기 위해 API를 사용하여 문서 보호를 설정할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용할 수 있습니다. 이는 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하여 수행할 수 있습니다. [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 DOTX로 변환: 사용 사례" %}}
CGM (Computer Graphics Metafile) 파일을 DOTX (Microsoft Word Macro-Enabled Document Template) 포맷으로 변환하는 것은 문서 생성과 편집能力을 최대한 활용할 수 있도록 해주는 중요한 작업입니다. 이 변환은 다음 사용자에게 다음과 같은 혜택을 제공합니다:

**사용 사례:**

* **비즈니스 리포트 및 발표:** CGM 파일을 DOTX로 변환하여 스타게이터들에게 전달할 수 있는 인터랙티브한 비즈니스 리포트, 프레젠테이션, 그리고 시각화를 통해 더 나은 결정을 내릴 수 있도록 합니다.
* **마케팅 자료 디자인:** DOTX를 사용하여 마케팅 자료，如 브로셔, 플라이어, 및 판매서를 쉽게设计하고 레이아웃할 수 있습니다.
* **기술 문서 작성:** CGM 파일을 변환하여 사용자 매뉴얼, 인스트루션 가이드, 및 제품 사양서 gibi 기술 문서를 생성할 수 있습니다.
* **과학적 발표 및 연구:** DOTX를 사용하여 과학적인 논문, 기사, 및 연구 보고서를 작성하고 편집할 수 있도록 합니다.
* **교육 및 훈련 자료 개발:** CGM 파일을 변환하여 인터랙티브한 교육 자료，如 튜토리얼, 워크북, 및 평가를 디자인할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}