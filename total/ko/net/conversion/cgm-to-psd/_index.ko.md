---
title: C# API를 통해 CGM을 PSD로 변환
description: 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램에서 CGM을 PSD로 내보내기
url_ignore: /ko/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통해 CGM 파일을 PSD로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader 또는 기타 타사 응용 프로그램을 사용하지 않고 .NET 응용 프로그램 내에서 CGM을 PSD로 내보내기" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/)을 사용하면 간단한 두 단계로 모든 .NET 응용 프로그램 내에서 CGM을 PSD 이미지로 쉽게 내보낼 수 있습니다. 먼저 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)을 사용하여 CGM을 JPEG로 내보낼 수 있습니다. 이후 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API를 사용하여 JPEG를 PSD로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET을 통해 CGM 파일을 PSD로 변환" %}}
1. [문서](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 CGM 파일을 엽니다.
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) 클래스 객체를 초기화하고 [Process](https://apireference.aspose)를 이용하여 CGM을 JPEG로 렌더링합니다. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 방법
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 JPEG 파일 로드
4. [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 문서를 PSD 형식으로 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 단일 파일에서 CGM 파일을 PSD로 변환" %}}
API를 사용하여 CGM 파일을 PSD로 변환하여 단일 이미지 파일로 변환할 수도 있습니다. 모든 페이지를 변환하려면 먼저 CGM 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 PSD로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 클래스. 마지막으로 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 TIFF 파일을 로드할 수 있습니다.
[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 방법을 사용하여 PSD 형식으로 저장합니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C#을 통해 CGM 파일을 PSD로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 PSD 이미지를 회전할 수도 있습니다. Image.RotateFlip 메서드를 사용하여 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집을 수 있습니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집기 위해 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스에 의해 노출된 팩토리 메서드를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출할 수 있습니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)을 지정하면서 .RotateFlip 메서드. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="프로그래밍 방식으로 CGM 파일을 PSD로 변환: 사용 사례" %}}
CGM (컴퓨터 그래픽스 메타파일) 파일은 벡터 그래픽스 정보를 저장하는 데 사용됩니다. 이 파일들은 정적 그래픽과 일러스트레이션에 적합합니다. 그러나 동적 데이터를 처리할 때, 사진 편집 소프트웨어如Photoshop가 필수적입니다.

CGM 파일을 PSD 형식으로 변환하는 것은 귀하의 그래픽 디자인 능력을 완전히 활용할 수 있도록 합니다. 이 변환은 다음用途를 제공합니다:

**用途:**

*   **로고 디자인**: CGM 파일을 변환하여 다양한 매체(비즈니스 카드, 빌보드, 웹사이트 등)에서 사용할 수 있는 확장 가능한 벡터 로고를 생성할 수 있습니다.
*   **브랜드와 인도entity**: PSD를 통해 브랜드 가이드라인을 시각화하고 일관적인 비주얼 ID를 만드는 데 사용할 수 있습니다.
*   **일러스트레이션과 아트워크**: CGM 파일을 변환하여 복잡한 일러스트레이션을 만들고 벡터 아트워크를 편집하고 디자인 개념을 수정할 수 있습니다.
*   **프린팅 디자인**: PSD를 통해 프린팅 디자인을 시각화하고 레이아웃을 최적화하고 다양한 프린팅 앱리케이션에서 높은 품질의 이미지 출력을 확보할 수 있습니다.
*   **그래픽 디자인 아셋**: CGM 파일을 변환하여 편집 가능한 그래픽 디자인 아셯을 만들고 다수의 프로젝트에 재사용할 수 있습니다.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}