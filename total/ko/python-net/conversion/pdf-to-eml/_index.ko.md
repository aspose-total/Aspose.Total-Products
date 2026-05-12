---
title: Python에서 PDF를 EML로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 PDF를 EML로 저장

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PDF를 EML로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PDF를 EML로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PDF를 EML로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 PDF 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 EML 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PDF를 EML로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 PDF 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PDF 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PDF가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PDF를 EML로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PDF를 EML로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 PDF를 EML로 변환하면 PDF 문서를 저장, 공유 또는 호환되는 메일 시스템에 가져올 수 있는 표준 이메일 메시지 파일로 변환할 수 있습니다. 이는 커뮤니케이션, 백업 및 상호 운용성을 위해 문서 내용을 메시지 지향 형식으로 보존하는 데 유용합니다.

PDF를 EML로 자동 변환하면 문서를 이메일 아카이브에 수집하고 자동 메시징 흐름 및 대량 처리 시스템에 활용함으로써 운영 효율성을 향상시킵니다. 구조화된 이메일 파일 출력이 필요한 확장 가능한 데이터 교환을 지원합니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **이메일 파일 생성**  
  PDF 문서를 저장, 전송 또는 나중에 전달하기 위한 EML 파일로 변환합니다.

* **보관 워크플로**  
  문서 내용을 표준 이메일 호환 형식으로 보존하여 기록 보관에 활용합니다.

* **메일 시스템 통합**  
  PDF에서 파생된 콘텐츠를 이메일 클라이언트 및 처리 시스템에 가져올 수 있도록 준비합니다.

* **콘텐츠 재활용**  
  PDF 정보를 디지털 커뮤니케이션 워크플로를 위한 구조화된 메시지 파일로 재구성합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **배치 이메일 파일 생성**  
  자동 스크립트를 사용하여 대량의 PDF를 하위 작업에 사용할 EML 파일로 변환할 수 있습니다.

* **아카이브 수집 파이프라인**  
  시스템은 변환된 EML 출력을 저장소나 규정 준수 저장소로 라우팅할 수 있습니다.

* **자동 메시지 준비**  
  PDF 콘텐츠를 프로그래밍 방식으로 이메일 파일로 준비하여 나중에 검토하거나 전송할 수 있습니다.

* **문서-메시지 변환**  
  Python 워크플로는 들어오는 PDF를 동적으로 재사용 가능한 EML 자산으로 전환할 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}