---
title: Python을 사용하여 DOT를 XLTX로 변환
description: Microsoft Word 또는 Excel을 사용하지 않고 Python 애플리케이션에서 DOT를 XLTX로 변환 

family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: XLTX
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 통해 DOT를 XLTX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Excel을 설치하지 않고 Python 애플리케이션에서 DOT를 XLTX로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}

응용 프로그램 내에서 XLTX 변환 기능에 DOT를 추가하려는 Python 개발자의 경우. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 다양한 형식을 다루는 다양한 API의 전체 패키지입니다.

주로 두 단계로 이루어집니다. 먼저 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API를 사용하여 DOT 파일을 HTML로 변환합니다. 그런 다음 Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/)을 사용하여 생성된 HTML을 원하는 Microsoft Excel 형식으로 저장합니다. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 DOT를 XLTX로 변환하는 방법" %}}
- **1단계** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 DOT 파일 열기
- 파일 이름과 원하는 디렉토리 경로를 제공하여 [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 방식을 사용하여 DOT 파일을 HTML로 저장
-  **2단계** 파일 및 LoadOptions를 매개 변수로 사용하여 Workbook 클래스의 인스턴스가 있는 HTML 파일을 로드합니다.
-  출력 XLTX 파일 경로를 지정하면서 `save` 메서드를 호출합니다. 따라서 DOT 파일은 지정된 경로에서 XLTX로 변환됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="전환 요건" %}}

- DOT를 XLTX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))에서 직접 프로젝트 내의 참조 API
-  또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install aspose-cells-python```을 사용합니다. 
-  또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 [단계별 지침](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 DOT를 HTML로 저장 - 1단계" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python에서 HTML을 XLTX로 저장 - 2단계" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}