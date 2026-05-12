---
title: Python で DOC を MBOX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で DOC を MBOX に保存します。

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して DOC を MBOX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで DOC から MBOX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に DOC から MBOX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に DOC ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、MBOX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で DOC を MBOX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース DOC ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、DOC ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にDOCが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- DOC から MBOX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでDOCをMBOXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

文書から MBOX への変換は、Word コンテンツをメールボックス互換のアーカイブ形式に変換し、メッセージ形式の出力をグループ化して保存または移行できるようにします。文書コンテンツを保存またはメールアーカイブワークフローで配信する必要がある場合に有用です。

Python API を使用すると、DOC から MBOX への変換を大規模なアーカイブ操作向けに自動化でき、再現性が向上し、メールボックスベースのコンテナで動作するシステムをサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主要な使用ケース" %}}

* **メールボックスアーカイブ作成**
  文書から派生したメッセージを MBOX に変換し、メール形式でのグループ保存を実現します。

* **移行準備**
  文書がメールアーカイブや転送ワークフローに組み込まれる必要がある場合に MBOX 出力を使用します。

* **コミュニケーション保存**
  変換された文書コンテンツを統合されたメールボックス対応形式で保存します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **アーカイブパッケージング自動化**
  コンプライアンスや移行のために、DOC コンテンツから MBOX 出力を自動的に生成します。

* **バッチメールコンテナ変換**
  複数の文書を最小限の手作業でメールボックスアーカイブに変換します。

* **ドキュメントからメールへのワークフローブリッジ**
  プログラムで文書ベースのコンテンツをメールアーカイブエコシステム向けに準備します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}