# HTS-STEGO
Hack this site stego solution
# Mission level 1
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/1)

![Mission 1](https://github.com/Cronic7/HTS-STEGO/blob/master/file/a.png?raw=true)

**HINT**: This is an encoded message, the only tip you get is '2 null bytes'
# solution
Open the picture in a hex editor and search for two null bytes.

![hex_editor](https://github.com/Cronic7/HTS-STEGO/blob/master/file/hex.PNG)

converting 16 to binary shows 0 as least significant bit
Binary convertor link [here](https://www.rapidtables.com/convert/number/hex-to-binary.html)

![hex to binary](https://github.com/Cronic7/HTS-STEGO/blob/master/file/16.PNG)

converting 17 to binary shows 1 as least significant bit

![hex to binary](https://github.com/Cronic7/HTS-STEGO/blob/master/file/17.PNG)

Now replace 16 with 0 and 17 with 1 .As we know that every 8-bit binary digits represent one ASCII character. Therefore, one bit is missing. After some hit and trials, I found that the missing bit is the trailing 0 of the first character. Now, after decoding the binary we get the password.

Binary to ASCII convertor link [here](https://www.binaryhexconverter.com/binary-to-ascii-text-converter)

![Binary to ascii](https://github.com/Cronic7/HTS-STEGO/blob/master/file/as.PNG?raw=true)

| binary | char | 
|--------|------|
|00111000|8|
|00110011|3|
|00110111|7|
|01101000|h|
|01100001|a|
|01110011|s|
|00110110|6|

Password = **837has6**

----
