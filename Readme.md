# Pasty

Echos the clipboard to std out on each change.

## Usage

Run `pasty` and `youtube-dl` in the background to download each copied URL in the background to an audio file


```
./pasty | xargs -n1 youtube-dl -x

```


Run `pasty` to append each copied string into a file

```
./pasty >> myfile.txt
```