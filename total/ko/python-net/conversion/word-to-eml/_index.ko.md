---
title: Python에서 WORD를 EML로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 WORD를 EML로 저장

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 WORD를 EML로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 WORD를 EML로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 WORD를 EML로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 WORD 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EML 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 WORD를 EML로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 WORD 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 WORD 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 WORD가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- WORD를 EML로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 WORD를 EML로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 Word를 EML로 변환하면 워드 프로세싱 문서를 표준 이메일 메시지 파일로 변환하여 저장, 공유 또는 호환되는 메일 클라이언트에 가져올 수 있습니다. 이는 커뮤니케이션이나 보관 용도로 메시지 기반 형식으로 문서 내용을 보존해야 하는 조직에 중요합니다.

자동화 및 통합을 위해, Word를 EML로 변환하면 승인 워크플로, 대량 처리 루틴 및 자동 메시징 아카이브에 사용할 수 있는 휴대용 이메일 파일을 반복적으로 생성할 수 있습니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **휴대용 이메일 파일 생성**
  문서 내용을 지원되는 이메일 도구에서 열거나 가져올 수 있는 EML 파일로 변환합니다.

* **메시지 보관**
  인식된 메일 파일 구조에 통신 또는 문서 기반 공지를 보존합니다.

* **템플릿 변환**
  재사용 가능한 워드 템플릿을 운영용 표준화된 메시지 파일로 변환합니다.

* **클라이언트 가져오기 지원**
  준비된 메시지 내용을 이메일 환경으로 이동하기 쉽게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **대량 메시지 파일 생성**
  배치 워크플로에서 여러 워드 문서로부터 자동으로 EML 파일을 생성합니다.

* **승인-보관 파이프라인**
  최종 문서를 보존 및 감사 목적을 위한 이메일 파일로 변환합니다.

* **자동 메시지 패키징**
  하위 메일 시스템 및 배포 도구를 위한 EML 출력을 생성합니다.

* **콘텐츠 재사용 워크플로**
  문서 내용을 재사용 가능한 이메일 아티팩트로 프로그래밍 방식 변환을 가능하게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}