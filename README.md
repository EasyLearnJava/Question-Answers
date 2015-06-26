# Question & Answers

<b> Core Java </b>

***
* Difference between a Thread and a Process
```
* Threads are part of process(A process can contain multiple threads).
* Every Process has its own memory space, executable code and unique process id, while every thread has its own stack in Java but it uses process main memory and share it with other threads.
* Threads from same process can communicate with each other by using Programming language construct like wait and notify in Java

NOTE: Each thread in java has it's own stack which is used for storing runtime data.
      Thread stack has a specific size
      StackOverflow error is thrown if a thread tries to store more items on the stack, than the specified size of the stack.
      
      Default stack size is 256KB
      To change the thread stack size use the -Xss command
      java -Xss:512k MyApp
```

***

* Why is String immutable in java

* Explain how substring works in java

* Why character array is preferred for storing passwords when comapred to String
