---
title: SVG을 DOTX으로 내보내기 위한 C++ API
description: C++ 응용 프로그램 내에서 SVG을 DOTX으로 변환합니다.
url: /ko/cpp/conversion/svg-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOTX
otherformats: PCL WORDML ODT OTT DOCM RTF PS XAMLFLOW MARKDOWN DOTM FLATOPC MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="SVG을 DOTX으로 내보내기 위한 C++ API" h2="타사 응용 프로그램 없이 C++ 응용 프로그램 내에서 SVG을 DOTX으로 렌더링" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 파일 형식 자동화 라이브러리를 사용하면 C++ 개발자가 두 가지 간단한 단계를 통해 SVG을 DOTX으로 변환할 수 있습니다. 먼저 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API를 사용하여 SVG 파일 형식을 DOC로 변환할 수 있습니다. 둘째, 고급 Word Document Processing API[Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 DOC를 DOTX으로 내보낼 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SVG을 DOTX으로 렌더링하는 C++ API" %}}
1. [문서](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스 참조를 사용하여 SVG 파일을 엽니다.
2. [저장](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) 멤버 함수를 사용하여 SVG을 DOC로 변환
3. Aspose.Words API의 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스 참조를 사용하여 DOC 파일 로드
4. [저장](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) 멤버 함수를 사용하여 문서를 DOTX 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://downloads.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotx
wordDoc->Save(u"output.Dotx");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 SVG 문서의 비밀번호 변경" %}}
SVG을 DOTX으로 렌더링하는 과정에서 암호로 보호된 SVG을 열고 암호를 변경할 수도 있습니다. SVG 파일의 비밀번호를 변경하려면 해당 문서의 소유자 비밀번호를 알아야 합니다. 소유자 암호를 지정하여 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)로 암호로 보호된 PDF 문서를 로드하고 ChangePasswords 메서드를 사용하여 암호를 변경할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통한 DOTX 파일 편집 제한" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API를 사용하여 DOTX 파일 편집을 제한할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. API를 사용하면 [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 예제에서는 양식 필드에서만 편집이 가능하도록 문서에서 편집을 제한하는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotx");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-pcl/" name="SVG 에게 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-wordml/" name="SVG 에게 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-odt/" name="SVG 에게 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-ott/" name="SVG 에게 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-dotx/" name="SVG 에게 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-rtf/" name="SVG 에게 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-ps/" name="SVG 에게 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-xamlflow/" name="SVG 에게 XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-markdown/" name="SVG 에게 MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-dotm/" name="SVG 에게 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-flatopc/" name="SVG 에게 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/conversion/svg-to-mhtml/" name="SVG 에게 MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}