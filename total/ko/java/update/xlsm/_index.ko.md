---
title: Java를 사용하여 XLSM 파일 업데이트
description: Microsoft Excel을 사용하지 않고 Java 응용 프로그램에서 XLSM 문서를 수정합니다. Java에서 Excel 파일을 작성하고 편집하는 가장 빠른 방법을 위해 코드를 최적화합니다.

family: total
platformtag: Java
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 XLSM 파일 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고도 Java 기반 애플리케이션을 통해 XLSM 스프레드시트를 수정합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

개발자의 경우 Java 응용 프로그램에서 누가 XLSM 파일을 업데이트하려고 합니까? [Aspose.Total for Java](https://products.aspose.com/total/java/) API는 업데이트 프로세스를 자동화하는 데 도움이 될 수 있습니다. Microsoft Excel 문서를 비롯한 여러 형식을 처리하는 다양한 Java API의 전체 패키지입니다. [Aspose.Total for Java](https://products.aspose.com/total/java/) 패키지의 일부인 ASPOSE.CELL API는 이러한 수정 프로세스를 쉽게 만듭니다. XLSM 문서 업데이트 프로세스는 먼저 시트에 액세스한 다음 Java를 사용하여 Excel에서 셀 값을 업데이트하면 간단합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java에서 XLSM 파일을 업데이트하는 방법" %}}

- 소스 XLSM 파일을 매개변수로 포함하는 새 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스 객체 생성
- [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) 방식을 사용하여 해당 Worksheet 및 해당 셀에 접근
- [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) 방법을 사용하여 액세스한 셀에 새 데이터 삽입
- 경로를 매개 변수로 파일을 전달하여 save() 메서드를 사용하여 파일을 .xlsm 파일로 저장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="수정 요구 사항" %}}

- XLSM 수정의 경우 Microsoft Windows 또는 JSP/JSF 애플리케이션 및 데스크탑 애플리케이션용 Java Runtime Environment와 호환되는 OS.
- J2SE 6.0(1.6), J2SE 7.0(1.7) 이상.
- [다운로드](https://docs.aspose.com/cells/java/installation/)에서 직접 최신 API 버전 받기

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="코드 - Java에서 XLSM 파일 업데이트" offSpacer="" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}