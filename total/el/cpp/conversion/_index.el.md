---
title: Μετατροπή εγγράφου μέσω C++ 
url: /el/cpp/conversion/
description: Μετατρέψτε διάφορες μορφές εγγράφων όπως Word, Excel, PowerPoint, PDF, JSON, Images και άλλα χρησιμοποιώντας C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή εγγράφου με χρήση C++" h2="Μετατρέψτε το Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Εικόνες και διάφορες άλλες μορφές χρησιμοποιώντας τη βιβλιοθήκη C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Total C++ Library](https://products.aspose.com/total/cpp/) επιλύει το ζήτημα της μετατροπής εγγράφων και οι προγραμματιστές μπορούν να αυτοματοποιήσουν τη λύση διαχείρισης και χειρισμού εγγράφων εύκολα ενσωματώνοντας το API σε νέες ανεπτυγμένες εφαρμογές ή σε υπάρχουσες εφαρμογές. Οι προγραμματιστές C++ μπορούν να προσθέσουν λειτουργίες όπως δημιουργία, επεξεργασία ή μετατροπή εγγράφων διαφόρων μορφών στη λύση τους χωρίς να βασίζονται σε οποιοδήποτε λογισμικό. Λίγες γενικές περιπτώσεις όπως txt σε PDF, SVG σε PNG, XLSX σε CSV, JSON σε CSV, Word σε PDF, HTML σε PDF, μπορεί κανείς να μετατρέψει εύκολα. Επιπλέον, λίγες περιπτώσεις που ασχολείται με το API παρατίθενται παρακάτω και λίγοι σύνδεσμοι που δίνονται για τις σχετικές περιπτώσεις μετατροπών. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το Microsoft Word σε Excel" %}}
Το Total C++ API υποστηρίζει τη μετατροπή Microsoft Word DOC/DOCX σε Excel.  Η διαδικασία είναι, Φορτώστε το αρχείο Word DOC / DOCX χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) και καλέστε [Αποθήκευση](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) συνάρτηση μέλους για μετατροπή σε HTML πρώτα. Στη συνέχεια, φορτώστε το έγγραφο HTML χρησιμοποιώντας την αναφορά κλάσης [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και καλέστε το [Save](https://reference.aspose.com/ κύτταρα/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) συνάρτηση μέλους για την αποθήκευση του εγγράφου σε μορφή Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Μετατροπή Word σε Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή PDF σε Word" %}}
Η βιβλιοθήκη μετατροπών C++ υποστηρίζει επίσης μετατροπή PDF σε word DOC, DOCX και άλλη μορφή. Λαμβάνοντας υπόψη την περίπτωση της απόδοσης PDF σε RTF, είναι μια διαδικασία δύο βημάτων, πρώτα μετατρέψτε το PDF σε μορφή Word DOC/DOCX και στη συνέχεια αποδώστε το σε RTF. Περιλαμβάνονται βήματα για αυτό, Φόρτωση αρχείου PDF με χρήση αναφοράς κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) και επίκληση [Αποθήκευση](https://reference.aspose .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) συνάρτηση μέλους για μετατροπή PDF σε Word. Τώρα φορτώστε ξανά το αρχείο Word DOC / DOCX χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) του Aspose.Words API και αποθηκεύστε το σε μορφή RTF χρησιμοποιώντας [Αποθήκευση](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) συνάρτηση μέλους.

{{% blocks/products/pf/feature-page-code h3="C++ - Μετατροπή PDF σε Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατροπή JSON σε Word" %}}
Για τη μετατροπή JSON, το C++ API υποστηρίζει διάφορους συνδυασμούς όπως JSON σε Word, Json σε PowerPoint, Word σε JSON κ.λπ. Λαμβάνοντας υπόψη την περίπτωση της μετατροπής του Word, η διαδικασία είναι η ανάγνωση έγκυρων δεδομένων JSON από το αρχείο χρησιμοποιώντας ένα νέο αντικείμενο [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) και, στη συνέχεια, καλέστε Μέθοδος [Αποθήκευση](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) για αποθήκευση JSON ως αρχείο PDF. Επομένως, φορτώστε τώρα το αποθηκευμένο αρχείο χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) και αποθηκεύστε το σε μορφή εγγράφου word χρησιμοποιώντας [Αποθήκευση](https://reference μέθοδος .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Μετατροπή JSON σε Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}