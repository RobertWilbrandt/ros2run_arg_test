ros2run_arg_test
================

This package is intended to test the argument passing behavior of ```ros2 run```.

Usage
-----

```console
> ros2 run ros2run_arg_test echo_args.sh
Number: 0
Arguments: 
```

```console
> ros2 run ros2run_arg_test echo_args.sh foo -- bar
Number: 3
Arguments: foo -- bar
```

```console
> ros2 run ros2run_arg_test echo_args.sh -- foo bar
Number: 2
Arguments: foo bar
```
