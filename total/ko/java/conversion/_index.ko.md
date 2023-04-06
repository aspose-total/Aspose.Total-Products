---
title: Java를 통한 파일 형식 변환 

description: 몇 줄의 Java 코드로 Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D 이미지, 다이어그램, 비디오 형식 및 기타 다른 형식을 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통한 파일 형식 변환" h2="다른 소프트웨어를 사용하지 않고도 Microsoft<sup>&reg;</sup> Office 문서, PDF, 이미지, HTML 및 기타 여러 파일을 변환할 수 있습니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/)는 문서 조작 솔루션을 처음부터 빠르게 개발하거나 기존 애플리케이션을 개선하여 문서 관리를 쉽게 처리할 수 있도록 합니다. API는 Microsoft Office 문서를 생성, 편집 및 변환할 뿐만 아니라 PDF, HTML, 이미지 TIFF, JPG, PNG, BMP 및 SVG, 이메일 파일, 비디오 형식, 3D, CAD 등을 처리합니다. Java J2SE, J2EE, J2ME 애플리케이션 내에서 소프트웨어 종속성이 없는 문서 관리 및 조작 솔루션 API의 모음입니다. 프로그래머는 모든 Java 기반 응용 프로그램 내에서 가장 널리 사용되는 형식을 쉽게 생성, 업데이트, 렌더링, 인쇄 및 변환할 수 있습니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="워드를 엑셀로 변환" %}}
Total API는 Microsoft Word 형식의 상호 변환은 물론 Word를 Excel, PDF, HTML, 이미지, EPUB, Markdown 및 XPS로 변환하는 기능도 지원합니다. 변환 과정은 간단합니다. **Word to Excel** 변환의 경우를 생각해 봅시다. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 Microsoft Word 파일을 로드하고 [Save method](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). 다음으로 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 변환된 HTML 문서를 열고 [저장](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 메서드.
 개발자는 [Word를 PDF로](https://products.aspose.com/words/java/conversion/word-to-pdf/)로 변환할 수도 있습니다.


{{% blocks/products/pf/feature-page-code h3="Java 워드를 엑셀로 변환" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="PDF를 이미지로 변환" %}}
API는 PDF를 JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel 및 기타 형식과 같은 이미지로 변환하는 것을 지원합니다. PDF를 이미지로 변환하는 경우 JPG 이미지를 대상 파일로 간주해 보겠습니다. 프로세스는 Document 클래스를 사용하여 PDF 파일을 로드하고 [JpegDevice 클래스](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) 객체를 초기화하고 [프로세스](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice)를 통해 PDF를 JPEG로 렌더링하는 것입니다. //apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) 메서드
[Image](https://reference.aspose.com/imaging/java/aspose.imaging/image) 클래스를 사용하여 JPEG 파일을 로드하고 마지막으로 Save 메소드를 호출합니다.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint를 Excel 파일로 변환" %}}

Microsoft PowerPoint 파일을 Excel Word, MHTML, 주요 Aspose.Total for Java API와 관련된 관련 하위 API를 포함한 다른 파일로 변환합니다. PowerPoint 파일을 Excel 문서로 변환하는 과정, [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 PowerPoint 파일을 로드하고 **PowerPoint를 HTML로** 변환 [저장](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) 메서드를 사용합니다. 다음으로 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 변환된 HTML 문서를 로드하고 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook/#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 메서드. **PowerPoint에서 Word로** 변환을 위한 코드도 나열됩니다.

{{% blocks/products/pf/feature-page-code h3="자바 파워포인트를 엑셀로 변환" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="자바 파워포인트를 워드로 변환" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}