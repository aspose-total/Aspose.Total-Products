---
title: Remove ODT Annotation Online or Manage Annotations using Android Mobile Apps
description: delete comments from ODT file through online app for free. Android API code to manage comments of ODT files.

family: total
platformtag: Android
feature: Annotate
informat: ODT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Clear Comments from ODT Document Online or Manage via Android Apps" h2="Develop powerful Android based ODT document annotation utility application. Code listed for managing comments of ODT file." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remove ODT Annotations Online" %}}

1. Import ODT file to delete comments by uploading it
1. Do it by clicking inside the drop area via drag and drop of annotation app
1. Depending on the size of ODT file and internet speed wait for few seconds
1. Click the 'Remove' button to clear comments
1. Download the file instantly

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Remove ODT Document Comments via Android App" %}}

1. Add library reference to android project 
1. Load Document via Document class object
1. Get all comments from the all nodes by using [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) and NodeType.COMMENT 
1. Invoke the [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) method to delete all comments
1. Call the save method to save the file.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Delete Comments from ODT File" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Remove and Add ODT Comment Reply" %}}

1. Add library reference to android project 
1. Load Document via Document class object
1. Get comment using getChild 
1. Use [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) for removing specified reply to this comment 
1. Use [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) for adding any reply to this comment 
1. Call the save method to save the file

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Add Comments via Android App" %}}

1. Add library reference to android project 
1. Create Document class object
1. Use [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) to create the comment 
1. Use getParagraphs().add and getFirstParagraph().getRuns().add  
1. Call the save method to save the file with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Code : Remove and Add Comment Reply from ODT File" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Code: Adding Comments" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Develop ODT Document Annotation Android App</h2>

Need to develop a ODT annotation mobile app or utility to provide feedback, make suggestions, or collaborate with others on the document? With [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) a child API of [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), any android developer can integrate the above API code within its document annotation application. Powerful android library allows programming any document annotation solution. Moreover it can support many popular formats including ODT format.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android Library to Annotate ODT Files" %}}

- We host our Java packages in [Maven repositories](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java is a common JAR file containing byte-code. 
- Follow the [step-by-step instructions](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) on how to install Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

- Java SE 7 and more recent Java versions are supported.
- Separate package for Java SE 6 in case one is obliged to use outdated JRE.
- Java package is cross-platform and runs on all operating systems with JVM implementation.
- Operating systems include Microsoft Windows, Linux, macOS, Android and iOS.

<br />
For more details about optional package dependencies, such as JogAmp JOGL, Harfbuzz font engine, Java Advanced Imaging JAI please refer to [Product Documentation](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}