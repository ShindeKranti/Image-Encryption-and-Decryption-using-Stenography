# Image-Encryption-and-Decryption-using-Stenography
Developed a system to hide and retrieve secret messages within images using steganography UsingPython.Implemented encryption techniques to securely embed data inside images.Designed a decryption module to extract hidden messages without altering the image quality.Used Python libraries for image processing and data encoding.
## What it does
We accept a user input image. The image is then transformed using our hardest-ever yet beautiful algorithm (ECC algorithm) and encoded into a Golden Record which is the only unique disk in the world. Even the same picture would be rendered into two different disks if a different person conducts the encryption, and each picture would have a unique private key associated with it. Of course, with our beautiful algorithm, we are able to translate the message engraving on the disk and transform it back into the original image. Come with your lovely picture and get your disk.

## How to use it
Using an IDE, you need to first enable the python flask. Run the app.py file, in the command line, you should see a localhost address. Proceed to that address by right-clicking and selecting the link and following the instruction as mentioned.


## Challenges we ran into
It was hard to fully integrate front end with back end. Moreover, we had difficulties understanding the ECC’s rationale and the instability of the decipher for the self-implemented ECC algorithm at the beginning of the project. It was also difficult to maintain information of the image as much as possible while achieving the most random and diverse transformations in a reasonable amount of time, so as to integrate the google cloud service.

