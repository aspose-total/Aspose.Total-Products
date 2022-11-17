---
title: Python을 사용하여 파일 생성 

description: Microsoft Office를 설치하지 않고 텍스트 및 Microsoft Word 문서 만들기 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python을 사용하여 문서 만들기" h2="Microsoft Office<sup>&reg;</sup>를 설치하지 않고 Python 응용 프로그램 내에서 텍스트 및 Microsoft Word DOCX, DOC 파일을 만듭니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
데이터 저장은 응용 프로그램 특성에 따라 모든 소프트웨어 응용 프로그램의 기본입니다. 저장 위치는 데이터베이스, XML, JSON, 텍스트 파일, Excel 보고서 또는 Microsoft Word 문서일 수 있습니다. 파일 I/O는 모든 언어의 일부이며 Python을 포함한 대부분의 언어는 텍스트 파일에 데이터 쓰기를 지원합니다. 파이썬 언어를 생각해 봅시다. Python을 사용하여 기존 텍스트 파일 쓰기, 이 작업에 대한 열기, 쓰기 및 닫기 방법을 제공합니다. 먼저 관련 파일 경로가 있는 파일을 열고 기능을 인수로 추가하거나 씁니다. 그런 다음 필요한 텍스트를 파일에 쓰고 마지막으로 close() 메서드를 사용하여 파일을 닫습니다. 

Python을 사용하여 Microsoft Word 문서를 생성하기 위해 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API를 패키지의 일부로 포함하는 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 패키지를 사용합니다. 이 API는 송장, 보고서 및 기술 문서에 대한 완전한 문서 자동화 솔루션을 제공합니다. 워드 문서 생성 절차는 아래와 같습니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Python을 사용하여 텍스트 파일을 만드는 방법" %}}

텍스트 파일을 만들고 쓰는 것은 간단합니다. Python은 3개의 매개변수가 있는 open() 메서드를 제공하며 파일 경로와 함께 매개변수 중 하나를 사용해야 합니다. 세 개의 매개변수는 "x", "a" 및 "w"입니다. "x"를 제공하면 새 파일이 생성되지만 파일이 이미 있는 경우 오류가 발생합니다. "a"를 제공함으로써 존재하지 않는 경우 새로운 텍스트 파일이 생성되고 존재하는 경우 콘텐츠가 끝에 추가됩니다. 마지막으로 "w"를 제공하면 새 텍스트 문서가 생성되고 이미 존재하는 경우 새 콘텐츠로 덮어씁니다.

{{% blocks/products/pf/feature-page-code h3="Python - 텍스트 파일 생성" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word 문서 만들기" %}}

Total Python Word API에는 Microsoft Word 파일 생성, 문서 내에 이미지 및 텍스트 삽입, 파일 내에 테이블 및 목록 추가, 기존 문서를 쉽게 수정하는 등 여러 기능이 있습니다. Microsoft Word 문서 프로세스를 생성하려면 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 및 [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/) 클래스의 개체를 생성합니다. 문서 내에 필요한 텍스트, 단락, 목록 및 표를 추가하고 마지막으로 저장합니다.

{{% blocks/products/pf/feature-page-code h3="Python - Microsoft Word 문서 만들기" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}