---
title: Java를 통해 HTML을 WMF로 변환
description: 타사 응용 프로그램을 사용하지 않고 Java 응용 프로그램에서 HTML 파일을 WMF로 내보내기
url_ignore: /ko/java/conversion/html-to-wmf/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: WMF
otherformats: IMAGE EMZ  WMF SVGZ JPEG2000 DXF TGA WMZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 HTML을 WMF로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Java J2SE, J2EE, J2ME 응용 프로그램 내에서 HTML 파일을 WMF로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 통해 Java에서 html 파일을 WMF 이미지로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 HTML을 JPEG로 내보낼 수 있습니다. 그런 다음 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API를 사용하여 JPEG를 WMF로 렌더링할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 HTML을 WMF로 내보내기" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 HTML 파일을 엽니다.
2. 클래스 객체를 초기화하고 [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)를 사용하여 HTML을 JPEG로 렌더링합니다. aspose.pdf.Page-java.io.OutputStream-) 메서드
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 파일 로드
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 WMF 형식으로 저장합니다 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 단일 파일에서 HTML을 WMF로 변환" %}}
API를 사용하면 HTML 파일을 단일 파일로 WMF로 내보낼 수도 있습니다. 모든 페이지를 변환하려면 먼저 HTML 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 WMF로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-)를 사용하여 단일 TIFF 이미지를 얻을 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 클래스의 java.io.OutputStream-) 메서드입니다. 마지막으로 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 TIFF 파일을 로드하고 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 메서드.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 워터마크를 사용하여 HTML을 WMF로 변환" %}}
API를 사용하면 WMF 문서에 워터마크가 있는 HTML 파일을 WMF로 내보낼 수도 있습니다. 워터마크를 추가하려면 먼저 HTML을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 WMF 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 HTML을 WMF 파일로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 WMF 이미지를 회전할 수도 있습니다. Image.rotateFlip 메서드는 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집는 데 사용할 수 있습니다. 라이브러리는 모든 추악한 세부 사항을 캡슐화하면서 복잡한 작업을 수행하는 간단한 방법을 제공합니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집으려면 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출하면 됩니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)을 지정하면서 rotateFlip 메서드를 사용합니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**HTML을 WMF (Windows Metafile)로 변환**하는 것은 HTML 페이지에서 **Windows 호환 벡터 그래픽**을 생성하는 데 필수적입니다. WMF 파일은 확장 가능성과 편집 가능성을 유지하여 사무용 애플리케이션, 비즈니스 보고서 및 기업 출판에 이상적입니다. HTML 콘텐츠를 WMF로 변환함으로써 조직은 Windows 기반 도구와의 원활한 통합을 보장하면서 전문적인 용도로 벡터 그래픽의 정밀도와 명확성을 유지할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* **사무실 그래픽** - Word, Excel 및 PowerPoint 문서용 편집 가능한 벡터 시각 자 생성.
* **보고서 다이어그램** - 비즈니스 및 기술 보고서에 고품질 다이어그램 통합.
* **비즈니스 프레젠테이션** - 확장 가능하고 명확한 벡터 그래픽으로 슬라이드 강화.
* **아카이브 워크플로우** - Windows 호환 벡터 형식으로 역사적 웹 콘텐츠 보존.
* **기업 출판** - 기업 문서에서 일관된 고품질 그래픽 유지.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **HTML-to-WMF 파이프라인** - 웹 페이지를 Windows 호환 벡터 파일로 자동 변환.
* **자동 다이어그램 변환** - 사무 및 기업용 일관된 WMF 그래픽 생성.
* **대량 그래픽 생성** - 대규모로 동시에 여러 웹 페이지 또는 다이어그램 처리.
* **기업급 문서 워크플로우** - 대규모 보고 및 출판 시스템에 WMF 생성 통합.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}