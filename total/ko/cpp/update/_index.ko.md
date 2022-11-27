---
title: C++를 사용하여 Excel 파일 업데이트 

description: C++ 기반 응용 프로그램과 함께 Microsoft Office를 설치하지 않고 Microsoft Excel XLSX, XLS, CSV 문서를 편집합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 Excel 문서 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 C++ 기반 애플리케이션 내에서 Microsoft Excel XLSX, XLS 파일을 수정합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
조직에서 회사 소프트웨어를 통해 학생 데이터, 환자 기록 및 창고 항목 목록 등과 같은 Excel 파일에 저장된 데이터를 업데이트하는 것이 일반적입니다. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API는 소프트웨어를 사용하여 스프레드시트를 수정하는 기능을 제공합니다. 프로그래머는 몇 줄의 API 코드를 작성하여 수정 기능으로 소프트웨어를 향상시킬 수 있습니다. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 패키지의 일부인 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API는 이 수정 프로세스를 쉽게 만듭니다. 다음은 Excel 문서를 업데이트하는 과정입니다.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="C++를 사용하여 Excel 문서 업데이트" %}}

[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API를 사용하여 [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)을 사용하여 소스 문서를 로드합니다. GetIWorksheets()->GetObjectByIndex(0)를 사용하여 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)에 액세스하고 GetICells()->GetObjectByIndex를 사용하여 필수 셀에 액세스하십시오. PutValue 메서드를 사용하여 액세스된 셀의 콘텐츠를 수정합니다. 마지막으로 save() 메서드를 호출하여 문서를 저장합니다.

{{% blocks/products/pf/feature-page-code h3="C++ 코드 - Excel 문서 업데이트" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="업데이트">}}