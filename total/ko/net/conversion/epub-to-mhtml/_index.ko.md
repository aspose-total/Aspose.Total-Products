---
title: EPUB을 MHTML으로 내보내기 위한 C# API
description: Microsoft Word를 사용하지 않고 EPUB을 MHTML으로 변환
url_ignore: /ko/net/conversion/epub-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MHTML
otherformats: PCL DOT DOTX ODT FLATOPC WORDML MARKDOWN DOTM XAMLFLOW MHTML PS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET을 통해 EPUB을 MHTML으로 렌더링" h2="Microsoft Word를 사용하지 않고 Windows, macOS 및 Linux에서 EPUB을 MHTML으로 내보내는 .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)은 .NET 애플리케이션 내부에 문서 조작 및 변환 기능을 추가하는 강력한 API입니다. 고급 PDF 처리 API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)를 사용하여 EPUB 파일 형식을 DOC로 변환할 수 있습니다. 그런 다음 강력한 문서 처리 API [Aspose.Words for .NET](https://products.aspose.com/words/net/)를 사용하여 DOC를 MHTML으로 렌더링할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB을 MHTML으로 변환하는 C# API" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 EPUB 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 EPUB을 문서로 변환
3. Aspose.Words의 [Document](https://reference.aspose.com/words/net/aspose.words/document) 클래스를 사용하여 Doc 파일을 로드합니다.
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) 방법을 사용하여 문서를 MHTML 형식으로 저장하고 Mhtml을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 소유자 암호를 사용하여 EPUB 파일 암호 해독" %}}
EPUB을 MHTML으로 변환하기 전에 문서의 암호를 해독하려면 API를 사용하면 됩니다. PDF 파일을 복호화하기 위해서는 먼저 [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 객체를 생성하고 소유자의 비밀번호로 EPUB을 열어야 합니다. 이후 Document 객체의 [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) 메소드를 호출해야 합니다. 마지막으로 Document 개체의 Save 메서드를 사용하여 업데이트된 파일을 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET을 통해 읽기 전용 MHTML 파일 만들기" %}}
MHTML이 편집되지 않도록 보호하고 다른 사람이 문서에서 민감한 기밀 정보를 편집하지 못하도록 하기 위해 API를 사용하여 문서 보호를 설정할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용할 수 있습니다. 이는 [Aspose.Words for .NET](https://products.aspose.com/words/net/) API를 사용하여 수행할 수 있습니다. [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 줄을 사용하여 문서를 읽기 전용으로 설정할 수 있습니다. 
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 EPUB 파일을 MHTML로 변환: 사용 사례" %}}
EPUB (Electronic Publication) 파일은 디지털 콘텐츠를 저장하는 데 사용되는 파일 포맷으로, 이包括 이북, 기사, 그리고 기타 유형의出版물입니다. 그러나 웹 기반 애플리케이션에서 작업할 때, MHTML (MIME HTML) 포맷은 콘텐츠를 공유하고 보기 위해 필수적이 됩니다.

EPUB 파일을 MHTML 포맷으로 변환하는 것은 당신의 디지털 콘텐츠 공유와 사용 능력을 극대화하기 위해 必須적인 과정입니다. 이 변환은 다음을 달성할 수 있도록 합니다:

**사용 사례:**

* **웹 콘텐츠 공유**: EPUB 파일을 MHTML 포맷으로 변환하여 기사, 블로그 게시물, 이북 등 웹 기반 콘텐츠를 더 많은 독자자와 공유할 수 있습니다.
* **디지털 잡지 발행**: MHTML 포맷을 사용하여 인터랙티브한 디지털 잡지를 만들 수 있고, 멀티미디어 콘텐츠와 하이퍼링크를 포함할 수 있습니다.
* **이북 분포**: EPUB 파일을 MHTML 포맷으로 변환하여 온라인 플랫�에서 이북과 기타 디지털出版물을 분포할 수 있습니다.
* **온라인 강의 자료**: MHTML 포맷을 사용하여 학생들에게 전달할 수 있는 교육적 자원, 예를 들어 강의 노트, 영상을 포함한 온라인 강의 자료를 공유할 수 있습니다.
* **디지털 자산 관리**: EPUB 파일을 MHTML 포맷으로 변환하여 다양한 기기와 플랫폼에서 관리하고 공유할 수 있는 디지털 자산, 예를 들어 이미지, 비디오, 문서 등을 포함한 콘텐츠를 공유할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}