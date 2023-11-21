# JetBrains binds

## Installation

```shell
cp .jb-binds ~/.jb-binds
```

Add these lines in `~/.bashrc` or `~/.zshrc`

```shell
source ~/.jb-binds
```

## Usage
```shell
codep ~/projects/some-php-project         # PHPStorm
codew ~/projects/some-html-js-css-project # WebStorm
codecl ~/projects/some-cpp-project        # CLion
coder ~/projects/some-c-sharp-project     # Rider
```

## More IDE
You can add any JetBrains IDE by adding new alias in your `~/.bashrc` or `~/.zshrc`
Example:
```shell
alias codei="__code intellij" # Intellij
```
