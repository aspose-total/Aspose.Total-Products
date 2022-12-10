---
title: .NET을 사용하여 XLSX 파일 업데이트
description: Microsoft Excel을 사용하지 않고 C# VB.NET 응용 프로그램에서 XLSX 문서를 수정합니다. 

family: total
platformtag: .NET
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1=".NET을 통해 XLSX 파일 업데이트" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 .NET 기반 응용 프로그램을 통해 XLSX 스프레드시트를 수정합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

개발자의 경우 누가 .NET 응용 프로그램을 통해 XLSX 파일을 업데이트하려고 합니까? [Aspose.Total for .NET](https://products.aspose.com/total/net/) API는 업데이트 프로세스를 자동화하는 데 도움이 될 수 있습니다. Microsoft Excel 파일을 포함하여 다양한 형식을 처리하는 다양한 .NET API의 전체 패키지입니다. [Aspose.Total for .NET](https://products.aspose.com/total/net/) 패키지의 일부인 ASPOSE.CELL API는 이러한 수정 프로세스를 쉽게 만듭니다. 다음은 XLSX 문서를 업데이트하는 과정입니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET에서 XLSX 파일을 업데이트하는 방법" %}}

- 소스 XLSX 파일을 매개변수로 포함하는 새 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) 클래스 객체 생성
- [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) 방식을 사용하여 해당 Worksheet 및 해당 셀에 접근
- [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) 방법을 사용하여 액세스한 셀에 새 데이터 삽입
- 경로를 매개 변수로 파일을 전달하여 save() 메서드를 사용하여 파일을 .xlsx 파일로 저장합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="수정 요구 사항" %}}

- XLSX 수정의 경우 Microsoft Windows 또는 .NET, .NET Core, Mono 또는 Xamarin 플랫폼과 호환되는 OS
- Microsoft Visual Studio와 같은 개발 환경 
- 명령줄에서 ```nuget install Aspose.Cells```로 설치하거나 ```Install-Package Aspose.Cells```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.
- 또는 오프라인 MSI 설치 프로그램 또는 [다운로드](https://releases.aspose.com/cells/net)에서 ZIP 파일의 모든 DLL을 가져옵니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="코드 - .NET에서 XLSX 파일 업데이트" offSpacer="" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 수정 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xls/" name="업데이트 XLS 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xlsx/" name="업데이트 XLSX 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/csv/" name="업데이트 CSV 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xlsb/" name="업데이트 XLSB 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xlsm/" name="수정하다 XLSM 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xlt/" name="업데이트 XLT 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xltx/" name="업데이트 XLTX 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/xltm/" name="업데이트 XLTM 파일" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/update/tsv/" name="업데이트 TSV 파일" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}