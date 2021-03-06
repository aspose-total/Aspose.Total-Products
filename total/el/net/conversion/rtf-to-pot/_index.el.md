---
title: Μετατροπή RTF σε POT μέσω C# .NET 
url: /el/net/conversion/rtf-to-pot/ 
description: Μετατρέψτε έγγραφα Word rtf σε αρχεία pot PowerPoint με C#. Μετατροπή πολλαπλών αρχείων εντός του ASP.NET ή άλλων εφαρμογών .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή RTF σε POT χρησιμοποιώντας C#" h2="Δημιουργήστε εφαρμογές μετατροπής Microsoft Word RTF σε PowerPoint POT σε πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" rtfsLink="https://rtfs.aspose.com/total/net" installationsRtfsLink="https://rtfs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://rtfs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το RTF σε POT χρησιμοποιώντας C#" %}}

Για να αυτοματοποιήσουμε τη διαδικασία για οποιαδήποτε αρχεία εγγράφων του Word σε μαζική μετατροπή παρουσιάσεων pot PowerPoint , θα χρησιμοποιήσουμε τα [Aspose.Words for .NET](https://products.aspose.com/words/net) και [Aspose.Slides για .NET](https://products.aspose.com/slides/net) API. Το πρώτο είναι ένα API επεξεργασίας κειμένου για επεξεργασία ή χειρισμό εγγράφων του Microsoft Word. Ενώ, το τελευταίο είναι ένα API χειρισμού παρουσίασης που σας επιτρέπει να δημιουργείτε ή να τροποποιείτε διαφάνειες του Microsoft PowerPoint. Και τα δύο API αποτελούν μέρος του πακέτου [Aspose.Total for .NET](https://products.aspose.com/total/net). Μπορείτε να κάνετε απευθείας [λήψη](https://downloads.aspose.com/) από το Nuget ή μπορείτε να χρησιμοποιήσετε τις ακόλουθες εντολές από την Κονσόλα του Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή RTF σε POT μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Προσθέστε αναφορά του Aspose.Total για .NET
1. Φορτώστε το αρχείο RTF χρησιμοποιώντας την κλάση [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Αποθηκεύστε το έγγραφο RTF σε HTML
1. Δημιουργήστε αντικείμενο [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Εισαγάγετε περιεχόμενο HTML σε πλαίσιο κειμένου οποιουδήποτε σχήματος διαφάνειας μέσα στην παρουσίαση
1. Αποθηκεύστε το έγγραφο χρησιμοποιώντας το [Aspose.Slides.Presentation.Save("output.pot", SaveFormat.Pot)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Windows Azure, Mono ή Xamarin.
- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio.
- Aspose.Words για .NET &amp; Aspose.Slides για .NET DLL ή Aspose.Total για .NET DLL που αναφέρονται στο έργο σας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αυτό το δείγμα κώδικα δείχνει πώς να μετατρέψετε ένα RTF σε POT χρησιμοποιώντας C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word RTF file
Aspose.Words.Document rtf = new Aspose.Words.Document("sourceWordFile.rtf");

// Save RTF file to HTML 
rtf.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages RTF documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POT.

using (Presentation pot = new Presentation()){

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

	// Save the POT Presentation
	pot.Save("filepath\\pres.pot", Aspose.Slides.Export.SaveFormat.Pot);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Δωρεάν εφαρμογή για μετατροπή RTF σε POT" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-ppt/" name="RTF Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-pptx/" name="RTF Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-pps/" name="RTF Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-pot/" name="RTF Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-ppsx/" name="RTF Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-pptm/" name="RTF Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-ppsm/" name="RTF Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-potx/" name="RTF Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-potm/" name="RTF Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/rtf-to-pot/" name="RTF Προς την POT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}