# URL Encode

A simple URL encoder written in bash.

The scripts reads a single line from stdin and applies urlencoding to it.

## Arguments

-h : Print help

-i : Don't URL encode given characters

## Example

```console
$ urlencode -i 'äö' <<<"pääkkösen paja"
pääkkösen%20paja
```
