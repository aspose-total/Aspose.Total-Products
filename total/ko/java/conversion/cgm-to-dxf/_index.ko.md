---
title: Java를 통해 CGM을 DXF로 변환
description: 타사 응용 프로그램을 사용하지 않고 Java 응용 프로그램에서 CGM 파일을 DXF로 내보내기
url_ignore: /ko/java/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 DXF로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Java J2SE, J2EE, J2ME 응용 프로그램 내에서 CGM 파일을 DXF로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 통해 Java에서 cgm 파일을 DXF 이미지로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 JPEG로 내보낼 수 있습니다. 그런 다음 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API를 사용하여 JPEG를 DXF로 렌더링할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM을 DXF로 내보내기" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. 클래스 객체를 초기화하고 [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)를 사용하여 CGM을 JPEG로 렌더링합니다. aspose.pdf.Page-java.io.OutputStream-) 메서드
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 파일 로드
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 DXF 형식으로 저장합니다 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 단일 파일에서 CGM을 DXF로 변환" %}}
API를 사용하면 CGM 파일을 단일 파일로 DXF로 내보낼 수도 있습니다. 모든 페이지를 변환하려면 먼저 CGM 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 DXF로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-)를 사용하여 단일 TIFF 이미지를 얻을 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 클래스의 java.io.OutputStream-) 메서드입니다. 마지막으로 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 TIFF 파일을 로드하고 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 메서드.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 워터마크를 사용하여 CGM을 DXF로 변환" %}}
API를 사용하면 DXF 문서에 워터마크가 있는 CGM 파일을 DXF로 내보낼 수도 있습니다. 워터마크를 추가하려면 먼저 CGM을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 DXF 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 CGM을 DXF 파일로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 DXF 이미지를 회전할 수도 있습니다. Image.rotateFlip 메서드는 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집는 데 사용할 수 있습니다. 라이브러리는 모든 추악한 세부 사항을 캡슐화하면서 복잡한 작업을 수행하는 간단한 방법을 제공합니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집으려면 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출하면 됩니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)을 지정하면서 rotateFlip 메서드를 사용합니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
**컴퓨터 그래픽스 메타파일 (CGM)** 파일을 **DXF (도면 교환 형식)**으로 변환하는 것은 **CAD (컴퓨터 지원 설계)** 워크플로우에서 매우 중요합니다. 이를 통해 공학, 건축 및 제조 시스템 간의 원활한 상호 운용성이 보장됩니다. **자바 기반 응용 프로그램**에서 이러한 변환을 수행하면 CGM에서 벡터 기반 기술 다이어그램이 널리 지원되는 CAD 형식으로 변환되어 편집 가능하고 공유 가능하며 산업 표준 설계 도구와 호환됩니다. 이는 협업 설계, 정밀 제조 및 기술 도면의 보관에 중요합니다.

## ✅ 주요 사용 사례

- **공학 설계 상호 운용성**  
  CGM 기반 설계를 DXF를 지원하는 CAD 도구에서 공유하고 편집하여 플랫폼 간 협업을 지원합니다.

- **제조용 청사진 교환**  
  CNC 가공 및 제조를 위해 CGM 다이어그램에서 파생된 DXF 파일을 생산 팀에 제공합니다.

- **벡터 그래픽 편집**  
  CGM 다이어그램을 DXF로 변환하여 벡터 정밀도 손실 없이 CAD 소프트웨어에서 직접 수정할 수 있습니다.

## ⚙️ 자동화 시나리오

- **자바 기반 CAD 도구**  
  CGM-to-DXF 변환을 자바 기반 CAD 편집 및 시각화 응용 프로그램에 직접 통합합니다.

- **공학 도면 변환기**  
  자바 API를 사용하여 다중 프로젝트 워크플로에 대한 대규모 CGM-to-DXF 일괄 변환을 자동화합니다.

- **자동화된 CAD 보관 시스템**  
  장기적인 공학 아카이브에 CGM 설계를 DXF 파일로 저장하여 향후 재사용과 규정 준수를 보장합니다.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}