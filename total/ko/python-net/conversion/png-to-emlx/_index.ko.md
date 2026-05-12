---
title: Python에서 PNG를 EMLX로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 PNG를 EMLX로 저장

family: total
platformtag: Python
feature: conversion
informat: PNG
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PNG를 EMLX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PNG를 EMLX로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PNG를 EMLX로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 PNG 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EMLX 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PNG를 EMLX로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 PNG 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PNG 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PNG가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PNG를 EMLX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PNG를 EMLX로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

PNG to EMLX 변환은 이미지 기반 콘텐츠를 특정 메일 저장 환경에서 일반적으로 사용되는 이메일 메시지 파일로 변환할 수 있게 하여, 시각 정보를 구조화되고 재사용 가능한 형식으로 보존하는 데 도움을 줍니다. 이는 조직 또는 마이그레이션을 위해 이미지 콘텐츠를 개별 이메일 레코드로 표현해야 하는 워크플로에 유용합니다.

Python API를 사용하면 PNG 파일에서 자동화된 EMLX 생성을 가능하게 하여 프로세스가 보다 효율적이고 확장 가능해지며, 수동 처리를 줄이고 메일 데이터 준비, 백업 및 변환 시스템과의 통합을 지원합니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일함 마이그레이션 준비**  
  메일 데이터 이동 워크플로를 위해 PNG 콘텐츠를 EMLX 호환 메시지 파일로 변환합니다.

* **시각 메시지 보존**  
  이미지 기반 커뮤니케이션을 구조화된 이메일 레코드로 저장하여 나중에 접근할 수 있도록 돕습니다.

* **이메일 파일 재구성**  
  시스템 호환성을 위해 PNG 소스에서 이메일 형식의 아티팩트를 생성하는 것을 지원합니다.

* **메일 데이터 조직**  
  운영 일관성을 위해 팀이 시각 콘텐츠를 메일 지향 파일 구조로 표현할 수 있게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 EMLX 내보내기 파이프라인**  
  Python API는 예정된 내보내기 작업의 일환으로 PNG 입력에서 EMLX 파일을 생성할 수 있습니다.

* **마이그레이션 지원 워크플로**  
  시스템은 메일함 전송 또는 통합 전에 이미지 기반 메일 레코드를 자동으로 준비할 수 있습니다.

* **대량 시각 콘텐츠 패키징**  
  대량의 PNG 파일 세트를 배치 자동화를 통해 EMLX 출력으로 변환할 수 있습니다.

* **아카이브 정규화 프로세스**  
  변환 루틴은 이미지 기반 커뮤니케이션 자산을 일관된 저장을 위해 EMLX 형식으로 표준화할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}