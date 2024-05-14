---
title: Távolítsa el a DOTX Annotation Online-t vagy kezelje a kommentárokat az Android mobilalkalmazások segítségével
description: ingyenesen törölje a megjegyzéseket a DOTX fájlból az online alkalmazáson keresztül.Android API kód a DOTX fájlok megjegyzéseinek kezeléséhez.

family: total
platformtag: Android
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Törölje a megjegyzéseket a DOTX Document Online alkalmazásból, vagy kezelje az Android-alkalmazásokon keresztül" h2="Hatékony Android alapú DOTX dokumentum annotációs segédprogram fejlesztése.A DOTX fájl megjegyzéseinek kezeléséhez felsorolt kód." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a DOTX megjegyzéseket online" %}}

1. Importáljon DOTX fájlt a megjegyzések feltöltésével való törléséhez
1. Ehhez kattintson a ledobási területen belülre a megjegyzés alkalmazás húzásával
1. A DOTX fájl méretétől és az internet sebességétől függően várjon néhány másodpercet
1. Kattintson az "Eltávolítás" gombra a megjegyzések törléséhez
1. Azonnal töltse le a fájlt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a DOTX-dokumentum megjegyzéseit az Android alkalmazáson keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. Dokumentum betöltése a Dokumentum osztály objektumon keresztül
1. A [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) és a NodeType.COMMENT használatával megkapja az összes csomópont összes megjegyzését
1. Hívja meg a [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) metódust az összes megjegyzés törléséhez
1. Hívja a mentési módot a fájl mentéséhez.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: Megjegyzések törlése a DOTX fájlból" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX megjegyzés eltávolítása és hozzáadása" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. Dokumentum betöltése a Dokumentum osztály objektumon keresztül
1. Megjegyzés kérése a getChild használatával
1. Használja a [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment)-et a megjegyzésre adott válasz eltávolításához
1. A [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) használatával válaszolhat erre a megjegyzésre
1. Hívja a mentési módot a fájl mentéséhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Megjegyzések hozzáadása Android alkalmazáson keresztül" %}}

1. Könyvtári hivatkozás hozzáadása az Android projekthez
1. Dokumentum osztály objektum létrehozása
1. A megjegyzés létrehozásához használja a [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)-ot
1. Használja a getParagraphs().add és getFirstParagraph().getRuns().add
1. Hívja a mentési módot a fájl mentéséhez with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Kód: Távolítsa el és adjon hozzá megjegyzést a DOTX fájlhoz" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Kód: Megjegyzések hozzáadása" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>DOTX Document Annotation Android alkalmazás fejlesztése</h2>

DOTX annotációs mobilalkalmazást vagy segédprogramot szeretne fejleszteni, hogy visszajelzést adjon, javaslatokat tegyen, vagy együttműködjön másokkal a dokumentummal kapcsolatban?A [Aspose.Words for Android via Java](https://products.aspose.com/words/hu/android-java/)-tal, amely a [Aspose.Total for Android via Java](https://products.aspose.com/total/hu/android-java/) gyermek API-ja, bármely androidos fejlesztő integrálhatja a fenti API-kódot dokumentumannotáló alkalmazásába.A nagy teljesítményű android könyvtár lehetővé teszi bármilyen dokumentum-annotációs megoldás programozását.Ezenkívül számos népszerű formátumot támogat, beleértve a DOTX formátumot.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android Library a DOTX fájlok megjegyzéseivel" %}}

- Java csomagjainkat [Maven adattárak](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)-ben tároljuk. 
- A Aspose.Words for Java egy gyakori JAR-fájl, amely bájtkódot tartalmaz.
- Kövesse a [lépésről lépésre utasításokat](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/)-t a Aspose.Words for Android via Java telepítéséhez.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

- A Java SE 7 és újabb Java verziók támogatottak.
- Külön csomag a Java SE 6-hoz arra az esetre, ha valaki köteles elavult JRE-t használni.
- A Java csomag többplatformos, és minden JVM implementációval rendelkező operációs rendszeren fut.
- Az operációs rendszerek közé tartozik a Microsoft Windows, Linux, macOS, Android és iOS.

<br />
Az opcionális csomagfüggőségekről, például a JogAmp JOGL-ről, a Harfbuzz font engine-ről, a Java Advanced Imaging JAI-ról további részletekért tekintse meg a [Termékdokumentáció](https://docs.aspose.com/words/java/system-requirements/)-at.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}