---
title: Convertir ODT en ODP via C# .NET ou avec le convertisseur en ligne gratuit
description: Convertissez des documents Word en fichiers PowerPoint odp avec C#. Convertissez plusieurs fichiers dans ASP.NET ou d'autres applications .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir ODT en ODP en utilisant C# ou en ligne" h2="Créez des applications de conversion Microsoft Word ODT vers PowerPoint ODP sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Comment convertir ODT en ODP en utilisant C#" %}}

Afin d'automatiser le processus pour tous les fichiers odt Word vers la conversion par lots de présentation PowerPoint odp, nous utiliserons [Aspose.Words pour .NET](https://products.aspose.com/words/net) et [Aspose.Slides pour les API .NET](https://products.aspose.com/slides/net). Le premier est une API de traitement de texte pour traiter ou manipuler des documents Microsoft Word. Alors que ce dernier est une API de manipulation de présentation qui vous permet de créer ou de modifier des diapositives Microsoft PowerPoint. Les deux API font partie du package [Aspose.Total pour .NET](https://products.aspose.com/total/net). Vous pouvez directement [télécharger](https://releases.aspose.com/) à partir de Nuget ou utiliser les commandes suivantes à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir ODT en ODP via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Ajouter la référence de Aspose.Total pour .NET
1. Chargez le fichier ODT à l'aide de la classe [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document)
1. Enregistrez le document ODT au format HTML
1. Créer un objet [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Importez du contenu HTML dans le cadre de texte de n'importe quelle forme de diapositive dans la présentation
1. Enregistrez le document en utilisant [Aspose.Slides.Presentation.Save("output.odp", SaveFormat.Odp)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
- Environnement de développement comme Microsoft Visual Studio.
- Aspose.Words pour .NET &amp; Aspose.Slides pour les DLL .NET ou Aspose.Total pour les DLL .NET référencées dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre comment convertir un ODT en ODP à l'aide de C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to ODP.

using (Presentation odp = new Presentation()){

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

	// Save the ODP Presentation
	odp.Save("filepath\\pres.odp", Aspose.Slides.Export.SaveFormat.Odp);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertisseur en ligne pour ODT en ODP</h3>

<iframe title="Outil en ligne de conversion odp en odt" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=odp&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour convertir ODT en ODP" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant ODP file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier ODT en ODP par programmation : cas d'utilisation" %}}
Les fichiers ODT (OpenDocument Text) sont utilisés pour stocker l'information de texte, les rendant idéaux pour créer des documents avec contenu structuré. Cependant, lorsqu'on travaille avec des éléments graphiques vectoriels et multimédias, les fichiers ODS (.ods) deviennent essentiels pour l'arrangement et la conception du document.

La conversion de fichiers ODT en formats ODS est nécessaire pour débloquer pleinement vos capacités de création de documents. Cette conversion vous permet :

**Cas d'utilisation :**

*   **Publication de Documents** : Convertir des fichiers ODT pour publier des documents dans divers formats, tels que PDF, EPUB et HTML.
*   **Collaboration et Revue** : Utiliser ODS pour collaborer avec les autres sur les documents, suivre les changements et réviser les étapes de manière plus efficace.
*   **Analyse de Données et Visualisation** : Convertir des fichiers ODT pour analyser les données, créer des graphiques et tableaux, et visualiser les résultats avec OpenOffice Calc (.ods).
*   **Présentations et Slideshows** : Utiliser ODS pour créer des présentations engageantes, des slideshows et des affiches avec des éléments multimédias et des graphiques vectoriels.
*   **Flexibilité de Format de Fichier** : Convertir des fichiers ODT en ODS pour une flexibilité accrue dans la formation de documents, l'arrangement et la conception.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Questions fréquemment posées</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Comment puis-je convertir ODT en ODP en ligne ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'application en ligne pour la conversion ODT est intégrée ci-dessus. Pour utiliser cette application, vous pouvez ajouter votre fichier ODT en le faisant glisser et en le déposant dans la zone blanche désignée ou en cliquant à l'intérieur de la zone pour importer le document. Ensuite, appuyez sur le bouton Convertir pour démarrer le processus de conversion. Une fois la conversion ODT en ODP terminée, vous pouvez télécharger votre fichier nouvellement converti en un seul clic, et il sera disponible sous la forme d'un fichier ODP.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Combien de temps faut-il pour convertir ODT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ce convertisseur en ligne fonctionne rapidement mais dépend principalement de la taille du fichier ODT à convertir. Pour les petits fichiers ODT, la conversion en ODP peut être effectuée en quelques secondes. Cependant, si vous avez intégré le code de conversion dans une application .NET, la vitesse de conversion dépendra de la qualité de l'optimisation de votre application pour le processus de conversion.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Est-il sûr de convertir ODT en ODP en utilisant le convertisseur gratuit Aspose.Total ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bien sûr! Une fois la conversion ODT en ODP terminée, le lien de téléchargement du fichier ODP nouvellement converti sera instantanément disponible. Cela garantit également la sécurité du processus de conversion, car tous les fichiers téléchargés, y compris les fichiers ODT, sont entièrement sécurisés et seront supprimés du système après 24 heures. De plus, les liens de téléchargement cesseront de fonctionner après cette période, garantissant la confidentialité et la protection de vos fichiers. L'application intégrée est gratuite et conçue à des fins de test afin que les utilisateurs puissent évaluer les résultats avant d'intégrer le code dans leurs projets.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quel navigateur dois-je utiliser pour convertir ODT ?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Vous pouvez utiliser n'importe quel navigateur Web moderne, tel que Google Chrome, Firefox, Opera ou Safari, pour la conversion ODT en ODP en ligne. Toutefois, si vous développez une application de bureau, l'API Aspose.Total ODT Conversion est recommandée pour un traitement fluide et efficace.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}