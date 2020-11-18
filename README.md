# kubernetes-helm v 2.13.0

Currently its a pain to install this version of kubernetes-helm

This is just a simple way to do it using the Forumla from the homebrew-core repo from the v 2.13.0 tag

## To install

```
brew install cedw93/kubernetes-helm/kubernetes-helm
```

result

```
==> Installing kubernetes-helm from cedw93/kubernetes-helm
==> Downloading https://homebrew.bintray.com/bottles-kubernetes-helm/kubernetes-helm-2.13.0.mojave.bottle.tar.gz
#=#=#                                                                         
curl: (22) The requested URL returned error: 404 Not Found
Error: Failed to download resource "kubernetes-helm"
Download failed: https://homebrew.bintray.com/bottles-kubernetes-helm/kubernetes-helm-2.13.0.mojave.bottle.tar.gz
Warning: Bottle installation failed: building from source.
==> Cloning https://github.com/helm/helm.git
Updating /Users/chris.edwards/Library/Caches/Homebrew/kubernetes-helm--git
==> Checking out tag v2.13.0
HEAD is now at 79d0794 add `make sign` and `make fetch-dist` (#5329)
HEAD is now at 79d0794 add `make sign` and `make fetch-dist` (#5329)
==> make bootstrap
==> make build
==> Caveats
Bash completion has been installed to:
  /usr/local/etc/bash_completion.d

zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/kubernetes-helm/2.13.0: 51 files, 73.2MB, built in 3 minutes 50 seconds
```