### Purpose

This formula installs the Frege REPL. As of this writing there is already one for the Frege _compiler_ but 1) there is not one for the REPL, and 2) the one for the compiler does not include the REPL. Moreover, this formula is set up as a tap since Homebrew has certain restrictions on which formulae can be included the main project based on stars/forks/etc.

### Usage

Just issue the following two commands:

```
brew tap quephird/homebrew-fregerepl
brew install fregerepl
```

Once installed, simply run `frege-repl`. Enjoy!