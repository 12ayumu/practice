# practice
githubの練習用リポジトリ

## コマンド
- git clone コピーしたリンク
  自分のローカルにローカルリポジトリを作成する  
  ローカルリポジトリとはリモートリポジトリのコピー  

- git checkout -b 任意のブランチ名  
任意のフォルダ下にブランチを作成するコマンド  
ブランチとはローカルリポジトリのコピー
  
- git checkout  
作成したブランチ名  
ブランチの移動を行う
  
- git branch  
作成したブランチの一覧表示と  
今いるブランチは色付きで表示してくれる
  
- git remote -v  
originが示しているgitのリポジトリを表示する  
  
- git add 任意のフォルダまたはファイル名  
指定したフォルダまたはファイルをステージに上げる  
(commitする下準備)  
「.」を指定することでカレントディレクトリ直下の  
全ての要素を指定できる  
  
- git commit -m "コメント"  
コミットを行う  
  
- git push  
ブランチをgithub上にあげる  
  

## 流れ
```
git clone クローンしたいリポジトリのリンク
```
でローカルリポジトリを作成する  
  
```
git checkout -b 任意のブランチ名
```
でブランチを作成する  
  
今いるブランチを確認したいときは
```
git branch
```
を利用する  
  
作業を行い、変更を完了したら
```
git add git add 任意のフォルダまたはファイル名
```
を用いてステージに上げる。  
その後
```
git commit -m "コメント"
```
を用いてコミットを行い
```
git push
```
でgithub上にブランチを上げる


