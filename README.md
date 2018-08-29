# past-projects
Descriptions of code I've written before, but that I won't release the code for. Contact me (ahuang98@stanford.edu) if you have questions!

**Shell Code**

Full Unix shell in C++. Features:
- Handles chains of pipes
- Support for foreground jobs that require control of the terminal (vim, emacs, etc.)
- Support for background processes
- Support for stopping/halting/continuing processes
- Support for moving halted processes to the background

**HTTP Proxy and Cache**

Multithreaded proxy and cache in C++. Handles cycles, blacklisting, proxy chaining.

**MapReduce**

Built fully operational MapReduce framework in C++, along with mapper/reducer to create a histogram of words from a piece of text. Coordinated multiple processes across multiple machines.

**Sentiment Analyzer**

Built a simple sentiment analyzer in Python. Used a softmax classifier along with word2vec vectors.

**Neural Transition-Based Dependency Parser**

Established relationships between “head” words and words which modify those heads, by incrementally building
up a parse one step at a time, maintaining a partial parse at each step. The neural network decides the transition at each step. 89.2 UAS (92.5 UAS is state of the art).

**Named-entity Recognition**

Built an RNN-based, and GRU-based, named-entity-recognizer. Implemented RNN and GRU from scratch (i.e., did not use Tensorflow's implementation).



