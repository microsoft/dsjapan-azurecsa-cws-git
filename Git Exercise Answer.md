# **Exercise 1 回答**

- C:\gitroot\firstRepo がリポジトリになっていること  

  <img width=400 src="images-exercise/gitExercise-Ans01-01.png" />

- file1.txt が Commit されていてファイルの内容が指示通りであること  

  <img width=250 src="images-exercise/gitExercise-Ans01-02.png" />  

- file2.txt が Commit されていてファイルの内容が指示通りであること  

  <img width=250 src="images-exercise/gitExercise-Ans01-03.png" />  

- Commit ログが２つあり、最初の Commit には file1.txt だけが保持されており、２つ目の Commit には file2.txt が保持されていること  

  <img width=200 src="images-exercise/gitExercise-Ans01-04.png" /><br />

  <img width=400 src="images-exercise/gitExercise-Ans01-05.png" /><br />

  <img width=400 src="images-exercise/gitExercise-Ans01-06.png" />

***

# **Exercise 2 回答**

- Commit ログは下図と同じであること  

  <img width=230 src="images-exercise/gitExercise-Ans02-01.png" />  

- BranchA に Commit が１つあり file2.txt の内容が以下の通りであること  

  <img width=260 src="images-exercise/gitExercise-Ans02-02.png" />  

- main に Commit が３つあり file1.txt の内容が以下の通りであること  

  <img width=260 src="images-exercise/gitExercise-Ans02-03.png" />

***

# **Exercise 3 回答**

- merge が完了すること( Commit ログが下図と同じであること)  
  - Conflict が発生しなかったこと
  - BranchA が削除されていること  

  <img width=260 src="images-exercise/gitExercise-Ans03-01.png" />

- file1.txt の内容が下記になっていること  

  <img width=260 src="images-exercise/gitExercise-Ans03-02.png" />

- file2.txt の内容が下記になっていること  
  <img width=260 src="images-exercise/gitExercise-Ans03-03.png" />

***

# **Exercise 4 回答**

- merge が完了すること( Commit ログが下図と同じであること)  
  - Conflict が発生したこと
  - Branchb が削除されていること  

  <img width=240 src="images-exercise/gitExercise-Ans04-01.png" />

- file3.txt の内容が下記になっていること  

  <img width=270 src="images-exercise/gitExercise-Ans04-02.png" />

***

# **Exercise 5 回答**

- Fast-forward merge だったこと( Commit ログが下図と同じであること)  
- main と BranchC が最新の Commit であること

  <img width=450 src="images-exercise/gitExercise-Ans05-01.png" />

***

# **Exercise 6 回答**

- remoteRepo.git が bare リポジトリとして初期化されていること

  <img width=270 src="images-exercise/gitExercise-Ans06-01.png" />

- localRepo1 の origin が remoteRepo.git であること

  <img width=270 src="images-exercise/gitExercise-Ans06-02.png" />

- Commit が２つあり、最初の Commit は空 Commit であること
- origin/main と main ブランチの両方が 2つ目の Commit を指していること

  <img width=270 src="images-exercise/gitExercise-Ans06-03.png" />

***

# **Exercise 7 回答**

- ClonedRepos に remoteRepo フォルダが Git リポジトリとして作成されていること

  <img width=270 src="images-exercise/gitExercise-Ans07-01.png" />

- Commit 履歴は BranchD と origin/BranchD が最新であること

  <img width=300 src="images-exercise/gitExercise-Ans07-02.png" />

- Clone した remoteRepo の origin が Exercise 6 のリモートリポジトリであること

  <img width=390 src="images-exercise/gitExercise-Ans07-03.png" />

- Exercise 6 の ローカルリポジトリの Commit 履歴が Exercise 7 と同じであること
  - 下図の状態の時はまだ Checkout していない  
    <img width=270 src="images-exercise/gitExercise-Ans07-04.png" />

***

# **Exercise 8 回答**

- localRepo1, ClonedRepos 配下の remoteRepo 共に最新の Commit が Revert であること

  <img width=350 src="images-exercise/gitExercise-Ans08-01.png" />

- revert 前の file4.txt の内容が以下であること

  <img width=650 src="images-exercise/gitExercise-Ans08-02.png" />

- revert 後の file4.txt の内容が以下であること

  <img width=350 src="images-exercise/gitExercise-Ans08-03.png" />

***

# **Exercise 9 回答**

- file5.txt への変更が Stage 前の状態であること

  <img width=500 src="images-exercise/gitExercise-Ans09-01.png" />

- file5.txt の内容が以下の通りであること

   <img width=320 src="images-exercise/gitExercise-Ans09-02.png" />

- Commit 後に reset した結果が残っていること

  <img width=750 src="images-exercise/gitExercise-Ans09-03.png" />

- reset 前の状態に戻して reset 前の Commit が正しく行われたことを確認すること
  - コマンドで reset した後の Commit 履歴が以下であること

    <img width=320 src="images-exercise/gitExercise-Ans09-04.png" />

  - file5.txt の内容が以下であること

   <img width=280 src="images-exercise/gitExercise-Ans09-05.png" />


***

# **Exercise 10 回答**

- Conflict したことを確認

  <img width=650 src="images-exercise/gitExercise-Ans10-01.png" />

- Merge の取り消しの確認
  - main と BranchE が 最初から数えて2番目の Commit で分岐していること

   <img width=280 src="images-exercise/gitExercise-Ans10-02.png" />

  - 最後の Commit への操作が reset であること

    <img width=650 src="images-exercise/gitExercise-Ans10-03.png" />

  - main ブランチの file5.txt の内容が以下の通りであること

    <img width=280 src="images-exercise/gitExercise-Ans10-04.png" />

  - BranchE の file5.txt の内容が以下の通りであること

    <img width=280 src="images-exercise/gitExercise-Ans10-05.png" />

***

# **Exercise 11 回答**

- Commit が３つ状態の確認

  <img width=280 src="images-exercise/gitExercise-Ans11-01.png" />

- Branch の切り忘れ時の方法
  1. 最新の Commit に対して BranchF を切る 

    <img width=380 src="images-exercise/gitExercise-Ans11-02.png" />

  2. main ブランチへ移動

    <img width=380 src="images-exercise/gitExercise-Ans11-03.png" />

  3. first commit を指定して reset

    <img width=380 src="images-exercise/gitExercise-Ans11-04.png" />

  4. reset オプションは hard を指定

    <img width=380 src="images-exercise/gitExercise-Ans11-05.png" />

  5. main にいるので、 BranchF へ移動

    <img width=230 src="images-exercise/gitExercise-Ans11-06.png" />

  6. 完了

   <img width=230 src="images-exercise/gitExercise-Ans11-07.png" />
