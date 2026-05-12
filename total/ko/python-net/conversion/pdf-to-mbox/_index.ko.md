---
title: Python에서 PDF를 MBOX로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 PDF를 MBOX로 저장

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PDF를 MBOX로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PDF를 MBOX로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PDF를 MBOX로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 PDF 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 MBOX 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PDF를 MBOX로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 PDF 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PDF 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PDF가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PDF를 MBOX로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PDF를 MBOX로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

PDF API를 사용한 PDF에서 MBOX로의 변환은 PDF 콘텐츠를 이메일 메시지 컬렉션을 저장하는 데 사용되는 메일박스 아카이브 형식으로 변환합니다. 이는 문서 정보를 이메일 아카이브 워크플로에 통합하거나 대량 메시지 저장소에 보존해야 할 때 유용합니다.

이 변환을 자동화하면 확장 가능한 아카이브 작업, 마이그레이션 프로세스 및 구조화된 커뮤니케이션 저장을 지원합니다. 통합 메일박스 데이터 형식에 의존하는 시스템을 위해 PDF 문서를 프로그래밍 방식으로 준비함으로써 수동 작업을 줄여줍니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **메일박스 아카이브 생성**  
  PDF 콘텐츠를 MBOX 호환 레코드로 변환하여 아카이브 및 저장 목적에 활용합니다.

* **대량 커뮤니케이션 패키징**  
  문서에서 파생된 메시지를 메일박스 컬렉션으로 정리하여 시스템 이식성을 높입니다.

* **이메일 아카이브 통합**  
  변환된 출력을 MBOX 컨테이너를 통해 데이터를 관리하는 환경에서 사용합니다.

* **레코드 보존**  
  PDF 기반 정보를 메시지 아카이브 워크플로에 보존합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **배치 아카이브 생성**  
  파이썬 워크플로를 사용해 다수의 PDF를 MBOX 호환 출력으로 자동 변환합니다.

* **규정 준수 보존 파이프라인**  
  변환된 콘텐츠를 장기 보관을 위한 아카이브 저장소에 삽입합니다.

* **마이그레이션 준비**  
  시스템이 PDF 파생 콘텐츠를 메일박스 기반 플랫폼으로 전송하도록 패키징합니다.

* **자동화된 저장소 업데이트**  
  들어오는 PDF 문서를 지속적으로 변환하고 아카이브 워크플로에 추가합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}