---
title: Python에서 DOTM를 MHTML로 변환
description: Microsoft Word를 사용하지 않고 Python 응용 프로그램에서 DOTM에서 mhtml 웹 아카이브 형식 및 HtmlFixed 파일 변환 

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 DOTM를 MHTML로 변환" h2="Microsoft Word<sup>&reg;</sup>를 설치하지 않고도 Python 응용 프로그램에서 DOTM에서 MHTML, HtmlFixed 및 HTML로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

DOTM를 MHTML(웹 아카이브 형식)로 변환 기능 또는 HtmlFixed에 추가하려는 Python 개발자의 경우 애플리케이션 내에서 절대적으로 배치된 요소를 사용하여 문서를 HTML 형식으로 저장하려고 합니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. 

[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API를 사용하여 DOTM를 MHTML로 변환 기능을 추가합니다. DOTM 파일이 간단한 경우 두 줄의 코드만 있으면 됩니다. DOTM 파일을 로드하고 MHTML 또는 HTML_FIXED로 SaveFormat 열거와 함께 적절한 파일 경로로 save 메소드를 호출하십시오. 그러나 문서 모델을 원본에 가깝게 복원해야 하는 경우 결과 문서 내에 왕복 정보라는 추가 정보를 저장할 필요가 있습니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="어떻게 Python에서 DOTM를 MHTML로 변환" %}}
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 DOTM 파일 로드
- [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)의 인스턴스를 만듭니다.
- export_roundtrip_information를 True로 설정
- [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/)을 MHTML로 지정
- 출력 파일 경로 및 SaveFormat을 매개변수로 지정하면서 `save` 메소드를 호출하십시오. 따라서 DOTM 파일은 지정된 경로에서 MHTML로 변환됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- DOTM를 MHTML 또는 HtmlFixed 형식으로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI([Aspose.Words](https://pypi.org/project/aspose-words/))에서 직접 프로젝트 내 참조 API
- 또는 다음 pip 명령 ```pip install aspose.words```를 사용합니다.
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따릅니다.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 DOTM를 MHTML로 저장 - 단순" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python에서 DOTM에서 MHTML로 변환" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}