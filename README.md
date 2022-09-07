# macosx
macosx


## Remove boot starting application

* Preferences -> Users & Groups -> Select the user -> Remove with -
* /Library/LaunchAgents  -> Remove the App

## Change desktop icon size
* click on the desktop + APPLE CMD + j

## Homebrew errors
```
$ brew -v
Traceback (most recent call last):
	11: from /usr/local/Homebrew/Library/Homebrew/brew.rb:31:in `<main>'
	10: from /usr/local/Homebrew/Library/Homebrew/brew.rb:31:in `require_relative'
	 9: from /usr/local/Homebrew/Library/Homebrew/global.rb:80:in `<top (required)>'
	 8: from /usr/local/Homebrew/Library/Homebrew/vendor/portable-ruby/2.6.3_2/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
	 7: from /usr/local/Homebrew/Library/Homebrew/vendor/portable-ruby/2.6.3_2/lib/ruby/2.6.0/rubygems/core_ext/kernel_require.rb:54:in `require'
	 6: from /usr/local/Homebrew/Library/Homebrew/os.rb:7:in `<top (required)>'
	 5: from /usr/local/Homebrew/Library/Homebrew/os.rb:43:in `<module:OS>'
	 4: from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:60:in `prerelease?'
	 3: from /usr/local/Homebrew/Library/Homebrew/os/mac.rb:28:in `version'
	 2: from /usr/local/Homebrew/Library/Homebrew/os/mac/version.rb:32:in `from_symbol'
	 1: from /usr/local/Homebrew/Library/Homebrew/os/mac/version.rb:32:in `fetch'
/usr/local/Homebrew/Library/Homebrew/os/mac/version.rb:32:in `block in from_symbol': unknown or unsupported macOS version: :dunno (MacOSVersionError)
```
=> 
```
brew update-reset

```
