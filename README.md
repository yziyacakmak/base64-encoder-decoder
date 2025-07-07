# base64-encoder-decoder

The base64 scale starts with all ASCII uppercase letters (A to Z) which represents the first 25 indexes in this scale (0 to 25). 
After that, we have all ASCII lowercase letters (a to z), which represents the range 26 to 51 in the scale. 
After that, we have the one digit numbers (0 to 9), which represents the indexes from 52 to 61 in the scale. Finally, the last two indexes in the scale (62 and 63) are represented by the characters + and /, respectively.

These are the 64 characters that compose the base64 scale. The equal sign character (=) is not part of the scale itself, but it is a special character in the base64 encoding system. This character is used solely as a suffix, to mark the end of the character sequence, or, to mark the end of meaningful characters in the sequence.

The bullet points below summarises the base64 scale:
range 0 to 25 is represented by: ASCII uppercase letters -> [A-Z];
range 26 to 51 is represented by: ASCII lowercase letters -> [a-z];
range 52 to 61 is represented by: one digit numbers -> [0-9];
index 62 and 63 are represented by the characters + and /, respectively;
the character = represents the end of meaningful characters in the sequence;

>[-Source](https://pedropark99.github.io/zig-book/Chapters/01-base64.html)
