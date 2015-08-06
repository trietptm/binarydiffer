#How to Compile

# Prerequisite #

You need Visual Studio, Microsoft Platform SDK and IDA SDK 5.0.
We will do support versions other than 5.0 later.

# Details #
1.You must get a IDA SDK and edit the Makefile in Plugin.
2.Edit the first line in inst.bat to fit your condition.
3.Run inst.bat in each directory.

Also, you can start a command prompt from visual studio tools menu, it will set the needed env for you, and then you can use nmake to compile.