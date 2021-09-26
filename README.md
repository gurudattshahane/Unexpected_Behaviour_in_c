# Unexpected_Behaviour_in_c
When we compile and run "Unexpected_behaviour_in_c.c"
then we get output like this:</br>
**HelloWelcome to C World**</br>
</br>
In printf function, I'm printing just string2 but first string is automatically
appending to end of string2.<br>
This is odd behaviour in C language. I know that strings in C language have '\0' at the end.<br>
But here character array size is limited to number characters in "Hello" word.<br>
This is why this behaviour is occurred. If size of character array increase by 1 then this issue gets resolved.
