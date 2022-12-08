---
title: Java API για εξαγωγή SVG σε DOCM
description: Μετατρέψτε το SVG σε DOCM χρησιμοποιώντας το Java API premise
url_ignore: /el/java/conversion/svg-to-docm/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOCM
otherformats: PCL DOT PS ODT OTT FLATOPC MARKDOWN XAMLFLOW WORDML DOTM DOTX MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατρέψτε το SVG σε DOCM μέσω Java" h2="On Premise Java API για απόδοση SVG σε DOCM χωρίς χρήση εφαρμογής τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το SVG σε DOCM χρησιμοποιώντας δύο απλά βήματα. Πρώτα πρέπει να αποδώσετε το αρχείο SVG στο DOC χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/). Μετά από αυτό, χρησιμοποιώντας το ισχυρό API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/), μπορείτε να μετατρέψετε το DOC σε DOCM. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή SVG σε DOCM" %}}
1. Ανοίξτε το αρχείο SVG χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το SVG σε DOC χρησιμοποιώντας το [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή DOCM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το DOCM ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη μετατροπή του SVG σε DOCM, ακόμα κι αν το έγγραφό σας προστατεύεται με κωδικό πρόσβασης, μπορείτε να το ανοίξετε χρησιμοποιώντας το API χειρισμού PDF [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/). Για να ανοίξετε το κρυπτογραφημένο αρχείο, πρέπει να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) και να ανοίξετε το SVG χρησιμοποιώντας τον κωδικό πρόσβασης κατόχου.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.svg", "password");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το έγγραφο SVG που προστατεύεται με κωδικό πρόσβασης μέσω Java" %}}
Κατά την αποθήκευση του εγγράφου εισόδου σας σε μορφή αρχείου DOCM, μπορείτε επίσης να αποθηκεύσετε το έγγραφό σας σε βάση δεδομένων αντί για σύστημα αρχείων. Ίσως χρειαστεί να εφαρμόσετε την αποθήκευση και την ανάκτηση αντικειμένων εγγράφου προς και από μια βάση δεδομένων. Αυτό θα ήταν απαραίτητο εάν εφαρμόζατε οποιοδήποτε τύπο συστήματος διαχείρισης περιεχομένου. Για να αποθηκεύσετε το DOCM σας στη βάση δεδομένων, είναι συχνά απαραίτητο να σειριοποιήσετε το έγγραφο για να αποκτήσετε έναν πίνακα byte. Αυτό μπορεί να γίνει χρησιμοποιώντας το [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Αφού λάβετε τον πίνακα byte, μπορείτε να τον αποθηκεύσετε στη βάση δεδομένων χρησιμοποιώντας την εντολή SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOCM);
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
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-rtf/" name="SVG Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-wordml/" name="SVG Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-odt/" name="SVG Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-flatopc/" name="SVG Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-ps/" name="SVG Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-pcl/" name="SVG Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-mhtml/" name="SVG Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-dotm/" name="SVG Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-ott/" name="SVG Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-dotx/" name="SVG Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-xamlflow/" name="SVG Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/svg-to-markdown/" name="SVG Προς την MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}