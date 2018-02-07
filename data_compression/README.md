# Data Compression {#data-compression}

The idea of data compression is maximizing storage efficiency by minimizing the distribution of data, in this case of computer science, binary distribution. There are two methods to do data compression: **Lossless** which avoid data losses in compressed result and **Lossy** which tolerate data losses within predicted rate. An important fact in data compression is **we can not built an universal data compression**.

We used bitstream (BinaryStdIn) rather than input stream (In) because in the case of compression algorithm we need to read each bit rater than each byte._BinaryStdIn.java_, _BinaryStdOut.java_, _BinaryDump.java_, etc can be found at https://algs4.cs.princeton.edu/55compression/.