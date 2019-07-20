The details of this command line tool is given on this [blog-post](http://tworitdash.in/2019/07/19/image-compression-using-singular-value-decomposition.html).

#### Usage:

Install it via pip with the following command:

	pip install compressjpg


It installs the dependencies like `numpy` and `scipy`. 

After the successful installation one can use it like the following directly from the terminal:

	compress-jpg  -i input_file.jpg -o output_file.jpg -p <% Of truncation you want>

Where the flag `-i` means input and `-o` means output.

The option `-p` is optional. If you don't use it, it automatically does it with 50% truncation. I will try to do it with a better logic where it checks the dB values so that it can become immune to different images. 

