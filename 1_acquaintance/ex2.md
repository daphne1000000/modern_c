"Try to imagine what happens when i has value 0 and is decremented by means of the operator --."

The context is this: 

for (size_t i = 9; i <= 9; --i) {
	something_else(i);
}

In this case, it would then become the maximum value representable on that machine (i.e. depends on if the chip is 32, 64 or 128 bit)
