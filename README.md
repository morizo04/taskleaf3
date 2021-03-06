2020/08/28

## アプリケーション概要  
社内用を想定した社員の価値を高めるアプリを制作中です。  


## 開発環境  
Ruby/Ruby on Rails/Postgresql/Github/Visual Studio Code


## 機能紹介  
### CRUD機能を用いてのタスク管理機能


### ログイン、ログアウト機能


### ユーザーの作成機能(管理者権限を持ってる人のみ)


### ログイン、ログアウト機能


### タスク検索機能


### タスクソート機能


### CSV形式でファイルのインポート/エクスポート機能


### ページネーション機能



## 各機能の詳細

### CRUD機能を用いてのタスク管理機能
  概要  
  タスクを投稿、編集、削除できるようにしました  
  以下のようなビューとなっております  
![image](https://user-images.githubusercontent.com/67141130/92218724-82040380-eed4-11ea-8d82-b6e77d647ffc.png)    




### ログイン、ログアウト機能
  概要  
  ログイン用のビューを作成しました  
![image](https://user-images.githubusercontent.com/67141130/92221857-140e0b00-eed9-11ea-8557-1c2c305813bf.png)    


### ユーザーの作成機能(管理者権限を持ってる人のみ)
　概要  
  ユーザーモデルでadminのカラムを持っているユーザーのみ以下のように作成されているユーザーを一覧で確認でき、作成・編集・削除ができるようになっています  
![image](https://user-images.githubusercontent.com/67141130/92222067-62bba500-eed9-11ea-85f9-b07c3d47f310.png)    


    
  adminを持ってないユーザーがログインすると以下のように表示され、ヘッダーにユーザー一覧が表示されないようになっています  
 ![image](https://user-images.githubusercontent.com/67141130/92222934-b4b0fa80-eeda-11ea-9ef7-f71d964cd4e9.png)

    


### タスク検索機能
  概要  
  名称及び作成された時間でタスクを検索できるようになっています
   
 ### タスクソート機能
 　概要  
   以下の写真にてNameを押していただくと名前の順で昇順・降順にタスクが表示されます  
   ![image](https://user-images.githubusercontent.com/67141130/92299948-e3d67300-ef91-11ea-8942-016ab917c394.png)    
   

### CSV形式でファイルのインポート/エクスポート機能
　概要  
  以下の写真よりエクスポートを押すとcsvファイルがダウンロードできます  
![image](https://user-images.githubusercontent.com/67141130/92299974-0bc5d680-ef92-11ea-822d-18d980834b73.png)      
　そうするとログインしているユーザーのタスクモデルが以下のような形でcsv形式で入手できます  
 ![image](https://user-images.githubusercontent.com/67141130/92300853-42531f80-ef99-11ea-9f95-968a973734c0.png)    

   
   また以下の写真のように適切なcsvファイルを選択しインポートするとcsvファイルからタスクを作成することができます  
![image](https://user-images.githubusercontent.com/67141130/92301872-40418e80-efa2-11ea-995e-a7f9fdaada7a.png)    

   
 ### ページネーション機能
 　概要   
    gem 'kaminari'を用いて実装しました  
    以下の写真のように25タスク毎に1ページが作成されるようになっていて、データが膨大になった際のブラウザの読み込み速度を落とさないよう配慮しました  
![image](https://user-images.githubusercontent.com/67141130/92301949-ed1c0b80-efa2-11ea-84d0-463f87817a62.png)




## 今後実装したいこと
### 全ユーザーのアウトプットスペースを作り、いいね機能を実装する。
→いいねが多い記事を書いた人にインセンティブつくようにすれば、質の高いノウハウが社内で共有できるのではないかと考えたため

### 自分軸の作成を手助けできるようなアプリの開発
→自分軸を持つことにより判断にタイムロスをなくし、生産性の高い会社を作れるのではないかと思ったため

