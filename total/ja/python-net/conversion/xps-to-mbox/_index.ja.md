---
title: Python で XPS を MBOX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で XPS を MBOX に保存します。

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して XPS を MBOX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで XPS から MBOX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XPS から MBOX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に XPS ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、MBOX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XPS を MBOX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース XPS ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、XPS ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にXPSが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XPS から MBOX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでXPSをMBOXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した XPS から MBOX への変換により、固定レイアウト文書をメールメッセージのコレクションを保存するために使用されるメールボックスアーカイブ形式に変換できます。これは、文書コンテンツをメールボックスベースのストレージ構造に依存するアーカイブ、移行、または長期保持ワークフローに組み込む必要がある場合に有用です。

自動化駆動システムにおいて、XPS から MBOX への変換はスケーラブルなコンテンツ保存を支援し、アーカイブパッケージ化を簡素化し、文書レコードをメール中心のストレージおよびコンプライアンスプロセスと統合するのに役立ちます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **メールボックスアーカイブ作成**  
  XPS コンテンツを統合された保存および保持ワークフロー用の MBOX 互換構造に変換します。

* **文書ベースのレコード保持**  
  通信システムで管理しやすいメールボックスアーカイブ内に文書情報を保存するのに役立ちます。

* **移行準備**  
  プラットフォームの移行や統合のために、文書コンテンツをメールアーカイブ形式に変換することを支援します。

* **大量コンテンツのパッケージ化**  
  複数の文書由来レコードをアーカイブ準備ができたメールボックスコレクションに整理できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動化アーカイブパイプライン**  
  システムは、スケジュールされた保持またはバックアップ手順の一環として XPS ファイルを MBOX 出力に変換できます。

* **バッチレコード統合**  
  大量の文書レコードをプログラムでメールボックスアーカイブにパッケージ化し、効率的に処理できます。

* **コンプライアンスストレージワークフロー**  
  自動化プロセスは、ガバナンスレビューに適したアーカイブ形式で文書由来の通信を保存できます。

* **データ移行準備**  
  変換ルーチンは、他の環境へ転送する前に文書ソースからメールボックス互換の出力を準備できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}