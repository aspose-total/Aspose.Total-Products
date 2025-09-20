---
title: Java를 통해 HTML을 EMZ로 변환
description: 타사 응용 프로그램을 사용하지 않고 Java 응용 프로그램에서 HTML 파일을 EMZ로 내보내기
url_ignore: /ko/java/conversion/html-to-emz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: EMZ
otherformats: PSD DXF TGA  SVGZ IMAGE WMZ JPEG2000 EMZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 HTML을 EMZ로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Java J2SE, J2EE, J2ME 응용 프로그램 내에서 HTML 파일을 EMZ로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 통해 Java에서 html 파일을 EMZ 이미지로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 HTML을 JPEG로 내보낼 수 있습니다. 그런 다음 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API를 사용하여 JPEG를 EMZ로 렌더링할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 HTML을 EMZ로 내보내기" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 HTML 파일을 엽니다.
2. 클래스 객체를 초기화하고 [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)를 사용하여 HTML을 JPEG로 렌더링합니다. aspose.pdf.Page-java.io.OutputStream-) 메서드
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 파일 로드
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 EMZ 형식으로 저장합니다 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 단일 파일에서 HTML을 EMZ로 변환" %}}
API를 사용하면 HTML 파일을 단일 파일로 EMZ로 내보낼 수도 있습니다. 모든 페이지를 변환하려면 먼저 HTML 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 EMZ로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-)를 사용하여 단일 TIFF 이미지를 얻을 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 클래스의 java.io.OutputStream-) 메서드입니다. 마지막으로 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 TIFF 파일을 로드하고 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 메서드.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 워터마크를 사용하여 HTML을 EMZ로 변환" %}}
API를 사용하면 EMZ 문서에 워터마크가 있는 HTML 파일을 EMZ로 내보낼 수도 있습니다. 워터마크를 추가하려면 먼저 HTML을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 EMZ 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 HTML을 EMZ 파일로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 EMZ 이미지를 회전할 수도 있습니다. Image.rotateFlip 메서드는 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집는 데 사용할 수 있습니다. 라이브러리는 모든 추악한 세부 사항을 캡슐화하면서 복잡한 작업을 수행하는 간단한 방법을 제공합니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집으려면 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출하면 됩니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)을 지정하면서 rotateFlip 메서드를 사용합니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTML을 EMZ(압축된 향상된 메타파일)로 변환**하는 것은 웹 페이지에서 **가벼운 Windows 호환 그래픽**을 생성하는 데 중요합니다. EMZ 파일은 압축된 벡터 그래픽을 제공하여 Microsoft Office, 비즈니스 응용 프로그램 및 보관 시스템과 완벽하게 통합됩니다. HTML을 EMZ로 변환함으로써 조직은 파일 크기를 줄이고 확장 가능성을 유지하며 기업 및 교육 워크플로우 전반에 걸쳐 원활한 호환성을 보장할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **오피스 그래픽** – 압축된 다이어그램과 시각 자료를 Word, Excel 및 PowerPoint에 직접 삽입합니다.
- **다이어그램** – 웹 기반 도표를 재사용할 수 있는 확장 가능한 EMZ 파일로 변환합니다.
- **비즈니스 보고 시각 자료** – 기업 문서 및 프레젠테이션용으로 간결한 그래픽을 생성합니다.
- **교육 자료** – 학술 콘텐츠에서 가벼운 고품질 일러스트레이션을 제공합니다.
- **보관 워크플로우** – 장기적인 액세스를 위해 압축된 Windows용 벡터 그래픽을 저장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **HTML에서 EMZ로의 파이프라인** – 웹 페이지를 압축된 메타파일로 자동 변환합니다.
- **자동화된 메타파일 압축** – 그래픽 크기를 줄이면서 품질을 유지하여 워크플로우를 간소화합니다.
- **대량 문서 그래픽 워크플로우** – 기업 규모의 보고 및 게시용으로 여러 시각 자료를 변환합니다.
- **기업 수준의 게시 자동화** – 부서 간 일관된 통합을 위해 EMZ 그래픽을 표준화합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}