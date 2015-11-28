Because `ebin` does not exist when dtl templates are compiled !

```
 APP    erlydtl
make[1]: Leaving directory '/home/glejeune/tmp/app1/deps/erlydtl'
 DEPEND sample.d
 DTL    ttt.dtl
{"init terminating in do_boot",{{case_clause,{error,[{"templates/ttt.dtl",[{none,erlydtl_beam_compiler,{write_file,enoent}}]}],[]}},[{erl_eval,expr,3,[]}]}}

Crash dump is being written to: erl_crash.dump...done
init terminating in do_boot ()
erlang.mk:4697: recipe for target 'ebin/sample.app' failed
make[1]: *** [ebin/sample.app] Error 1
erlang.mk:4788: recipe for target 'app' failed
make: *** [app] Error 2
```
