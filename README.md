現在のUnityバージョン：`2021.3.12f1`  
10月27日に更新

## 紅霧の森プロジェクトのドキュメント

目次：

- ### [制作状況](#progress_memo)
- ### [ガイドライン](#guidline)  
- ### [制作ガイド](#guid)
- ### [参加手順](#guid2proj)

<br>
<br>

---

# <a name="progress_memo">制作状況</a>

## 今間違いなくできること

Unityを使わない制作  
> 例： ストーリー, BGM  
<br>

アセット探し
> 例： SE, BGM, 3Dモデル, テクスチャ  
> Unityアセットストアなどで フリーアセット/素材 を探索  
<br>

ステージ制作  
> Gitで競合しないように、自分一人が作業するシーン内でステージを作る形が良さそう。  
> 複数人で同じステージを作る場合はプレファブを使って、自分のプレファブ内のみを編集することで、シーンでの競合を減らせると良さそう。  
<br>

中村に、ほしいゲーム要素を頼む
> プログラミングして動かす時間を確保するためにできるだけ早めにお願いします。  
>> 例：  
>> 1. このような(**動画リンク**)テンキーパスワード式の鍵ギミックがあると良いと思うのですが、作れそうですか？  
>> 1. こんな感じの(**複数の画像リンク**)グラフィックを今作ってるステージで使いたいんだけど作れる？
>> 1. ~~進捗どうですか？~~
<br>
<br>

---

# <a name="guidline">ガイドライン</a>


<br>

## 競合の回避  

基本的には自分のフォルダの中にあるものだけを変更しましょう。

<br>

## Gitのブランチ機能で自分だけのスペースを確保する  

ブランチ機能を使って、他の人の作業内容と競合しない様に整えましょう。  
現在、以下のブランチがこのGitHubリポジトリに用意されています  
- ~~main~~ (基本的にはいじらない。チームで安定稼働するものを共有するためのブランチ)
- Kawaguchi  
- Nakajima  
- Nakamura  
- Noguchi  
- Hattori

[SourceTreeで自分のブランチを作る方法](#branchguid)

<br>
<br>

---  

# <a name="guid">制作ガイド</a>

## GitIgnore  

フォルダ構成に依存しないものを、コミットに載せない方法：  
- `_gitignore` または `_giti` と命名したフォルダの中に、ファイルを入れる

<br>
<br>

---  

# <a name="guid2proj">参加手順</a>

## クローン  

リポジトリに移動  
https://github.com/e-mau/Akagiri_no_mori01

<br>

GitリポジトリのURLをコピー  
<img src="https://user-images.githubusercontent.com/45002974/196025857-d5c84b5a-6269-4184-94eb-1ea39ddf3d19.png" width="60%">

<br>

**SourceTreeを起動する**

<br>

**`+`** ボタンを押す  
<img src="https://user-images.githubusercontent.com/45002974/196026293-cda2a3d4-0fc7-4086-be0c-c38f180886d0.png" width="40%">

<br>

`Clone` を押す  
<img src="https://user-images.githubusercontent.com/45002974/196026309-bc56deed-59cc-4d68-be99-271d2763f64c.png" width="40%">

<br>

先程コピーしたURLを貼り付ける  
`クローン` ボタンを押す  
<img src="https://user-images.githubusercontent.com/45002974/196026363-368f2d15-4318-47fb-b7df-8e76b2c0574e.png" width="40%">

<br>

## Unityでプロジェクトを開く  

**Unity Hubを起動する**

### Editorのバージョンを揃える

<br>

`Installs` を押す  
<img src="https://user-images.githubusercontent.com/45002974/196027038-8a76be2c-3395-4b66-a0c4-20477e250a58.png" width="20%">

<br>

`Install Editor` を押す  
<img src="https://user-images.githubusercontent.com/45002974/196027167-4e3830a7-4d03-4735-9be1-fb7740008edd.png" width="40%">

<br>

最新のLTSのバージョンを確認して、もしインストールされていなかったら`Install`ボタンを押してインストールする  
※ 指定するバージョンが最新のバージョンではない場合があります。その場合は別途指示に従ってください。  
<img src="https://user-images.githubusercontent.com/45002974/196027246-3f0ec735-acd2-443a-9720-59c82366968c.png" width="40%">

<br>

`Projects`に戻り、`Open`からGitでクローンした先のフォルダを開く  
<img src="https://user-images.githubusercontent.com/45002974/196027399-1b191c16-e25e-4cc2-a068-7ecb2d789b0b.png" width="40%">

<br>

## <a name="branchguid"> SourceTreeで自分のブランチを作る </a>  

`ブランチ`ボタンを押す  
<img src="https://user-images.githubusercontent.com/45002974/197389538-c7cdcfc0-d3b6-4deb-9746-10be1e189459.png" width="40%">

<br>

自分の苗字をローマ字で入力  
例：`Toyotomi`  
`ブランチを作成`を押す  
<img src="https://user-images.githubusercontent.com/45002974/197389692-f36f0e9c-fbbb-4a0f-a8f3-8eae603a70a2.png" width="40%">

<br>

コミット時は自分が編集した自分のファイルのみ（基本的には）をコミット  
コミットする前にしっかり確認  
<img src="https://user-images.githubusercontent.com/45002974/197389775-ef8bfc42-26aa-4895-aaea-84c475ee0f10.png" width="40%">

<br>

コミットしたら、先程のコミットが自分のブランチになっているか確認して大丈夫そうなら  
`プッシュ`ボタンを押す  
<img src="https://user-images.githubusercontent.com/45002974/197389858-a327125f-527e-4bce-bdab-14837117a51a.png" width="40%">

<br>

最後にプッシュする先のリモートブランチ（GitHub上のブランチ）を`main`ではなく先程設定した自分の苗字のブランチに変更する  
`main`から☑が外れ、自分の苗字ブランチになっていることをしっかり確認したら、`プッシュ`ボタンからプッシュする  
<img src="https://user-images.githubusercontent.com/45002974/197389943-3472c6a8-6985-4e6a-a6f4-59b779f77a65.png" width="40%">

