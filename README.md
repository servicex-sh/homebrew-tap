# Homebrew Formula

## How do I install these formulae?
`brew tap servicex-sh/tap` then `brew install --no-quarantine servicex-sh/tap/httpx`

```
brew install https://raw.githubusercontent.com/servicex-sh/homebrew-tap/master/Formula/httpx.rb
```

If you are using macOS Catalina or later you may need to remove the quarantine attribute from the bits before you can use the httpx binaries. To do this, run the following:


```
$ brew install --no-quarantine servicex-sh/tap/httpx
$ brew reinstall --no-quarantine servicex-sh/tap/httpx
```
or 

```
$ sudo xattr -r -d com.apple.quarantine $(readlink -f $(brew --prefix httpx))/bin/httpx
```

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
