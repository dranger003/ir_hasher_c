ir_hasher_c
===========

Function to hash a code from an IR receiver (reading an IR remote control).<br />
This uses the pigpio library from http://abyz.co.uk/rpi/pigpio/index.html<br />
<br />
Source: http://abyz.co.uk/rpi/pigpio/code/ir_hasher_c.zip<br />
<br />
Compile with:
<pre>gcc -o ir_hash_c test_ir_hasher.c  ir_hasher.c -lpigpio -lrt -lpthread</pre>
