---
title: C++를 통한 문서 변환 
url: /ko/cpp/conversion/
description: C++ API를 사용하여 Word, Excel, PowerPoint, PDF, JSON, 이미지 등과 같은 다양한 문서 형식을 변환합니다. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 사용한 문서 변환" h2="C++ 라이브러리를 사용하여 Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, 이미지 및 기타 다양한 형식을 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/)는 문서 변환 문제를 해결하고 개발자는 새로 개발된 응용 프로그램 또는 기존 응용 프로그램에 API를 통합하여 문서 관리 및 조작 솔루션을 쉽게 자동화할 수 있습니다. C++ 프로그래머는 소프트웨어에 의존하지 않고 솔루션 내에서 다양한 형식의 문서 생성, 편집 또는 변환과 같은 기능을 추가할 수 있습니다. txt에서 PDF로, SVG에서 PNG로, XLSX에서 CSV로, JSON에서 CSV로, Word에서 PDF로, HTML에서 PDF와 같은 몇 가지 일반적인 경우는 쉽게 변환할 수 있습니다. 또한 API가 아래에 나열된 사례와 관련 전환 사례에 대해 제공된 링크가 거의 없습니다. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="마이크로소프트 워드를 엑셀로 변환" %}}
Total C++ API는 Microsoft Word DOC/DOCX에서 Excel로의 변환을 지원합니다.  [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스 참조를 사용하여 Word DOC/DOCX 파일을 로드하고 [저장](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)을 호출하는 프로세스입니다.  멤버 함수를 사용하여 먼저 HTML로 변환합니다. 그런 다음 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 클래스 참조를 사용하여 HTML 문서를 로드하고 [저장](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)을 호출합니다.  멤버 함수를 사용하여 문서를 Excel 형식으로 저장합니다. 

{{% blocks/products/pf/feature-page-code h3="C++ - Word에서 Excel로 변환" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF에서 워드로 변환" %}}
C++ 변환 라이브러리는 PDF에서 Word DOC, DOCX 및 기타 형식 변환도 지원합니다. PDF를 RTF로 렌더링하는 경우를 고려하면 먼저 PDF를 Word DOC/DOCX 형식으로 변환한 다음 RTF로 렌더링하는 두 단계 프로세스입니다. 이를 위해 포함된 단계, [문서](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 클래스 참조를 사용하여 PDF 파일 로드 및 [저장](https://reference.aspose) 호출 .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) PDF를 Word로 변환하는 멤버 함수. 이제 Aspose.Words API의 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스 참조를 사용하여 Word DOC/DOCX 파일을 다시 로드하고 다음을 사용하여 RTF 형식으로 저장합니다. [저장](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) 멤버 함수.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF에서 워드로 변환" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="JSON을 Word로 변환" %}}
JSON 변환을 위해 C++ API는 JSON에서 Word로, Json에서 PowerPoint로, Word에서 JSON으로 등 다양한 조합을 지원합니다. Word 변환의 경우를 고려하여 Process는 새로운 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 객체를 이용하여 파일에서 유효한 JSON 데이터를 읽어와서 호출합니다. [저장](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 메서드를 사용하여 JSON을 PDF 파일로 저장합니다. 이제 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 클래스를 사용하여 저장된 파일을 로드하고 [Save](https://reference)를 사용하여 워드 문서 형식으로 저장합니다. .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 메서드.
{{% blocks/products/pf/feature-page-code h3="C++ - JSON을 Word로 변환" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}