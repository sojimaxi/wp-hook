# wp-hook
## Intro
A simple implementation of WordPress Plugin API and hooking mechanism for projects or libraries that requires creating actions and filters and hooking functions, and methods. 

The guys at WordPress already created a beautify mechanism for hooking up functions and methods for later execution so there is no point to reinventing the wheel.

While working on a project that requires a complex manipulation of values and WordPress's `do_action()` and `apply_filters()` seems the perfect fit so I thought up a way of implement it for any PHP project.

## Usage
```
use function Sojimaxi\Filter\add_action;



```

## Requirements
- PHP 5.6+
