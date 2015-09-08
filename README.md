## Git開発手順  

### わたし  
1.ブランチ切って  
1.切ったブランチで作業  
1.作業  
1.git commit -am "ああああ"  
1.git pull  
1.masterに移動  
1.git merge 切ったブランチ  
1.git push origin master  

### しののめ氏  
1.ブランチ切って  
1.切ったブランチで作業  
1.作業  
1.git add -a  
1.git commit -am "aaaa"  
1.git pull(リモートのを持ってくる)  
1.git push -u origin HEAD  
1.git checkout master  
1.git pull  
1.git merge 作ったブランチ

## Atomでgitのbranchからcommit、push、pullまで

AtomEditor内で利用する場合にはgitconfigの設定及びgit-plusの導入が必要です。  
導入が終わると初期では'Ctrl+shift+H'で利用できます。
(リポジトリフォルダで無い場所はgit initしか書けません)
