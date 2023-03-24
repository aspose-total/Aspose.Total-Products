---
title: TEX을 PS으로 내보내기 위한 C++ API
description: C++ 응용 프로그램 내에서 TEX을 PS으로 변환합니다.

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PS
otherformats: OTT WORDML DOTX DOCM DOTM MHTML MARKDOWN FLATOPC RTF XAMLFLOW DOT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="TEX을 PS으로 내보내기 위한 C++ API" h2="타사 응용 프로그램 없이 C++ 응용 프로그램 내에서 TEX을 PS으로 렌더링" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 파일 형식 자동화 라이브러리를 사용하면 C++ 개발자가 두 가지 간단한 단계를 통해 TEX을 PS으로 변환할 수 있습니다. 먼저 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API를 사용하여 TEX 파일 형식을 DOC로 변환할 수 있습니다. 둘째, 고급 Word Document Processing API[Aspose.Words for C++](https://products.aspose.com/words/cpp/)를 사용하여 DOC를 PS으로 내보낼 수 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX을 PS으로 렌더링하는 C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스 참조를 사용하여 TEX 파일을 엽니다.
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) 멤버 함수를 사용하여 TEX을 DOC로 변환
3. Aspose.Words API의 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스 참조를 사용하여 DOC 파일 로드
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) 멤버 함수를 사용하여 문서를 PS 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Ps
wordDoc->Save(u"output.Ps");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 TEX 문서의 비밀번호 변경" %}}
TEX을 PS으로 렌더링하는 과정에서 암호로 보호된 TEX을 열고 암호를 변경할 수도 있습니다. TEX 파일의 비밀번호를 변경하려면 해당 문서의 소유자 비밀번호를 알아야 합니다. 소유자 암호를 지정하여 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)로 암호로 보호된 PDF 문서를 로드하고 ChangePasswords 메서드를 사용하여 암호를 변경할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통한 PS 파일 편집 제한" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) API를 사용하여 PS 파일 편집을 제한할 수도 있습니다. 문서 편집 기능을 제한하고 문서에 대한 특정 작업만 허용해야 하는 경우가 있습니다. API를 사용하면 [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) 열거 매개변수를 사용하여 콘텐츠를 제한하는 방식을 제어할 수 있습니다. 다음 코드 예제에서는 양식 필드에서만 편집이 가능하도록 문서에서 편집을 제한하는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Ps");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}