---
title: C#을 통한 파일 형식 변환 
url: /ko/net/conversion/
description: 단 몇 줄의 C# 코드로 Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D 이미지, 다이어그램, 비디오 형식 및 기타 널리 사용되는 파일을 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C#을 통한 파일 형식 변환 .NET" h2="다른 소프트웨어를 사용하지 않고 Microsoft<sup>&reg;</sup> Office 파일, PDF, 이미지, HTML 및 기타 형식을 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET 토탈 라이브러리](https://products.aspose.com/total/net/) 문서 관리 솔루션을 처음부터 개발하거나 기존 애플리케이션을 개선하여 문서 조작을 쉽게 처리하는 속도를 높입니다. API는 Microsoft Office 문서를 관리할 뿐만 아니라 PDF, HTML, 이미지 TIFF, JPG, PNG, BMP 및 SVG, 이메일 파일, 비디오 형식, GIS 데이터 형식 등을 처리합니다. 소프트웨어 종속성이 없는 완전한 문서 관리 및 조작 솔루션 API 세트입니다. 프로그래머는 모든 .NET 기반 응용 프로그램 내에서 가장 널리 사용되는 형식을 쉽게 생성, 업데이트, 렌더링, 인쇄 및 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="워드를 PDF로 변환" %}}
Total API는 Microsoft Word 형식의 상호 변환은 물론 Word를 PDF, HTML, 이미지, EPUB, Markdown 및 XPS로 변환하는 기능도 지원합니다. 변환 과정은 간단합니다. Document 클래스를 통해 Document를 로드하고 대상 형식으로 Save 메서드를 호출하기만 하면 됩니다. 아주 간단합니다. 개발자는 **Word to PDF**의 코드 통합 전에 [변환 결과](https://products.aspose.com/words/net/conversion/word-to-pdf/)를 확인할 수 있습니다.


{{% blocks/products/pf/feature-page-code h3="C# - Word에서 PDF로 변환" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="PDF를 이미지로 변환" %}}
API는 PDF를 이미지, PowerPoint, Excel 및 기타 형식으로 변환하는 것을 지원합니다. PDF를 이미지로 변환하는 경우 JPG 이미지를 대상 파일로 간주해 보겠습니다. 프로세스는 Document 클래스를 사용하여 PDF 파일을 로드하고 [JpegDevice 클래스](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) 객체를 초기화하고 [프로세스](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)를 통해 PDF를 JPEG로 렌더링하는 것입니다. //apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 방법
[Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 클래스를 사용하여 JPEG 파일을 로드하고 마지막으로 Save 메서드를 호출합니다.

{{% blocks/products/pf/feature-page-code h3="C# - PDF를 이미지로 변환" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Excel을 Word 및 PowerPoint로 변환" %}}

Microsoft Excel 형식을 Word 및 PowerPoint를 포함한 다른 파일로 변환하기 위해 .NET API용 주요 Aspose.Total과 관련된 관련 하위 API. Excel 파일을 Word 문서로 변환하는 과정, [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 이용하여 EXCEL 파일을 불러오고, 먼저 EXCEL을 PDF로 변환하고 SaveFormat을 Auto로 설정합니다. 그런 다음 변환된 PDF 파일을 Document 클래스를 사용하여 로드하고 Save 메서드를 호출하고 Doc, Docx를 SaveFormat으로 설정합니다. Microsoft **Excel을 Powerpoint로** 변환하는 코드도 나열되어 있습니다.

{{% blocks/products/pf/feature-page-code h3="C# - JSON에서 Excel로의 변환" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Excel에서 JSON으로 변환" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}