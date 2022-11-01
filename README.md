# Common-Words
This task is a development of the example that motivated several of the lectures in the unit: finding all the words in text, and from that, the most common word, etc. The program you are to write should be called common_words. With no arguments, the usage summary should be:

Usage: common_words [-w word | -nth N] <directory of text files>

The program will implement two related functions, indicated by the optional arguments -w and -nth, which are mutually exclusive. In both cases, the program also expects a mandatory argument, which is a directory containing text files.

If the optional argument -w, followed by a word, is provided, you must determine the frequency rank for that word in each text file and report the highest rank. Frequency ranks are numbered from 1 for the most common word in a file, 2 for second most common word in that file, etc. The program should report the text file for which the frequency rank of the specified word is highest along with the rank of the word in that file. If there are equal highest ranks, just return the first that your program finds.

If the optional argument -nth, followed by an integer N, is provided, your program is to report the word that is the Nth most common for the largest number of files in the specified directory. Your program must also report the number of files for which that word is Nth most common.

If there are no options, then assume you are being asked for the word that is the most common across the largest number of files, i.e. -nth 1

You can assume that all the text files in the text-file directory have the suffix .txt. As in the examples seen in lectures, for these purposes, a word is a sequence of one or more letters, so even though "common-garden" word-pair is linguistically one word, please treat them as two words. Secondly, unlike the examples in lectures, please preserve letter case. That is, please don't convert every letter to lower case.

In the directory textfiles you can find a selection of texts from the wonderful Project Gutenberg archive of copy-right-free books. 
