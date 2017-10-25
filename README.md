### NAME
toggler - Use at your own risk :P

### SYNOPSIS
toggler
  
### DESCRIPTION
Toggler does one thing, it executes the configured command on all toggled items in a list.

### OPTIONS
none

### CONFIGURATION
`~/.toggler.conf`

Configuration file for the script, created automatic when running the script for the first time.


`/tmp/toggler_list`

File containing the list of items and toggle status, created when running for the first time. The location of this file can be changed by either editing `~/.toggler.conf` or pressing `c` when running the script

### KEYS
Press `h` to display a help screen inside toggler
```
The following keys are available.
a = Add item
c = Configure script
d = Delete current item
f = Edit display filter
i = Invert selected
q = Quit
r = Execute command with selected items
+ = Select all
- = Deselect all
```

