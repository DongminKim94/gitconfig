# gitconfig
gitconfig 정보

[git command]

git log --reflog --graph --oneline --decorate
git commit --allow --empty(빈 커밋 생성)

[alias]

lg = log --graph --abbrev-commit --decorate --format=format:'%C(cyan)%h%C(reset) - %C(green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(yellow)%d%C(reset)' --all
