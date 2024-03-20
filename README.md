# Face-Fractals

This repo currently contains pre-computed NSR and NMSID values for sierpinski carpet upto 6 iterations.

## Usage

1. Go to the Google [`Colab notebook`](https://colab.research.google.com/drive/1haXgQ2K-c1hGtKapm4KVJHrzArlEsnlB?usp=sharing).

1. Follow the steps given in the notebook.

1. Upload the corresponding NSR and NMSID files for a particular iteration.

1. Run the code cells.

## TODO

1. Edit the notebook such that an image can be taken as input directly.

1. C++ is used to compute the NMSID as it is faster in that language, could also use numpy in python to generate the NMSID values, now that I think of it.

1. Re-evaluate the fractal dimension for 6th-iteration carpet values.

## DOCS

<em>.nsr</em> and <em>.nmsid</em> files contain values on separate lines.<br><br>
If you want to find out i-th NSR / NMSID value, you would get it at i-th line in the <em>.nsr</em> / <em>.nmsid file</em>.</h3>
