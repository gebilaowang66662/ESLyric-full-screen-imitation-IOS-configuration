[简体中文](https://github.com/gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration/blob/main/README.zh-CN.md)
[繁体中文](https://github.com/gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration/blob/main/README.zh-TW.md)
[English](https://github.com/gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration/blob/main/README.md)
[日本語](https://github.com/gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration/blob/main/README.Japan.md)

------------------------------------------------------------------------------------------
# プレビュー
現在、5種類のインターフェース形式が提供されており、用途に応じて使用可能

Miniウィンドウ

Mini.xml

![GMY ~Z18$NGV7P7A_YP6Y{2](https://github.com/user-attachments/assets/e2a17b38-bbfc-478c-96a9-e1261d85a9ed)


下部バー

Bottom bar.xml

![1`${73~KE0HOCIOGM(8JJZ5](https://github.com/user-attachments/assets/bac7df9f-62dc-4837-9379-89449125a565)


縦画面

Vertical .xml

![RXGVRX$N04SF8 HGJF BEN9](https://github.com/user-attachments/assets/d28d0016-8cc0-4f19-8663-8844e9f9d129)


横画面

Horizontal.xml

![2~U(PO)NSB462P2`U9O97RL](https://github.com/user-attachments/assets/780bcbab-5d38-4e3a-aeb7-263311df32af)

![77@JA$B}ZPE_65U7%Z{X4SO](https://github.com/user-attachments/assets/4de81bcf-3f7b-4598-8eef-34b0015e9232)

Horizontal 2.xml

![image](https://github.com/user-attachments/assets/37db2290-1de4-4f5c-a521-dfb0f2aa68af)

![image](https://github.com/user-attachments/assets/664fd3d0-ccb4-4f6c-8017-9215d4161cd6)


コンポーネントなし横画面縦画面（既存の下部バーと組み合わせて使用）

Horizontal and Vertical No control 

![QX}$YIGN(P%}YMYD V59L6J](https://github.com/user-attachments/assets/f4126f8b-a1cd-4bc5-b827-cde0dbec3109)

![D4{{7`$N7H8_3$_{)G8}T8O](https://github.com/user-attachments/assets/e97f11b9-ced3-48da-8ee8-d9f8d9bf94d0)

![3{ZLCK} O1Q537BGBL67`I5](https://github.com/user-attachments/assets/8e489964-702e-4f10-95e8-7df0926ba1f2)

![(G1IVDS}}8WXVHU )%SF1{W](https://github.com/user-attachments/assets/eac3cae9-8011-4fa6-839d-e2cb775a3b44)

------------------------------------------------------------------------------------------
# 0️⃣ layout設定ファイル 🤓

⚙ESLyricカスタムインターフェースAPI解説参考⚙

🔗[https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80](https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80)

------------------------------------------------------------------------------------------

# 1️⃣ ダウンロード 🧐

新しいESLyricプラグインを使用する💖  

作者GitHubプロジェクトで更新がないかチェック可能：

🔗https://github.com/ESLyric/release/releases

![U{E( 4QB ZQ4IICLV7T~PGJ](https://github.com/user-attachments/assets/f053a7e9-7482-49d0-822d-5f3dc1ffdee9)
    
------------------------------------------------------------------------------------------

# 2️⃣ インストール 🤖

下図の通りプラグイン🔩をインストールしソフトを再起動🔄

![image](https://github.com/user-attachments/assets/0b41147a-ee0c-406f-b380-8d0dbd50ffdb)

インストール後プラグイン画面が表示されない場合❓

ビューで`クイック編集モード`をオンにする

![image](https://github.com/user-attachments/assets/bbd8b7ad-5ecd-4860-932e-9ad7085ddbd1)

右クリックして`ESLyric`を選択して置換

![image](https://github.com/user-attachments/assets/8fbecf24-14a2-4425-a4b8-f234597766f7)

出てきたら`クイック編集モード`をオフに戻す

![image](https://github.com/user-attachments/assets/0a9083a2-a7f9-4d9e-b1f0-d264791d28c0)

------------------------------------------------------------------------------------------

# 3️⃣ 設定 😴


完成イメージ🌌

![image](https://github.com/user-attachments/assets/5c3285d1-8e36-4a76-831f-855ce95f45d2)

レイアウトファイルlayoutを以下の場所にドラッグ🤏

    C:\Users\（各ユーザー名は異なります）\AppData\Roaming\foobar2000-v2\eslyric-data\layout

このパスは通常版のもの

![XSFP0UBQ0F$T3C9 QG0 7S](https://github.com/user-attachments/assets/3b0a4c34-7b94-46c7-90c4-e9440d872407)


見つからない場合はインストールフォルダ内に`profie`フォルダ📁がないか確認、ポータブル版の場合ここに

    eslyric-data\layout

がある

![image](https://github.com/user-attachments/assets/d019c3c7-d820-4559-9fa6-1e856e879e42)

その後フルスクリーンパネルのパラメータから適切なレイアウトを選択

画面右クリック🖱

![image](https://github.com/user-attachments/assets/e64b63ea-c67d-403c-a633-97273f3b69d5)

![image](https://github.com/user-attachments/assets/ac4a4fcb-39db-4ab1-a229-02f0116baec3)

下部の設定は個人の好みで調整可能。上図のような効果を出したい場合は同じように調整👣

各ユーザーのPCの画面サイズ🖥💻により数値は異なるため、自分で調整して似た感じにすればよい。🔧

外部と全画面インターフェースは別々の設定なのでまず`全画面モード`🔳へ

画面右クリック🖱

![image](https://github.com/user-attachments/assets/1dfecb88-ea89-4cbd-893b-867fde2baed0)

画面右クリック🖱

![image](https://github.com/user-attachments/assets/37808317-3ad7-47bd-afee-6d78ff4ba673)

![image](https://github.com/user-attachments/assets/f3a866a3-a022-4ec0-9c3c-01d7d6a0a2c7)

![image](https://github.com/user-attachments/assets/363827c5-974f-4c07-8f05-07f1a943ad6d)

![image](https://github.com/user-attachments/assets/00d4f32d-1e9d-4919-90ca-e15373076da6)

![image](https://github.com/user-attachments/assets/82de95fa-e019-4af8-93c0-0b77b67296e4)

![image](https://github.com/user-attachments/assets/687fac90-d661-483e-b50e-95cb4720c170)

![image](https://github.com/user-attachments/assets/09693ac2-c83e-499f-a49f-729c3d9e5cd9)

`ハイライト歌詞`がずれている場合は、ここで調整🔧

![image](https://github.com/user-attachments/assets/0fd13294-fa67-43b4-83dd-6e85af034ceb)

![image](https://github.com/user-attachments/assets/6b18e9d3-8962-4470-a886-90ed209c78f9)

`動的ぼかし`も試してみて🔮

![image](https://github.com/user-attachments/assets/c72f7dcc-eb40-49d4-b8e6-3e26e4f8cfb5)

Miniウィンドウ設定

ここからダウンロードが必要

https://github.com/ttsping/foo_flowin

![XE`~SCE(02JLVK B5BE0}{I](https://github.com/user-attachments/assets/afa464af-6dcb-4ea6-b5c1-5b19018a6722)

下部バーにMini切替スイッチあり

最初にここで新しいフローティングウィンドウを作成

![5JCVIQYSBN2($2A5JZD~A_X](https://github.com/user-attachments/assets/10b0ee3c-7c2e-4f77-94c4-ac4e8cb2ca0d)

![)B9HZFOX2%3LLPNXA{S 1J](https://github.com/user-attachments/assets/b2c5d68d-c194-4975-b0b3-125596219660)

フローティングウィンドウがボーダーレスの時、マウス中ボタンドラッグで移動可能

![image](https://github.com/user-attachments/assets/a7a3af3c-4e36-497f-908e-0ba5262e8d35)

フローティングウィンドウ名を変更した場合、対応する'locales.xml'のボタンパスも修正必要、さもないとボタンが機能しない

![M$1UXH$}VE5M62Z{N_~HXTN](https://github.com/user-attachments/assets/0501568a-9a69-41d5-9754-cdf33e37f35f)

ウィンドウボタンのショートカットパス

![5(9{@C(NYM5LMPYJD_%8FWP](https://github.com/user-attachments/assets/3a6547ca-d9db-41ba-8545-aa58a4f5039c)

ESLyric画面のダブルクリックで全画面切替/終了。面倒なら全画面モード🔳に`ショートカットキー`設定可能、再生▶停止⏸ショートカットキーも追加可能

`ショートカットキー`は個人の好みで❤

![image](https://github.com/user-attachments/assets/087f2366-ac3d-4f4f-8717-3d2da4c9951a)

![image](https://github.com/user-attachments/assets/6d3b0392-1d3e-42d1-8041-db3b62d8f37b)

![image](https://github.com/user-attachments/assets/4afaab25-7a59-4d0c-85db-88acb186373f)


左のタイトルなどの行間が狭くフォントが半分しか表示されない場合🚫

![image](https://github.com/user-attachments/assets/9fc7e46c-a947-402d-8a05-49bf4515944e)

`.xml`のフォントサイズ`font-size=" "`を変更してみる。注釈あり

🔗[https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80](https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80)

適当なサイズに調整し保存すれば即時反映❗

PCやフォント設定により異なるため↕

`レイアウト要素識別表示`をオンにして調整補助可

![_467OPN%W5D1{{BEZ3YWJ)8](https://github.com/user-attachments/assets/2519cdd0-8e44-4bcb-922b-f9890c500bfe)


先ほど置いた設定ファイル`.xml`をテキストエディタで開く

        C:\Users\gebilaowang66662\AppData\Roaming\foobar2000-v2\eslyric-data\layout\Style1


以下のパラメータを調整🔢 

![(6XX%~{B)M)NG2SKGGQ_YFR](https://github.com/user-attachments/assets/8822ef8b-4b05-4c5e-a6b9-d277e2c4504d)

付録：カスタムボタン

🔗[https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80](https://github.com/ESLyric/release/wiki/%E9%9D%A2%E6%9D%BF%E5%B8%83%E5%B1%80)

![カスタムボタン](https://github.com/user-attachments/assets/10824db4-c4e4-42db-ab75-f33d68ff6c84)


------------------------------------------------------------------------------------------

# 4️⃣ 歌詞単語単位ソース 💬

他の地域の歌詞ソースについては不明なので、ここではインストール方法のみを説明します。

以下のパスに配置

    C:\Users\（各ユーザー名は異なります）\AppData\Roaming\foobar2000-v2\eslyric-data\scripts

![image](https://github.com/user-attachments/assets/7fd4ecc1-2047-4559-9222-7f11a8ddd409)

見つからない場合はインストールフォルダ内に`profie`フォルダがないか確認、ここに

    eslyric-data\scripts

がある

![b9bdf403918fa0ec4115922e609759ee3c6ddbb5](https://github.com/user-attachments/assets/b60c8bd0-e5ce-44a4-bba0-2d89d9962e63)

`標準フォーマットに変換`のチェックを外す🚫、なければ無視

![image](https://github.com/user-attachments/assets/3136593d-4451-43a5-8234-14e456995adc)

`EX`ソースはチェック✅

![image](https://github.com/user-attachments/assets/6b1725d1-18df-461c-b783-f550c4229444)

`EX`ソースのみが逐語対応。酷狗の逐語は運次第🗿

`カラオケモード`の下の`強化歌詞`もONに

全画面と外部インターフェースは別設定のため両方ON✅✅

![image](https://github.com/user-attachments/assets/1edfc16e-71fd-4143-a549-2407988dcfea)

![image](https://github.com/user-attachments/assets/d8cef639-a24e-43bf-be0f-311aa612e765)

プラグインが歌詞を検索した後🔍

歌詞を曲ファイルに保存可能📎

歌詞画面を右クリック🖱

![image](https://github.com/user-attachments/assets/3d25fa3d-2d56-4fd8-9073-32a408058b59)


------------------------------------------------------------------------------------------

# 5️⃣ 歌詞ルール 🤩

歌詞上の原唱などを除去する方法❓🚮

下図のように

![image](https://github.com/user-attachments/assets/c54782e3-ebac-4c72-add9-046551cc2eba)

ソフト設定でワイルドカード除去を選択、`*`は任意の文字列

たとえば`演唱：林俊杰`のように多くの曲の頭に付いている場合は

`演唱：*`と入力🗿

![image](https://github.com/user-attachments/assets/7b8caf75-5654-44bf-a634-dce61aa19ba7)

------------------------------------------------------------------------------------------

# 6️⃣ アートワーク埋め込み 😇

曲にアートワークを埋めていないと真っ黒で見づらい◼

![image](https://github.com/user-attachments/assets/df4ea3e5-778d-463f-90f1-b1ab8945601e)

画面右クリック🖱

![$Q5DNGMD76} (M`K)U%%@B3](https://github.com/user-attachments/assets/980ab659-7827-4cc3-8f27-56e553833ff8)

![C1G`~GZ)ZSH_LRUSJGR4064](https://github.com/user-attachments/assets/c4cc8e60-66ca-43f7-9bf1-dd44f6d1d1e9)

------------------------------------------------------------------------------------------

# 7️⃣ プラグイン読み込み 🤨

このプラグインは歌詞を`タグフィールド`📝から読み取る

ファイル名では検索しないため、違う場合は右クリック🖱最下部の`プロパティ`で二つのフィールドを正しく修正

![image](https://github.com/user-attachments/assets/e41846ad-73cf-4b3e-8dce-bf540d77c688)

歌手が多すぎると検索結果に影響、曲名は変えずに歌手を一人ずつ追加して検索🔍可能

![image](https://github.com/user-attachments/assets/dcf5efad-429b-4f58-ba5b-7bf576de7997)

------------------------------------------------------------------------------------------

# 8️⃣ 歌詞なし設定（純音楽） 😎

歌詞なしの場合、レイアウトは中央寄せとなり歌詞コンポーネントを隠す

3つの条件を満たす必要あり

1. `%UNSYNCED LYRICS%` `%LYRICS%` のいずれかのタグに`純音楽`という文字が含まれること

![image](https://github.com/user-attachments/assets/eb1c14f0-e9ae-4c61-a83e-0e1195588236)

2. 歌詞は表示しないこと

歌詞に`純音楽`がある場合、歌詞処理に`*純音楽*`を追加可能

![image](https://github.com/user-attachments/assets/a34173bb-c365-46bb-86b7-95f738b1cf8d)

3. 歌詞検索をしないこと

検索フィルターに `%UNSYNCED LYRICS%` `%LYRICS%` のワイルドカード `*純音楽*`を追加

これら二つのローカルタグに`純音楽`がある場合、歌詞検索を停止

![image](https://github.com/user-attachments/assets/c879d358-8098-48d5-81a1-6cf207041fe9)

------------------------------------------------------------------------------------------

# 9️⃣ フォント 🤠
推奨
Poppins-Black（英語・スペイン語） + NotoSansSC-ExtraBold(中国語・日本語) + NotoSans-Black（ロシア語）を必要に応じて組み合わせ

（NotoSansSC-ExtraBoldの英語・スペイン語をPoppins-Blackに、ロシア語をNotoSans-Blackにフォントツールで置き換えが必要）

Poppins（西洋文字）：

🔗https://fonts.google.com/specimen/Poppins?query=Poppins   

思源黑体/Noto Sans（中日韓）：

🔗https://fonts.google.com/noto/specimen/Noto+Sans+SC   

思源黑体/Noto Sans（ロシア語）：

🔗https://fonts.google.com/noto/specimen/Noto+Sans?lang=ru_Cyrl   

iOS用フォント

🔗https://developer.apple.com/fonts/

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration&type=Date)](https://star-history.com/#gebilaowang66662/ESLyric-full-screen-imitation-IOS-configuration&Date)

