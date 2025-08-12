---
title: Java를 통해 CGM을 DICOM로 변환
description: 타사 응용 프로그램을 사용하지 않고 Java 응용 프로그램에서 CGM 파일을 DICOM로 내보내기
url_ignore: /ko/java/conversion/cgm-to-dicom/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DICOM
otherformats: EMZ PSD WMF WMZ TGA DICOM DXF SVGZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 CGM을 DICOM로 변환" h2="Adobe<sup>&reg;</sup> Acrobat Reader를 사용하지 않고 Java J2SE, J2EE, J2ME 응용 프로그램 내에서 CGM 파일을 DICOM로 내보내기" >}}
{{% blocks/products/pf/feature-page-summary %}}
두 가지 간단한 단계를 통해 Java에서 cgm 파일을 DICOM 이미지로 변환할 수 있습니다. 먼저 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)를 사용하여 CGM을 JPEG로 내보낼 수 있습니다. 그런 다음 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API를 사용하여 JPEG를 DICOM로 렌더링할 수 있습니다. 두 API 모두 [Java용 Aspose.Total](https://products.aspose.com/total/java/) 패키지에 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 CGM을 DICOM로 내보내기" %}}
1. [문서](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 CGM 파일을 엽니다.
2. 클래스 객체를 초기화하고 [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com)를 사용하여 CGM을 JPEG로 렌더링합니다. aspose.pdf.Page-java.io.OutputStream-) 메서드
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
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 단일 파일에서 CGM을 DICOM로 변환" %}}
API를 사용하면 CGM 파일을 단일 파일로 DICOM로 내보낼 수도 있습니다. 모든 페이지를 변환하려면 먼저 CGM 문서를 하나의 TIFF 파일로 렌더링한 다음 TIFF 파일을 DICOM로 내보낼 수 있습니다. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 입력 파일을 열고 Resolution, TiffSettings 및 TIFF 장치 개체를 생성할 수 있습니다. [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-)를 사용하여 단일 TIFF 이미지를 얻을 수 있습니다. [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 클래스의 java.io.OutputStream-) 메서드입니다. 마지막으로 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 TIFF 파일을 로드하고 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 메서드.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 워터마크를 사용하여 CGM을 DICOM로 변환" %}}
API를 사용하면 DICOM 문서에 워터마크가 있는 CGM 파일을 DICOM로 내보낼 수도 있습니다. 워터마크를 추가하려면 먼저 CGM을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 DICOM 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 CGM을 DICOM 파일로 변환 및 회전" %}}
API를 사용하여 필요에 따라 출력 DICOM 이미지를 회전할 수도 있습니다. Image.rotateFlip 메서드는 이미지를 90/180/270도 회전하고 이미지를 가로 또는 세로로 뒤집는 데 사용할 수 있습니다. 라이브러리는 모든 추악한 세부 사항을 캡슐화하면서 복잡한 작업을 수행하는 간단한 방법을 제공합니다. 이미지에 적용할 회전 및 뒤집기 유형을 지정할 수 있습니다. 이미지를 회전하고 뒤집으려면 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 변환된 JPEG 이미지를 로드하고 Image를 호출하면 됩니다. 적절한 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)을 지정하면서 rotateFlip 메서드를 사용합니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ 주요 사용 사례

- **자바 통합 라디오로지 뷰어**  
  진단 해석을 향상시키기 위해 자바 기반 DICOM 뷰어 내에서 CGM 기반 의료 그림을 직접 표시합니다.

- **병원 정보 시스템 (HIS)**  
  병원 네트워크 전반에 걸쳐 접근 가능한 표준화된 이미징 레코드를 위해 CGM를 DICOM으로 변환합니다.

- **방사선 데이터 교환**  
  DICOM의 글로벌 표준을 활용하여 의료 시설 간 변환된 이미징 파일의 원활한 전송을 가능하게 합니다.

- **진단 시각화**  
  다중 모달리티 이미징 연구에 변환된 CGM 데이터를 포함하여 임상 워크플로우를 개선합니다.


## ⚙️ 자동화 시나리오

- **DICOM 처리를 위한 자바 API**  
  이미지 처리 및 DICOM 메타데이터 관리를 위한 자바 라이브러리를 활용하여 CGM에서 DICOM으로의 변환 파이프라인을 자동화합니다.

- **PACS 시스템 통합**  
  변환된 DICOM 이미지를 직접 Picture Archiving and Communication Systems에 공급하여 즉각적인 검색 및 저장이 가능합니다.

- **자바 기반 ETL 파이프라인**  
  병원 전체 이미징 데이터 관리를 위한 추출-변환-로드 워크플로에 자동 변환을 통합합니다.

- **AI 기반 진단 워크플로**  
  변환된 DICOM 이미지를 분석하여 패턴 인식, 이상 징후 감지 및 예측 진단을 위한 자바 통합 AI 모델을 활용합니다.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}