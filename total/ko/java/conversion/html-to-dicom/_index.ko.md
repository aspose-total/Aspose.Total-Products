---
title: Java를 통해 HTML을 DICOM로 변환
description: 타사 응용 프로그램을 사용하지 않고 Java 응용 프로그램에서 HTML 파일을 DICOM로 내보내기
url_ignore: /ko/java/conversion/html-to-dicom/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: DICOM
otherformats: WMZ TGA SVGZ DICOM WMF EMZ DXF PSD JPEG2000 IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 HTML을 DICOM로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Java J2SE, J2EE, J2ME 응용 프로그램 내에서 HTML 파일을 DICOM로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 통해 Java에서 html 파일을 DICOM 이미지로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 HTML을 JPEG로 내보낼 수 있습니다. 그런 다음 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API를 사용하여 JPEG를 DICOM로 렌더링할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 HTML을 DICOM로 내보내기" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 HTML 파일을 엽니다.
2. 클래스 객체를 초기화하고 [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)를 사용하여 HTML을 JPEG로 렌더링합니다. aspose.pdf.Page-java.io.OutputStream-) 메서드
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 파일 로드
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 DICOM 형식으로 저장합니다 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 단일 파일에서 HTML을 DICOM로 변환" %}}
API를 사용하면 HTML 파일을 단일 파일로 DICOM로 내보낼 수도 있습니다. 모든 페이지를 변환하려면 먼저 HTML 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 DICOM로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-)를 사용하여 단일 TIFF 이미지를 얻을 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 클래스의 java.io.OutputStream-) 메서드입니다. 마지막으로 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 TIFF 파일을 로드하고 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 메서드.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 워터마크를 사용하여 HTML을 DICOM로 변환" %}}
API를 사용하면 DICOM 문서에 워터마크가 있는 HTML 파일을 DICOM로 내보낼 수도 있습니다. 워터마크를 추가하려면 먼저 HTML을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 DICOM 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 HTML을 DICOM 파일로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 DICOM 이미지를 회전할 수도 있습니다. Image.rotateFlip 메서드는 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집는 데 사용할 수 있습니다. 라이브러리는 모든 추악한 세부 사항을 캡슐화하면서 복잡한 작업을 수행하는 간단한 방법을 제공합니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집으려면 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출하면 됩니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)을 지정하면서 rotateFlip 메서드를 사용합니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTML을 DICOM으로 변환하는 것**은 웹 기반 데이터로부터 **의료 이미지 호환성 출력물을 생성**하는 데 필수적입니다. DICOM은 임상 이미지와 관련된 정보가 의료 시스템 전반에 걸쳐 상호 운용성, 아카이빙 및 통합을 위해 표준화되도록 보장합니다. HTML 콘텐츠를 DICOM으로 변환함으로써, 의료 공급 업체와 연구자들은 산업 표준을 준수하면서 의료 워크플로우를 최적화할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}
- **원격 의료 플랫폼** – 웹 기반 의료 데이터를 DICOM 호환 시스템에 통합합니다.
- **의료 보고서 통합** – 텍스트 및 이미지 보고서를 표준 의료 형식에 포함시킵니다.
- **의료 워크플로우** – 부서 간 환자 데이터의 원활한 교환을 가능하게 합니다.
- **방사선학 아카이빙** – DICOM 아카이브에 이미지 및 관련 웹 기반 콘텐츠를 저장합니다.
- **시스템 간 상호 운용성** – 의료 응용 프로그램 간에 표준화된 데이터 공유를 용이하게 합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}
- **HTML-to-DICOM 파이프라인** – 웹 기반 의료 콘텐츠를 DICOM으로 자동 변환합니다.
- **자동화된 의료 보고서 포함** – HTML 데이터를 환자 이미징 워크플로에 통합합니다.
- **대량 의료 데이터 변환** – 다수의 보고서 또는 웹 페이지를 효율적으로 대규모로 처리합니다.
- **기업 수준의 임상 워크플로** – 의료 기관 전반에 걸쳐 HTML-to-DICOM 변환을 표준화합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}