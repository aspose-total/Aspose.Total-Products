---
title: सी ++ के माध्यम से दस्तावेज़ रूपांतरण 
url: /hi/cpp/conversion/
description: C++ API का उपयोग करके विभिन्न दस्तावेज़ स्वरूपों जैसे Word, Excel, PowerPoint, PDF, JSON, छवियों और अधिक को कनवर्ट करें। 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ . का उपयोग कर दस्तावेज़ रूपांतरण" h2="Microsoft<sup>&reg;</sup> ऑफिस वर्ड, एक्सेल, पॉवरपॉइंट, पीडीएफ, इमेज और कई अन्य फॉर्मेट को C++ लाइब्रेरी का उपयोग करके कन्वर्ट करें।" >}}

{{% blocks/products/pf/feature-page-summary %}}
[कुल सी++ लाइब्रेरी](https://products.aspose.com/total/cpp/) दस्तावेज़ रूपांतरण के मुद्दे को हल करता है और डेवलपर्स नए विकसित अनुप्रयोगों या मौजूदा अनुप्रयोगों में एपीआई को एकीकृत करके दस्तावेज़ प्रबंधन और हेरफेर समाधान को आसानी से स्वचालित कर सकते हैं। सी ++ प्रोग्रामर किसी भी सॉफ्टवेयर पर भरोसा किए बिना अपने समाधान के भीतर विभिन्न प्रारूप दस्तावेजों को बनाने, संपादित करने या परिवर्तित करने जैसी कार्यक्षमताओं को जोड़ सकते हैं। कुछ सामान्य मामले जैसे txt to PDF, SVG to PNG, XLSX to CSV, JSON to CSV, Word to PDF, HTML to PDF, कोई भी आसानी से कनवर्ट कर सकता है। इसके अलावा, कुछ मामले जो एपीआई नीचे सूचीबद्ध हैं और प्रासंगिक रूपांतरण मामलों के लिए कुछ लिंक दिए गए हैं। 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="माइक्रोसॉफ्ट वर्ड को एक्सेल में बदलें" %}}
कुल C++ API Microsoft Word DOC/DOCX से Excel रूपांतरण का समर्थन करता है।  प्रक्रिया है, [दस्तावेज़](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग संदर्भ का उपयोग करके Word DOC / DOCX फ़ाइल लोड करें और [सहेजें](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) मेंबर फंक्शन सबसे पहले HTML में कन्वर्ट करने के लिए। फिर [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) क्लास रेफरेंस का उपयोग करके HTML दस्तावेज़ लोड करें और [Save](https://reference.aspose.com/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) को इनवाइट करें। सेल्स/सीपीपी/क्लास मेंबर फंक्शन दस्तावेज़ को एक्सेल फॉर्मेट में सेव करने के लिए। 

{{% blocks/products/pf/feature-page-code h3="सी++ - वर्ड टू एक्सेल रूपांतरण" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="पीडीएफ से वर्ड रूपांतरण" %}}
C++ कनवर्ज़न लाइब्रेरी PDF से वर्ड DOC, DOCX और अन्य प्रारूप रूपांतरण का भी समर्थन करती है। पीडीएफ को आरटीएफ में प्रस्तुत करने के मामले को ध्यान में रखते हुए, यह दो चरणों वाली प्रक्रिया है, पहले पीडीएफ को वर्ड डीओसी/डीओसीएक्स प्रारूप में कनवर्ट करें और फिर इसे आरटीएफ में प्रस्तुत करें। इसके लिए चरण शामिल हैं, [दस्तावेज़](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके पीडीएफ फाइल लोड करना और [सहेजें](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) का आह्वान करना पीडीएफ को वर्ड में बदलने के लिए  मेंबर फंक्शन। अब Aspose.Words API के [दस्तावेज़](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग संदर्भ का उपयोग करके Word DOC / DOCX फ़ाइल को फिर से लोड करें और इसे RTF प्रारूप में उपयोग करके सहेजें [सहेजें](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) सदस्य समारोह।

{{% blocks/products/pf/feature-page-code h3="C++ - पीडीएफ से वर्ड रूपांतरण" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="JSON को वर्ड में बदलें" %}}
JSON रूपांतरण के लिए, C++ API विभिन्न संयोजनों का समर्थन करता है जैसे JSON से Word, Json से PowerPoint, Word से JSON आदि। शब्द रूपांतरण के मामले को ध्यान में रखते हुए, प्रक्रिया है, एक नई [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ऑब्जेक्ट का उपयोग करके फ़ाइल से मान्य JSON डेटा पढ़ें और फिर इनवोक करें [सेव करें](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) JSON को पीडीएफ फाइल के रूप में सेव करने की विधि। तो अब [दस्तावेज़](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग का उपयोग करके सहेजी गई फ़ाइल को लोड करें और [सहेजें](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) का उपयोग करके इसे शब्द दस्तावेज़ प्रारूप में सहेजें  विधि।
{{% blocks/products/pf/feature-page-code h3="सी ++ - जेएसओएन से वर्ड रूपांतरण" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}