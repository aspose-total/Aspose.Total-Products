---
title: Java를 사용하여 Excel 파일 업데이트 

description: Java 기반 응용 프로그램 내에서 Microsoft Office를 설치하지 않고 Microsoft Excel XLSX, XLS, CSV 문서를 편집합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통해 Excel 문서 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 Java 기반 애플리케이션 내에서 Microsoft Excel XLSX, XLS 파일을 수정합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
조직에서 회사 소프트웨어를 통해 학생 데이터, 환자 기록 및 창고 항목 목록 등과 같은 Excel 파일에 저장된 데이터를 업데이트하는 것이 일반적입니다. [Aspose.Total for Java](https://products.aspose.com/total/java/) API는 자체 소프트웨어를 사용하여 스프레드시트를 수정하는 기능을 제공합니다. 프로그래머는 몇 줄의 API 코드를 작성하여 수정 기능으로 소프트웨어를 향상시킬 수 있습니다. [Aspose.Total for Java](https://products.aspose.com/total/java/) 패키지의 일부인 [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API는 이 수정 프로세스를 쉽게 만듭니다. 다음은 Excel 문서를 업데이트하는 과정입니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Java를 사용하여 Excel 문서 업데이트" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API는 Excel 스프레드시트의 로딩을 처리하는 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 제공합니다. 프로세스는 간단합니다. 소스 파일을 매개변수로 제공하여 Workbook 클래스 객체를 생성합니다. [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) 방식으로 해당 Worksheet 및 해당 셀에 접근합니다. [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) 메서드를 사용하여 액세스된 셀의 내용을 수정하고 마지막으로 save() 메서드를 호출하여 문서를 저장합니다.

{{% blocks/products/pf/feature-page-code h3="Java 코드 - Excel 문서 업데이트" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="업데이트">}}