# Parsedown/Markdown

## Content

- [Installation - how to install](#installation)
- [Extension - how to configure](#configuration)
- [Usage - how to use](#usage)

## Installation

```sh
composer require contributte/latte-parsedown-extra
```

## Configuration

```yaml
extensions:
    parsedown: Contributte\Parsedown\DI\ParsedownExtraExtension

parsedown:
    # Default name is parsedown
    helper: parsedown # Name of the helper in Latte
```

## Usage

```smarty
{block|parsedown}
# Headline

## Headline2

This is my text!

{/block}
```
