# Install Homebrew
```
shahazzat@Mohammads-MacBook-Pro ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password).
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew
==> The following new directories will be created:
/opt/homebrew/bin
/opt/homebrew/etc
/opt/homebrew/include
/opt/homebrew/lib
/opt/homebrew/sbin
/opt/homebrew/share
/opt/homebrew/var
/opt/homebrew/opt
/opt/homebrew/share/zsh
/opt/homebrew/share/zsh/site-functions
/opt/homebrew/var/homebrew
/opt/homebrew/var/homebrew/linked
/opt/homebrew/Cellar
/opt/homebrew/Caskroom
/opt/homebrew/Frameworks
==> The Xcode Command Line Tools will be installed.

Press RETURN to continue or any other key to abort==> /usr/bin/sudo /bin/mkdir -p /opt/homebrew
Password:
==> /usr/bin/sudo /usr/sbin/chown root:wheel /opt/homebrew
==> /usr/bin/sudo /bin/mkdir -p /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /bin/chmod g+rwx /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /usr/sbin/chown shahazzat /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /usr/bin/chgrp admin /opt/homebrew/bin /opt/homebrew/etc /opt/homebrew/include /opt/homebrew/lib /opt/homebrew/sbin /opt/homebrew/share /opt/homebrew/var /opt/homebrew/opt /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions /opt/homebrew/var/homebrew /opt/homebrew/var/homebrew/linked /opt/homebrew/Cellar /opt/homebrew/Caskroom /opt/homebrew/Frameworks
==> /usr/bin/sudo /usr/sbin/chown -R shahazzat:admin /opt/homebrew
==> /usr/bin/sudo /bin/mkdir -p /Users/shahazzat/Library/Caches/Homebrew
==> /usr/bin/sudo /bin/chmod g+rwx /Users/shahazzat/Library/Caches/Homebrew
==> /usr/bin/sudo /usr/sbin/chown -R shahazzat /Users/shahazzat/Library/Caches/Homebrew
==> Searching online for the Command Line Tools
==> /usr/bin/sudo /usr/bin/touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
==> Installing Command Line Tools for Xcode-12.5
==> /usr/bin/sudo /usr/sbin/softwareupdate -i Command\ Line\ Tools\ for\ Xcode-12.5
Software Update Tool

Finding available software

Downloading Command Line Tools for Xcode
Downloaded Command Line Tools for Xcode
Installing Command Line Tools for Xcode
Done with Command Line Tools for Xcode
Done.
==> /usr/bin/sudo /bin/rm -f /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
Password:
==> /usr/bin/sudo /usr/bin/xcode-select --switch /Library/Developer/CommandLineTools
==> Downloading and installing Homebrew...
remote: Enumerating objects: 182601, done.
remote: Counting objects: 100% (331/331), done.
remote: Compressing objects: 100% (164/164), done.
remote: Total 182601 (delta 166), reused 300 (delta 156), pack-reused 182270
Receiving objects: 100% (182601/182601), 48.40 MiB | 3.20 MiB/s, done.
Resolving deltas: 100% (135455/135455), done.
From https://github.com/Homebrew/brew
 * [new branch]          dependabot/bundler/Library/Homebrew/sorbet-0.5.6386 -> origin/dependabot/bundler/Library/Homebrew/sorbet-0.5.6386
 * [new branch]          master                                              -> origin/master
 * [new tag]             0.1                                                 -> 0.1
 * [new tag]             0.2                                                 -> 0.2
 * [new tag]             0.3                                                 -> 0.3
 * [new tag]             0.4                                                 -> 0.4
 * [new tag]             0.5                                                 -> 0.5
 * [new tag]             0.6                                                 -> 0.6
 * [new tag]             0.7                                                 -> 0.7
 * [new tag]             0.7.1                                               -> 0.7.1
 * [new tag]             0.8                                                 -> 0.8
 * [new tag]             0.8.1                                               -> 0.8.1
 * [new tag]             0.9                                                 -> 0.9
 * [new tag]             0.9.1                                               -> 0.9.1
 * [new tag]             0.9.2                                               -> 0.9.2
 * [new tag]             0.9.3                                               -> 0.9.3
 * [new tag]             0.9.4                                               -> 0.9.4
 * [new tag]             0.9.5                                               -> 0.9.5
 * [new tag]             0.9.8                                               -> 0.9.8
 * [new tag]             0.9.9                                               -> 0.9.9
 * [new tag]             1.0.0                                               -> 1.0.0
 * [new tag]             1.0.1                                               -> 1.0.1
 * [new tag]             1.0.2                                               -> 1.0.2
 * [new tag]             1.0.3                                               -> 1.0.3
 * [new tag]             1.0.4                                               -> 1.0.4
 * [new tag]             1.0.5                                               -> 1.0.5
 * [new tag]             1.0.6                                               -> 1.0.6
 * [new tag]             1.0.7                                               -> 1.0.7
 * [new tag]             1.0.8                                               -> 1.0.8
 * [new tag]             1.0.9                                               -> 1.0.9
 * [new tag]             1.1.0                                               -> 1.1.0
 * [new tag]             1.1.1                                               -> 1.1.1
 * [new tag]             1.1.10                                              -> 1.1.10
 * [new tag]             1.1.11                                              -> 1.1.11
 * [new tag]             1.1.12                                              -> 1.1.12
 * [new tag]             1.1.13                                              -> 1.1.13
 * [new tag]             1.1.2                                               -> 1.1.2
 * [new tag]             1.1.3                                               -> 1.1.3
 * [new tag]             1.1.4                                               -> 1.1.4
 * [new tag]             1.1.5                                               -> 1.1.5
 * [new tag]             1.1.6                                               -> 1.1.6
 * [new tag]             1.1.7                                               -> 1.1.7
 * [new tag]             1.1.8                                               -> 1.1.8
 * [new tag]             1.1.9                                               -> 1.1.9
 * [new tag]             1.2.0                                               -> 1.2.0
 * [new tag]             1.2.1                                               -> 1.2.1
 * [new tag]             1.2.2                                               -> 1.2.2
 * [new tag]             1.2.3                                               -> 1.2.3
 * [new tag]             1.2.4                                               -> 1.2.4
 * [new tag]             1.2.5                                               -> 1.2.5
 * [new tag]             1.2.6                                               -> 1.2.6
 * [new tag]             1.3.0                                               -> 1.3.0
 * [new tag]             1.3.1                                               -> 1.3.1
 * [new tag]             1.3.2                                               -> 1.3.2
 * [new tag]             1.3.3                                               -> 1.3.3
 * [new tag]             1.3.4                                               -> 1.3.4
 * [new tag]             1.3.5                                               -> 1.3.5
 * [new tag]             1.3.6                                               -> 1.3.6
 * [new tag]             1.3.7                                               -> 1.3.7
 * [new tag]             1.3.8                                               -> 1.3.8
 * [new tag]             1.3.9                                               -> 1.3.9
 * [new tag]             1.4.0                                               -> 1.4.0
 * [new tag]             1.4.1                                               -> 1.4.1
 * [new tag]             1.4.2                                               -> 1.4.2
 * [new tag]             1.4.3                                               -> 1.4.3
 * [new tag]             1.5.0                                               -> 1.5.0
 * [new tag]             1.5.1                                               -> 1.5.1
 * [new tag]             1.5.10                                              -> 1.5.10
 * [new tag]             1.5.11                                              -> 1.5.11
 * [new tag]             1.5.12                                              -> 1.5.12
 * [new tag]             1.5.13                                              -> 1.5.13
 * [new tag]             1.5.14                                              -> 1.5.14
 * [new tag]             1.5.2                                               -> 1.5.2
 * [new tag]             1.5.3                                               -> 1.5.3
 * [new tag]             1.5.4                                               -> 1.5.4
 * [new tag]             1.5.5                                               -> 1.5.5
 * [new tag]             1.5.6                                               -> 1.5.6
 * [new tag]             1.5.7                                               -> 1.5.7
 * [new tag]             1.5.8                                               -> 1.5.8
 * [new tag]             1.5.9                                               -> 1.5.9
 * [new tag]             1.6.0                                               -> 1.6.0
 * [new tag]             1.6.1                                               -> 1.6.1
 * [new tag]             1.6.10                                              -> 1.6.10
 * [new tag]             1.6.11                                              -> 1.6.11
 * [new tag]             1.6.12                                              -> 1.6.12
 * [new tag]             1.6.13                                              -> 1.6.13
 * [new tag]             1.6.14                                              -> 1.6.14
 * [new tag]             1.6.15                                              -> 1.6.15
 * [new tag]             1.6.16                                              -> 1.6.16
 * [new tag]             1.6.17                                              -> 1.6.17
 * [new tag]             1.6.2                                               -> 1.6.2
 * [new tag]             1.6.3                                               -> 1.6.3
 * [new tag]             1.6.4                                               -> 1.6.4
 * [new tag]             1.6.5                                               -> 1.6.5
 * [new tag]             1.6.6                                               -> 1.6.6
 * [new tag]             1.6.7                                               -> 1.6.7
 * [new tag]             1.6.8                                               -> 1.6.8
 * [new tag]             1.6.9                                               -> 1.6.9
 * [new tag]             1.7.0                                               -> 1.7.0
 * [new tag]             1.7.1                                               -> 1.7.1
 * [new tag]             1.7.2                                               -> 1.7.2
 * [new tag]             1.7.3                                               -> 1.7.3
 * [new tag]             1.7.4                                               -> 1.7.4
 * [new tag]             1.7.5                                               -> 1.7.5
 * [new tag]             1.7.6                                               -> 1.7.6
 * [new tag]             1.7.7                                               -> 1.7.7
 * [new tag]             1.8.0                                               -> 1.8.0
 * [new tag]             1.8.1                                               -> 1.8.1
 * [new tag]             1.8.2                                               -> 1.8.2
 * [new tag]             1.8.3                                               -> 1.8.3
 * [new tag]             1.8.4                                               -> 1.8.4
 * [new tag]             1.8.5                                               -> 1.8.5
 * [new tag]             1.8.6                                               -> 1.8.6
 * [new tag]             1.9.0                                               -> 1.9.0
 * [new tag]             1.9.1                                               -> 1.9.1
 * [new tag]             1.9.2                                               -> 1.9.2
 * [new tag]             1.9.3                                               -> 1.9.3
 * [new tag]             2.0.0                                               -> 2.0.0
 * [new tag]             2.0.1                                               -> 2.0.1
 * [new tag]             2.0.2                                               -> 2.0.2
 * [new tag]             2.0.3                                               -> 2.0.3
 * [new tag]             2.0.4                                               -> 2.0.4
 * [new tag]             2.0.5                                               -> 2.0.5
 * [new tag]             2.0.6                                               -> 2.0.6
 * [new tag]             2.1.0                                               -> 2.1.0
 * [new tag]             2.1.1                                               -> 2.1.1
 * [new tag]             2.1.10                                              -> 2.1.10
 * [new tag]             2.1.11                                              -> 2.1.11
 * [new tag]             2.1.12                                              -> 2.1.12
 * [new tag]             2.1.13                                              -> 2.1.13
 * [new tag]             2.1.14                                              -> 2.1.14
 * [new tag]             2.1.15                                              -> 2.1.15
 * [new tag]             2.1.16                                              -> 2.1.16
 * [new tag]             2.1.2                                               -> 2.1.2
 * [new tag]             2.1.3                                               -> 2.1.3
 * [new tag]             2.1.4                                               -> 2.1.4
 * [new tag]             2.1.5                                               -> 2.1.5
 * [new tag]             2.1.6                                               -> 2.1.6
 * [new tag]             2.1.7                                               -> 2.1.7
 * [new tag]             2.1.8                                               -> 2.1.8
 * [new tag]             2.1.9                                               -> 2.1.9
 * [new tag]             2.2.0                                               -> 2.2.0
 * [new tag]             2.2.1                                               -> 2.2.1
 * [new tag]             2.2.10                                              -> 2.2.10
 * [new tag]             2.2.11                                              -> 2.2.11
 * [new tag]             2.2.12                                              -> 2.2.12
 * [new tag]             2.2.13                                              -> 2.2.13
 * [new tag]             2.2.14                                              -> 2.2.14
 * [new tag]             2.2.15                                              -> 2.2.15
 * [new tag]             2.2.16                                              -> 2.2.16
 * [new tag]             2.2.17                                              -> 2.2.17
 * [new tag]             2.2.2                                               -> 2.2.2
 * [new tag]             2.2.3                                               -> 2.2.3
 * [new tag]             2.2.4                                               -> 2.2.4
 * [new tag]             2.2.5                                               -> 2.2.5
 * [new tag]             2.2.6                                               -> 2.2.6
 * [new tag]             2.2.7                                               -> 2.2.7
 * [new tag]             2.2.8                                               -> 2.2.8
 * [new tag]             2.2.9                                               -> 2.2.9
 * [new tag]             2.3.0                                               -> 2.3.0
 * [new tag]             2.4.0                                               -> 2.4.0
 * [new tag]             2.4.1                                               -> 2.4.1
 * [new tag]             2.4.10                                              -> 2.4.10
 * [new tag]             2.4.11                                              -> 2.4.11
 * [new tag]             2.4.12                                              -> 2.4.12
 * [new tag]             2.4.13                                              -> 2.4.13
 * [new tag]             2.4.14                                              -> 2.4.14
 * [new tag]             2.4.15                                              -> 2.4.15
 * [new tag]             2.4.16                                              -> 2.4.16
 * [new tag]             2.4.2                                               -> 2.4.2
 * [new tag]             2.4.3                                               -> 2.4.3
 * [new tag]             2.4.4                                               -> 2.4.4
 * [new tag]             2.4.5                                               -> 2.4.5
 * [new tag]             2.4.6                                               -> 2.4.6
 * [new tag]             2.4.7                                               -> 2.4.7
 * [new tag]             2.4.8                                               -> 2.4.8
 * [new tag]             2.4.9                                               -> 2.4.9
 * [new tag]             2.5.0                                               -> 2.5.0
 * [new tag]             2.5.1                                               -> 2.5.1
 * [new tag]             2.5.10                                              -> 2.5.10
 * [new tag]             2.5.11                                              -> 2.5.11
 * [new tag]             2.5.12                                              -> 2.5.12
 * [new tag]             2.5.2                                               -> 2.5.2
 * [new tag]             2.5.3                                               -> 2.5.3
 * [new tag]             2.5.4                                               -> 2.5.4
 * [new tag]             2.5.5                                               -> 2.5.5
 * [new tag]             2.5.6                                               -> 2.5.6
 * [new tag]             2.5.7                                               -> 2.5.7
 * [new tag]             2.5.8                                               -> 2.5.8
 * [new tag]             2.5.9                                               -> 2.5.9
 * [new tag]             2.6.0                                               -> 2.6.0
 * [new tag]             2.6.1                                               -> 2.6.1
 * [new tag]             2.6.2                                               -> 2.6.2
 * [new tag]             2.7.0                                               -> 2.7.0
 * [new tag]             2.7.1                                               -> 2.7.1
 * [new tag]             2.7.2                                               -> 2.7.2
 * [new tag]             2.7.3                                               -> 2.7.3
 * [new tag]             2.7.4                                               -> 2.7.4
 * [new tag]             2.7.5                                               -> 2.7.5
 * [new tag]             2.7.6                                               -> 2.7.6
 * [new tag]             2.7.7                                               -> 2.7.7
 * [new tag]             3.0.0                                               -> 3.0.0
 * [new tag]             3.0.1                                               -> 3.0.1
 * [new tag]             3.0.10                                              -> 3.0.10
 * [new tag]             3.0.11                                              -> 3.0.11
 * [new tag]             3.0.2                                               -> 3.0.2
 * [new tag]             3.0.3                                               -> 3.0.3
 * [new tag]             3.0.4                                               -> 3.0.4
 * [new tag]             3.0.5                                               -> 3.0.5
 * [new tag]             3.0.6                                               -> 3.0.6
 * [new tag]             3.0.7                                               -> 3.0.7
 * [new tag]             3.0.8                                               -> 3.0.8
 * [new tag]             3.0.9                                               -> 3.0.9
 * [new tag]             3.1.0                                               -> 3.1.0
 * [new tag]             3.1.1                                               -> 3.1.1
 * [new tag]             3.1.2                                               -> 3.1.2
 * [new tag]             3.1.3                                               -> 3.1.3
 * [new tag]             3.1.4                                               -> 3.1.4
 * [new tag]             3.1.5                                               -> 3.1.5
HEAD is now at 64b6846d6 Merge pull request #11346 from jbampton/fix-spelling
==> Tapping homebrew/core
remote: Enumerating objects: 954340, done.
remote: Counting objects: 100% (36/36), done.
remote: Compressing objects: 100% (25/25), done.
remote: Total 954340 (delta 20), reused 22 (delta 11), pack-reused 954304
Receiving objects: 100% (954340/954340), 382.32 MiB | 3.00 MiB/s, done.
Resolving deltas: 100% (648783/648783), done.
From https://github.com/Homebrew/homebrew-core
 * [new branch]            master     -> origin/master
HEAD is now at d82dff1ab1 helmsman: update 3.6.10 bottle.
Warning: /opt/homebrew/bin is not in your PATH.
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (or will be during this `install` run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Add Homebrew to your PATH in /Users/shahazzat/.zprofile:
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/shahazzat/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run `brew help` to get started
- Further documentation: 
    https://docs.brew.sh
shahazzat@Mohammads-MacBook-Pro ~ % shahazzat@Mohammads-MacBook-Pro ~ % brew help
zsh: command not found: brew
```
## Add Homebrew to your PATH in ```/Users/shahazzat/.zprofile```
```
shahazzat@Mohammads-MacBook-Pro ~ % echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/shahazzat/.zprofile
shahazzat@Mohammads-MacBook-Pro ~ % eval "$(/opt/homebrew/bin/brew shellenv)"
shahazzat@Mohammads-MacBook-Pro ~ % brew help
Example usage:
  brew search TEXT|/REGEX/
  brew info [FORMULA|CASK...]
  brew install FORMULA|CASK...
  brew update
  brew upgrade [FORMULA|CASK...]
  brew uninstall FORMULA|CASK...
  brew list [FORMULA|CASK...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA|CASK

Contributing:
  brew create URL [--no-fetch]
  brew edit [FORMULA|CASK...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
shahazzat@Mohammads-MacBook-Pro ~ % 
```
## Check cache
```
shahazzat@Mohammads-MacBook-Pro ~ % brew --cache
/Users/shahazzat/Library/Caches/Homebrew
shahazzat@Mohammads-MacBook-Pro ~ % 

/System/Volumes/Data/Users/shahazzat/Library/Caches/Homebrew/downloads/fd593d01c4cf064cd749cb3662af7f99b9a3ccec253c256430d5fb14cd0e3cdf--gimp-2.10.22-x86_64-3.dmg

shahazzat@Mohammads-MacBook-Pro ~ % ls ~/Library/Caches/Homebrew
Cask				descriptions.json		external_commands_list.txt
all_commands_list.txt		downloads
shahazzat@Mohammads-MacBook-Pro ~ % ls ~/Library/Caches/Homebrew/Cask 
appcleaner--3.6.0,4070.zip	gimp--2.10.22.dmg		vlc--3.0.14.dmg
shahazzat@Mohammads-MacBook-Pro ~ % 
```
## Install virtualbox
```
shahazzat@Mohammads-MacBook-Pro ~ % brew install --cask virtualbox
Updating Homebrew...
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/core and homebrew/cask).
==> New Formulae
clazy             elan-init         gitbackup         ipinfo-cli        mathlibtools      neovim-remote
==> Updated Formulae
Updated 183 formulae.
==> New Casks
jgrennison-openttd         mem                        privileges                 vamiga
==> Updated Casks
Updated 174 casks.

==> Caveats
virtualbox requires a kernel extension to work.
If the installation fails, retry after you enable it in:
  System Preferences → Security & Privacy → General

For more information, refer to vendor documentation or this Apple Technical Note:
  https://developer.apple.com/library/content/technotes/tn2459/_index.html

==> Downloading https://download.virtualbox.org/virtualbox/6.1.22/VirtualBox-6.1.22-144080-OSX.dmg
######################################################################## 100.0%
==> Installing Cask virtualbox
==> Running installer for virtualbox; your password may be necessary.
Package installers may write to any location; options such as `--appdir` are ignored.
Password:
installer: Package name is Oracle VM VirtualBox
installer: choices changes file '/private/tmp/choices20210519-30509-5env23.xml' applied
installer: Installing at base path /
installer: The install was successful.
🍺  virtualbox was successfully installed!
shahazzat@Mohammads-MacBook-Pro ~ % 
```
## Uninstall application (virtualbox)
```
shahazzat@Mohammads-MacBook-Pro ~ % brew list

==> Casks
appcleaner	gimp		google-chrome	skype		virtualbox	vlc
shahazzat@Mohammads-MacBook-Pro ~ % brew uninstall virtualbox
==> Uninstalling Cask virtualbox
==> Running uninstall script VirtualBox_Uninstall.tool
Password:

Welcome to the VirtualBox uninstaller script.

Executing: /usr/bin/kmutil showloaded --list-only --bundle-identifier org.virtualbox.kext.VBoxUSB
No variant specified, falling back to release
Executing: /usr/bin/kmutil showloaded --list-only --bundle-identifier org.virtualbox.kext.VBoxNetFlt
No variant specified, falling back to release
Executing: /usr/bin/kmutil showloaded --list-only --bundle-identifier org.virtualbox.kext.VBoxNetAdp
No variant specified, falling back to release
Executing: /usr/bin/kmutil showloaded --list-only --bundle-identifier org.virtualbox.kext.VBoxDrv
No variant specified, falling back to release
The following files and directories (bundles) will be removed:
    /Users/shahazzat/Library/LaunchAgents/org.virtualbox.vboxwebsrv.plist
    /usr/local/bin/VirtualBox
    /usr/local/bin/VirtualBoxVM
    /usr/local/bin/VBoxManage
    /usr/local/bin/VBoxVRDP
    /usr/local/bin/VBoxHeadless
    /usr/local/bin/vboxwebsrv
    /usr/local/bin/VBoxBugReport
    /usr/local/bin/VBoxBalloonCtrl
    /usr/local/bin/VBoxAutostart
    /usr/local/bin/VBoxDTrace
    /usr/local/bin/vbox-img
    /Library/Python/2.7/site-packages/vboxapi/VirtualBox_constants.py
    /Library/Python/2.7/site-packages/vboxapi/VirtualBox_constants.pyc
    /Library/Python/2.7/site-packages/vboxapi/__init__.py
    /Library/Python/2.7/site-packages/vboxapi/__init__.pyc
    /Library/Python/2.7/site-packages/vboxapi-1.0-py2.7.egg-info
    /Library/Python/2.7/site-packages/vboxapi/

And the traces of following packages will be removed:
    org.virtualbox.pkg.vboxkexts
    org.virtualbox.pkg.virtualbox
    org.virtualbox.pkg.virtualboxcli

The uninstallation processes requires administrative privileges
because some of the installed files cannot be removed by a normal
user. You may be prompted for your password now...

Successfully unloaded VirtualBox kernel extensions.
Forgot package 'org.virtualbox.pkg.vboxkexts' on '/'.
Forgot package 'org.virtualbox.pkg.virtualbox' on '/'.
Forgot package 'org.virtualbox.pkg.virtualboxcli' on '/'.
Done.
==> Uninstalling packages; your password may be necessary:
==> Removing files:
/usr/local/bin/vboximg-mount
==> Purging files for version 6.1.22,144080 of Cask virtualbox
shahazzat@Mohammads-MacBook-Pro ~ % brew list                

==> Casks
appcleaner	gimp		google-chrome	skype		vlc
shahazzat@Mohammads-MacBook-Pro ~ %
```
