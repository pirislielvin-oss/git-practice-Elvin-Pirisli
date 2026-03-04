# Git Practice Project

Bu layihə Git və GitHub praktikası üçün yaradılmışdır.
Branch yaratma, merge və pull əmrləri test edilir.
Hazırlayan: Elvin Pirisli.
Kicik market sistemini eks etdirir.

README.md -nin githuba push olunmasi ucun islenen emirler.
elvin@Elvin-MacBook-Air task % git init
Initialized empty Git repository in /Users/elvin/Desktop/task/.git/
elvin@Elvin-MacBook-Air task % git add README.md
elvin@Elvin-MacBook-Air task % git commit -m "first commit"
[main (root-commit) 5a828f9] first commit
 1 file changed, 6 insertions(+)
 create mode 100644 README.md
elvin@Elvin-MacBook-Air task % git branch -M main
elvin@Elvin-MacBook-Air task % git remote add origin https://github.com/pirislielvin-oss/git-practice-Elvin-Pirisli.git
elvin@Elvin-MacBook-Air task % git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 379 bytes | 379.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/pirislielvin-oss/git-practice-Elvin-Pirisli.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
elvin@Elvin-MacBook-Air task % 


## Feature-1 bölməsi

Bu dəyişiklik feature-1 branchində əlavə olunmuşdur.