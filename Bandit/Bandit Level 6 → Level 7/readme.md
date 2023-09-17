# subject:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/101bc5e2-bc17-4297-8bd2-af760967413c)

# Solution: 

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/be29505a-d007-4819-892e-813fdd16f645)

# RTFM!:

### find:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/b60b86d8-31fb-4416-8afe-220ca5d142f4)

### -type f:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/d48dd6e1-8ee9-47b2-9cff-628eb52a695e)

### -user:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/77c7134c-5b1f-4d25-accc-9b851da6bac4)

### -group:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/cc0b5700-4ae0-4114-b94e-f7fdfb83263f)

### -size:

![image](https://github.com/zakaria0101echifaouy/OverTheWire-Wargames/assets/108145379/d33c2ebf-d51d-40eb-af35-be3e9b461462)

# 2>/dev/null:

2>: This part specifies that we want to redirect file descriptor 2 (stderr).

/dev/null: This is a special file on Unix-like systems.

2>/dev/null command, it means that we are redirecting all error messages (output on stderr) to /dev/null, effectively silencing or discarding them. It's a way to suppress error messages and prevent them from being displayed on the terminal.

try this command : find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null without 2>/dev/null and you will see the difference
