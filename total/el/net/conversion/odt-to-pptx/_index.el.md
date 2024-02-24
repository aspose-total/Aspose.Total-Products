---
title: Μετατροπή ODT σε PPTX μέσω C# .NET ή με δωρεάν Online Converter
description: Μετατρέψτε έγγραφα Word odt σε αρχεία pptx PowerPoint με C#. Μετατροπή πολλαπλών αρχείων εντός του ASP.NET ή άλλων εφαρμογών .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή ODT σε PPTX χρησιμοποιώντας C# ή διαδικτυακά" h2="Δημιουργήστε εφαρμογές μετατροπής Microsoft Word ODT σε PowerPoint PPTX σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το ODT σε PPTX χρησιμοποιώντας C#" %}}

Για να αυτοματοποιήσουμε τη διαδικασία για οποιαδήποτε αρχεία εγγράφων του Word σε μαζική μετατροπή παρουσιάσεων pptx PowerPoint, θα χρησιμοποιήσουμε τα [Aspose.Words for .NET](https://products.aspose.com/words/net) και [Aspose.Slides για .NET](https://products.aspose.com/slides/net) API. Το πρώτο είναι ένα API επεξεργασίας κειμένου για επεξεργασία ή χειρισμό εγγράφων του Microsoft Word. Ενώ, το τελευταίο είναι ένα API χειρισμού παρουσίασης που σας επιτρέπει να δημιουργείτε ή να τροποποιείτε διαφάνειες του Microsoft PowerPoint. Και τα δύο API αποτελούν μέρος του πακέτου [Aspose.Total for .NET](https://products.aspose.com/total/net). Μπορείτε να κάνετε απευθείας [λήψη](https://releases.aspose.com/) από το Nuget ή μπορείτε να χρησιμοποιήσετε τις ακόλουθες εντολές από την Κονσόλα του Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή ODT σε PPTX μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Προσθέστε αναφορά του Aspose.Total για .NET
1. Φορτώστε το αρχείο ODT χρησιμοποιώντας την κλάση [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Αποθηκεύστε το έγγραφο ODT σε HTML
1. Δημιουργήστε αντικείμενο [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Εισαγάγετε περιεχόμενο HTML σε πλαίσιο κειμένου οποιουδήποτε σχήματος διαφάνειας μέσα στην παρουσίαση
1. Αποθηκεύστε το έγγραφο χρησιμοποιώντας το [Aspose.Slides.Presentation.Save("output.pptx", SaveFormat.Pptx)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.
- Aspose.Words για .NET &amp; Aspose.Slides για .NET DLL ή Aspose.Total για .NET DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει πώς να μετατρέψετε ένα ODT σε PPTX χρησιμοποιώντας C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTX.

using (Presentation pptx = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPTX Presentation
	pptx.Save("filepath\\pres.pptx", Aspose.Slides.Export.SaveFormat.Pptx);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Διαδικτυακός μετατροπέας για ODT σε PPTX</h3>

<iframe title="Εργαλείο μετατροπής pptx σε odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή ODT σε PPTX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

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
                          <span itemprop="name"><b>Πώς μπορώ να μετατρέψω ODT σε PPTX Online;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Η διαδικτυακή εφαρμογή για μετατροπή ODT είναι ενσωματωμένη παραπάνω. Για να χρησιμοποιήσετε αυτήν την εφαρμογή, μπορείτε να προσθέσετε το αρχείο ODT σας σύροντας και αποθέτοντάς το στην καθορισμένη λευκή περιοχή ή κάνοντας κλικ μέσα στην περιοχή για να εισαγάγετε το έγγραφο. Στη συνέχεια, πατήστε το κουμπί Μετατροπή για να ξεκινήσει η διαδικασία μετατροπής. Αφού ολοκληρωθεί η μετατροπή ODT σε PPTX, μπορείτε να κάνετε λήψη του αρχείου που μετατράπηκε πρόσφατα με ένα μόνο κλικ και θα είναι διαθέσιμο σε εσάς με τη μορφή αρχείου PPTX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Πόσος χρόνος χρειάζεται για τη μετατροπή ODT;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Αυτός ο διαδικτυακός μετατροπέας λειτουργεί γρήγορα, αλλά εξαρτάται κυρίως από το μέγεθος του αρχείου ODT που μετατρέπεται. Για μικρά αρχεία ODT, η μετατροπή σε PPTX μπορεί να ολοκληρωθεί μέσα σε λίγα δευτερόλεπτα. Ωστόσο, εάν έχετε ενσωματώσει τον κώδικα μετατροπής σε μια εφαρμογή .NET, η ταχύτητα μετατροπής θα εξαρτηθεί από το πόσο καλά έχει βελτιστοποιηθεί η εφαρμογή σας για τη διαδικασία μετατροπής.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Είναι ασφαλής η μετατροπή ODT σε PPTX χρησιμοποιώντας τον δωρεάν μετατροπέα Aspose.Total;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Φυσικά! Μόλις ολοκληρωθεί η μετατροπή ODT σε PPTX, ο σύνδεσμος λήψης για το νέο αρχείο PPTX που μετατράπηκε θα είναι άμεσα διαθέσιμος. Διασφαλίζει επίσης την ασφάλεια της διαδικασίας μετατροπής, καθώς όλα τα μεταφορτωμένα αρχεία, συμπεριλαμβανομένων των αρχείων ODT, είναι απολύτως ασφαλή και θα διαγραφούν από το σύστημα μετά από 24 ώρες. Επιπλέον, οι σύνδεσμοι λήψης θα σταματήσουν να λειτουργούν μετά από αυτό το διάστημα, διασφαλίζοντας το απόρρητο και την προστασία των αρχείων σας. Η ενσωματωμένη εφαρμογή είναι δωρεάν για χρήση και έχει σχεδιαστεί για δοκιμαστικούς σκοπούς, έτσι ώστε οι χρήστες να μπορούν να αξιολογούν τα αποτελέσματα πριν ενσωματώσουν τον κώδικα στα έργα τους.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Τι πρόγραμμα περιήγησης πρέπει να χρησιμοποιήσω για τη μετατροπή ODT;</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Μπορείτε να χρησιμοποιήσετε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού, όπως Google Chrome, Firefox, Opera ή Safari, για τη διαδικτυακή μετατροπή ODT σε PPTX. Ωστόσο, εάν αναπτύσσετε μια εφαρμογή για υπολογιστές, το Aspose.Total ODT Conversion API συνιστάται για ομαλή και αποτελεσματική επεξεργασία.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}