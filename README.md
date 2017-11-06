# ImageProcessingCheck
Some Stuff to help you check you've done image processing correctly

**check.py** This checks your implementations against opencv's
**lena.png** The base image
**lenaClose,Dil,Ero,Open** Correct versions of the outputs
**test.sh** A comprehensive test

# How to test
Put the following in a folder on its own
* test.sh
* check.py
* your erosion.py
* your dilation.py
* your closing.py
* your opening.py
* lena.png

Navigate to the folder in the terminal and run bash test.sh

After it finishes running, you should see
    Erosion Correct
    Dilation Correct
    Opening Correct
    Closing Correct
    
If you don't, you **will** lose marks. If you don't see *Erosion Not Correct* or similar, execution did not finish. This means that your program has crashed. This will probably be obvious. Make sure you are actually listening to the program arguments passed to python, and make sure that your scripts are named correctly (this is specified in the assignment brief)
