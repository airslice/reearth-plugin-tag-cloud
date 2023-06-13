# Tag Cloud プラグイン

![test reearth dev_published html_alias=chiafhhehd(1440 desktop)](https://user-images.githubusercontent.com/21994748/182887355-a26709cc-d3db-4f47-86ac-c04c021b9207.png)

## このプラグインについて
- Tag Cloud プラグインは各レイヤーのタグをリストに一覧表示することで、レイヤーの表示・非表示を効率的に行えます。<br>
- このプラグインは[reearth-plugin-toolbox](https://github.com/airslice/reearth-plugin-toolbox)を利用して作成されています。

　
## 使用方法
### 準備
- タグクラウドで制御したいレイヤーにタグを設定します。
![](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/aafd9e53-045c-4e2b-859e-c6bdc0d6657a)



### 右パネルの設定項目


- Tag Group Name <br>
    リスト表示するタググループを右パネルで指定します。
    ここで指定したタググループに属するレイヤーがリストに表示されます。<br>
    ![](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/462970c0-322a-49dc-bc74-1c7afe89302d)
- Customize <br>
    ウイジェットUIの表示色をカスタマイズします。<br>
    ![](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/eb4a05b3-4010-46c8-9f19-b39da3063f81)


(左：ThemeをDark、中央：ThemeをLight、右：BackgroundColorとPrimary Colorを指定)
![](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/2de9e4f4-30bf-4ca9-88b2-fa58eb26861a)

### 操作方法


- Tag Cloud ウィジェットには右パネルで設定したタググループに含まれるタグがリストに表示されます。
- タグをクリックすることで、対応するレイヤの表示・非表示を切り替えます。以下の例では、京都、奈良は表示、大阪は非表示に設定されています。<br>
    ![](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/105af2c4-3b7e-4020-bc22-3092858c81b3)


### 留意点
- 複数タグが指定されているレイヤーの場合、少なくとも一つのタグが選択されるとそのレイヤーは表示されます。
- 指定タググループ内のタグを持たないレイヤーは 「... 」に分類されます。
## 備考
- テストブラウザ環境
  - OS:Mac OS Montery 12.6.5
  - ブラウザ：Google Chrome 112.0.5615.121

## 開発者欄

このプラグインは、Re:Earth公式プラグインです。

![logo-3](https://github.com/airslice/reearth-plugin-tag-cloud/assets/13118515/937a85ee-0b13-492a-9525-1b76583468d0)


ソースコードはこちら(https://github.com/airslice/reearth-plugin-tag-cloud)

- コミュニティ

  - このプラグインを利用したプロジェクトをユーザーコミュニティでシェアしましょう。

  - このプラグインについての不明点がある場合にもここからRe:Earthチームや他の開発者に質問することができます。

  - Discordへのリンクはこちら(https://discord.gg/BXcQhvwqqM)

<br>
<br>

# Tag Cloud

This is a Re:earth plugin made with [reearth-plugin-toolbox](https://github.com/airslice/reearth-plugin-toolbox).

Tag Cloud will be helpful when you want to organize layer data in ONE dimension.

![test reearth dev_published html_alias=chiafhhehd(1440 desktop)](https://user-images.githubusercontent.com/21994748/182887355-a26709cc-d3db-4f47-86ac-c04c021b9207.png)

- Features:
  - Show a certain tag group as tag cloud.
  - Show/hide layers by tags.
  
- Setup:
  - Input the tag group name from Re:earth Earth Editor.

- Tips:
  - Layer will be visible when any of its tag is enabled.
  - If a layer does not have any tags of selected tag group it will be list in a special tag `...`
