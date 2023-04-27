# SHA-1

An implementation of the SHA-1 hashing algorithm in pure python. 

This library was designed to demonstrate a straight-forward implementation of
the algortihm, and is not designed for speed. The current implementation
matches the [hashlib](https://docs.python.org/3/library/hashlib.html) api. 


## Usage

The library may be called from the command line.
Message input may be piped in stdin:

    $ echo hello | python sha1.py
    sha1-digest: f572d396fae9206628714fb2ce00f72e94f2258f


One or more files may also be specified as arguments to the script:
 
     $ python sha1.py myfile myfile2
     sha1-digest: 3f786850e387550fdab836ed7e6dc881de23001b
     sha1-digest: 57a9901af6fe030198ef1737783e2048ee96da4a
