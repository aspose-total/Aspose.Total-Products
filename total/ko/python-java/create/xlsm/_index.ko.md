---
title: Python에서 XLSM 만들기
description: Microsoft Office를 사용하지 않고 Python 응용 프로그램을 사용하여 XLSM 파일을 생성합니다. 

family: total
platformtag: Python
feature: create
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 XLSM 만들기" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 Python 애플리케이션을 통해 XLSM를 생성합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

개발자의 경우 Python 응용 프로그램을 통해 XLSM 파일을 만들려는 사람은 누구입니까? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API는 생성 프로세스를 자동화하는 데 도움이 될 수 있습니다. Microsoft Office 파일 및 이미지를 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 패키지의 일부인 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API는 이 생성 프로세스를 쉽게 만듭니다. 아래는 생성 과정입니다. 또한 개발자는 XLSM 파일 수정 응용 프로그램을 쉽게 향상시킬 수 있습니다. Python 프로세스를 사용하여 XLSM 파일을 업데이트하는 방법은 Workbook 개체를 생성할 때 기존 파일이 매개변수로 필요하다는 점을 제외하면 동일합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XLSM 파일을 만드는 방법" %}}

- 파일FormatType이 매개변수로 포함된 새 [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 클래스 객체 생성
- [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 방법을 사용하여 필요한 [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet)에 액세스
- [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) 방식을 사용하여 접근한 셀에 데이터 삽입
- 경로를 매개 변수로 파일을 전달하여 [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)을 사용하여 문서를 .xlsm 파일로 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="생성 요구 사항" %}}

- XLSM 생성의 경우 PyPI([Aspose.Cells](https://pypi.org/project/aspose-cells/))에서 직접 프로젝트 내 API 참조
- 또는 다음 pip 명령 ```pip install aspose.cells``를 사용하십시오.` 
- 또한 [downloads](https://releases.aspose.com/cells/python-java) 섹션에서 API 패키지를 다운로드하십시오. 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XLSM 만들기" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}