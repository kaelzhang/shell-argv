> Ohhhhhhhh, I will refractor shell-argv in the next version, and support full features.
> 
> Just hold on and wait for that, guys.
>
> Or, just do that with me ?


# shell-argv

The logic of parsing argument vector for shell programming.

## Usage

Copy the slices of code from 'START' to 'END' in `argv.sh` to `my-shell.sh`

And, for example:

	bash my-shell.sh -iv --force --recursive abc def

Then, you will have severial parsed variables available:

### `FLAGS`

The array (I mean the array-like variable in shell) of flags, options or short-hand options

	['-i', '-v', '--force', '--recursive']


### `REMAINS`

	['abc', 'def']
	

### Features

`--`

`--xxxx`

`-x`

`-abcd`