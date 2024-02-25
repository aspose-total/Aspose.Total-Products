---
title: जावा एपीआई सीजीएम को डीओसीएम में निर्यात करने के लिए
description: ऑन-प्रिमाइसेस जावा एपीआई का उपयोग करके सीजीएम को डीओसीएम में बदलें
url_ignore: /hi/java/conversion/tex-to-ps/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PS
otherformats: RTF ODT DOTX MHTML FLATOPC PCL DOT OTT DOTM XAMLFLOW WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से सीजीएम को डीओसीएम में बदलना" h2="किसी भी तृतीय पक्ष एप्लिकेशन का उपयोग किए बिना डीओसीएम को सीजीएम प्रस्तुत करने के लिए परिसर जावा एपीआई पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
आप दो सरल चरणों का उपयोग करके TEX को PS में परिवर्तित कर सकते हैं। सबसे पहले आपको [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) का उपयोग करके DOC को TEX फ़ाइल प्रस्तुत करनी होगी। उसके बाद, शक्तिशाली दस्तावेज़ संसाधन API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके, आप DOC को PS में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Java](https://products.aspose.com/total/java/) पैकेज के तहत आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को डीओसीएम में बदलने के लिए जावा एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- का उपयोग करके TEX को DOC में बदलें। ) तरीका
3. Aspose.Words के [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके DOC फ़ाइल लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को PS प्रारूप में सहेजें और PS सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) और [Aspose.Words for Java](https://docs.aspose.com/words/java/) शामिल करें स्थापना/) अपने pom.xml में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
TEX को PS में कनवर्ट करते समय, भले ही आपका दस्तावेज़ पासवर्ड से सुरक्षित हो, फिर भी आप PDF मैनिपुलेशन API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) का उपयोग करके इसे खोल सकते हैं। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आपको एक [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) ऑब्जेक्ट बनाना होगा और मालिक के पासवर्ड का उपयोग करके TEX खोलना होगा।  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.tex", "password");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से पासवर्ड संरक्षित सीजीएम दस्तावेज़ खोलें" %}}
अपने इनपुट दस्तावेज़ को PS फ़ाइल स्वरूप में सहेजते समय, आप फ़ाइल सिस्टम के बजाय अपने दस्तावेज़ को डेटाबेस में सहेज भी सकते हैं। आपको डेटाबेस में और से दस्तावेज़ ऑब्जेक्ट्स को संग्रहीत करने और पुनर्प्राप्त करने की आवश्यकता हो सकती है। यह आवश्यक होगा यदि आप किसी भी प्रकार की सामग्री प्रबंधन प्रणाली को लागू कर रहे थे। अपने PS को डेटाबेस में सहेजने के लिए बाइट सरणी प्राप्त करने के लिए दस्तावेज़ को क्रमबद्ध करना अक्सर आवश्यक होता है। यह [Aspose.Words for Java](https://products.aspose.com/words/Java/) API का उपयोग करके किया जा सकता है। अपनी बाइट सरणी प्राप्त करने के बाद, आप इसे SQL कथन का उपयोग करके डेटाबेस में संग्रहीत कर सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}