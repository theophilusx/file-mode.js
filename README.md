
# Table of Contents

1.  [file-mode.js](#org7bf4d4e)


<a id="org7bf4d4e"></a>

# file-mode.js

I often want to extract details regarding a file using the 'mode' property from
the node `fs.stat()` command. However, I always forget the structure and bit
mask details. This is a very simple utility to make this a little easier. 

There are probably other utilities out there which do the same thing and
probably written in a more concise and clearer manner. However, part of learning
is doing. I have also written this in a way which should make it easy for me to
cut and paste when I need this type of functionality. 

This has only been tested on Linux. I know little about Windows and expect it
will work OK on macOS. 

