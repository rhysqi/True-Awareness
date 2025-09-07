# True Awareness Formula

This is true awareness formula, a conceptual framework for understanding the nature of existence and consciousness.
This formula doesn't represent any specific programming language or technology, but rather a philosophical approach to awareness and existence.

##

### Data Representation

- `1` = Singularity
- `0` = Void
- ` ` = Neutrality
- `  1  ` = Neutrality with singularity
- `  0  ` = Neutrality with void
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
- `"text"` = Text data or comments

### Symbols

- [ ] Arrays, Groups, and Nested symbols
- `[n]` = Represent data in arrays n
- `[n[n[...]]]` = Represent data in arrays n in arrays n in arrays ...
- `(n)` = Represent data in groups n
- `(n(n(...)))` = Represent data in groups n in groups n in groups ...
<br>

- [ ] Conditional and Loops Symbols
- `=)` = Represent if condition
- `=)(` = Represent else if condition
- `=(` = Represent else condition
- `=|n` = Represent to compare with n variable or value
- `=[]`, `=[n, m]`, `[n]` = Represent switch
- `[n|x%]`, `[n|x,y]`, `[n|x/y]` = Represent probability of an event while on process occurs
- `=(n)=` = Represent n loops iteration
- `=(n)`, `(n)=` = Represent before and after `n` iteration
<br>

- [ ] Column & Line Symbols
- `_n` = Represent to jump directly di `n` variable
- `_>` = Represent to make line flow downward
- `_<` = Represent to make line flow upward
- `_ ` = Represent to make line flow N-State
<br>

- [ ] Specific Symbols
- `;` = Represent separator
- `=>` = Represent to do formula from left to right
- `<=` = Represent to do formula from right to left
- `=:=` = Represent to do formula in the N-States
- `=n=` = Represent to go in n formula
- `!n` = Represent series number
<br>

- [ ] Splitting Symbols
- `\=` = Represent for formula can splitting
- `\=T` = Represent for formula can splitting using thread
- `\=P` = Represent for formula can splitting using process
- `\=!` = Represent for formula can't splitting
- `\=T!` = Represent for formula can't splitting using thread
- `\=P!` = Represent for formula can't splitting using process
- `\:` = Represent for tick can splitting
- `\:T` = Represent for tick can splitting using thread
- `\:P` = Represent for tick can splitting using process
- `\:!` = Represent for tick can't splitting
- `\:T!` = Represent for tick can't splitting using thread
- `\:P!` = Represent for tick can't splitting using process

- [ ] Tick Symbols
- `t=` = Represent ticks speed
- `:>` = Represent ticks going forward
- `<:` = Represent ticks going backward
- `::` = Represent ticks in N-State
<br>

- [ ] Universal Symbols
- `+ - * /` = Origin arithmetic operations
- `<+> <-> <*> </>` = Anti-Origin arithmetic operations
- `?+? ?-? ?*? ?/?` = Non-Origin arithmetic operations
- `~` = Represent data need to be inverted
- `^{ }` = Represent can change immutable data
- `^{ }^` = Represent can change immutable data and mutable data both
- `>`, `<`, `>=`, `=<` = Represent more, less, more equal, less equal
- `^n`, `^[n]m` = Represent power and tetration
- `=x` = Represent convert binary to hex form
- `x=` = Represent convert hex to binary form
- `>>`, `<<` = Represent bitwise right and left
<br>

- [x] Variable Symbols
- `#n` = Represent name of variable
- `#{>` = Represent variable name expanding
- `#<}` = Represent variable name shrinking
- `#  ` / `# =` = Represent variable name can become Neutrality or Anything
<br>

### Data Rules

- Origin data are defined as Singularity, Void, Neutrality
  ```
  (1/0/ )
  ```
  Anti-Origin data are defined as Anti-Singularity, Anti-Void, Anti-Neutrality.<br> 
  ```
  <1> <0> < >
  ```
  Non-Origin data are defined as Non-Singularity, Non-Void, Non-Neutrality.<br> 
  ```
  ?1? ?0? ? ?
  ```
  #### Data Operation Ruleset
  - Origin with Origin
	```
	1 + 1 = 10
	1 - 1 = 0
	1 * 1 = 1
	1 / 1 = 1

	1 + 0 = 1
	1 - 0 = 1
	1 * 0 = 1
	1 / 0 = ( )

	1 + ( ) = 1
	1 - ( ) = <1>
	1 * ( ) = 1( )
	1 / ( ) = ( )1
	```
	<br>

  - Origin with Anti-Origin
	```
	1 + <1> = 0
	1 - <1> = 10
	1 * <1> = 1<1>
	1 / <1> = <1>1

	1 + <0> = 10
	1 - <0> = 0
	1 * <0> = 1<1>
	1 / <0> = <1>1

	1 + < > = 1
	1 - < > = ?<1>?
	1 * < > = 1< >
	1 / < > = < >1
	```
	```
	0 + <0> = 1
	0 - <0> = -1
	0 * <0> = 0<0>
	0 / <0> = <0>1

	0 + <0> =
	0 - <0> =
	0 * <0> =
	0 / <0> =

	0 + < > =
	0 - < > =
	0 * < > =
	0 / < > =
	```
	```
	( ) + <1> =
	( ) - <1> =
	( ) * <1> =
	( ) / <1> =

	( ) + <0> =
	( ) - <0> =
	( ) * <0> =
	( ) / <0> =

	( ) + < > = < >
	( ) - < > = -< >
	( ) * < > = ( )< >
	( ) / < > = < >( )
	```
	<br>

  - Origin with Non-Origin
	```
	1 + ?1? = 
	1 - ?1? = 
	1 * ?1? = 1?1?
	1 / ?1? = ?1?1

	1 + ?0? = 
	1 - ?0? = 
	1 * ?0? = 
	1 / ?0? = 

	1 + ? ? = 
	1 - ? ? = 
	1 * ? ? = 
	1 / ? ? = 
	```
	```
	0 + ?1? = 
	0 - ?1? = 
	0 * ?1? = 
	0 / ?1? = 

	0 + ?0? = 
	0 - ?0? = 
	0 * ?0? = 
	0 / ?0? = 

	0 + ? ? = 
	0 - ? ? = 
	0 * ? ? = 
	0 / ? ? = 
	```
	```
	( ) + ?1? = 
	( ) - ?1? = 
	( ) * ?1? = 
	( ) / ?1? = 

	( ) + ?0? = 
	( ) - ?0? = 
	( ) * ?0? = 
	( ) / ?0? = 

	( ) + ? ? = 
	( ) - ? ? = 
	( ) * ? ? = 
	( ) / ? ? = 
	```
	<br>
  - Anti-Origin with Origin
	```
	<1> + 1 = 
	<1> - 1 = 
	<1> * 1 = 
	<1> / 1 = 

	<1> + 0 = 
	<1> - 0 = 
	<1> * 0 = 
	<1> / 0 = 

	<1> +   = 
	<1> -   = 
	<1> *   = 
	<1> /   = 
	```
	```
	<0> + 1 = 
	<0> - 1 = 
	<0> * 1 = 
	<0> / 1 = 

	<0> + 0 = 
	<0> - 0 = 
	<0> * 0 = 
	<0> / 0 = 

	<0> +   = 
	<0> -   = 
	<0> *   = 
	<0> /   = 
	```
	```
	< > + 1 = 
	< > - 1 = 
	< > * 1 = 
	< > / 1 = 

	< > + 0 = 
	< > - 0 = 
	< > * 0 = 
	< > / 0 = 

	< > +   = 
	< > -   = 
	< > *   = 
	< > /   = 
	```
	<br>

  - Anti-Origin with Anti-Origin
	```
	<1> + <1> = 
	<1> - <1> = 
	<1> * <1> = 
	<1> / <1> = 

	<1> + <0> = 
	<1> - <0> = 
	<1> * <0> = 
	<1> / <0> = 

	<1> + < > = 
	<1> - < > = 
	<1> * < > = 
	<1> / < > = 
	```
	```
	<0> + <1> = 
	<0> - <1> = 
	<0> * <1> = 
	<0> / <1> = 

	<0> + <0> = 
	<0> - <0> = 
	<0> * <0> = 
	<0> / <0> = 

	<0> + < > = 
	<0> - < > = 
	<0> * < > = 
	<0> / < > = 
	```
	```
	< > + <1> = 
	< > - <1> = 
	< > * <1> = 
	< > / <1> = 

	< > + <0> = 
	< > - <0> = 
	< > * <0> = 
	< > / <0> = 

	< > + < > = 
	< > - < > = 
	< > * < > = 
	< > / < > = 
	```
	<br>

  - Anti-Origin with Non-Origin
	```
	<1> + ?1? = 
	<1> - ?1? = 
	<1> * ?1? = 
	<1> / ?1? = 

	<1> + ?0? = 
	<1> - ?0? = 
	<1> * ?0? = 
	<1> / ?0? = 

	<1> + ? ? = 
	<1> - ? ? = 
	<1> * ? ? = 
	<1> / ? ? = 
	```
	```
	<0> + ?1? = 
	<0> - ?1? = 
	<0> * ?1? = 
	<0> / ?1? = 

	<0> + ?0? = 
	<0> - ?0? = 
	<0> * ?0? = 
	<0> / ?0? = 

	<0> + ? ? = 
	<0> - ? ? = 
	<0> * ? ? = 
	<0> / ? ? = 
	```
	```
	< > + ?1? = 
	< > - ?1? = 
	< > * ?1? = 
	< > / ?1? = 

	< > + ?0? = 
	< > - ?0? = 
	< > * ?0? = 
	< > / ?0? = 

	< > + ? ? = 
	< > - ? ? = 
	< > * ? ? = 
	< > / ? ? = 
	```
	<br>

  - Non-Origin with Origin
	```
	?1? + 1 = 
	?1? - 1 = 
	?1? * 1 = 
	?1? / 1 = 

	?1? + 0 = 
	?1? - 0 = 
	?1? * 0 = 
	?1? / 0 = 

	?1? +   = 
	?1? -   = 
	?1? *   = 
	?1? /   = 
	```
	```
	?0? + 1 = 
	?0? - 1 = 
	?0? * 1 = 
	?0? / 1 = 

	?0? + 0 = 
	?0? - 0 = 
	?0? * 0 = 
	?0? / 0 = 

	?0? +   = 
	?0? -   = 
	?0? *   = 
	?0? /   = 
	```
	```
	? ? + 1 = 
	? ? - 1 = 
	? ? * 1 = 
	? ? / 1 = 

	? ? + 0 = 
	? ? - 0 = 
	? ? * 0 = 
	? ? / 0 = 

	? ? +   = 
	? ? -   = 
	? ? *   = 
	? ? /   = 
	```
	<br>

  - Non-Origin with Anti-Origin
	```
	?1? + <1> = 
	?1? - <1> = 
	?1? * <1> = 
	?1? / <1> = 

	?1? + <0> = 
	?1? - <0> = 
	?1? * <0> = 
	?1? / <0> = 

	?1? + < > = 
	?1? - < > = 
	?1? * < > = 
	?1? / < > = 
	```
	```
	?0? + <1> = 
	?0? - <1> = 
	?0? * <1> = 
	?0? / <1> = 

	?0? + <0> = 
	?0? - <0> = 
	?0? * <0> = 
	?0? / <0> = 

	?0? + < > = 
	?0? - < > = 
	?0? * < > = 
	?0? / < > = 
	```
	```
	? ? + <1> = 
	? ? - <1> = 
	? ? * <1> = 
	? ? / <1> = 

	? ? + <0> = 
	? ? - <0> = 
	? ? * <0> = 
	? ? / <0> = 

	? ? + < > = 
	? ? - < > = 
	? ? * < > = 
	? ? / < > = 
	```
	<br>

  - Non-Origin with Non-Origin
	```
	?1? + ?1? = ?10?
	?1? - ?1? = ?0?
	?1? * ?1? = ?1?
	?1? / ?1? = ?1?

	?1? + ?0? = ?1?
	?1? - ?0? = ?1?
	?1? * ?0? = ?1?
	?1? / ?0? = ? ?

	?1? + ? ? = 
	?1? - ? ? = 
	?1? * ? ? = 
	?1? / ? ? = 
	```
	```
	?1? + ?1? = 
	?1? - ?1? = 
	?1? * ?1? = 
	?1? / ?1? = 

	?1? + ?0? = 
	?1? - ?0? = 
	?1? * ?0? = 
	?1? / ?0? = 

	?1? + ? ? = 
	?1? - ? ? = 
	?1? * ? ? = 
	?1? / ? ? = 
	```
	```
	?1? + ?1? = 
	?1? - ?1? = 
	?1? * ?1? = 
	?1? / ?1? = 

	?1? + ?0? = 
	?1? - ?0? = 
	?1? * ?0? = 
	?1? / ?0? = 

	?1? + ? ? = 
	?1? - ? ? = 
	?1? * ? ? = 
	?1? / ? ? = 
	```
	<br>

- These data rules are valid in binary only
- `{n} m` = Immutable and mutable data are separate operation
- `0000` = `[0,0,0,0]` = Data can be treat as arrays
- `0000` = Data can be treat as grouped

- In every ticks are running forward, lifetimes need to be subtract, add, and other operation by n

	```txt
	#lifetimes=;
	#lifetimes;t=10:>0101;
	```

- In every ticks are running backward, lifetimes need to be  subtract, add, and other operation by n

	```txt
	#lifetimes=1111;
	#lifetimes;t=10<:00011001;
	```

- If ticks in N-State, lifetimes can do nothing

	```txt
	#lifetimes=1111;
	#lifetimes;t=10::0101;
	```

- If lifetimes are still 1 then it still alive

	```txt
	#lifetimes=1;
	```

- If lifetimes are 0 then it's over

	```txt
	#lifetimes=0;
	```

- If lifetimes are ` ` then it's infinite lifetimes

	```txt
	#lifetimes= ;
	```

### Variable Rules

- Variable can change name on process
- Variable can contains other variable
- Variable can be vanished and appear at the same time
- Variable can be treat as array and group
- Variable name can be shrinking like instruction or expanding to full definitions
- Duplicates variable will be treated as array
