# Install Docker
```
shahazzat@Mohammads-MacBook-Pro ~ % brew install docker
Updating Homebrew...
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/core and homebrew/cask).
==> New Formulae
gradle@6                            nomino                              parquet-cli
==> Updated Formulae
Updated 108 formulae.
==> Deleted Formulae
osquery
==> New Casks
enclave
==> Updated Casks
Updated 24 casks.

Warning: Treating docker as a formula. For the cask, use homebrew/cask/docker
==> Downloading https://ghcr.io/v2/homebrew/core/docker/manifests/20.10.6
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/docker/blobs/sha256:126059108fcbcc3a48839c2f4baa8f797b23d2
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:126059108fcbcc3a48839c
######################################################################## 100.0%
==> Pouring docker--20.10.6.arm64_big_sur.bottle.tar.gz
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions
==> Summary
🍺  /opt/homebrew/Cellar/docker/20.10.6: 12 files, 57.8MB
shahazzat@Mohammads-MacBook-Pro ~ %

==================================================================================
shahazzat@Mohammads-MacBook-Pro ~ % brew install docker-compose
==> Downloading https://ghcr.io/v2/homebrew/core/libyaml/manifests/0.2.5
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libyaml/blobs/sha256:fe1082f3475a144261b41e2c3e0728b933191
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:fe1082f3475a144261b41e
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gdbm/manifests/1.19
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gdbm/blobs/sha256:2eea26ad3d3d013c3ed2e2b985d4749719e8be32
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:2eea26ad3d3d013c3ed2e2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/mpdecimal/manifests/2.5.1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/mpdecimal/blobs/sha256:eebbc5c7e71710c848eb60b90f946aefdee
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:eebbc5c7e71710c848eb60
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/manifests/1.1.1k
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/blobs/sha256:0a75e0f116c0653bc7a2b422e5dc500e7
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:0a75e0f116c0653bc7a2b4
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/readline/manifests/8.1
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/readline/blobs/sha256:940e7c2b80ef7f59b26726a5669a31fcb8ba
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:940e7c2b80ef7f59b26726
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/sqlite/manifests/3.35.5
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/sqlite/blobs/sha256:85e058d256013feea4835f51d9054dd1b8eec4
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:85e058d256013feea4835f
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/xz/manifests/5.2.5
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/xz/blobs/sha256:c84206005787304416ed81094bd3a0cdd2ae8eb626
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:c84206005787304416ed81
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.9/manifests/3.9.5
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.9/blobs/sha256:1bbe1682fa834dbd546107d642ece2fdb7
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:1bbe1682fa834dbd546107
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/docker-compose/manifests/1.29.2
######################################################################## 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/docker-compose/blobs/sha256:67d4e74c8293c978dd8e4133fedbd1
==> Downloading from https://pkg-containers.githubusercontent.com/ghcr1/blobs/sha256:67d4e74c8293c978dd8e41
######################################################################## 100.0%
==> Installing dependencies for docker-compose: libyaml, gdbm, mpdecimal, openssl@1.1, readline, sqlite, xz and python@3.9
==> Installing docker-compose dependency: libyaml
==> Pouring libyaml--0.2.5.arm64_big_sur.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libyaml/0.2.5: 10 files, 369.9KB
==> Installing docker-compose dependency: gdbm
==> Pouring gdbm--1.19.arm64_big_sur.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gdbm/1.19: 24 files, 880.3KB
==> Installing docker-compose dependency: mpdecimal
==> Pouring mpdecimal--2.5.1.arm64_big_sur.bottle.tar.gz
🍺  /opt/homebrew/Cellar/mpdecimal/2.5.1: 71 files, 2.2MB
==> Installing docker-compose dependency: openssl@1.1
==> Pouring openssl@1.1--1.1.1k.arm64_big_sur.bottle.tar.gz
==> Regenerating CA certificate bundle from keychain, this may take a while...
==> Caveats
A CA file has been bootstrapped using certificates from the system
keychain. To add additional certificates, place .pem files in
  /opt/homebrew/etc/openssl@1.1/certs

and run
  /opt/homebrew/opt/openssl@1.1/bin/c_rehash

openssl@1.1 is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS provides LibreSSL.

If you need to have openssl@1.1 first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/openssl@1.1/bin:$PATH"' >> ~/.zshrc

For compilers to find openssl@1.1 you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/openssl@1.1/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/openssl@1.1/include"

==> Summary
🍺  /opt/homebrew/Cellar/openssl@1.1/1.1.1k: 8,071 files, 18MB
==> Installing docker-compose dependency: readline
==> Pouring readline--8.1.arm64_big_sur.bottle.tar.gz
==> Caveats
readline is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS provides BSD libedit.

For compilers to find readline you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/readline/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/readline/include"

==> Summary
🍺  /opt/homebrew/Cellar/readline/8.1: 48 files, 1.7MB
==> Installing docker-compose dependency: sqlite
==> Pouring sqlite--3.35.5.arm64_big_sur.bottle.tar.gz
==> Caveats
sqlite is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have sqlite first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/sqlite/bin:$PATH"' >> ~/.zshrc

For compilers to find sqlite you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/sqlite/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/sqlite/include"

==> Summary
🍺  /opt/homebrew/Cellar/sqlite/3.35.5: 11 files, 4.2MB
==> Installing docker-compose dependency: xz
==> Pouring xz--5.2.5.arm64_big_sur.bottle.tar.gz
🍺  /opt/homebrew/Cellar/xz/5.2.5: 95 files, 1.4MB
==> Installing docker-compose dependency: python@3.9
==> Pouring python@3.9--3.9.5.arm64_big_sur.bottle.tar.gz
==> /opt/homebrew/Cellar/python@3.9/3.9.5/bin/python3 -m ensurepip
==> /opt/homebrew/Cellar/python@3.9/3.9.5/bin/python3 -m pip install -v --no-deps --no-index --upgrade --is
==> Caveats
Python has been installed as
  /opt/homebrew/bin/python3

Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
`python3`, `python3-config`, `pip3` etc., respectively, have been installed into
  /opt/homebrew/opt/python@3.9/libexec/bin

You can install Python packages with
  pip3 install <package>
They will install into the site-package directory
  /opt/homebrew/lib/python3.9/site-packages

tkinter is no longer included with this formula, but it is available separately:
  brew install python-tk@3.9

See: https://docs.brew.sh/Homebrew-and-Python
==> Summary
🍺  /opt/homebrew/Cellar/python@3.9/3.9.5: 3,080 files, 55.3MB
==> Installing docker-compose
==> Pouring docker-compose--1.29.2.arm64_big_sur.bottle.tar.gz
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions
==> Summary
🍺  /opt/homebrew/Cellar/docker-compose/1.29.2: 1,310 files, 16.4MB
==> Caveats
==> openssl@1.1
A CA file has been bootstrapped using certificates from the system
keychain. To add additional certificates, place .pem files in
  /opt/homebrew/etc/openssl@1.1/certs

and run
  /opt/homebrew/opt/openssl@1.1/bin/c_rehash

openssl@1.1 is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS provides LibreSSL.

If you need to have openssl@1.1 first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/openssl@1.1/bin:$PATH"' >> ~/.zshrc

For compilers to find openssl@1.1 you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/openssl@1.1/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/openssl@1.1/include"

==> readline
readline is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS provides BSD libedit.

For compilers to find readline you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/readline/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/readline/include"

==> sqlite
sqlite is keg-only, which means it was not symlinked into /opt/homebrew,
because macOS already provides this software and installing another version in
parallel can cause all kinds of trouble.

If you need to have sqlite first in your PATH, run:
  echo 'export PATH="/opt/homebrew/opt/sqlite/bin:$PATH"' >> ~/.zshrc

For compilers to find sqlite you may need to set:
  export LDFLAGS="-L/opt/homebrew/opt/sqlite/lib"
  export CPPFLAGS="-I/opt/homebrew/opt/sqlite/include"

==> python@3.9
Python has been installed as
  /opt/homebrew/bin/python3

Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
`python3`, `python3-config`, `pip3` etc., respectively, have been installed into
  /opt/homebrew/opt/python@3.9/libexec/bin

You can install Python packages with
  pip3 install <package>
They will install into the site-package directory
  /opt/homebrew/lib/python3.9/site-packages

tkinter is no longer included with this formula, but it is available separately:
  brew install python-tk@3.9

See: https://docs.brew.sh/Homebrew-and-Python
==> docker-compose
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions
shahazzat@Mohammads-MacBook-Pro ~ % 
shahazzat@Mohammads-MacBook-Pro ~ % brew list                                       
==> Formulae
docker		gdbm		mpdecimal	python@3.9	sqlite
docker-compose	libyaml		openssl@1.1	readline	xz

==> Casks
appcleaner	gimp		google-chrome	skype		vlc
shahazzat@Mohammads-MacBook-Pro ~ %
```
