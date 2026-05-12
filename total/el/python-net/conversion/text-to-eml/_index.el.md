---
title: Μετατροπή TEXT σε EML στην Python
description: Αποθηκεύστε το TEXT σε EML εντός εφαρμογών Python χωρίς να χρησιμοποιήσετε το Microsoft Word ή το Outlook

family: total
platformtag: Python
feature: conversion
informat: TEXT
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή TEXT σε EML χρησιμοποιώντας Python" h2="Μετατροπή TEXT σε EML στις εφαρμογές σας Python χωρίς εγκατάσταση του Microsoft Word<sup>&reg;</sup> ή του Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Για έναν προγραμματιστή Python, ποιος προσπαθεί να προσθέσει μια δυνατότητα μετατροπής TEXT σε EML εντός της εφαρμογής; Το [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API μπορεί να βοηθήσει στην αυτοματοποίηση της διαδικασίας μετατροπής. Είναι ένα πλήρες πακέτο διαφόρων API που αφορούν διαφορετικές μορφές, συμπεριλαμβανομένων μορφών email, εικόνων και Microsoft Word. Τα API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) και [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) που αποτελούν μέρος του πακέτου [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) καθιστούν αυτή τη μετατροπή εύκολη με τη χρήση της Python. Είναι μια διαδικασία δύο βημάτων, πρώτα φορτώστε το αρχείο TEXT και αποδώστε το σε HTML μέσω του [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Δεύτερον, φορτώστε το μετατρεπόμενο HTML χρησιμοποιώντας το [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) και αποθηκεύστε το σε μορφή EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το TEXT σε EML στην Python" %}}

- Ανοίξτε το αρχείο προέλευσης TEXT χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Καλέστε τη μέθοδο «αποθήκευση» ενώ καθορίζετε τη διαδρομή αρχείου HTML εξόδου και τις σχετικές επιλογές αποθήκευσης HTML ως παράμετρο. Έτσι, το αρχείο TEXT μετατρέπεται σε HTML στην καθορισμένη διαδρομή
- Τώρα Φορτώστε το αποθηκευμένο αρχείο HTML χρησιμοποιώντας το MailMessage.load
- Καλέστε τη μέθοδο αποθήκευσης με σχετική διαδρομή αρχείου. Έτσι τελικά το TEXT μετατρέπεται

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

- Για τη μετατροπή TEXT σε EML, απαιτείται Python 3.5 ή νεότερη έκδοση
- Αναφορά API εντός του έργου απευθείας από το PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) και [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Ή χρησιμοποιήστε την ακόλουθη εντολή pip ```pip install aspose.words``` και ``pip install Aspose.Email-for-Python-via-NET``` 
- Επιπλέον, λειτουργικό σύστημα που βασίζεται σε Microsoft Windows ή Linux (δείτε περισσότερα για [Words](https://docs.aspose.com/words/python-net/system-requirements/) και [Email](https://docs.aspose.com/email/python-net/system-requirements/)) και για Linux ελέγξτε τις πρόσθετες απαιτήσεις για gcc και libpython και ακολουθήστε τις οδηγίες βήμα προς βήμα [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκευση TEXT σε EML στην Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Η μετατροπή κειμένου σε μορφή EML χρησιμοποιώντας τις Python APIs επιτρέπει το απλό κειμενικό περιεχόμενο να μετατρέπεται σε τυπικά αρχεία μηνυμάτων email που διατηρούν τη δομή και τη φορητότητα του email. Αυτό είναι σημαντικό για την αρχειοθέτηση, τη διαλειτουργικότητα και τα συστήματα που χρειάζονται να δημιουργούν αυτόνομα αρχεία email για αποθήκευση ή ανταλλαγή.

Με τη μετατροπή του κειμένου σε μορφή EML, οι αυτοματοποιημένες ροές εργασίας μπορούν να δημιουργούν επαναχρησιμοποιήσιμα αρχεία μηνυμάτων, να υποστηρίζουν ενσωματώσεις βασισμένες σε email και να βελτιστοποιούν τη μετατροπή εγγράφου-σε-μήνυμα σε κλιμακώσιμα ψηφιακά περιβάλλοντα.

{{% blocks/products/pf/agp/feature-section-col title="Κύριες Περιπτώσεις Χρήσης" %}}

* **Δημιουργία Αρχείου Email**  
  Μετατρέπει απλό κείμενο σε αρχεία EML για αποθήκευση, μεταφορά ή μεταγενέστερη επεξεργασία email.

* **Διατήρηση Αρχείων**  
  Βοηθά στη διατήρηση των κειμενικών επικοινωνιών σε αναγνωρισμένη μορφή αρχείου email για συμμόρφωση και διαχείριση αρχείων.

* **Διαλειτουργική Ανταλλαγή Μηνυμάτων**  
  Υποστηρίζει την κοινή χρήση δομημένων αρχείων email μεταξύ εργαλείων και συστημάτων που αναγνωρίζουν το EML.

* **Αυτοματοποιημένη Συσκευασία Αναφορών**  
  Επιτρέπει σε περιλήψεις ή αναφορές κειμένου να αποθηκεύονται ως αρχεία μηνυμάτων για ανασκόπηση και διανομή.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Σενάρια Αυτοματοποίησης" %}}

* **Αυτόματα Δημιουργημένα Αρχεία Ταχυδρομείου**  
  Τα συστήματα μπορούν να μετατρέπουν τα κειμενικά αποτελέσματα σε αρχεία EML για αρχεία επικοινωνίας με δυνατότητα ανίχνευσης.

* **Συμπλέγματα Δημιουργίας Μαζικών Αρχείων**  
  Το κειμενικό περιεχόμενο από βάσεις δεδομένων ή σενάρια μπορεί να μετατραπεί σε παρτίδες αρχείων EML προγραμματιστικά.

* **Ροές Εξαγωγής Μηνυμάτων**  
  Η αυτοματοποίηση μπορεί να προετοιμάσει επικοινωνίες βασισμένες σε κείμενο ως περιουσιακά στοιχεία EML για μετανάστευση ή επεξεργασία σε επόμενα στάδια.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}