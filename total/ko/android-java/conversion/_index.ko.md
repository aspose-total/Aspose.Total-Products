---
title: Android API를 통한 문서 변환 

description: Android 변환 API를 사용하여 Word, Excel, PowerPoint, HTML, PDF 및 이미지 형식을 변환합니다. Android는 Office docx, xlsx, pptx를 PDF로 변환합니다. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android API를 사용한 문서 변환" h2="Java를 통해 Android용 Aspose.Total을 사용하여 Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, 이미지 및 기타 다양한 형식을 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/)는 다른 소프트웨어에 의존하지 않고 Android 애플리케이션을 위한 문서 변환 및 관리 솔루션을 제공합니다. 프로그래머는 새로 개발된 애플리케이션 또는 기존 애플리케이션에 API를 통합하여 문서 관리 및 조작 솔루션을 쉽게 자동화할 수 있습니다. API를 통합함으로써 프로그래머는 애플리케이션 내에서 다양한 형식의 문서를 생성, 편집 또는 변환하는 기능을 쉽게 추가할 수 있습니다. Android의 PDF Converter API는 Office DOCX, XLSX, PPTX를 PDF로 또는 그 반대로 변환하는 경우를 처리합니다. 또한 API가 아래에 나열된 몇 가지 사례와 관련 전환 사례에 대해 제공된 링크가 거의 없습니다. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PDF를 CSV로 변환" %}}
Total Android API는 PDF에서 Excel XLSX 및 CSV로의 변환을 지원합니다. 2단계 프로세스입니다. 두 개의 총 API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 및 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 관련. 프로세스는 먼저 PDF를 Excel XLSX 형식으로 변환한 다음 XLSX를 CSV로 변환하는 것입니다. 자세한 내용은 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 통해 PDF 파일을 로드하고 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-)을 통해 XLSX로 렌더링합니다.  메서드. 다음으로 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 렌더링된 XLSX 문서를 로드하고 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 메서드.

{{% blocks/products/pf/feature-page-code h3="Android - PDF에서 Excel로 변환" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel에서 Word로 변환" %}}
Android API는 Excel 변환도 처리합니다. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 사용하여 EXCEL XLSX 파일을 로드하고 먼저 SaveFormat을 AUTO로 설정하여 EXCEL을 PDF로 변환하는 것입니다. 그런 다음 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 클래스를 사용하여 저장된 PDF 파일을 로드하고 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 메서드를 사용하여 문서를 Word DOC/DOCX 형식으로 저장합니다.

{{% blocks/products/pf/feature-page-code h3="Android - Excel에서 Word로 변환" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="POWERPOINT를 HTML 및 MHTML로 변환" %}}
Android Total API는 PowerPoint 파일을 비롯한 다양한 형식을 처리하므로 프레젠테이션을 HTML 및 MHTML로 변환할 수 있습니다. 프로세스는 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 클래스를 사용하여 POWERPOINT PPT/ PPTX 파일을 로드하고 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) 메서드를 사용하여 POWERPOINT를 HTML로 변환합니다. 그리고 이제 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 클래스를 이용하여 변환된 HTML 문서를 로드하고 [save](https://reference.aspose.com/cells/java/com.aspose.cells/) MHTML 변환 방법. 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint 슬라이드를 HTML 및 MHTML로 변환" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}