# Parallel-Processing-Huffman
    This project will take inspiration from this awesome paper!!: https://www.ittc.ku.edu/~jsv/Papers/HoV95.pdcfull.pdf

    This project is a passion idea I came up with awhile back with hopes of trying to learn more about the applications of introducing 
    parallel procressing techniques and structures while learning c/c++ programming. With this project, I hope to introduce parallel 
    processing into the encoding and decoding process, creating compressed files that can only be decoded with programs that recognize 
    the break I will be introducing in between every ~ N/M characters, where N is the total compressed file size and M is the total 
    number of threads I will evaluate the program on. Given that we will be able to split up the encoded character base into
    M groups and result in a compression time Mx times faster than a general huffman encoding counterpart.
