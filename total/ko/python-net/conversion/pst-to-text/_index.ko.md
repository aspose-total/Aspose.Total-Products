---
title: Python에서 PST를 TEXT로 변환
description: Microsoft Outlook 또는 Word를 사용하지 않고 Python 응용 프로그램에서 PST를 TEXT로 저장 

family: total
platformtag: Python
feature: conversion
informat: PST
outformat: TEXT
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PST를 TEXT로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PST를 TEXT로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PST를 TEXT로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 이메일을 로드하고 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 사용하여 변환된 HTML을 로드하고 TEXT 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PST를 TEXT로 변환하는 방법" %}}

- MailMessage.load 클래스를 사용하여 소스 PST 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PST 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PST가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PST를 TEXT로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PST를 TEXT로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API에서 PST를 TEXT로 변환하면 메일함 내용을 인덱싱, 분석 및 가벼운 보관용으로 순수 텍스트로 추출합니다. 형식보다 가독성에 중점을 두는 경우, 특히 검색 가능성과 처리 효율성을 우선시하는 시스템에서 유용합니다.

자동화를 위해 PST를 TEXT로 변환하면 텍스트 마이닝, 콘텐츠 추출 및 단순 구조화된 입력에 최적화된 파이프라인과의 통합을 지원합니다. 이를 통해 메일함 보관 파일을 대규모로 파싱, 변환 및 분석하기가 쉬워집니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **Plain Text Extraction**
  PST 콘텐츠를 텍스트로 변환하여 메시지 데이터를 깔끔하고 형식 없는 형태로 접근합니다.

* **Search and Index Support**
  메일함 보관 파일을 검색 및 콘텐츠 발견 워크플로에 적합하도록 준비합니다.

* **Analysis-Ready Output**
  형식이 있는 문서보다 단순 텍스트가 선호되는 다운스트림 처리에 활용됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **Text Processing Pipelines**
  자동화 시스템이 PST에서 추출한 텍스트를 인덱싱 또는 분석 워크플로에 전달할 수 있습니다.

* **Data Extraction Workflows**
  순수 텍스트 출력은 파싱, 필터링 및 변환 작업을 단순화합니다.

* **Scalable Content Mining**
  프로그래밍 방식 변환을 통해 대규모 메일함 보관 파일을 보다 효율적으로 분석할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}