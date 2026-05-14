# CTF Tools

## Burp Suite

Burp Suiteは、Webアプリケーションの通信を解析するための代表的なツールである。  
ブラウザとWebサーバの間に入り、HTTPリクエストやレスポンスを確認・改変できる。

特に、

- パラメータの改ざん
- Cookieの確認
- ログイン処理の解析
- 脆弱性調査

などに利用される。

CTFのWeb問題では非常に使用頻度が高く、セキュリティ業界でも広く利用されている。

公式サイト：  
https://portswigger.net/burp

---

## Wireshark

Wiresharkは、ネットワーク通信を解析するためのパケットキャプチャツールである。

通信内容をリアルタイムで確認できるため、

- 通信プロトコルの解析
- 不審な通信の調査
- パケット内のflag探索

などに利用される。

Forensics分野では特に重要なツールであり、pcapファイルの解析問題でよく使用される。

公式サイト：  
https://www.wireshark.org/

---

## Nmap

Nmapは、ネットワーク上のホストやサービスを調査するためのツールである。

主に、

- ポートスキャン
- 稼働中サービスの確認
- OS推定
- ネットワーク調査

などを行うことができる。

CTFでは「まずNmapを実行する」と言われるほど基本的なツールである。

公式サイト：  
https://nmap.org/

---

## Ghidra

Ghidraは、NSAによって公開されたリバースエンジニアリングツールである。

実行ファイルを解析し、

- アセンブリコードの確認
- 関数の解析
- プログラムの動作理解

などを行うことができる。

Reverse Engineering分野で非常に重要なツールであり、無料で高機能な点が特徴である。

公式サイト：  
https://ghidra-sre.org/

---

## pwntools

pwntoolsは、PythonでExploitコードを作成するためのライブラリである。

主に、

- ソケット通信
- バイナリ攻撃
- ROPチェーン作成
- 自動化

などを簡単に記述できる。

Pwn問題では非常によく利用されている。

公式サイト：  
https://github.com/Gallopsled/pwntools

---

## CyberChef

CyberChefは、データ変換や暗号解析をGUI上で行えるツールである。

以下のような処理を簡単に試すことができる。

- Base64変換
- ROT13
- XOR解析
- ハッシュ変換

プログラミングを書かなくても操作できるため、初心者にも扱いやすい。

公式サイト：  
https://gchq.github.io/CyberChef/

---

## binwalk

binwalkは、ファイル内部のデータ構造を解析するツールである。

特に、

- ファームウェア解析
- 埋め込みデータ抽出
- 圧縮ファイルの発見

などに利用される。

ForensicsやReverse Engineering分野で活躍する。

公式サイト：  
https://github.com/ReFirmLabs/binwalk

---

## ExifTool

ExifToolは、画像やファイルに含まれるメタデータを解析するツールである。

例えば、

- 撮影日時
- GPS情報
- 使用機器情報

などを確認できる。

CTFでは画像ファイルの隠された情報を調査する際によく利用される。

公式サイト：  
https://exiftool.org/

---

## John the Ripper

John the Ripperは、パスワード解析ツールである。

ハッシュ化されたパスワードに対して、

- 辞書攻撃
- 総当たり攻撃

などを実行できる。

パスワード強度の検証にも利用される有名なツールである。

公式サイト：  
https://www.openwall.com/john/

---

## Hydra

Hydraは、ログイン認証に対する総当たりテストを行うツールである。

SSHやFTP、HTTPなど多くのプロトコルに対応しており、

- ログイン画面の解析
- 認証テスト
- パスワード検証

などに利用される。

CTFでは認証突破問題で使用されることが多い。

公式サイト：  
https://github.com/vanhauser-thc/thc-hydra
``
