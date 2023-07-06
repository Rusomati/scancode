# scancode
a tool to search for keywords in codebases..
expected to run on any unix system that uses the gnu userland and bash
# note
the program scans the working directory as i am too lazy to
add the directory-to-scan as an argument
# installation
note: 
this code is not tested because i am too lazy
``git clone https://github.com/Rusomati/scancode;sudo mv scancode /bin/scancode;rm -rf scancode``
# usage
``scancode [the extention that you want to scan] [keyword]``
eg:
``scancode c malloc``
opens every file that ends in .c in every subfolder then outputs the line including the keyword (if any)

wow my explanation sucks


example output:
``in main.c:``

``62 malloc(blablabla);//i forgot how to use malloc``

``84 malloc(asdfg);``

``in temp/loadimage.c:``

``112 malloc(wowowowowow);``
