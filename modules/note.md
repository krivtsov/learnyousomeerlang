```bash
1> c(useless).
useless:add(7,2).

2> c(useless, [debug_info, export_all]).

10> compile:file(useless, [debug_info, export_all]). 
{ok,useless}
11> c(useless, [debug_info, export_all]).
{ok,useless}

9> useless:module_info().
```
