# cprint
A small code printing utility

Dependencies: a2ps, python. Also Ghostscript if you want to save as PDF.

Usage: cprint [-h header] [-o outfile] [-p printer] file(s)

    -h, -header
        Give a header that will be printed at the start of the file. Use
        '<hline>' to draw a horizontal line.
    -p, -printer
        Give a printer to print the document on. This will override any given
        '-o' option.
        NOTE: No default printer is selected! You have to specify this if you
        want to print.
    -o, -output
        Don't print it, but instead output it to the specified location. Default
        is 'file.pdf' in the current working dir. (Ghostscript required)
