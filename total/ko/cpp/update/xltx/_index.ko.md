---
title: C++를 사용하여 XLTX 파일 업데이트
description: Microsoft Excel을 사용하지 않고 C++ 애플리케이션에서 XLTX 문서 수정.
family: total
platformtag: C++
feature: update
informat: XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 XLTX 파일 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 C++ 기반 응용 프로그램을 통해 XLTX 스프레드시트를 수정할 수 있습니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

C++ 응용 프로그램 내에서 XLTX 파일을 업데이트하려는 프로그래머의 경우, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API는 업데이트 프로세스를 자동화하는 데 도움이 될 수 있습니다. Microsoft Excel 문서를 포함하여 다양한 형식을 다루는 다양한 C++ 라이브러리의 전체 패키지입니다. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 패키지의 일부인 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API를 사용하면 이러한 수정 프로세스를 쉽게 수행할 수 있습니다. XLTX 문서를 업데이트하는 프로세스는 먼저 시트에 액세스한 다음 C++를 사용하여 Excel에서 셀 값을 업데이트하면 간단합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 XLTX 파일을 업데이트하는 방법" %}}

- [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)을 사용하여 XLTX 파일 로드
- GetIWorksheets()->GetObjectByIndex(0)를 이용한 해당 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) 및 GetICells()->GetObjectByIndex를 이용한 해당 셀 접근
- PutValue 방식을 사용하여 접근한 셀에 새로운 데이터 삽입
- 경로를 매개변수로 하는 파일을 전달하여 Save 메서드를 사용하여 파일을 .xltx 파일로 저장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="수정 요구 사항" %}}

- XLTX 수정의 경우 Windows 및 Linux 시스템용 [시스템 요구 사항](https://docs.aspose.com/cells/cpp/system-requirements/)에 따라 
- 명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치
- 또는 ```Install-Package Aspose.Total.Cpp```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해
- 또는 [다운로드](https://downloads.aspose.com/cells/cpp)에서 ZIP 파일로 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="코드 - C++에서 XLTX 파일 업데이트" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 수정 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xls/" name="업데이트 XLS 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xlsx/" name="업데이트 XLSX 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/csv/" name="업데이트 CSV 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xlsb/" name="업데이트 XLSB 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xlsm/" name="수정하다 XLSM 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xlt/" name="업데이트 XLT 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xltx/" name="업데이트 XLTX 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/xltm/" name="업데이트 XLTM 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/cpp/update/tsv/" name="업데이트 TSV 파일" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}