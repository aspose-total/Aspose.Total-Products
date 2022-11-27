---
title: Python을 사용하여 Excel 파일 업데이트 

description: Python 애플리케이션 내에서 Microsoft Office를 설치하지 않고 Microsoft Excel XLSX, XLS, CSV 문서 편집
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 통해 Excel 문서 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 Python 애플리케이션 내에서 Microsoft Excel XLSX, XLS 파일을 수정합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
조직에서 회사 소프트웨어를 통해 학생 데이터, 환자 기록 및 창고 항목 목록 등과 같은 Excel 파일에 저장된 데이터를 업데이트하는 것이 일반적입니다. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API는 소프트웨어를 통해 스프레드시트를 수정하는 기능을 제공합니다. 프로그래머는 API를 통합하고 몇 줄의 코드를 작성하여 수정 기능으로 소프트웨어를 향상시킬 수 있습니다. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 패키지의 일부인 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API를 사용하면 이러한 수정 프로세스를 쉽게 수행할 수 있습니다. 다음은 Excel 문서를 업데이트하는 과정입니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 Excel 문서 업데이트" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API는 Excel 스프레드시트의 로딩을 처리하는 Workbook 클래스를 제공합니다. 프로세스는 간단합니다. 소스 파일을 매개변수로 제공하여 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 클래스 객체를 생성합니다. 색인을 제공하여 관련 워크시트에 액세스하려면 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 방법을 사용하십시오. [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) 메서드를 호출하여 액세스된 셀의 내용을 수정하고 마지막으로 save() 메서드를 호출하여 문서를 저장합니다.

{{% blocks/products/pf/feature-page-code h3="Python - Excel 문서 업데이트" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="업데이트">}}