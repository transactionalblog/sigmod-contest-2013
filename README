ACM SIGMOD 2013 Programming Contest
© 2013 KAUST - InfoCloud group
Amin Allam  <amin.allam@kaust.edu.sa>
Fuad Jamour <fuad.jamour@kaust.edu.sa>


=============================================

ACM SIGMOD 2013 Programming Contest

=============================================

This readme file contains information about using the contents of this archive
to build and test your contest submission.

The task details of the contest can be found at:
http://sigmod.kaust.edu.sa/

----------------------------------------------
-                  Contents                  -
----------------------------------------------
Included in this release are the following files and directories:
  - README                        This document
  - Makefile                      Makefile to compile and link the provided source code
  - include/core.h                The API that must be implemented by the contestants
  - ref_impl/                     Contains an example implementation of the task interface
  - test_data/                    Contains example data files, used by the test driver
  - test_driver/                  Contains the test driver implementation. This
                                  program will test correctness of the task
                                  implementation and measures its runtime
                                  
----------------------------------------------
-               Getting started              -
----------------------------------------------
The interface that has to be implemented is described in include/core.h.
The detailed description of each function is included in the 
file itself. So core.h has all what you need to start writing a working
implementation.

The example implementation available in ref_impl/ is provided
to further clarify the task requirements, as it produces correct results
based on the provided task details. The example implementation is slow
as it doesn't use any smart data structures/algorithms. A good implementation
is expected to be much faster than the provided example implementation.

----------------------------------------------
-         Testing your implementation        -
----------------------------------------------
A Makefile is provided to compile all the provided code.
Calling
    > make
will produce a shared library (libcore.so) that is 
later linked to the test driver's code, in addition to 
the test driver binary (testdriver). The shared library
file (libcore.so) is what you are supposed to submit online
when the leaderboard becomes available.

To run the example implementation and measure its performance
all you have to do is:
    > make
    > ./testdriver
The program (testdriver) will run the task implementation on 
the workload specified by test_data/small_test.txt and produce
a simple output that will show the runtime for the implementation
if it has correctly passed all tests.

To test your own implementation you need to modify the provided
Makefile to compile it instead of the code in ref_impl/
Once you compile your implementation, testdriver can be used
to test its correctness and measure its performance. In case
an incorrect result is returned, testdriver will tell where 
the error happened to help you debug your code.

Please note that the test driver does both correctness testing
and performance evaluation. Each result returned by your implementation
is tested for correctness by testdriver.   
