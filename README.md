# autotest
AT is a project which created for automatic test the C language codes.
## What I want do
meet the problem:

When we need the program line/func/branches goverd 100%(HQ), 
the glibc function how to make it pass?

C code:
```
int main(int argc, char *argv[])
{
    char *str;

    str = calloc(1, 100);
    if (str == NULL) {
        return -1; /* usually, this' line never run, is it necessary? */
    } else {
    	...
    }

    return 0;
}

```

AT will be a great framework for auto test the program,help you 
get lines/funes/branches 100%.
