# Sublime Text 3

##How to install Package Control

There is an alpha quality release of Package Control for Sublime Text 3 available. Please note that it currently functions the same as for ST2, however there will be changes in the future to properly support the new preferred method of keeping .sublime-package files on disk instead of extracting them to the Packages/ folder.

Please use GitHub issues and prefix all bug titles with ST3: .

### Git Install (MAC ONLY)

Since Sublime Text 3 no longer extracts the contents of .sublime-package files by default, and the fact that Package Control needs to read CA cert files from disk for SSL certificate verification, the only viable install method right now is via Git.

	cd ~/Library/"Application Support"/"Sublime Text 3"/Packages
	git clone https://github.com/wbond/sublime_package_control.git "Package Control"
	cd "Package Control"
	git checkout python3
	
	
[Source](http://wbond.net/sublime_packages/package_control/installation)
