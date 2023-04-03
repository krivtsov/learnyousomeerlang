# Syntax in functions

```bash
1> c(functions).
{ok, functions}

2> functions:head([1,2,3,4]).
1

3> functions:second([1,2,3,4]).
2

4> c(functions).
{ok, functions}

5> functions:valid_time({{2023,04,03},{00,38,43}}).
The Date tuple ({2023,4,3}) says today is: 2023/4/3,
The time tuple ({0,38,43}) indicates: 0:38:43.
ok


6> functions:valid_time({{2023,04,03},{00,37}}).
Stop feeding me wrong data!
ok
```
