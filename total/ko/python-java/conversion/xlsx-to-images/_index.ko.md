---
title: Python을 사용하여 XLSX을 이미지로 변환
description: Microsoft Excel을 사용하지 않고 Python 응용 프로그램에서 이미지 TIFF BMP PNG JPEG GIF EMF SVG 변환 XLSX 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 통해 XLSX을 이미지로 변환" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고도 Python 응용 프로그램에서 XLSX을 JPG, TIFF, BMP, PNG, GIF 이미지로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

응용 프로그램 내에서 PNG, BMP, TIFF, JPEG 및 GIF 이미지 변환 기능에 XLSX을 추가하려는 Python 개발자의 경우. 웹 또는 데스크탑 애플리케이션에 Excel 스프레드시트를 포함해야 하는 경우가 있습니다. 이러한 경우 스프레드시트를 이미지로 내보내는 것이 유일한 해결책입니다. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API를 사용하면 Excel 파일을 이미지로 내보내고 변환 프로세스를 자동화할 수 있습니다. 하위 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API를 통해 Microsoft Excel 형식을 비롯한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. 현재 Python Excel to Image Converter API는 Excel 파일을 EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM 및 Office 호환 EMF로 변환하거나 지원되는 [형식](https://docs.aspose.com/cells/python-java/supported-file-formats/)를 확인하는 것을 지원합니다. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XLSX을 이미지로 변환하는 방법" %}}

- XLSX 파일을 로드하기 위한 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 클래스 객체 생성
- [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) 클래스 사용 및 출력 이미지 관련 옵션 지정
- [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) 방법을 사용하여 변환을 위한 워크시트에 액세스
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) 방법을 사용하여 워크시트의 모든 페이지를 이미지로 저장합니다. 이제 XLSX 파일이 지정된 경로의 이미지로 변환됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- XLSX에서 이미지(JPG, PNG, GIF, BMP, TIFF)로 변환하는 경우 PyPI([Aspose.Cells](https://pypi.org/project/aspose-cells/))에서 직접 프로젝트 내 참조 API
- 또는 다음 pip 명령을 사용하십시오. ```pip install aspose.cells``` 
- 또한 [다운로드](https://releases.aspose.com/cells/python-java) 섹션에서 API 패키지를 다운로드합니다. 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python을 통한 XLSX 이미지 변환" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}