## Problem info
<table>
  <tr>
    <td><strong>Name</strong></td>
    <td>Intro to Netcat</td>
  </tr>
  <tr>
    <td><strong>Category</strong></td>
    <td>Pwn</td>
  </tr>
  <tr>
    <td><strong>Flags</strong></td>
    <td>hsctf{internet_cats}</td>
  </tr>
  <tr>
    <td><strong>Files</strong></td>
    <td></td>
  </tr>
  <tr>
    <td><strong>Hints</strong></td>
    <td></td>
  </tr>
</table>

#### Message :

Written by: Ptomerty
Hey there! This challenge is a quick introduction to netcat and how to use it. Netcat is a program that will help you "talk" with many of our challenges, especially pwn and misc. To begin, Windows users should download this file: https://drive.google.com/open?id=1Z8MS8SZYqZrteXOVPRL7BHwB4JL9t9J8

Extract the file, then open a command prompt and navigate to the directory using `cd <download-directory>`. From there, you can run `nc misc.hsctf.com 1111` to get your first flag.

Have fun!

## Problem info
simply run `nc misc.hsctf.com 1111` in bash and gets the flag.
```
$ nc misc.hsctf.com 1111
Hey, here's your flag! hsctf{internet_cats}
```
