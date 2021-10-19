# run python files on windows

#### python index.py

# 1 lesson
#### basics of argparse

# #2 lesson

1. basics of cv2(imshow,imread,imwrite,waitKey)
1. channels
1. why its height, width and not width, height
1. rows, columns

### python
* python destructuring
* print formatting

# #3 lesson

1. basics of pixels
1. basics of rgb
1. why its BGR and not RGB in opencv
1. why height, width and y,x and not the other way around
1. how to crop an image, numpy array slicing.
1. how to get top left, top right, bottom left, bottom right of the image

### python

* floor division
* slicing in lists

# #4 lesson

1. you can supply a blank canvas
1. initialize empty canvas
1. numpy.zeros to fill it with black background for an empty canvas
1. how to understand a cv2.image better which is just a multidimensional array with rows columns and channels
1. draw aline
1. draw a rectangle
1. draw a circle
1. numpy random
1. get a random color, get a random radius, get random points(as a tuple)

# #5 translate

# #6 rotate

# #7 resize

1. how to maintain aspect ratio
1. why is it easier to resize from a larger image to a smaller one
1. how to resize from a smaller image to a larger one
1. interpolation methods

# #8 flip

# #9 crop

1. importance of slicing.
1. numpy slicing
1. roi = region of interest (for cropping)
1. numpy slicing image

### python
* python slicing

# #10 image-arithmetic

1. why its important to know image-aritmhetic
1. clipping
1. how subtracting a 100 from an image matrix will make a darker image
1. how adding a 100 from an image matrix will brighten the image
1. different ways to add an substract. cv2.add / cv2. subtract and numpy's alternative
1. which one is less bugg prone and gives more freedom.
1. how to brighten the image
1. how to darken the image

# #11 bitwise

1. the importance
1. AND, OR, XOR, NOT bitwise operations

# #12 masking

1. masking
1. bitwise_and
1. circle,rectangle masking

# #13 splitting-merging

# #14 morphological-operations

1. list of morphological operations
1. structuring element
1. convert to grayscale
1. erosion
1. dilation
1. opening
1. getStructuringElement types
1. closing
1. Morphological gradient
1. white hat(top hat)
1. black hat
1. why are kernel tuples odd numbers (3,3) (5,5) (7,7)

# #15 smoothing,blurring

1. why blur an image
1. what benefits does it give computers
1. what kind of images can we blur and smooth
1. why are kernel tuples odd numbers (3,3) (5,5) (7,7)
1. different types of blurring
1. why gaussian blur is better than normal blur and is a standard one to use
1. Lower level explanation on how normal and gaussian blurring work
1. Median blur and when to use it
1. What's salt-and-pepper noise
1. Bilateral blurring (filtering)
1. Which filter to use when you want to preserve the edges in the image
1. Downside to bilateral blurring
1. cartoon.py