---
title: Python で WORDML を MBOX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORDML を MBOX に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORDML を MBOX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORDML から MBOX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORDML から MBOX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORDML ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、MBOX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORDML を MBOX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORDML ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORDML ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDMLが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORDML から MBOX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDMLをMBOXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-email/" name="WORDML に EMAIL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-msg/" name="WORDML に MSG" description="" >}},
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-pst/" name="WORDML に PST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-ost/" name="WORDML に OST" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-oft/" name="WORDML に OFT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-eml/" name="WORDML に EML" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-emlx/" name="WORDML に EMLX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-mbox/" name="WORDML に MBOX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-ics/" name="WORDML に ICS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/python-net/conversion/wordml-to-vcf/" name="WORDML に VCF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}