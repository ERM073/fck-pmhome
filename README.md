# fck-pmhome ⚠公開後1週間ですぐに対策がされたためもう使用できません。
## 私の知る合法的な抜け道はまだありますが、様々な観点からリスクが高い為アップデートは今後行いません。

# 👻index.m3u8を公開しました！

私が隠し持ってるPrimeのm3u8リストを公開します。

このm3u8プレイリストはIPアドレスと再生する環境(プレイヤー)に依存します。日本のVPNに接続してVLCで再生してください。

PrimeHomeなので544pで画質は悪いです。<br>

BSやCSのプレイリストが欲しい人は私から購入するか、私が公開しているTVBox(無料)を使用してください。

https://github.com/ERM073/TVBox
<br><br><br><br><br><br>

<s> 唐突にサーバーを規制した日本向けのIPTV PMHを強制的に復活させて使用する抜け道を見つけました。

ソースコードを公開すると対策される可能性があるのでexe形式と難読化したpythonスクリプトのみを配布します。

見れるチャンネルはあなたの環境によって大きく異なりますが、4~6割程度のチャンネルを復活させました。

つまりこのスクリプトを使っても、誰かの環境ではTokyoMXは視聴できるけど、あなたの環境ではTokyoMXが視聴できない可能性があります。

注意：※IPアドレスが代わると見れなくなります。その際は再度スクリプトを実行してプレイリストを再生成してください。

全部のprimehomeチャンネルが見える訳ではありませんがこのスクリプトを実行すれば限定されたチャンネルのみ復活します。

生成したindex.m3u8をVLCで読み込むだけです:)

### 使い方

Linux 
```bash
pip install requests beautifulsoup4
git clone https://github.com/ERM073/fck-pmhome/
cd fck-primehome
python3 fck.py
```



Windows

https://github.com/ERM073/fck-pmhome/releases/latest

からfck.exeをインストールして実行するだけ

index.m3u8が生成されるのでVLC等で読み込んで下さい。
