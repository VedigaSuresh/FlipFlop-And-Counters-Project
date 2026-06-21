# Flip-Flops

## SR Flip-Flop
### Truth Table

| S | R | Q(next) |
|---|---|---------|
|0|0|No Change|
|0|1|0|
|1|0|1|
|1|1|Invalid|

### Applications
- Memory storage
- Sequential circuits

## JK Flip-Flop

The JK Flip-Flop eliminates the invalid state present in the SR Flip-Flop.

Truth Table
J    	K	     Q(next)
0   	0	      No Change
0    	1	       0
1    	0	        1
1	    1	       Toggle


Applications

     * Counters
     * Registers
     * Frequency division circuits

## D Flip-Flop
The D (Data) Flip-Flop transfers input data directly to the output on the clock edge.

Truth Table
D	  Q(next)
0   	0
1   	1

Applications

    *Shift registers
    *Data storage
     *Memory devices


## T Flip-Flop
The T (Toggle) Flip-Flop changes state whenever T = 1.

Truth Table
T	   Q(next)
0	    No Change
1    	Toggle

Applications

     *Binary counters
      *Frequency dividers
