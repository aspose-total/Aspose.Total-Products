---
title: Python을 통한 문서 변환 

description: Microsoft Word 형식 DOC, DOCX를 PDF, 이미지 등으로 변환하고 프레젠테이션 슬라이드, 이메일 메시지 및 3D 이미지를 Python 코드 몇 줄로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python API를 사용한 문서 변환" h2=".NET을 통해 Python용 Aspose.Words를 사용하여 Microsoft<sup>&reg;</sup> Office Word, PDF, 이미지 및 기타 다양한 형식을 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python APIs](https://products.aspose.com/total/python-net/)는 문서 자동화 솔루션을 처음부터 빠르게 개발하거나 기존 애플리케이션을 개선하여 문서, 프리젠테이션, 이메일 및 3D 파일을 생성, 편집 또는 변환하는 속도를 높입니다. Python API는 Microsoft Office Word 및 프레젠테이션 슬라이드를 처리할 뿐만 아니라 PDF, HTML, 이미지 및 이메일 파일 등을 처리합니다. API는 소프트웨어에 의존하지 않으며 문서 관리 및 조작 솔루션의 전체 세트입니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="마이크로소프트 워드를 PDF로 변환" %}}
Total Python API는 Microsoft Word에서 PDF, 이미지, 마크다운 및 HTML로의 다양한 형식 변환을 지원합니다. API는 DOC, DOCX 파일과 같은 문서에 가까운 품질의 출력으로 Word 문서를 PDF로 변환하는 과정을 간단하게 만듭니다. 프로세스는 DOC 또는 DOCX 파일을 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 개체에 로드하고 [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 메서드를 디렉터리 경로와 함께 대상 PDF 형식으로 사용합니다. 아주 간단합니다. PDF 1.7 또는 1.5와 같은 PDF 표준을 지정해야 하는 경우 API는 설정을 위해 [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) 열거를 제공합니다. [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python - Word에서 PDF로 변환" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word에서 이미지로 변환" %}}
Word에서 이미지로의 변환은 Python API의 anthor 기능입니다. 변환뿐 아니라 밝기, 대비, 수평 및 수직 해상도 등 다양한 저장 옵션을 쉽게 설정할 수 있습니다. 프로세스는 Document 개체를 통해 문서를 로드한 다음 지정된 경로를 가진 원하는 이미지 파일 확장명으로 저장 메서드를 호출하는 것입니다. 다양한 저장 옵션을 지정하기 위해 API는 [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) 또는 [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) 클래스는 필요한 시나리오로 사용됩니다. 아래 코드 샘플은 몇 가지 추가 설정을 적용하여 첫 번째 문서 페이지의 미리보기를 만드는 방법을 보여줍니다.

{{% blocks/products/pf/feature-page-code h3="파이썬 - 워드에서 이미지로의 변환" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint를 Word로 변환" %}}
Python API는 Microsoft PowerPoint PPT/PPTX를 Word DOC/DOCX 파일로 변환하는 것을 지원합니다. 두 가지 API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) 및 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 이 변환을 수행하는 데 사용됩니다. [프레젠테이션](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)을 사용하여 PPT / PPTX 파일을 로드합니다. Words Document 클래스 개체를 가져옵니다. 각 슬라이드를 반복하고 슬라이드 이미지를 생성 및 삽입한 다음 슬라이드 모양을 반복하여 슬라이드 텍스트를 삽입합니다.

{{% blocks/products/pf/feature-page-code h3="Python - PowerPoint 슬라이드를 Word로 변환" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}

{{% blocks/products/pf/feature-page-section  h2="이메일을 Word, PDF, HTML 및 이미지로 변환" %}}
이메일 파일이 PDF, Word, 이미지 및 HTML로 변환되는 경우 Email Python API [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/)가 변환을 수행합니다. API는 개체 모델에서 소스 파일을 로드하고 관련 매개 변수와 함께 Save 메서드를 호출합니다. 

{{% blocks/products/pf/feature-page-code h3="Python - 이메일 파일을 Word로 변환" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="email-to-doc ics-to-docx mbox-to-pdf ost-to-image msg-to-tiff pst-to-jpeg oft-to-gif vcf-to-docm emlx-to-png eml-to-text" >}}