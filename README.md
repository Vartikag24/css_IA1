# HASHCAT Implementation

Hashcat is a password recovery tool. It had a proprietary code base until 2015, but was then released as open source software. Versions are available for Linux, OS X, and Windows. The hashcat-supported hashing algorithms are LM hashes, MD4, MD5, SHA-family and Unix Crypt formats as well as algorithms used in MySQL and Cisco PIX.

We have implemented our version of HashCat in the Python programming language using the Flask framework.

Hash functions implemented - 
> 1. SHA256
> 2. SHA384
> 3. SHA224
> 4. SHA512
> 5. SHA1
> 6. MD5
> 7. MD4

### Tech Stack
> 1. Python
> 2. HTML5
> 3. CSS3
> 4. Flask

### File Description
> 1. Style.css - CSS code for frontend 
> 2. HashCat.html - HTML code for frontend
> 3. Hashapp.py - Flask program module

### Installation and Execution
urllib3, hashlib and Flask can be installed using pip:

    $ python3 -m pip install urllib3
    
    $ python3 -m pip install hashlib
    
    $ pip install Flask

To run the application, go to the folder with the files and open the command prompt directed to the current directory. Then give the following commands - 

    $ set FLASK_APP = hashapp
    $ flask run

For Output - Go to http://127.0.0.1:5000/ to open the page

---
###### Future Work
There are currently two versions of the tool available: Hashcat and oclHashcat, one to use CPU and one to use GPU. We can expect the final version of Hashcat and the most important news will be the fusion of the two tools. Not only that, but you’ll also be able to utilize both CPU and GPU, even in parallel, and it will support exotic hardware like FPGA and DSP.

###### References
[1] https://www.youtube.com/watch?v=gjAMD_4aV4E
[2] https://www.csoonline.com/article/3542630/hashcat-explained-why-you-might-need-this-password-cracker.html
[3] https://www.youtube.com/watch?v=uZRaeZwzDXE
[4] https://resources.infosecinstitute.com/topic/hashcat-tutorial-beginners/


### Contributors
> * 1811065 Sanika Bagwe <sanika.bagwe@somaiya.edu>
> * 1811071 Jugal Chauhan <jugal.dc@somaiya.edu>
> * 1811081 Vartika Gupta <vartika.g@somaiya.edu>