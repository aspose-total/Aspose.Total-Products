---
title: C# API를 통해 CGM을 DXF로 변환
description: 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램에서 CGM을 DXF로 내보내기
url_ignore: /ko/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 CGM 파일을 DXF로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader 또는 기타 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램 내에서 CGM을 DXF로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 간단한 두 단계로 모든 .NET 응용 프로그램 내에서 CGM을 DXF 이미지로 쉽게 내보낼 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 JPEG로 내보낼 수 있습니다. 이후 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API를 사용하여 JPEG를 DXF로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 CGM 파일을 DXF로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) 클래스 객체를 초기화하고 [Process](https://apireference.aspose)를 이용하여 CGM을 JPEG로 렌더링합니다. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 방법
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 JPEG 파일 로드
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 문서를 DXF 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 단일 파일에서 CGM 파일을 DXF로 변환" %}}
API를 사용하여 CGM 파일을 DXF로 변환하여 단일 이미지 파일로 변환할 수도 있습니다. 모든 페이지를 변환하려면 먼저 CGM 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 DXF로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 클래스. 마지막으로 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 TIFF 파일을 로드할 수 있습니다.
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 DXF 형식으로 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 CGM 파일을 DXF로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 DXF 이미지를 회전할 수도 있습니다. Image.RotateFlip 메서드를 사용하여 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집을 수 있습니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집기 위해 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스에 의해 노출된 팩토리 메서드를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출할 수 있습니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)을 지정하면서 .RotateFlip 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 DXF로 변환: 사용 사례" %}}
CGM (컴퓨터 그래픽스 메타파일) 파일을 DXF (다이싱크스 파일) 파일로 변환하는 것은 CAD 설계와 제조 생산의 풀 포텐셜을 극대화하기 위해 중요한 과정입니다. 이 변환은 다음 목표를 달성하도록 도와줍니다:

**사용 사례:**

* **CAD 설계통합**: CGM 파일을 DXF 파일로 변换하여 CAD 소프트웨어와의 유연한 데이터 교환을 가능하게 합니다.
* **제조 생산 최적화**: DXF 파일을 통해 제조 공정을 개선하고, 생산 비용을 절감하며 제품 품질을 향상시키는 데 도움이 됩니다.
* **디자인 맞춤형 제조 (DFM)**: CGM 파일을 DXF 파일로 변换하여 소재 특성, 도具 요구사항, 조립 제한 등이 고려된 DFM 설계를 생성할 수 있습니다.
* **CNC 기계와의 데이터 전송**: DXF 파일을 통해 제품을 정확하게 잘라내고, 가공할 수 있도록 CNC 기계와의 정확한 데이터 전송을 가능하게 합니다.
* **제품 개발 및 테스트**: CGM 파일을 DXF 파일로 변换하여 원형을 제작하고, 제품 기능을 검증하는 데 도움이 됩니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}