---
title: Μετατροπή μορφής αρχείου μέσω C# 
url: /el/net/conversion/
description: Μετατρέψτε τα Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, τρισδιάστατες εικόνες, διαγράμματα, μορφές βίντεο και πολλά άλλα δημοφιλή αρχεία με λίγες μόνο γραμμές κώδικα C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή μορφής αρχείου μέσω C# .NET" h2="Μετατρέψτε αρχεία Microsoft<sup>&reg;</sup> Office, PDF, Εικόνες, HTML και διάφορες άλλες μορφές χωρίς να χρησιμοποιήσετε άλλο λογισμικό." >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET Total Library](https://products.aspose.com/total/net/) επιταχύνει την ανάπτυξη λύσεων διαχείρισης εγγράφων από την αρχή ή τη βελτίωση των υπαρχουσών εφαρμογών για την εύκολη διαχείριση των εγγράφων. Το API όχι μόνο διαχειρίζεται έγγραφα του Microsoft Office, αλλά χειρίζεται επίσης PDF, HTML, Εικόνες TIFF, JPG, PNG, BMP και SVG, αρχεία email, μορφές βίντεο, μορφές δεδομένων GIS και πολλά άλλα. Είναι ένα πλήρες σύνολο API λύσεων διαχείρισης και χειρισμού εγγράφων χωρίς εξαρτήσεις λογισμικού. Οι προγραμματιστές μπορούν εύκολα να δημιουργήσουν, να ενημερώσουν, να αποδώσουν, να εκτυπώσουν και να μετατρέψουν μεταξύ των πιο δημοφιλών μορφών σε οποιαδήποτε εφαρμογή που βασίζεται στο .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Word σε PDF" %}}
Το Total API υποστηρίζει όχι μόνο τη μετατροπή μορφών Microsoft Word αλλά και τη μετατροπή του Word σε PDF, HTML, Εικόνες, EPUB, Markdown και XPS. Η διαδικασία μετατροπής είναι απλή. Φορτώστε το Document μέσω της κλάσης Document και απλώς καλέστε τη μέθοδο Save με τη μορφή προορισμού. Είναι τόσο απλό. Οι προγραμματιστές μπορούν να ελέγξουν το [αποτέλεσμα μετατροπής](https://products.aspose.com/words/net/conversion/word-to-pdf/) πριν από την ενσωμάτωση κώδικα του **Word σε PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Μετατροπή Word σε PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PDF σε Εικόνες" %}}
Το API υποστηρίζει τη μετατροπή PDF σε Εικόνες, Powerpoint, Excel και άλλες μορφές. Για τη μετατροπή PDF σε εικόνα, ας θεωρήσουμε την εικόνα JPG ως αρχείο προορισμού. Η διαδικασία είναι, φορτώστε το αρχείο PDF χρησιμοποιώντας την κλάση Document και αρχικοποιήστε το αντικείμενο [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) και αποδώστε το PDF σε JPEG μέσω [Process](https μέθοδος ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
Φορτώστε το αρχείο JPEG χρησιμοποιώντας την κλάση [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) και τέλος καλέστε τη μέθοδο Save.

{{% blocks/products/pf/feature-page-code h3="C# - Μετατροπή PDF σε εικόνα" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Excel σε Word και PowerPoint" %}}

Για τη μετατροπή μορφών Microsoft Excel σε διαφορετικά αρχεία, συμπεριλαμβανομένων των Word και PowerPoint, σχετικά δευτερεύοντα API που περιλαμβάνονται στο κύριο Aspose.Total για .NET API. Διαδικασία μετατροπής αρχείων Excel σε έγγραφο Word, φορτώστε το αρχείο EXCEL χρησιμοποιώντας την κλάση [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) και μετατρέψτε το EXCEL σε PDF πρώτα και ορίστε το SaveFormat σε Auto. Στη συνέχεια, φορτώστε το αρχείο PDF που μετατράπηκε χρησιμοποιώντας την κλάση Document και καλέστε τη μέθοδο Save και ορίστε το Doc, Docx ως SaveFormat. Ο κώδικας παρατίθεται επίσης για τη μετατροπή Microsoft **Excel σε Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Μετατροπή JSON σε Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Μετατροπή Excel σε JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}