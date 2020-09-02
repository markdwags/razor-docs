# Keywords Overview

## and

Syntax: `(statement) and (statement)`

Description: The `and` keyword links statements together and if all statements are `true` the condition is met.

Example:

```php
if insysmsg 'hello' and insysmsg 'bye'
    say 'found'
endif
```

## break

Syntax: `break`

Description: The `break` keyword terminate the closest enclosing loop such as a `for` loop.

Example:

```php
for 100
    if stam = 100
        break
    else
        say 'loop again'
    endif
endfor
```

## continue

Syntax: `continue`

Description: The `continue` keyboard passes control to the next iteration of the enclosing `for` or `while` loop which the keyboard appears.

Example:

```php
while stam < 100

    if stam = 50
      say 'At 50!'
      continue
    endif

    say 'Not at 50'

endwhile
```

## loop/replay

Syntax: `loop` OR `replay`

Description: The `loop` or `replay` keyword will restart the currently run script back to the beginning indefinitely.

Example:

```php
if mana = 100
    say 'all done!'
    stop
else
    say 'still meditating'
endif
wait 1000
loop
```

## not

Syntax: `not (statement)`

Description: They `not` keyword returns the opposite of the statement result.

Example:

```php
if not 'dead'
    say 'I live!'
endif

if 'dead'
    say 'I died!'
endif
```

## or

Syntax: `(statement) or (statement)`

Description: The `or` keyword links statements together and if one statements is `true` the condition is met.

Example:

```php
if insysmsg 'hello' or insysmsg 'bye'
    say 'found'
endif
```

## stop

Syntax: `stop`

Description: The `stop` keyword will stop the execution of the current script.

Example:

```php
if stam = 100
    say 'all done!'
    stop
else
    say 'still waiting'
endif
wait 1000
loop
```
