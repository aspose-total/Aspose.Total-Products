---
title: Python で ODT を EMAIL に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で ODT を EMAIL に保存します。

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して ODT を EMAIL に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで ODT から EMAIL への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に ODT から EMAIL への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に ODT ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EMAIL 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で ODT を EMAIL に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース ODT ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、ODT ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にODTが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- ODT から EMAIL への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでODTをEMAILに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

ODT から Email への変換は、文書コンテンツをメール送信可能な出力に変換し、レポート、通知、要約、または書式設定されたテキストをメッセージングワークフローで共有しやすくします。正式な文書を直接コミュニケーション用に再利用する必要がある場合に便利です。

Python API を使用すると、ODT から Email への変換を自動通知システム、承認フロー、文書駆動型コミュニケーションパイプラインに統合できます。静的ファイルを実行可能な送信コンテンツに変換することで効率が向上します。

{{% blocks/products/pf/agp/feature-section-col title="主なユースケース" %}}

* **文書ベースの通知**  
  書かれたコンテンツをメールに適したコミュニケーションに変換します。

* **レポート配布**  
  ソース文書から要約、更新、または告知を迅速に共有できるようにします。

* **ワークフローコミュニケーション**  
  承認、アラート、ステータスメッセージングのシナリオをサポートします。

* **コンテンツの再利用**  
  文書テキストを外部または内部の通信に再利用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **トリガーされたメール生成**  
  新しい文書が到着した際に、システムが ODT ファイルを自動的にメールコンテンツに変換できます。

* **承認ワークフローメッセージング**  
  Python の自動化により、文書の要約をレビュアーやステークホルダー向けのメッセージに変換できます。

* **大量アウトリーチの準備**  
  複数の文書をスケールで送信可能なメールコンテンツに変換できます。

* **イベント駆動型通知**  
  文書リポジトリの変更が自動変換と配信をトリガーできます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}