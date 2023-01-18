4/20
<br>

# Linuxとは
OSの一種  
Windows上に仮想OSを構築して運用する

<br>

# Linuxの長所
* `オープンソース`
* 開発環境が無償
* 少ないリソースで運用できる
* 世界中で`サーバー用途`として利用されている

<br>

# Linuxの短所
* 英語版しかないことがある
* 文字化けを起こすことが多い

<br>

# ディストリビューションとは
「**Linuxディストリビューション**」  
→中核となる部分もアプリケーションも含んで指す  
`RedHat系`と`Debian系`が存在する  
<br>
「**Linuxカーネル**」  
→中核となる部分のみを指す  
<br>

# Linuxメモ
Linuxの管理者名は`root`  
「＃」が管理者の証  
<br>
**・シャットダウンコマンド**  
$ sudo poweroff

$ ls -al
total 8
drwxr-xr-x  3 maho  staff   102  1  5 09:41 .
drwxr-xr-x  9 maho  staff   306  1  5 09:23 ..
-rw-r--r--  1 maho  staff  1276  1  5 09:38 index.md

$ git init
Initialized empty Git repository in /Users/maho/git_homepage/md_docs/.git/

$ git add index.md 

$ git commit -m "first commit"
[master (root-commit) 2e462ca] first commit
 1 file changed, 20 insertions(+)
 create mode 100644 index.md

$ git remote add origin https://github.com/takara9/md_docs.git

$ git push -u origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 871 bytes | 871.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/takara9/md_docs.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.


