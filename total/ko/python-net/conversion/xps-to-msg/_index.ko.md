---
title: Python에서 XPS를 MSG로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 XPS를 MSG로 저장

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: MSG
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 XPS를 MSG로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 XPS를 MSG로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 XPS를 MSG로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 XPS 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 MSG 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 XPS를 MSG로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 XPS 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 XPS 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 XPS가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- XPS를 MSG로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 XPS를 MSG로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 XPS에서 MSG로의 변환을 통해 고정 레이아웃 문서를 일반적인 데스크톱 기반 메일링 환경에서 사용되는 개별 이메일 메시지 파일로 변환할 수 있습니다. 이는 문서 내용을 검토, 공유 또는 구조화된 커뮤니케이션 워크플로를 위해 독립적인 메시지 레코드로 보존해야 할 때 유용합니다.

자동화는 수동 메시지 생성을 줄이고, 반복 가능한 문서-메시지 변환을 가능하게 하며, 보관, 승인 및 기업 커뮤니케이션 시스템과의 통합을 지원함으로써 명확한 가치를 제공합니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **독립 메시지 파일 생성**  
  XPS 문서를 MSG 파일로 변환하여 체계적인 이메일 형식 저장 및 교환을 가능하게 합니다.

* **문서-커뮤니케이션 변환**  
  고정 레이아웃 문서 내용을 비즈니스 워크플로를 위한 메시지 레코드로 재활용하는 데 도움을 줍니다.

* **검토 가능한 메시지 출력**  
  변환된 콘텐츠를 개별 메시지로 열어보고, 확인하거나 승인해야 하는 워크플로를 지원합니다.

* **기업 레코드 관리**  
  문서에서 파생된 커뮤니케이션을 메시지 파일 형식으로 구조화하여 보존할 수 있게 합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **프로그램 방식 메시지 생성**  
  시스템은 XPS 문서가 최종 완료될 때마다 자동으로 MSG 파일을 생성할 수 있습니다.

* **승인 워크플로 라우팅**  
  변환된 메시지는 자동 검토 또는 승인 프로세스로 전달될 수 있습니다.

* **대량 변환 작업**  
  대규모 XPS 컬렉션을 일관되고 확장 가능한 파이프라인에서 MSG 출력으로 변환할 수 있습니다.

* **보관 및 검색 자동화**  
  문서에서 생성된 메시지 파일은 나중에 접근할 수 있도록 자동으로 인덱싱 및 저장될 수 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}