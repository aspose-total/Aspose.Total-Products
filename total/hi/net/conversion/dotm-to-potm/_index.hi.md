---
title: C# .NET . के माध्यम से DOTM को POTM में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: Word दस्तावेज़ दस्तावेज़ों को C# के साथ PowerPoint potm फ़ाइलों में कनवर्ट करें। ASP.NET या अन्य .NET अनुप्रयोगों में एकाधिक फ़ाइलों को कनवर्ट करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="सी # का उपयोग कर डीओसी को ओडीपी में कनवर्ट करें या ऑनलाइन" h2=".NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफॉर्म पर PowerPoint POTM रूपांतरण ऐप्स के लिए Microsoft Word DOTM बनाएँ।" logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="C# का उपयोग करके DOTM को POTM में कैसे बदलें" %}}

किसी भी Word dotm फ़ाइल की प्रक्रिया को PowerPoint potm प्रस्तुति बैच रूपांतरण में स्वचालित करने के लिए, हम [Aspose.Words for .NET](https://products.aspose.com/words/net) और [Aspose.Slides का उपयोग करेंगे .NET](https://products.aspose.com/slides/net) API के लिए। पूर्व Microsoft Word दस्तावेज़ों को संसाधित करने या उनमें हेरफेर करने के लिए एक वर्ड प्रोसेसिंग API है। जबकि, बाद वाला एक प्रेजेंटेशन मैनिपुलेशन एपीआई है जो आपको माइक्रोसॉफ्ट पावरपॉइंट स्लाइड्स बनाने या संशोधित करने देता है। दोनों एपीआई [Aspose.Total for .NET](https://products.aspose.com/total/net) पैकेज का हिस्सा हैं। आप Nuget से सीधे [डाउनलोड](https://releases.aspose.com/) कर सकते हैं या पैकेज मैनेजर कंसोल से निम्न कमांड का उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="DOTM को C# के माध्यम से POTM में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose का संदर्भ जोड़ें। .NET के लिए कुल
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके DOTM फ़ाइल लोड करें
1. DOTM दस्तावेज़ को HTML में सहेजें
1. बनाएं [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) ऑब्जेक्ट
1. प्रस्तुति के अंदर किसी भी स्लाइड आकार के टेक्स्ट फ्रेम में HTML सामग्री आयात करें
1. दस्तावेज़ को [Aspose.Slides.Presentation.Save("output.potm", SaveFormat.Potm)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods) का उपयोग करके सेव करें। /5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Windows Azure, Mono या Xamarin Platforms के साथ संगत OS।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल।
- Aspose.Words for .NET &amp; Aspose.Slides for .NET DLL या Aspose.Total for .NET DLL आपके प्रोजेक्ट में संदर्भित।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह कोड नमूना दिखाता है कि सी # का उपयोग करके एक डीओसी को ओडीपी में कैसे परिवर्तित किया जाए" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word DOTM file
Aspose.Words.Document dotm = new Aspose.Words.Document("sourceWordFile.dotm");

// Save DOTM file to HTML 
dotm.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages DOTM documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to POTM.

using (Presentation potm = new Presentation()){

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

	// Save the POTM Presentation
	potm.Save("filepath\\pres.potm", Aspose.Slides.Export.SaveFormat.Potm);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>बीएमपी से जीआईएफ के लिए ऑनलाइन कन्वर्टर</h3>

<iframe title="potm से dotm रूपांतरण ऑनलाइन टूल" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potm&from=dotm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DOTM को POTM में बदलने के लिए फ्री ऐप" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOTM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
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
              <h2>अक्सर पूछे जाने वाले प्रश्नों</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>मैं बीएमपी को जीआईएफ में ऑनलाइन कैसे बदल सकता हूं?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बीएमपी रूपांतरण के लिए ऑनलाइन ऐप ऊपर एकीकृत है। इस ऐप का उपयोग करने के लिए, आप अपनी बीएमपी फ़ाइल को निर्दिष्ट सफेद क्षेत्र में खींचकर और छोड़ कर या दस्तावेज़ आयात करने के लिए क्षेत्र के अंदर क्लिक करके जोड़ सकते हैं। अगला, रूपांतरण प्रक्रिया शुरू करने के लिए कन्वर्ट बटन दबाएं। DOTM से POTM रूपांतरण पूरा होने के बाद, आप अपनी नई परिवर्तित फ़ाइल को केवल एक क्लिक से डाउनलोड कर सकते हैं, और यह आपके लिए POTM फ़ाइल के रूप में उपलब्ध होगी।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी को बदलने में कितना समय लगता है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">यह ऑनलाइन कन्वर्टर तेजी से काम करता है लेकिन मुख्य रूप से परिवर्तित की जा रही बीएमपी फाइल के आकार पर निर्भर करता है। छोटी बीएमपी फाइलों के लिए, जीआईएफ में रूपांतरण कुछ ही सेकंड में पूरा किया जा सकता है। हालाँकि, यदि आपने रूपांतरण कोड को .NET एप्लिकेशन के भीतर एकीकृत किया है, तो रूपांतरण की गति इस बात पर निर्भर करेगी कि आपका एप्लिकेशन रूपांतरण प्रक्रिया के लिए कितनी अच्छी तरह अनुकूलित किया गया है।</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>क्या मुक्त Aspose.Total कन्वर्टर का उपयोग करके DOTM को POTM में बदलना सुरक्षित है?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">बिल्कुल! एक बार DOTM से POTM रूपांतरण पूरा हो जाने पर, नई परिवर्तित POTM फ़ाइल के लिए डाउनलोड लिंक तुरंत उपलब्ध हो जाएगा। यह रूपांतरण प्रक्रिया की सुरक्षा का भी आश्वासन देता है, क्योंकि बीएमपी फाइलों सहित सभी अपलोड की गई फाइलें पूरी तरह से सुरक्षित हैं और 24 घंटे के बाद सिस्टम से हटा दी जाएंगी। इसके अलावा, डाउनलोड लिंक इस अवधि के बाद काम करना बंद कर देंगे, जिससे आपकी फाइलों की गोपनीयता और सुरक्षा सुनिश्चित होगी। एकीकृत ऐप उपयोग करने के लिए स्वतंत्र है और परीक्षण उद्देश्यों के लिए डिज़ाइन किया गया है ताकि उपयोगकर्ता अपनी परियोजनाओं में कोड को एकीकृत करने से पहले परिणामों का मूल्यांकन कर सकें।</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>बीएमपी कन्वर्ट करने के लिए मुझे किस ब्राउजर का इस्तेमाल करना चाहिए?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">ऑनलाइन DOTM से POTM रूपांतरण के लिए आप किसी भी आधुनिक वेब ब्राउज़र, जैसे Google Chrome, Firefox, Opera, या Safari का उपयोग कर सकते हैं। हालाँकि, यदि आप एक डेस्कटॉप एप्लिकेशन विकसित कर रहे हैं, तो सुचारू और कुशल प्रसंस्करण के लिए Aspose.Total DOTM रूपांतरण API की अनुशंसा की जाती है।</span>
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