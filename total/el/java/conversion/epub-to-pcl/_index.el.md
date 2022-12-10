---
title: Java API για εξαγωγή EPUB σε PCL
description: Μετατρέψτε το EPUB σε PCL χρησιμοποιώντας το Java API premise
url_ignore: /el/java/conversion/epub-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PCL
otherformats: ODT PS PCL DOT DOTX WORDML XAMLFLOW OTT FLATOPC MARKDOWN MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατρέψτε το EPUB σε PCL μέσω Java" h2="On Premise Java API για απόδοση EPUB σε PCL χωρίς χρήση εφαρμογής τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το EPUB σε PCL χρησιμοποιώντας δύο απλά βήματα. Πρώτα πρέπει να αποδώσετε το αρχείο EPUB στο DOC χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/). Μετά από αυτό, χρησιμοποιώντας το ισχυρό API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/), μπορείτε να μετατρέψετε το DOC σε PCL. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή EPUB σε PCL" %}}
1. Ανοίξτε το αρχείο EPUB χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το EPUB σε DOC χρησιμοποιώντας το [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή PCL χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το PCL ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PCL
outputDocument.save("output.pcl", SaveFormat.PCL);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη μετατροπή του EPUB σε PCL, ακόμα κι αν το έγγραφό σας προστατεύεται με κωδικό πρόσβασης, μπορείτε να το ανοίξετε χρησιμοποιώντας το API χειρισμού PDF [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/). Για να ανοίξετε το κρυπτογραφημένο αρχείο, πρέπει να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) και να ανοίξετε το EPUB χρησιμοποιώντας τον κωδικό πρόσβασης κατόχου.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το έγγραφο EPUB που προστατεύεται με κωδικό πρόσβασης μέσω Java" %}}
Κατά την αποθήκευση του εγγράφου εισόδου σας σε μορφή αρχείου PCL, μπορείτε επίσης να αποθηκεύσετε το έγγραφό σας σε βάση δεδομένων αντί για σύστημα αρχείων. Ίσως χρειαστεί να εφαρμόσετε την αποθήκευση και την ανάκτηση αντικειμένων εγγράφου προς και από μια βάση δεδομένων. Αυτό θα ήταν απαραίτητο εάν εφαρμόζατε οποιοδήποτε τύπο συστήματος διαχείρισης περιεχομένου. Για να αποθηκεύσετε το PCL σας στη βάση δεδομένων, είναι συχνά απαραίτητο να σειριοποιήσετε το έγγραφο για να αποκτήσετε έναν πίνακα byte. Αυτό μπορεί να γίνει χρησιμοποιώντας το [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Αφού λάβετε τον πίνακα byte, μπορείτε να τον αποθηκεύσετε στη βάση δεδομένων χρησιμοποιώντας την εντολή SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-rtf/" name="EPUB Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-wordml/" name="EPUB Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-odt/" name="EPUB Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-flatopc/" name="EPUB Προς την FLAΠρος τηνPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-ps/" name="EPUB Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-pcl/" name="EPUB Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-mhtml/" name="EPUB Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-dotm/" name="EPUB Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-ott/" name="EPUB Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-dotx/" name="EPUB Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-xamlflow/" name="EPUB Προς την XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/epub-to-markdown/" name="EPUB Προς την MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}