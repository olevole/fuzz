# fuzz
Instruction fuzzing for testing OS stability

-- Do not run on your bare metal unless you are at the console and want to create a panic --

Just cc -o fuzz fuzz.c and sh fuzz.sh, wait a couple of seconds....

Doesn't seem to work on Ubuntu (but it's still testing)
fuzz2.c is pseudo random and needs a seed as parameter (unsigned int)
