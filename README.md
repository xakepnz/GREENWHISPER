# GREENWHISPER

## Description:

This is a simple shell script that extracts certain strings from a file, these could be hidden encoded messages in a jpg, to IPV4 addresses from an ELF, I decided to create this to save a lot of time when attempting Steganography challenges.<br />

<b>[+] Author:</b> xakep<br />
<b>[+] Language:</b> Bash<br />
<b>[+] OS:</b> Linux<br />

## Requirements:

[+] strings<br />
[+] hexdump<br />
[+] egrep<br />
[+] exiftool<br />

## Install:

```
$ git clone https://github.com/xakepnz/GREENWHISPER.git
```

```
$ cd GREENWHISPER
```

```
$ chmod +x greenwhisper
```

# Usage:

```
$ ./greenwhisper my-file.jpg
```

<b>Optional:</b>

```
$ sudo cp greenwhisper /bin/
```

```
$ greenwhisper /steg-challenges/hidden.png
```
