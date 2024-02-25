---
title: CGM을 SWF로 변환하는 C++ API
description: Microsoft Word 또는 Adobe Acrobat Reader를 사용하지 않고 C++를 통해 CGM을 SWF로 변환

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: SWF
otherformats: OTP PPSX PPT ODP XAML PPTM PPSM POTX POWERPOINT POT POTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ 응용 프로그램 내에서 CGM을 SWF로 렌더링" h2="Microsoft<sup>&reg;</sup> PowerPoint를 사용하지 않고 C++ 응용 프로그램 내에서 CGM을 SWF로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}
C++ 응용 프로그램 내부에 CGM에서 SWF로의 변환 기능을 통합하기 위해 추가하려는 C++ 개발자입니까? 간단한 두 단계로 수행할 수 있습니다. [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)를 사용하여 CGM을 PPTX로 내보낼 수 있습니다. 둘째, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)를 사용하여 PPTX를 SWF로 변환할 수 있습니다. 두 API 모두 [C++용 Aspose.Total](https://products.aspose.com/total/cpp/) 패키지에 있습니다. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM을 SWF로 내보내기 위한 C++ API" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스 참조를 사용하여 CGM 파일 열기
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) 메서드 함수를 사용하여 CGM을 PPTX로 변환
3. [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 클래스 참조를 사용하여 PPTX 문서 로드
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 멤버 함수를 사용하여 문서를 SWF 형식으로 저장하고 'Swf'를 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Swf format
prs->Save(u"output.swf", Aspose::Slides::Export::SaveFormat::Swf);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 CGM 문서의 비밀번호 변경" %}}
CGM을 SWF로 렌더링하는 과정에서 암호로 보호된 CGM을 열고 암호를 변경할 수도 있습니다. CGM 파일의 비밀번호를 변경하려면 해당 문서의 소유자 비밀번호를 알아야 합니다. 소유자 암호를 지정하여 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/)로 암호로 보호된 PDF 문서를 로드하고 ChangePasswords 메서드를 사용하여 암호를 변경할 수 있습니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 통해 웹에서 SWF 파일의 이미지 추가" %}}
CGM을 SWF로 변환한 후 웹에서 출력 문서로 이미지를 추가할 수도 있습니다. [C++용 Aspose.Slides](https://products.aspose.com/slides/cpp/)는 JPEG, PNG, BMP, GIF 등 널리 사용되는 형식의 이미지 작업을 지원합니다. 컴퓨터에 있는 하나 이상의 이미지를 프레젠테이션의 슬라이드에 추가할 수 있습니다. C++의 이 샘플 코드는 SWF 파일에 이미지를 추가하는 방법을 보여줍니다.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a SWF file
auto pres = System::MakeObject<Presentation>("output.swf");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.swf", SaveFormat::Swf);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}