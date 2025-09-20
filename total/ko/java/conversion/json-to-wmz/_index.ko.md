---
title: Java를 통해 JSON 형식을 WMZ로 변환
description: Microsoft PowerPoint를 사용하지 않고 Java에서 JSON을 WMZ로 구문 분석
url_ignore: /ko/java/conversion/json-to-wmz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMZ
otherformats: SVGZ WMZ JPEG2000 TGA DICOM IMAGE EMZ DXF PSD WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 WMZ로 변환" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 JSON 형식을 WMZ로 구문 분석하는 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 두 가지 간단한 단계를 통해 모든 Java 애플리케이션 내에서 JSON 형식을 WMZ로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 JPEG로 파싱할 수 있습니다. 그 후 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)를 사용하여 JPEG를 WMZ로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 WMZ로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 객체를 생성하고 JSON 파일을 엽니다.
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)을 사용하여 JSON을 JPEG로 저장합니다. ) 방법
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 문서를 로드합니다.
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 WMZ 형식으로 저장합니다 방법
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
[Maven](https://releases.aspose.com/total/java/) 기반 프로젝트에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://releases.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
또한 API를 사용하면 지정된 레이아웃 옵션을 사용하여 JSON을 WMZ로 구문 분석할 수 있습니다. 레이아웃 옵션을 지정하기 위해 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 클래스를 사용할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 레이아웃 설정 및 JSON 형식을 WMZ로 변환" %}}
API를 사용하여 WMZ 문서에 워터마크가 있는 JSON을 WMZ로 변환할 수도 있습니다. 워터마크를 추가하려면 먼저 JSON을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 WMZ 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSON을 WMZ로 변환**하는 것은 **구조화된 데이터에서 압축된 Windows Metafile 그래픽을 생성하는 데 필수적**입니다. WMZ 파일은 문서, 보고서 및 기업 시스템에 임베딩하기에 이상적인 조밀하고 확장 가능한 벡터 그래픽을 제공합니다. JSON을 WMZ로 변환함으로써 조직은 저장 공간을 최적화하고 크로스 플랫폼 호환성을 향상시키며 가벼우면서 고품질 그래픽을 자동으로 생성할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **가벼운 그래픽 저장** – 효율적인 저장 및 전송을 위해 벡터 그래픽을 압축합니다.
- **문서 임베딩** – WMZ 그래픽을 워드, 파워포인트 및 엑셀 파일에 원활하게 통합합니다.
- **크로스 플랫폼 호환성** – Windows 및 기타 환경에서 확장 가능한 그래픽을 유지합니다.
- **비즈니스 보고 시각화** – 기업 보고서를 위한 차트 및 다이어그램 생성을 자동화합니다.
- **최적화된 기업 다이어그램** – 기업 문서 작성을 위한 표준화된 압축된 시각 자료를 생성합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **JSON-to-WMZ 파이프라인** – 구조화된 데이터를 압축된 WMZ 그래픽으로 자동 변환합니다.
- **자동화된 압축 그래픽 생성** – 벡터 품질을 유지하면서 파일 크기를 줄입니다.
- **JSON 기반 시각 최적화** – 데이터 기반 시각을 효율적으로 생성합니다.
- **기업용 가벼운 일러스트레이션 워크플로우** – 부서 및 시스템 전반에 걸쳐 WMZ 생성을 확장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}