---
title: Python에서 EMAIL를 PCL로 변환
description: Microsoft Outlook 또는 Word를 사용하지 않고 Python 응용 프로그램에서 EMAIL를 PCL로 저장 

family: total
platformtag: Python
feature: conversion
informat: EMAIL
outformat: PCL
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 EMAIL를 PCL로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 EMAIL를 PCL로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 EMAIL를 PCL로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 이메일을 로드하고 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 사용하여 변환된 HTML을 로드하고 PCL 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 EMAIL를 PCL로 변환하는 방법" %}}

- MailMessage.load 클래스를 사용하여 소스 EMAIL 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 EMAIL 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 EMAIL가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- EMAIL를 PCL로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 EMAIL를 PCL로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python에서 이메일을 PCL로 변환하면 메시지 내용을 프린터 명령 언어 출력으로 변환하여 장치 중심 인쇄 워크플로에 적합하게 합니다. 이는 이메일을 직접 렌더링하여 운영 환경이나 레거시 인쇄 환경에서 일관된 인쇄를 해야 할 때 유용합니다.

메시지 내용을 직접 인쇄 파이프라인으로 이동시켜 자동화를 지원하고, 준비 단계를 줄이며 대규모 출력 생성을 간소화합니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **직접 인쇄 워크플로 지원**
  프린터 준비 출력에 의존하는 시스템을 위해 이메일을 PCL로 변환합니다.

* **운영 메시지 인쇄**
  통신을 표준화된 형식으로 인쇄해야 하는 경우 PCL 출력을 사용합니다.

* **레거시 환경 호환성**
  직접 이메일 렌더링으로 오래된 인쇄 인프라를 지원합니다.

* **중앙 집중식 인쇄 대기열**
  변환된 이메일 파일을 대량 인쇄 프로세스에 공급합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동 인쇄 디스패치**
  수신 이메일을 PCL로 변환하고 예약된 인쇄 대기열로 보냅니다.

* **배치 운영 출력**
  물류, 관리 또는 검토를 위한 프린터 준비 이메일 레코드를 생성합니다.

* **디바이스 기반 문서 전달**
  이메일 변환을 자동 인쇄 관리 시스템과 통합합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}