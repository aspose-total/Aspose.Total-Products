---
title: Java API για εξαγωγή CGM σε DOTM
description: Μετατρέψτε το CGM σε DOTM χρησιμοποιώντας το Java API premise
url_ignore: /el/java/conversion/cgm-to-dotm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTM
otherformats: OTT MHTML MARKDOWN PCL WORDML DOTM XAMLFLOW ODT DOTX DOT RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατρέψτε το CGM σε DOTM μέσω Java" h2="On Premise Java API για απόδοση CGM σε DOTM χωρίς χρήση εφαρμογής τρίτων" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το CGM σε DOTM χρησιμοποιώντας δύο απλά βήματα. Πρώτα πρέπει να αποδώσετε το αρχείο CGM στο DOC χρησιμοποιώντας το [Aspose.PDF για Java](https://products.aspose.com/pdf/java/). Μετά από αυτό, χρησιμοποιώντας το ισχυρό API Επεξεργασίας Εγγράφων [Aspose.Words για Java](https://products.aspose.com/words/java/), μπορείτε να μετατρέψετε το DOC σε DOTM. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API για μετατροπή CGM σε DOTM" %}}
1. Ανοίξτε το αρχείο CGM χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Μετατρέψτε το CGM σε DOC χρησιμοποιώντας το [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) μέθοδος
3. Φορτώστε το αρχείο DOC χρησιμοποιώντας την κατηγορία [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) του Aspose.Words
4. Αποθηκεύστε το έγγραφο σε μορφή DOTM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) και ορίστε το DOTM ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://releases.aspose.com/total/java/) και περιλαμβάνουν τα [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/) και [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "cgm-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Κατά τη μετατροπή του CGM σε DOTM, ακόμα κι αν το έγγραφό σας προστατεύεται με κωδικό πρόσβασης, μπορείτε να το ανοίξετε χρησιμοποιώντας το API χειρισμού PDF [Aspose.PDF για Java](https://docs.aspose.com/pdf/java/installation/). Για να ανοίξετε το κρυπτογραφημένο αρχείο, πρέπει να δημιουργήσετε ένα αντικείμενο [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) και να ανοίξετε το CGM χρησιμοποιώντας τον κωδικό πρόσβασης κατόχου.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ανοίξτε το έγγραφο CGM που προστατεύεται με κωδικό πρόσβασης μέσω Java" %}}
Κατά την αποθήκευση του εγγράφου εισόδου σας σε μορφή αρχείου DOTM, μπορείτε επίσης να αποθηκεύσετε το έγγραφό σας σε βάση δεδομένων αντί για σύστημα αρχείων. Ίσως χρειαστεί να εφαρμόσετε την αποθήκευση και την ανάκτηση αντικειμένων εγγράφου προς και από μια βάση δεδομένων. Αυτό θα ήταν απαραίτητο εάν εφαρμόζατε οποιοδήποτε τύπο συστήματος διαχείρισης περιεχομένου. Για να αποθηκεύσετε το DOTM σας στη βάση δεδομένων, είναι συχνά απαραίτητο να σειριοποιήσετε το έγγραφο για να αποκτήσετε έναν πίνακα byte. Αυτό μπορεί να γίνει χρησιμοποιώντας το [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Αφού λάβετε τον πίνακα byte, μπορείτε να τον αποθηκεύσετε στη βάση δεδομένων χρησιμοποιώντας την εντολή SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}