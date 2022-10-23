---
title: पायथन का उपयोग करके फ़ाइल बनाएं 
url: /hi/python-net/create/
description: Microsoft Office स्थापित किए बिना टेक्स्ट और Microsoft Word दस्तावेज़ बनाएँ 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन का उपयोग करके दस्तावेज़ बनाएं" h2="Microsoft Office<sup>&reg;</sup> को इंस्टाल किए बिना Python अनुप्रयोगों में टेक्स्ट और Microsoft Word DOCX, DOC फ़ाइलें बनाएँ।" >}}

{{% blocks/products/pf/feature-page-summary %}}
एप्लिकेशन प्रकृति के आधार पर डेटा संग्रहीत करना किसी भी सॉफ़्टवेयर एप्लिकेशन का मूल है। भंडारण स्थान डेटाबेस, एक्सएमएल, जेएसओएन, टेक्स्ट फाइलें, एक्सेल रिपोर्ट या माइक्रोसॉफ्ट वर्ड दस्तावेज़ हो सकता है। फ़ाइल I/O किसी भी भाषा का हिस्सा है और पायथन सहित अधिकांश भाषाएं टेक्स्ट फ़ाइलों में डेटा लिखने का समर्थन करती हैं। आइए पायथन भाषा पर विचार करें। पायथन का उपयोग करके मौजूदा पाठ फ़ाइलों को लिखना, यह इस कार्यों के लिए खुली, लिखने और बंद करने की विधि प्रदान करता है। सबसे पहले फ़ाइल को प्रासंगिक फ़ाइल पथ के साथ खोलें और तर्क के रूप में सुविधा संलग्न करें या लिखें। फिर फ़ाइल में आवश्यक टेक्स्ट लिखें और अंत में क्लोज़ () विधि का उपयोग करके फ़ाइल को बंद करें। 

पायथन का उपयोग करके माइक्रोसॉफ्ट वर्ड दस्तावेज़ बनाने के लिए, हम [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs पैकेज का उपयोग करते हैं जिसमें [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API इसके पैकेज के हिस्से के रूप में होता है। यह एपीआई इनवॉइस, रिपोर्ट और तकनीकी लेखों के लिए पूर्ण दस्तावेज़ स्वचालन समाधान प्रदान करता है। शब्द दस्तावेज़ निर्माण की प्रक्रिया नीचे सूचीबद्ध है।

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="पायथन का उपयोग करके टेक्स्ट फ़ाइल कैसे बनाएं" %}}

टेक्स्ट फ़ाइलों को बनाना और लिखना सरल है। पायथन तीन मापदंडों के साथ खुली () विधि प्रदान करता है और फ़ाइल पथ के साथ एक पैरामीटर का उपयोग करना होता है। तीन पैरामीटर "x", "a" और "w" हैं। "X" प्रदान करके, नई फ़ाइल बनाई जाएगी लेकिन फ़ाइल पहले से मौजूद होने की स्थिति में त्रुटि उत्पन्न करती है। "ए" प्रदान करके, यदि मौजूद नहीं है तो नई टेक्स्ट फ़ाइल बनाई जाएगी और यदि यह मौजूद है, तो अंत में सामग्री जोड़ दी जाएगी। और अंत में "w" प्रदान करते हुए, नया टेक्स्ट दस्तावेज़ बनाया जाएगा और नई सामग्री के साथ अधिलेखित कर दिया जाएगा यदि यह पहले से मौजूद है।

{{% blocks/products/pf/feature-page-code h3="पायथन - टेक्स्ट फाइल बनाएं" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="माइक्रोसॉफ्ट वर्ड दस्तावेज़ बनाएं" %}}

टोटल पायथन वर्ड एपीआई में माइक्रोसॉफ्ट वर्ड फाइलों के निर्माण, दस्तावेजों के भीतर छवियों और पाठ को सम्मिलित करने, फाइलों में टेबल और सूचियों को जोड़ने के साथ-साथ मौजूदा दस्तावेजों को आसानी से संशोधित करने सहित कई विशेषताएं हैं। Microsoft Word दस्तावेज़ प्रक्रिया बनाने के लिए, [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) और [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/) वर्गों का ऑब्जेक्ट बनाएँ। दस्तावेज़ के भीतर आवश्यक पाठ, अनुच्छेद, सूचियाँ और तालिकाएँ जोड़ें और अंत में इसे सहेजें।

{{% blocks/products/pf/feature-page-code h3="पायथन - माइक्रोसॉफ्ट वर्ड दस्तावेज़ बनाएं" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}