---
title: Python에서 PDF를 EMAIL로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 PDF를 EMAIL로 저장

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PDF를 EMAIL로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PDF를 EMAIL로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PDF를 EMAIL로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 PDF 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EMAIL 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PDF를 EMAIL로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 PDF 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PDF 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PDF가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PDF를 EMAIL로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PDF를 EMAIL로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

PDF를 이메일로 변환하는 Python API를 사용하면 조직이 정적 PDF 문서를 커뮤니케이션, 보관 및 워크플로우 전달을 위한 이메일 준비 콘텐츠로 변환할 수 있습니다. 이 프로세스는 접근성, 가독성 및 배포 속도가 중요한 메시징 환경에서 팀이 문서 기반 정보를 재사용하도록 돕습니다.

PDF를 이메일로 변환하는 작업을 자동화함으로써 기업은 알림, 보고, 고객 접촉 및 문서 기반 커뮤니케이션 파이프라인을 효율화할 수 있습니다. 수동 포맷팅 작업을 줄이고 문서 콘텐츠가 현대 자동화 시스템으로 효율적으로 이동하도록 함으로써 확장 가능한 워크플로우를 지원합니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **문서 기반 알림**  
  PDF 콘텐츠를 이메일 메시지로 변환하여 보고서, 알림 또는 요약을 빠르게 전달합니다.

* **워크플로우 커뮤니케이션**  
  변환된 이메일 콘텐츠를 승인 체인, 내부 업데이트 및 서비스 커뮤니케이션에 사용합니다.

* **디지털 콘텐츠 재활용**  
  PDF 기반 정보를 이메일 채널에서 수동으로 콘텐츠를 다시 만들지 않고 재사용합니다.

* **고객 문서 전달**  
  청구서, 명세서 및 정보 문서를 보다 접근성 높은 이메일 형식으로 보냅니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 보고서 배포**  
  예약된 시스템이 PDF 보고서를 이메일로 변환하고 이해관계자에게 자동으로 전송할 수 있습니다.

* **트리거된 알림 파이프라인**  
  비즈니스 이벤트가 PDF를 이메일로 변환을 시작하여 즉시 외부 커뮤니케이션을 수행합니다.

* **문서 라우팅 워크플로우**  
  변환된 이메일 콘텐츠를 팀, 부서 또는 고객에게 동적으로 라우팅할 수 있습니다.

* **대규모 메시징 운영**  
  Python 기반 자동화를 통해 대량의 PDF 파일을 이메일 준비 출력으로 효율적으로 처리할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}