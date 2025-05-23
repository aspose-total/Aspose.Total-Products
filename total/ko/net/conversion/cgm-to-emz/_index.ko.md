---
title: C# API를 통해 CGM을 EMZ로 변환
description: 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램에서 CGM을 EMZ로 내보내기
url_ignore: /ko/net/conversion/cgm-to-emz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: EMZ
otherformats: SVGZ WMF PSD EMZ WMZ TGA JPEG2000 IMAGE DXF  DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 CGM 파일을 EMZ로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader 또는 기타 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램 내에서 CGM을 EMZ로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 간단한 두 단계로 모든 .NET 응용 프로그램 내에서 CGM을 EMZ 이미지로 쉽게 내보낼 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 JPEG로 내보낼 수 있습니다. 이후 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API를 사용하여 JPEG를 EMZ로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 CGM 파일을 EMZ로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) 클래스 객체를 초기화하고 [Process](https://apireference.aspose)를 이용하여 CGM을 JPEG로 렌더링합니다. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 방법
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 JPEG 파일 로드
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 문서를 EMZ 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 단일 파일에서 CGM 파일을 EMZ로 변환" %}}
API를 사용하여 CGM 파일을 EMZ로 변환하여 단일 이미지 파일로 변환할 수도 있습니다. 모든 페이지를 변환하려면 먼저 CGM 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 EMZ로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 클래스. 마지막으로 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 TIFF 파일을 로드할 수 있습니다.
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 EMZ 형식으로 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 CGM 파일을 EMZ로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 EMZ 이미지를 회전할 수도 있습니다. Image.RotateFlip 메서드를 사용하여 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집을 수 있습니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집기 위해 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스에 의해 노출된 팩토리 메서드를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출할 수 있습니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)을 지정하면서 .RotateFlip 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 EMZ로 변환: 사용 사례" %}}
CGM 파일을 EMZ 형식으로 전환하여 데이터 시각화 및 분석 능력을 극대화할 수 있습니다. 이 전환은 다음을 달성할 수 있도록 합니다:

**사용 사례:**

* **디지털 시gnage 콘텐츠 관리**: CGM 파일을 EMZ로 전환하여 디지털 시gnage 콘텐츠를 관리하고 디스플레이를 업데이트하며 미디어 요소들을 동기화할 수 있습니다.
* **게임 개발**: EMZ를 활용하여 인터랙티브한 게임 환경을 창출하고 gameplay 시�션을 진행하며 그래픽 성능을 최적화할 수 있습니다.
* **벡터 그래픽 편집**: CGM 파일을 EMZ로 전환하여 벡터 그래픽을 편집할 수 있어 형상, 선, 문자 등의 요소에 대한 정확한 제어를 가능하게 합니다.
* **웹 콘텐츠 전달**: EMZ를 활용하여 웹 콘텐츠, 특히 벡터 그래픽과 일러스트레이션을 빠르게 로드하고 사용자 경험을 개선할 수 있습니다.
* **CAD 설계 및制造**: CGM 파일을 EMZ로 전환하여 복잡한 CAD 디자인을 생성하고 제조 과정의 시�션을 진행하며 제품 성능을 최적화할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}