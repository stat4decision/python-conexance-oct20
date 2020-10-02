SOMPY
=====

A Python Library for Self Organizing Map (SOM)

As much as possible, the structure of SOM is similar to somtoolbox in Matlab. It has the following functionalities:

1- Only Batch training, which is faster than online training. It has parallel processing option similar to sklearn format and it speeds up the training procedure, but it depends on the data size and mainly the size of the SOM grid.I couldn't manage the memory problem and therefore, I recommend single core processing at the moment. But nevertheless, the implementation of the algorith is carefully done for all those important matrix calculations, such as scipy sparse matrix and numexpr for calculation of Euclidean distance.  
2- PCA (or RandomPCA (default)) initialization, using sklearn or random initialization.  
3- component plane visualization (different modes).
4- Hitmap.  
5- U-Matrix visualization.  
6- 1-d or 2-d SOM with only rectangular, planar grid. (works well in comparison with hexagonal shape, when I was checking in Matlab with somtoolbox).  
7- Different methods for function approximation and predictions (mostly using Sklearn).

I must say that I am a bit lazy for documentation, but below are few examples showing how to use the library. But there are more functionalities, which are not documented yet. I suggest you go through the code itself.

http://bit.ly/1eZvaCM

http://bit.ly/1DHdLpn

http://bit.ly/1zfn77s

http://vahidmoosavi.com/2014/02/18/a-self-organizing-map-som-package-in-python-sompy/

http://bit.ly/1ujaD36

For more information, you can contact me via sevamoo@gmail.com or svm@arch.ethz.ch
