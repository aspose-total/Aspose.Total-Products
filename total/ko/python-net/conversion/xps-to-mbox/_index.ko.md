---
title: Python에서 XPS를 MBOX로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 XPS를 MBOX로 저장

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 XPS를 MBOX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 XPS를 MBOX로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 XPS를 MBOX로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 XPS 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 MBOX 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XPS를 MBOX로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 XPS 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 XPS 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 XPS가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- XPS를 MBOX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XPS를 MBOX로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

XPS에서 MBOX로의 변환은 Python API를 사용하여 고정 레이아웃 문서를 이메일 메시지 컬렉션을 저장하는 메일함 아카이브 형식으로 변환할 수 있게 합니다. 이는 문서 내용이 메일함 기반 저장 구조에 의존하는 보관, 마이그레이션 또는 장기 보존 워크플로에 통합되어야 할 때 유용합니다.

자동화 기반 시스템의 경우, XPS에서 MBOX로의 변환은 확장 가능한 콘텐츠 보존을 지원하고, 보관 패키징을 간소화하며, 문서 레코드를 메일 중심 저장 및 규정 준수 프로세스와 통합하는 데 도움을 줍니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일함 아카이브 생성**  
  XPS 콘텐츠를 MBOX 호환 구조로 변환하여 통합 저장 및 보존 워크플로에 사용합니다.

* **문서 기반 레코드 보존**  
  통신 시스템에서 관리하기 쉬운 메일함 아카이브에 문서 정보를 보존하는 데 도움을 줍니다.

* **마이그레이션 준비**  
  플랫폼 이동 또는 통합을 위해 문서 내용을 메일 아카이브 형식으로 변환하는 것을 지원합니다.

* **대량 콘텐츠 패키징**  
  여러 문서 기반 레코드를 아카이브 준비된 메일함 컬렉션으로 조직할 수 있게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 보관 파이프라인**  
  시스템은 예정된 보존 또는 백업 루틴의 일환으로 XPS 파일을 MBOX 출력으로 변환할 수 있습니다.

* **배치 레코드 통합**  
  대량의 문서 레코드를 효율적인 처리를 위해 프로그래밍 방식으로 메일함 아카이브에 패키징할 수 있습니다.

* **규정 준수 저장 워크플로**  
  자동화된 프로세스는 거버넌스 검토에 적합한 아카이브 형식으로 문서 기반 커뮤니케이션을 보존할 수 있습니다.

* **데이터 마이그레이션 준비**  
  변환 루틴은 다른 환경으로 전송하기 전에 문서 소스에서 메일함 호환 출력을 준비할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}