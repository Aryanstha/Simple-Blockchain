# Blockchain
## A blockchain is a ledger which has been written in such a way that updating the data contained within it becomes very difficult, some say the blockchain is immutable and to all intents and purposes they’re right but immutability suggests permanence and nothing on a hard drive could ever be considered permanent.

<p> In this repo I have develop  simple blockchain with different  programming language just for educational pyrpose.</p>

# Simple-blockchain with c++ <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>  
<a href="https://github.com/Aryanstha/Simple-Blockchain/tree/main/blockchain%20with%20C%2B%2B">Click here..</a>
<p> As with most C/C++ programs, everything is kicked off by calling the main method, this one creates a new blockchain (line 2) and informs the user that a block is being mined by printing to the output buffer (line 4) then creates a new block and adds it to the chain (line 5); the process for mining that block will then kick off until a valid hash is found. Once the block is mined the process is repeated for two more blocks.</p>

<p>Time to run it! If you are using CLion simply hit the ‘Run TestChain’ button in the top right hand corner of the window. If you’re old skool, you can compile and run the program using the following commands from the command line:</p>
```
gcc -lstdc++ \
    -o TestChain \
    -std=c++11 \
    -stdlib=libc++ \
    -x c++ \
    main.cpp Block.cpp Blockchain.cpp sha256.cpp
./blockchain with c++
```


