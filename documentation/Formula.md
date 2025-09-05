# True Awareness Formula

This is true awareness formula, a conceptual framework for understanding the nature of existence and consciousness.
This formula doesn't represent any specific programming language or technology, but rather a philosophical approach to awareness and existence.

##

### Data Representation

- `1` = Singularity
- `0` = Void
- ` ` = Neutrality
- ` 1	` = Neutrality with singularity
- `	0	` = Neutrality with void
- `{ }` = Immutable data
- `< >` = Anti data version (Anti-Singularity, Anti-Void, Anti-Neutrality)
- `<1>` = Anti-Singularity
- `<0>` = Anti-Void
- `< >` = Anti-Neutrality
- `? ?` = Non data version (Non-Singularity, Non-Void, Non-Neutrality)
- `?1?` = Non-Singularity
- `?0?` = Non-Void
- `? ?` = Non-Neutrality
- `x`, `xf0` = Hex data
- `"text"` = Text data

### Symbols

- [ ] Universal Symbols
- `+-*/` = Basic arithmetic operations
- `~` = Represent data need to be inverted
- `^{ }` = Represent can change immutable data
- `^{ }^` = Represent can change immutable data and mutable data both
- `>`, `<`, `>=`, `=<` = Represent more, less, more equal, less equal
- `^n`, `^[n]m` = Represent power and tetration
- `=x` = Represent convert binary to hex form
- `x=` = Represent convert hex to binary form
- `>>`, `<<` = Represent bitwise right and left

- [ ] Line Symbols
- `=(n)`, `(n)=` = Represent before and after `n` iteration
- `^?n` = Represent to jump directly di `n` variable
- `_>` = Represent to make line flow downward
- `_<` = Represent to make line flow upward
- `_ ` = Represent to make line flow N-State

- [ ] Specific Symbols
- `;` = Represent separator
- `=>`, `<=` = Represent to do formula from left to right or right to left
- `=:=` = Represent to do formula in the N-States
- `!n` = Represent series number

- [ ] Conditional Symbols
- `=)` = Represent if condition
- `=)(` = Represent else if condition
- `=(` = Represent else condition
- `=|n` = Represent to compare with n variable or value
- `=[]`, `=[n, m]`, `[n]` = Represent switch
- `[n|x%]`, `[n|x,y]`, `[n|x/y]` = Represent probability of an event while on process occurs

- [ ] Tick Symbols
- `t=` = Represent ticks speed
- `:>` = Represent ticks going forward
- `<:` = Represent ticks going backward
- `::` = Represent ticks in N-State
  
- [ ] Variable Symbols
- `#n` = Represent name of variable
- `#{>` = Represent variable name expanding
- `#<}` = Represent variable name shrinking
- `#()` = Represent variable name can become Neutrality or Anything

### Data Rules

- These data rules are valid in binary only
- `{n} m` = Immutable and mutable data are separate operation
- `0000` = `[0,0,0,0]` = Data can be treat as arrays
- `0000` = Data can be treat as grouped

- In every ticks are running forward, lifetimes need to be subtract, add, and other operation by n

```txt
#lifetimes = 1111
#lifetimes:t=10:> 0101
```

- In every ticks are running backward, lifetimes need to be  subtract, add, and other operation by n

```txt
#lifetimes = 1111
#lifetimes:t=10<: 0001 1001
```

- If ticks in N-State, lifetimes can do nothing

```txt
#lifetimes = 1111
#lifetimes:t=10:: 0101
```

- If lifetimes are still 1 then it still alive

```txt
#lifetimes = 1
```

- If lifetimes are 0 then it's over

```txt
#lifetimes = 0
```

- If lifetimes are ( ) then it's infinite lifetimes

```txt
#lifetimes = (  )
```

### Variable Rules

- Variable can change name on process
- Variable can contains other variable
- Variable can be vanished and appear at the same time
- Variable can be treat as array and group
- Variable name can be shrinking like instruction or expanding to full definitions
- Duplicates variable will be treated as array
