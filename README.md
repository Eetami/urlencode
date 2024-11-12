# URL Encode & Decide

A simple URL encoder and decoder written in bash.

The scripts read a single line from stdin and applies URL encoding/decoding to it.

## urlencode arguments

-h : Print help

-i : Don't URL encode given characters

## urldecode arguments

-h : Print help

## Example

```console
$ urlencode -i 'äö' <<<"pääkkösen paja"
pääkkösen%20paja

$ urldecode <<<"p%E4%E4kk%F6sen%20paja"
pääkkösen paja
```
