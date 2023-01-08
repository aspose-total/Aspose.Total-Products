---
title: Python을 사용하여 XLT를 DOTX로 변환
description: Microsoft Office를 사용하지 않고 Python 애플리케이션에서 XLT를 DOTX로 변환 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: DOTX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 통해 XLT를 DOTX로 변환" h2="Microsoft Excel<sup>&reg;</sup> 또는 Word를 설치하지 않고 Python 애플리케이션에서 XLT를 DOTX로 변환" >}}

{{% blocks/products/pf/feature-page-summary %}}

응용 프로그램 내에서 DOTX 변환 기능에 XLT를 추가하려는 Python 개발자의 경우. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. XLT 및 DOTX 파일을 포함하여 다양한 형식을 다루는 다양한 API의 전체 패키지입니다.

주로 두 단계로 이루어집니다. 먼저 [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API를 사용하여 XLT 파일을 HTML로 변환합니다. 그런 다음 Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 사용하여 생성된 HTML을 원하는 Microsoft Word 형식으로 저장합니다. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XLT를 DOTX로 변환하는 방법" %}}
- **1 단계** Workbook 클래스를 사용하여 소스 XLT 파일 열기
- 파일 이름과 원하는 디렉토리 경로를 제공하여 save(file, SaveFormat.HTML) 방식을 사용하여 XLT 파일을 HTML로 저장
-  **2 단계** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스의 인스턴스로 HTML 파일 로드
-  출력 DOTX 파일 경로를 지정하면서 `save` 메서드를 호출합니다. 따라서 XLT 파일은 지정된 경로에서 DOTX로 변환됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="전환 요건" %}}

- XLT를 DOTX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 및 [Aspose.Words](https://pypi.org/project/aspose-words/))에서 직접 프로젝트 내의 참조 API
-  또는 다음 pip 명령 ```pip install aspose-cells-python``` 및 ```pip install aspose.words```를 사용합니다.
-  또한 Microsoft Windows 또는 Linux 기반 OS([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 및 [Words](https://docs.aspose.com/words/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 [단계별 지침](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XLT를 HTML로 저장 - 1단계" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python에서 HTML을 DOTX로 저장 - 2단계" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-word/" name="XLT 에게 WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-doc/" name="XLT 에게 DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-docx/" name="XLT 에게 DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-docm/" name="XLT 에게 DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-dot/" name="XLT 에게 DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-dotm/" name="XLT 에게 DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-dotx/" name="XLT 에게 DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-mobi/" name="XLT 에게 MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-odt/" name="XLT 에게 ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-ott/" name="XLT 에게 OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-rtf/" name="XLT 에게 RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/python-net/conversion/xlt-to-wordml/" name="XLT 에게 WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}