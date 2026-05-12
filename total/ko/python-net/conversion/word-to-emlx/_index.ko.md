---
title: Python에서 WORD를 EMLX로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 WORD를 EMLX로 저장

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 WORD를 EMLX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 WORD를 EMLX로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 WORD를 EMLX로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 WORD 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EMLX 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 WORD를 EMLX로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 WORD 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 WORD 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 WORD가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- WORD를 EMLX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 WORD를 EMLX로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 Word에서 EMLX로의 변환은 워드 프로세싱 문서를 특정 이메일 환경에서 일반적으로 사용되는 EMLX 메시지 파일로 변환할 수 있게 합니다. 이는 문서 내용이 보존되거나 메일 중심 형식으로 재사용되어야 하는 상황을 지원합니다.

자동화된 시스템에서 이 변환은 문서가 구조화된 이메일 아티팩트가 되어 메시지 저장, 마이그레이션 또는 커뮤니케이션 처리 파이프라인에 맞게 흐름 연속성을 향상시킵니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일 클라이언트 호환성**
  문서 내용을 호환 가능한 메시징 환경에서 사용할 수 있도록 EMLX 파일로 변환합니다.

* **문서 기반 메시지 보관**
  워드로 작성된 콘텐츠를 체계적인 저장에 적합한 메시지 형식으로 보존합니다.

* **다중 형식 콘텐츠 재사용**
  동일한 원본 자료가 문서와 이메일 용도 모두에 활용될 수 있도록 합니다.

* **마이그레이션 준비**
  문서 소스에서 메시지 호환 파일이 필요한 전환을 지원합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 메일 파일 변환**
  워드 문서를 저장 또는 이후 가져오기를 위해 EMLX 출력물로 처리합니다.

* **보존 워크플로 지원**
  비즈니스 문서를 구조화된 보관을 위한 이메일 형식 기록으로 변환합니다.

* **배치 콘텐츠 패키징**
  표준화된 문서 템플릿으로부터 대규모 메시지 파일을 생성합니다.

* **시스템 통합 파이프라인**
  EMLX 출력을 보다 넓은 콘텐츠 및 커뮤니케이션 워크플로에서 중간 자산으로 사용합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}