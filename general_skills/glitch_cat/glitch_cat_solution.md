When we use the suggested instruction:

nc saturn.picoctf.net 65353

We get an answer which contains some glitches:

'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'

This seems a python concatenation, if we replace the chr(hex) with their respective symbols we get:

The whole string would be:
picoCTF{gl17ch_m3_n07_9c42a45d}

I used the table on https://www.ascii-code.com.
