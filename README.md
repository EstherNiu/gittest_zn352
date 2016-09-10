# gittest_zn352
I had two attempts: 
1, creating the link seems perfect until
2, when solving the merging question and after editing in emacs, the keeps telling me 
<Git error on commit after merge - fatal: cannot do a partial commit during a merge>
so I find http://stackoverflow.com/questions/5827944/git-error-on-commit-after-merge-fatal-cannot-do-a-partial-commit-during-a-mer
add -i before commit:
git commit -i myfirstfile.txt -m 'solving merging problem' 
then the problem is solved. 

