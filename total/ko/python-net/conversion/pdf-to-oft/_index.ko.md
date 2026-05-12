---
title: Python에서 PDF를 OFT로 변환
description: Microsoft Word 또는 Outlook을 사용하지 않고 Python 응용 프로그램 내에서 PDF를 OFT로 저장

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 PDF를 OFT로 변환" h2="Microsoft Word<sup>&reg;</sup> 또는 Outlook을 설치하지 않고도 Python 응용 프로그램에서 PDF를 OFT로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

Python 개발자의 경우 응용 프로그램 내에서 PDF를 OFT로 변환 기능을 추가하려는 사람은 누구입니까? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API는 변환 프로세스를 자동화하는 데 도움이 될 수 있습니다. 이메일, 이미지 및 Microsoft Word 형식을 포함한 다양한 형식을 처리하는 다양한 API의 전체 패키지입니다. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 패키지의 일부인 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 및 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API를 사용하면 Python을 사용하여 이 변환을 쉽게 수행할 수 있습니다. 2단계 프로세스로, 먼저 PDF 파일을 로드하고 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)를 통해 HTML로 렌더링합니다. 두 번째로 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)을 사용하여 변환된 HTML을 로드하고 OFT 형식으로 저장합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python에서 PDF를 OFT로 변환하는 방법" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 클래스를 사용하여 소스 PDF 파일 열기
- 출력 HTML 파일 경로 및 관련 HTML 저장 옵션을 매개변수로 지정하면서 `save` 메소드를 호출합니다. 따라서 PDF 파일은 지정된 경로에서 HTML로 변환됩니다.
- 이제 MailMessage.load를 사용하여 저장된 HTML 파일을 로드합니다.
- 해당 파일 경로로 save 메소드를 호출합니다. 그래서 마침내 PDF가 변환됩니다

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}

- PDF를 OFT로 변환하려면 Python 3.5 이상이 필요합니다.
- PyPI에서 직접 프로젝트 내 참조 API([Aspose.Words](https://pypi.org/project/aspose-words/) 및 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- 또는 다음 pip 명령 ```pip install aspose.words``` 및 ```pip install Aspose.Email-for-Python-via-NET```을 사용합니다. 
- 또한 Microsoft Windows 또는 Linux 기반 OS([Words](https://docs.aspose.com/words/python-net/system-requirements/) 및 [Email](https://docs.aspose.com/email/python-net/system-requirements/)에 대한 자세한 내용 참조) 및 Linux의 경우 gcc 및 libpython에 대한 추가 요구 사항을 확인하고 단계별 지침 [INSTALL](https://docs.aspose.com/words/python-net/installation/)을 따르십시오.
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python에서 PDF를 OFT로 저장" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API를 사용한 PDF에서 OFT 변환은 PDF 문서를 반복적인 커뮤니케이션 시나리오에 재사용할 수 있는 이메일 템플릿 파일로 변환할 수 있게 합니다. 이는 문서 내용이 표준화된 발신 메시지의 기반이 될 때 특히 가치가 있습니다.

자동화는 대규모로 소스 문서에서 템플릿 생성을 가능하게 하여 이 사용 사례를 강화합니다. 반복 가능한 워크플로를 지원하고, 형식 일관성을 개선하며, 조직이 기존 PDF 자료에서 재사용 가능한 커뮤니케이션 자산을 만들도록 돕습니다.

{{% blocks/products/pf/agp/feature-section-col title="핵심 사용 사례" %}}

* **재사용 가능한 이메일 템플릿 생성**  
  반복적인 커뮤니케이션 요구를 위해 PDF 내용을 OFT 템플릿으로 변환합니다.

* **표준화된 메시징**  
  문서 기반 소스 자료에서 일관된 메시지 구조를 구축합니다.

* **운영 커뮤니케이션 지원**  
  변환된 템플릿을 공지, 응답 또는 서비스 기반 홍보에 사용합니다.

* **템플릿 라이브러리 개발**  
  PDF 문서에서 재사용 가능한 커뮤니케이션 자산을 생성하고 유지합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="자동화 시나리오" %}}

* **자동화된 템플릿 생성**  
  Python 워크플로는 표준화된 PDF를 자동으로 재사용 가능한 OFT 파일로 변환할 수 있습니다.

* **대량 커뮤니케이션 준비**  
  시스템은 반복적인 이메일 작업을 처리하는 팀을 위해 템플릿 준비된 출력을 생성할 수 있습니다.

* **문서 기반 메시징 파이프라인**  
  PDF 소스 파일은 수동 재구성 없이 템플릿 생성 프로세스에 공급될 수 있습니다.

* **확장 가능한 홍보 워크플로**  
  자동 변환은 대규모 운영 전반에 걸쳐 일관된 메시지를 유지하는 데 도움이 됩니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}