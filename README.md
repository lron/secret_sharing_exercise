# Secret Sharing exercise

We’ll be using the Ubuntu library **libgfshare**, which you can install in any Unix machine. 

In Linux, you can do so by entering the following commands in the terminal:

    sudo apt update
    sudo apt install libgfshare-bin

In Mac, you can use

    brew install libgfshare

The library contains a few command line tools related to using Shamir’s Secret Sharing scheme:

    gfsplit     – splits a file into a number of shares
    gfcombine   – combines a number of shares to form the original file


1. The current repository contains all the existing shares of a secret file. Using the *gfcombine* command, recover the secret file. 

1. How much is the threshold of the scheme? That is, what is the minimum amount of different shares that need to be provided for the gfcombine tool to recover the secret?

1. Once you recover the secret, have a look at the resulting file and compare it to the shares. Is there any information about the secret that could have been guessed from the shares alone? 
