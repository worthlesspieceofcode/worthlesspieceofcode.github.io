0. mv themes a/submodule_tmp

1. git submodule deinit -f -- themes/ananke
2. rm -rf .git/modules/themes/ananke
3. git rm -f themes/ananke
# Note: a/submodule (no trailing slash)

# or, if you want to leave it in your working tree and have done step 0
3.   git rm --cached themes/ananke
3bis mv a/submodule_tmp a/submodule


https://discourse.gohugo.io/t/hugo-modules-for-dummies/20758

https://github.com/theNewDynamic/gohugo-theme-ananke

sudo add-apt-repository --remove ppa:therealkenc/wsl-pulseaudio

hugo mod init 

https://hackernoon.com/how-to-set-up-godaddy-domain-with-github-pages-a9300366c7b


hugo mod init github.com/worthlesspieceofcode/worthlesspieceofcode.github.io

https://gohugo.io/hosting-and-deployment/hosting-on-github/
