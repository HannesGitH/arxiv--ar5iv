# Automatic arxiv->ar5iv link replacement in Chrome.

This chrome extension will automatically replace arxiv.org/pdf/* links with ar5iv links for more web-friendly reading.

## Installation

1. Clone the repo

``` git@github.com:yobibyte/rct.git```

2. Go to `chrome://extensions/` and turn on the developer mode

3. Press to `Load unpacked` and select the repo folder to open.

## Usage

The extension will automatically replace Arxiv pdf links with ar5iv. If you want to still load the pdf, add the question mark to the link:

```
# this will open ar5iv
https://arxiv.org/pdf/2010.01856.pdf

# this will open a pdf file
https://arxiv.org/pdf/2010.01856.pdf?

```