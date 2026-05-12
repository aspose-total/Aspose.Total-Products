---
title: Python에서 XPS를 EMLX로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 XPS를 EMLX로 저장

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 XPS를 EMLX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 XPS를 EMLX로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 XPS를 EMLX로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 XPS 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EMLX 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XPS를 EMLX로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 XPS 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 XPS 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 XPS가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- XPS를 EMLX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XPS를 EMLX로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 XPS에서 EMLX로의 변환은 고정 레이아웃 XPS 문서를 EMLX 스타일 저장을 사용하는 환경에 맞춘 이메일 메시지 파일로 변환하는 데 도움을 줍니다. 이는 문서 콘텐츠를 메일함 형태의 조직, 메시지 검토 또는 마이그레이션 관련 워크플로에 재활용해야 할 때 유용합니다.

XPS에서 EMLX로의 변환을 자동화함으로써 조직은 문서 처리 과정을 간소화하고 반복적인 서식 작업을 줄이며, 문서 생성 프로세스를 구조화된 이메일 저장 및 플랫폼별 메시지 관리 작업과 연결할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일함 지향 문서 패키징**  
  메시지 기반 구조에 콘텐츠를 저장하는 워크플로를 위해 XPS 파일을 EMLX 메시지로 변환합니다.

* **플랫폼별 메시지 준비**  
  메일 데이터 처리 또는 마이그레이션에 EMLX 호환성이 중요한 환경을 지원합니다.

* **메시지 형태의 문서 보존**  
  조직된 접근 및 검토를 위해 이메일과 유사한 구조에 문서 콘텐츠를 유지하는 데 도움이 됩니다.

* **마이그레이션 지원 워크플로**  
  호환 가능한 메일 생태계로 전송하기 위해 문서에서 파생된 메시지 파일을 준비하는 데 도움을 줍니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 콘텐츠 변환**  
  시스템은 파일이 생성되거나 업로드되는 즉시 XPS 문서를 EMLX 출력으로 변환할 수 있습니다.

* **메일함 데이터 준비**  
  자동화된 워크플로는 구조화된 메일함 가져오기 또는 조직을 위해 메시지 형식 파일을 준비할 수 있습니다.

* **대용량 변환 파이프라인**  
  배치 처리 스크립트는 반복 가능한 EMLX 출력 생성을 통해 대규모 문서 컬렉션을 효율적으로 처리할 수 있습니다.

* **통합 보존 프로세스**  
  변환된 파일은 메시지 기반 레코드가 필요한 저장 및 거버넌스 워크플로에 자동으로 라우팅될 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}