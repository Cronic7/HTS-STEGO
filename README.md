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

# Mission level 2
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/2)

![Mission 2](https://www.hackthissite.org/missions/stego/lvl/2.wav)

**HINT**:did I hear that correctly?  
# solution
Download the audio file.

Audio file consist of whitenoise.

Use Audacity and view the spectrogram of the audio wave.

you will find the password.


Password = **jb298abc9qb2**

----

# Mission level 3
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/3)

![Mission 3](https://www.hackthissite.org/missions/stego/lvl/3.bmp)

**HINT**:Look carefully: it's obvious, just not at first sight 
# solution
Open the photo in Forensically website.

Forensically link [here](https://29a.ch/photo-forensics/#forensic-magnifier)

Check the principal analysis conponent.
you will find the password.




Password = **n38f298hsjf**

----

# Mission level 4
Challenge link [here](https://www.hackthissite.org/missions/stego/template.php)

![Mission 4](https://github.com/Cronic7/HTS-STEGO/blob/master/file/stego4.gif)

**HINT**: I am being hexed!.
# solution
Open the picture in a hex editor and scroll down to bottom.

![hex_editor](https://github.com/Cronic7/HTS-STEGO/blob/master/file/lvl4b.PNG)

Convert the binary to ascii

![Binary to ascii](https://github.com/Cronic7/HTS-STEGO/blob/master/file/lvl4a.PNG)

Password = **p68cq1hb**

----

# Mission level 5
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/5)

![Mission 5](https://www.hackthissite.org/missions/stego/lvl/stego5.bmp)

**HINT**:  
# solution
 


Password = **hgbvZw07**

----
# Mission level 6
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/6)

![Mission 6](https://www.hackthissite.org/missions/stego/lvl/stego6.png)

**HINT**:  
# solution
Extract the strings from the picture
Check the strings you will find code that looks like it is encoded in Base64

code=Tm90IGxpa2UgaXQncyBoYXJkIHRvICdkZWNyeXB0JyB0aGlzIGh1aD8gVGhlIHBhc3N3b3JkIGlzIGhnYnZadzA3Lg==

Decode this code with Base64 decoder\

Decoded=Not like it's hard to 'decrypt' this huh? The password is hgbvZw07.


Password = **hgbvZw07**

----
# Mission level 7
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/7)

[Mission 7](https://www.hackthissite.org/missions/stego/lvl/stego7.zip)

**HINT**:  
# solution

DOwnload and extract the zip file.

It is a .tif extension.

Open the file in photoshop.You will find three layers of the image.

turn off the first layer you will get the password.


 
Password = **4aH5CEta**

----
# Mission level 8
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/8)

![Mission 8](https://www.hackthissite.org/missions/stego/lvl/stego8.bmp)

**HINT**:  
# solution
Open the picture in hex editor.

scroll to the middle.

You will find= p��a��s��s��w��o��r��d��=��Y��r��R��o��t��7


Password = **YrRot7**

----
# Mission level 9
Challenge link [here](https://www.hackthissite.org/missions/playit/stego/9)

Download file[link](https://www.hackthissite.org/missions/stego/lvl/Stego9.zip)

**HINT**:  
# solution
 


Password = **YrRot7**

----
