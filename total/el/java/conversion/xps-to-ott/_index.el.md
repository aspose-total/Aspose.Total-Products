---
title: Διαδικτυακή μετατροπή XPS σε OTT ή ανάπτυξη εφαρμογής που βασίζεται σε Java για μετατροπή αρχείων XPS
description: Δωρεάν διαδικτυακή εφαρμογή για τη μετατροπή αρχείων XPS σε OTT. Κώδικας βιβλιοθήκης μετατροπών Java για έγγραφα XPS.  

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: OTT
otherformats: DOTM FLATOPC DOT MHTML WORDML PCL PS OTT MARKDOWN RTF DOTX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Διαδικτυακή εφαρμογή μετατροπής XPS σε OTT και κώδικας Java για μετατροπή αρχείων XPS" h2="Αναπτύξτε ισχυρή εφαρμογή μετατροπής και εξαγωγής XPS που βασίζεται σε Java.  Μετατρέψτε μεμονωμένα ή πολλαπλά αρχεία XPS σε OTT και άλλες μορφές μέσω του Java automation API.  Μετατρέψτε ελεύθερα αρχεία XPS στο διαδίκτυο μέσω εφαρμογής με άμεση λήψη." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Δωρεάν διαδικτυακή εφαρμογή μετατροπής XPS σε OTT" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ott&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε τα αρχεία XPS σε OTT Online χρησιμοποιώντας την εφαρμογή" %}}

1. Ανεβάστε αρχεία XPS για μετατροπή
1. Περιμένετε μερικά δευτερόλεπτα ή περισσότερα ανάλογα με το μέγεθος XPS
1. Παρακολουθήστε τη γραμμή κατάστασης μεταφόρτωσης
1. Κάντε κλικ στο κουμπί "Μετατροπή".
1. Το XPS θα μετατραπεί σε έγγραφο OTT
1. Κάντε λήψη του αρχείου OTT που μετατράπηκε

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Μετατρέψτε το XPS σε OTT μέσω Java Automation API" %}}


1. Ανοίξτε το αρχείο XPS χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το XPS σε DOC χρησιμοποιώντας το [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή OTT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το OTT ως SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-ott.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Λίγες ακόμη περιπτώσεις για αποθήκευση του XPS στο OTT με άλλες λειτουργίες όπως το Απαιτήσεις μετατροπής, Ανοίξτε το έγγραφο XPS που προστατεύεται με κωδικό πρόσβασης μέσω Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.OTT);
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

<h2>Αναπτύξτε την εφαρμογή μετατροπής αρχείων XPS χρησιμοποιώντας Java</h2>

Χρειάζεστε να αναπτύξετε εφαρμογή λογισμικού βασισμένη σε Java για εύκολη αποθήκευση και εξαγωγή αρχείων XPS στο έγγραφο OTT;  Με το [Aspose.Total for Java](https://products.aspose.com/total/el/java/), οποιοσδήποτε προγραμματιστής Java μπορεί να ενσωματώσει τον παραπάνω κώδικα API για να προγραμματίσει την εφαρμογή μετατροπής σε διάφορες μορφές, όπως το Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, αρχεία email, εικόνες (JPG, PNG, BMP, GIF) και άλλες μορφές.  Ισχυρή βιβλιοθήκη Java για μετατροπή εγγράφων, υποστηρίζει πολλές δημοφιλείς μορφές, συμπεριλαμβανομένης της μορφής XPS.  Εξάγοντας και αποδίδοντας έγγραφα σε άλλες μορφές, οι προγραμματιστές μπορούν να χρησιμοποιήσουν θυγατρικά API Aspose.Total for Java, συμπεριλαμβανομένων των [Aspose.Words for Java](https://products.aspose.com/words/el/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/el/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/el/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/el/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/el/java/) και άλλων.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Βιβλιοθήκη μετατροπών XPS για Java" %}}

Υπάρχουν εναλλακτικές επιλογές για να ενσωματώσετε το Aspose.Total for Java στο σύστημά σας.  Επιλέξτε αυτό που μοιάζει με τις ανάγκες σας και ακολουθήστε τις οδηγίες βήμα προς βήμα:<br /><br />

- Χρησιμοποιήστε το Aspose.Total for Java απευθείας από ένα έργο που βασίζεται στο Maven και συμπεριλάβετε σχετικό θυγατρικό API στο pom.xml.
- Εναλλακτικά, μπορεί κανείς να πάρει ένα αρχείο ZIP από το [λήψεις](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Αποθήκευση XPS στις Απαιτήσεις εφαρμογής OTT" %}}

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