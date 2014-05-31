ir_hasher_c
===========

Function to hash a code from an IR receiver (reading an IR remote control).<br />
This uses the pigpio library from http://abyz.co.uk/rpi/pigpio/index.html<br />
Source: http://abyz.co.uk/rpi/pigpio/code/ir_hasher_c.zip<br />
<br />
Compile with:
<pre>gcc -Wall -Ofast -mfpu=vfp -mfloat-abi=hard -march=armv6zk -mtune=arm1176jzf-s -mcpu=arm1176jzf-s test_ir_hasher.c  ir_hasher.c -lpigpio -lrt -lpthread -o ir_hash_c</pre>
