---
title: Remove PDF Annotation Online or Manage Annotations using Android Mobile Apps
description: delete comments from PDF file through online app for free. Android API code to manage comments of PDF files.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Clear Comments from PDF Document Online or Manage via Android Apps" h2="Develop powerful Android based PDF document annotation utility application. Code listed for managing comments of PDF file." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remove PDF Annotations Online" %}}

1. Import PDF file to delete comments by uploading it
1. Do it by clicking inside the drop area via drag and drop of annotation app
1. Depending on the size of PDF file and internet speed wait for few seconds
1. Click the 'Remove' button to clear comments
1. Download the file instantly

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Remove PDF Document Comments via Android App API" %}}

1. Add library reference to android project 
1. Load Document via Document class object
1. Select the specific page via getPages().get_Item(Index) 
1. Use the AnnotationSelector and get all text annotations via annotationSelector.getSelected()
1. Iterate through each annotationa call the delete method to remove it.
1. Call the save method to save the file.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Delete Comments from PDF File" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Add Annotation via Android App API" %}}

1. Add library reference to android project 
1. Create Document class object
1. Add the new page and content using getPages().add() 
1. Use getPages().get_Item(Index) of TextAnnotation class
1. Set the relevant annotations such as title, subject, content etc
1. Use getAnnotations().add to add the annotations
1. Call the save method to save the file with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Add PDF Annotation" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Develop PDF Document Annotation Android App</h2>

Need to develop a PDF annotation mobile app or utility to provide feedback, make suggestions, or collaborate with others on the document? With [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) a child API of [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), any android developer can integrate the above API code within its document annotation application. Powerful android library allows programming any document annotation solution. Moreover it can support many popular formats including PDF format.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android Library to Annotate PDF Files" %}}

- We host our Java packages in [Maven repositories](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java is a common JAR file containing byte-code. 
- Follow the [step-by-step instructions](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) on how to install Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

- Android API 31 and 32
- Android 4.0 and above
- Android Studio and SDK tools

<br />
For more details about optional package dependencies, such as JogAmp JOGL, Harfbuzz font engine, Java Advanced Imaging JAI please refer to [Product Documentation](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}