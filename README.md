Barotar is a tool for packing and unpacking Barotrauma saved games. A
Barotrauma saved game is a very simple compressed archive format, so it can be
unpacked to files in a directory and repacked from that form. Barotar’s
command-line syntax is inspired by traditional `tar`, though much simplified:

`barotar c /path/to/file.save` creates the specified save file, overwriting it
if it already exists, and packing into it all files in the current directory.

`barotar t /path/to/file.save` lists the files contained in the specified save.

`barotar x /path/to/file.save` extracts the files contained in the specified
save into the current directory, overwriting files that already exist.
