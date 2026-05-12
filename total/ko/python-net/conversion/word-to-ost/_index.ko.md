---
title: Python에서 WORD를 OST로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 WORD를 OST로 저장

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: OST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 WORD를 OST로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 WORD를 OST로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 WORD를 OST로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 WORD 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 OST 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 WORD를 OST로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 WORD 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 WORD 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 WORD가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- WORD를 OST로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 WORD를 OST로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 Word에서 OST로의 변환은 문서 내용을 오프라인 메일함 지향 출력으로 변환하여 동기화된 메일 저장 및 메시지 패키징이 필요한 시나리오에 적용됩니다. 이는 문서 기반 커뮤니케이션 아티팩트가 오프라인 액세스, 보존 또는 마이그레이션 관련 워크플로와 일치해야 할 때 관련될 수 있습니다.

자동화 환경에서 이 변환은 문서 내용을 메일 저장 호환 자산으로 구조화된 변환을 지원하며, 이를 통해 대규모 기업 커뮤니케이션 및 아카이브 프로세스에 통합할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **오프라인 메일 지향 패키징**
  오프라인 메시지 저장 환경과 관련된 워크플로에 맞게 문서 내용을 조정합니다.

* **커뮤니케이션 기록 준비**
  정식 콘텐츠를 메일 호환 아카이브 자산으로 변환하는 것을 지원합니다.

* **마이그레이션 지원**
  메일함 관련 전송 시나리오를 위해 문서 기반 콘텐츠를 준비하는 데 도움을 줍니다.

* **기업 보존 지원**
  문서 워크플로를 메시지 보존 및 저장 요구사항에 맞춥니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **아카이브 변환 워크플로**
  Word 문서를 오프라인 메일 저장 파이프라인에 적합한 출력으로 처리합니다.

* **배치 커뮤니케이션 패키징**
  표준화된 문서를 메일함 지향 자산으로 자동 변환합니다.

* **보존 자동화**
  변환 루틴을 사용하여 대규모로 커뮤니케이션 스타일 콘텐츠를 보존합니다.

* **마이그레이션 준비 파이프라인**
  Word에서 OST로의 변환을 기업 콘텐츠 이동 워크플로에 통합합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}