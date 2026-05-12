---
title: Python에서 ODT를 OST로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 ODT를 OST로 저장

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: OST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 ODT를 OST로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 ODT를 OST로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 ODT를 OST로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 ODT 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 OST 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 ODT를 OST로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 ODT 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 ODT 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 ODT가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- ODT를 OST로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 ODT를 OST로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

ODT에서 OST로의 변환은 문서 내용을 오프라인 메일함 데이터 워크플로와 연관된 형식으로 변환하며, 이때 내용은 저장, 마이그레이션 또는 커뮤니케이션 관련 패키징을 위해 재활용될 수 있습니다. 이는 특수한 보관 또는 기업 메세징 시나리오에서 유용할 수 있습니다.

Python API를 사용하면 ODT에서 OST로의 변환이 메일함 형태 저장 프로세스와의 통합이 필요한 자동화된 문서 변환을 지원할 수 있습니다. 이는 메시지 중심 환경에서 반복성을 향상시키고 수동 준비 작업을 줄여줍니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일함 지향 패키징**  
  오프라인 메세지 저장 워크플로에서 사용하기 위해 문서 내용을 변환합니다.

* **보관 지원**  
  커뮤니케이션 관련 저장 형식에서 재활용된 텍스트를 보존하는 데 도움을 줍니다.

* **마이그레이션 준비**  
  문서에서 파생된 내용을 메일함 생태계로 이동하는 것을 지원합니다.

* **구조화된 레코드 변환**  
  문서와 메세징 아티팩트를 결합하는 기업 프로세스를 지원합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 콘텐츠 패키징**  
  Python 스크립트를 사용하여 정의된 워크플로에서 ODT 파일을 메일함 관련 출력으로 변환할 수 있습니다.

* **배치 보관 처리**  
  대규모 문서 저장소를 커뮤니케이션 중심 저장 작업을 위해 변환할 수 있습니다.

* **마이그레이션 파이프라인 통합**  
  자동화된 작업이 변환된 내용을 하위 메일함 처리에 준비할 수 있습니다.

* **보존 워크플로우 지원**  
  문서에서 파생된 출력은 장기 기록 보관을 위해 일관되게 생성될 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}