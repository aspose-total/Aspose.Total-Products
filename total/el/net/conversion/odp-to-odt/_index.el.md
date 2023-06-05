---
title: Μετατροπή ODP σε ODT μέσω C# .NET ή με δωρεάν Online Converter
description: Μετατρέψτε έγγραφα odp του PowerPoint σε αρχεία εγγράφων του Word με C#. Μετατροπή πολλαπλών αρχείων εντός του ASP.NET ή άλλων εφαρμογών .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή ODP σε ODT χρησιμοποιώντας C# ή διαδικτυακά" h2="Δημιουργήστε εφαρμογές μετατροπής εγγράφων Microsoft PowerPoint ODP σε Word ODT σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το ODP σε ODT χρησιμοποιώντας C#" %}}

Για να αυτοματοποιήσουμε τη διαδικασία για οποιαδήποτε παρουσίαση PowerPoint odp σε μαζική μετατροπή αρχείων εγγράφων του Word, θα χρησιμοποιήσουμε τα [Aspose.Slides for .NET](https://products.aspose.com/slides/net) και [Aspose.Words για .NET](https://products.aspose.com/words/net) API. Το πρώτο είναι ένα API χειρισμού παρουσίασης PowerPoint που σας επιτρέπει να δημιουργείτε ή να τροποποιείτε διαφάνειες του Microsoft PowerPoint. Ενώ, το τελευταίο είναι ένα API επεξεργασίας κειμένου για επεξεργασία ή χειρισμό εγγράφων του Microsoft Word. Και τα δύο API αποτελούν μέρος του πακέτου [Aspose.Total for .NET](https://products.aspose.com/total/net). Μπορείτε να κάνετε απευθείας [λήψη](https://releases.aspose.com/) από το Nuget ή μπορείτε να χρησιμοποιήσετε τις ακόλουθες εντολές από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή του ODP σε ODT μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Προσθέστε αναφορά του Aspose.Slides για .NET και Aspose.Words για .NET
1. Φορτώστε την παρουσίαση ODP του PowerPoint χρησιμοποιώντας την τάξη [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Αποθηκεύστε το έγγραφο στο [MemoryStream](https://odts.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Αντικείμενο
1. Δημιουργήστε το [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) και αρχικοποιήστε το με το MemoryStream Object
1. Αποθηκεύστε το έγγραφο χρησιμοποιώντας το [Aspose.Words.Document.Save("output.odt", SaveFormat.Odt)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.
- Aspose.Slides για .NET και Aspose.Words για .NET DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει πώς να μετατρέψετε ένα ODP σε ODT χρησιμοποιώντας C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint ODP file
Aspose.Slides.Presentation odp = new Aspose.Slides.Presentation("source.odp");

var stream = new MemoryStream();

odp.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var odt = new Aspose.Words.Document(stream);
      
// Save the Word ODT document
odt.Save("output.odt", Aspose.Words.SaveFormat.Odt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Διαδικτυακός μετατροπέας για ODP σε ODT</h3>

<iframe title="Εργαλείο μετατροπής odt σε odp" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odt&from=odp" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή ODP σε ODT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant ODP file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Συχνές Ερωτήσεις</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πώς μπορώ να μετατρέψω ODP σε ODT Online;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Η διαδικτυακή εφαρμογή για μετατροπή ODP είναι ενσωματωμένη παραπάνω. Για να χρησιμοποιήσετε την εφαρμογή, μπορείτε να προσθέσετε το αρχείο ODP είτε σύροντάς το και αποθέτοντάς το στην καθορισμένη περιοχή είτε κάνοντας κλικ μέσα στην περιοχή για να εισαγάγετε το αρχείο. Μόλις προστεθεί το αρχείο, κάντε κλικ στο κουμπί Μετατροπή για να ξεκινήσει η διαδικασία μετατροπής. Αφού ολοκληρωθεί η μετατροπή ODP σε ODT, μπορείτε να κάνετε λήψη του αρχείου που μετατράπηκε πρόσφατα με ένα μόνο κλικ και θα είναι διαθέσιμο σε μορφή ODT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πόσος χρόνος χρειάζεται για τη μετατροπή ODP;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">αυτός ο διαδικτυακός μετατροπέας είναι γρήγορος, αλλά η ταχύτητα της μετατροπής ODP σε ODT εξαρτάται κυρίως από το μέγεθος του αρχείου ODP που μετατρέπεται. Τα μικρότερα αρχεία ODP μπορούν να αποδοθούν σε μορφή ODT μέσα σε λίγα δευτερόλεπτα. Επιπλέον, εάν έχετε ενσωματώσει τον κώδικα μετατροπής ODP σε ODT σε μια εφαρμογή .NET, η ταχύτητα μετατροπής θα εξαρτηθεί από το πόσο καλά έχετε βελτιστοποιήσει την εφαρμογή σας για τη διαδικασία μετατροπής.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλής η μετατροπή ODP σε ODT χρησιμοποιώντας τον δωρεάν μετατροπέα Aspose.Total;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Φυσικά! Μόλις ολοκληρωθεί η διαδικασία μετατροπής ODP σε ODT, ο σύνδεσμος λήψης για το αρχείο ODT που έχει μετατραπεί θα είναι άμεσα διαθέσιμος. Όλα τα μεταφορτωμένα αρχεία, συμπεριλαμβανομένων των αρχείων ODP, διαγράφονται από το σύστημα μετά από 24 ώρες και οι σύνδεσμοι λήψης παύουν να λειτουργούν μετά από αυτήν τη χρονική περίοδο. Ο διαδικτυακός μετατροπέας διασφαλίζει την ασφάλεια και το απόρρητο των αρχείων σας και η ενσωματωμένη εφαρμογή διατίθεται δωρεάν για δοκιμαστικούς σκοπούς. Αυτό επιτρέπει στους χρήστες να ελέγχουν το αποτέλεσμα πριν ενσωματώσουν τον κώδικα στα έργα τους.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Τι πρόγραμμα περιήγησης πρέπει να χρησιμοποιήσω για τη μετατροπή ODP;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως το Google Chrome, το Firefox, το Opera ή το Safari για να μετατρέψετε αρχεία ODP σε ODT στο διαδίκτυο. Ωστόσο, εάν δημιουργείτε μια εφαρμογή για υπολογιστές, το Aspose.Total ODP Conversion API συνιστάται για μια ομαλή και απρόσκοπτη διαδικασία μετατροπής.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}