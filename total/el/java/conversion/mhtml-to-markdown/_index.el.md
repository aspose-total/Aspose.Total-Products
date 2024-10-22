---
title: Διαδικτυακή μετατροπή MHTML σε MARKDOWN ή ανάπτυξη εφαρμογής που βασίζεται σε Java για μετατροπή αρχείων MHTML
description: Δωρεάν διαδικτυακή εφαρμογή για τη μετατροπή αρχείων MHTML σε MARKDOWN. Κώδικας βιβλιοθήκης μετατροπών Java για έγγραφα MHTML.  

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: MARKDOWN
otherformats: RTF WORDML FLATOPC DOT ODT OTT DOTX DOTM PCL XAMLFLOW MARKDOWN PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Διαδικτυακή εφαρμογή μετατροπής MHTML σε MARKDOWN και κώδικας Java για μετατροπή αρχείων MHTML" h2="Αναπτύξτε ισχυρή εφαρμογή μετατροπής και εξαγωγής MHTML που βασίζεται σε Java.  Μετατρέψτε μεμονωμένα ή πολλαπλά αρχεία MHTML σε MARKDOWN και άλλες μορφές μέσω του Java automation API.  Μετατρέψτε ελεύθερα αρχεία MHTML στο διαδίκτυο μέσω εφαρμογής με άμεση λήψη." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Δωρεάν διαδικτυακή εφαρμογή μετατροπής MHTML σε MARKDOWN" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=markdown&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε τα αρχεία MHTML σε MARKDOWN Online χρησιμοποιώντας την εφαρμογή" %}}

1. Ανεβάστε αρχεία MHTML για μετατροπή
1. Περιμένετε μερικά δευτερόλεπτα ή περισσότερα ανάλογα με το μέγεθος MHTML
1. Παρακολουθήστε τη γραμμή κατάστασης μεταφόρτωσης
1. Κάντε κλικ στο κουμπί "Μετατροπή".
1. Το MHTML θα μετατραπεί σε έγγραφο MARKDOWN
1. Κάντε λήψη του αρχείου MARKDOWN που μετατράπηκε

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε το MHTML σε MARKDOWN μέσω Java Automation API" %}}


1. Ανοίξτε το αρχείο MHTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το MHTML σε DOC χρησιμοποιώντας το [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή MARKDOWN χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το MARKDOWN ως SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κώδικας Java για μετατροπή MHTML σε MARKDOWN" offSpacer="" %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-markdown.java" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Λίγες ακόμη περιπτώσεις για αποθήκευση του MHTML στο MARKDOWN με άλλες λειτουργίες όπως το Απαιτήσεις μετατροπής, Ανοίξτε το έγγραφο MHTML που προστατεύεται με κωδικό πρόσβασης μέσω Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Αναπτύξτε την εφαρμογή μετατροπής αρχείων MHTML χρησιμοποιώντας Java</h2>

Χρειάζεστε να αναπτύξετε εφαρμογή λογισμικού βασισμένη σε Java για εύκολη αποθήκευση και εξαγωγή αρχείων MHTML στο έγγραφο MARKDOWN;  Με το [Aspose.Total for Java](https://products.aspose.com/total/el/java/), οποιοσδήποτε προγραμματιστής Java μπορεί να ενσωματώσει τον παραπάνω κώδικα API για να προγραμματίσει την εφαρμογή μετατροπής σε διάφορες μορφές, όπως το Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, αρχεία email, εικόνες (JPG, PNG, BMP, GIF) και άλλες μορφές.  Ισχυρή βιβλιοθήκη Java για μετατροπή εγγράφων, υποστηρίζει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής MHTML.  Εξάγοντας και αποδίδοντας έγγραφα σε άλλες μορφές, οι προγραμματιστές μπορούν να χρησιμοποιήσουν θυγατρικά API Aspose.Total for Java, συμπεριλαμβανομένων των [Aspose.Words for Java](https://products.aspose.com/words/el/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/el/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/el/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/el/java/) και άλλων.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη μετατροπών MHTML για Java" %}}

Υπάρχουν εναλλακτικές επιλογές για να ενσωματώσετε το Aspose.Total for Java στο σύστημά σας.  Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:<br /><br />

- Χρησιμοποιήστε το Aspose.Total for Java απευθείας από ένα έργο που βασίζεται στο Maven και συμπεριλάβετε σχετικό θυγατρικό API στο pom.xml.
- Εναλλακτικά, μπορεί κανείς να πάρει ένα αρχείο ZIP από το [λήψεις](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Αποθήκευση MHTML στις Απαιτήσεις εφαρμογής MARKDOWN" %}}

Οποιοδήποτε λειτουργικό σύστημα που μπορεί να εκτελέσει το Java Runtime Environment (JRE) μπορεί να εκτελέσει Aspose.Total for Java.  Οι παρακάτω λίστες ως επί το πλείστον, αλλά όχι όλα, υποστηριζόμενα λειτουργικά συστήματα.  <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS και άλλα
- macOS : 10.9 (Mavericks) και νεότερη έκδοση
- Κινητό: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}