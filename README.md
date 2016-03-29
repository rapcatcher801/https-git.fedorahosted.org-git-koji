# https-git.fedorahosted.org-git-koji
echo "# https-git.fedorahosted.org-git-koji" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/rapcatcher801/https-git.fedorahosted.org-git-koji.git
git push -u origin master
