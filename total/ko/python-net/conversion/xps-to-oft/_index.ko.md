---
title: Python에서 XPS를 OFT로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 XPS를 OFT로 저장

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 XPS를 OFT로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 XPS를 OFT로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 XPS를 OFT로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 XPS 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 OFT 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XPS를 OFT로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 XPS 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 XPS 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 XPS가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- XPS를 OFT로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XPS를 OFT로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 XPS에서 OFT로의 변환은 고정 레이아웃 문서 콘텐츠를 재사용 가능한 이메일 템플릿 파일로 변환할 수 있게 합니다. 이는 조직이 구조화된 문서 출력을 알림, 캠페인, 승인 또는 표준화된 서신을 위한 반복 가능한 메시지 템플릿으로 변환하려는 경우에 유용합니다.

자동화 워크플로우에서 이 변환은 일관성을 향상시키고 반복적인 작성 작업을 줄이며, 문서 중심 시스템 및 비즈니스 규칙으로부터 템플릿화된 커뮤니케이션을 확장 가능하게 생성하는 것을 지원합니다.

{{% blocks/products/pf/agp/feature-section-col title="주요 사용 사례" %}}

* **재사용 가능한 이메일 템플릿 생성**  
  XPS 콘텐츠를 OFT 템플릿으로 변환하여 반복적인 커뮤니케이션 시나리오에 재사용할 수 있습니다.

* **표준화된 서신 워크플로우**  
  문서 기반 이메일 프로세스 전반에 걸쳐 일관된 구조와 메시지를 유지하도록 돕습니다.

* **템플릿 기반 알림 시스템**  
  문서 출력을 운영 메시지를 위한 반복 가능한 이메일 템플릿으로 전환하는 것을 지원합니다.

* **프로세스 기반 커뮤니케이션 설계**  
  구조화된 문서 콘텐츠가 템플릿화된 아웃리치 워크플로우에 직접 연결될 수 있게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **동적 템플릿 생성**  
  시스템은 XPS 문서를 OFT 템플릿으로 변환하여 향후 자동화된 메시지 채우기에 사용할 수 있습니다.

* **규칙 기반 커뮤니케이션 파이프라인**  
  자동화된 워크플로우는 문서 유형이나 워크플로우 단계에 따라 템플릿을 선택하고 생성할 수 있습니다.

* **대량 템플릿 준비**  
  배치 작업은 표준화된 XPS 입력으로부터 다수의 OFT 파일을 생성하여 확장 가능한 커뮤니케이션 작업을 수행할 수 있습니다.

* **통합 알림 자동화**  
  변환된 템플릿은 데이터를 프로그래밍 방식으로 병합하여 개인화된 발신 메시지를 생성하는 시스템에서 사용할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}