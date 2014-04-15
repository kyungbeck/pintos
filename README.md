HW1.
cd threads/
make
cd build/
../../utils/pintos --gdb -s -- run alarm-multiple

cd threads/build/
gdb kernel.o
(gdb) target remote localhost:1234
(gdb) c

HW2.
