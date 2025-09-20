---
title: Java를 통해 JSON 형식을 JPEG2000로 변환
description: Microsoft PowerPoint를 사용하지 않고 Java에서 JSON을 JPEG2000로 구문 분석
url_ignore: /ko/java/conversion/json-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: PSD SVGZ TGA WMZ IMAGE JPEG2000 DICOM DXF EMZ WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 JSON 형식을 JPEG2000로 변환" h2="Java J2SE, J2EE, J2ME 애플리케이션 내에서 JSON 형식을 JPEG2000로 구문 분석하는 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하면 두 가지 간단한 단계를 통해 모든 Java 애플리케이션 내에서 JSON 형식을 JPEG2000로 변환할 수 있습니다. 먼저 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)를 사용하여 JSON을 JPEG로 파싱할 수 있습니다. 그 후 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)를 사용하여 JPEG를 JPEG2000로 변환할 수 있습니다.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 JSON 형식을 JPEG2000로 변환" %}}
1. 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 객체를 생성하고 JSON 파일을 엽니다.
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)을 사용하여 JSON을 JPEG로 저장합니다. ) 방법
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 사용하여 JPEG 문서를 로드합니다.
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase)을 사용하여 문서를 JPEG2000 형식으로 저장합니다 방법
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
또한 API를 사용하면 지정된 레이아웃 옵션을 사용하여 JSON을 JPEG2000로 구문 분석할 수 있습니다. 레이아웃 옵션을 지정하기 위해 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 클래스를 사용할 수 있습니다. 배열을 테이블로 처리하고, null을 무시하고, 배열 제목을 무시하고, 개체 제목을 무시하고, 문자열을 숫자 또는 날짜로 변환하고, 날짜 및 숫자 형식을 설정하고, 제목 스타일을 설정할 수 있습니다. 이러한 모든 옵션을 사용하면 필요에 따라 데이터를 표시할 수 있습니다. 다음 코드 스니펫은 레이아웃 옵션을 설정하는 방법을 보여줍니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java를 통해 레이아웃 설정 및 JSON 형식을 JPEG2000로 변환" %}}
API를 사용하여 JPEG2000 문서에 워터마크가 있는 JSON을 JPEG2000로 변환할 수도 있습니다. 워터마크를 추가하려면 먼저 JSON을 JPEG로 변환하고 워터마크를 추가할 수 있습니다. 워터마크를 추가하기 위해서는 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스를 이용하여 이미지 파일을 불러오고, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 클래스의 객체를 생성합니다. ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) 클래스를 생성하고 Image 객체로 초기화하고 새로운 [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 객체를 생성하고 번역 및 변형을 원하는 각도로 설정하고 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#)을 사용하여 워터마크를 추가합니다. drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 메서드. 이미지에 워터마크를 추가한 후 JPEG를 JPEG2000 형식으로 저장할 수 있습니다. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
**JSON을 JPEG2000으로 변환**하는 것은 구조화된 데이터로부터 **고품질 압축 이미지**를 생성하는 데 중요합니다. JPEG2000은 기존 포맷과 비교하여 우수한 압축 효율성, 확장성 및 이미지 충실도를 제공하여 정밀성과 최적화된 저장 공간을 요구하는 산업에 이상적입니다. JSON 데이터 세트를 JPEG2000으로 변환함으로써 조직은 파일 크기를 줄이고 이미지 품질을 향상시킨 상태에서 의료, 지리정보, 보존 및 기업 애플리케이션용 고급 시각 자료를 생성할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

- **디지털 아카이브** – 구조화된 데이터를 압축된 고품질 이미지 파일로 저장합니다.
- **의료 이미징** – 의료 데이터 세트를 진단용 JPEG2000 이미지로 변환합니다.
- **지리정보 매핑** – JSON 입력으로부터 확장 가능한 위성 또는 GIS 시각 자료를 생성합니다.
- **기업 이미지 워크플로우** – 대규모 사용을 위한 표준화된 압축 이미지 형식을 구축합니다.
- **데이터 주도 시각화** – 데이터 세트를 최적화된 고해상도 그래픽으로 변환합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

- **JSON-to-JPEG2000 파이프라인** – 구조화된 데이터를 압축된 이미지 파일로 자동 변환합니다.
- **고해상도 이미지 생성** – 복잡한 JSON 데이터 세트로부터 상세한 이미지를 생성합니다.
- **자동화된 압축 워크플로우** – 효율적인 압축으로 대규모 이미지 저장을 최적화합니다.
- **아카이브 데이터 이미징** – 데이터 세트를 공간 효율적인 장기 이미지 기록으로 보존합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}