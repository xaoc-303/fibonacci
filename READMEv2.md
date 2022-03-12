# fibonacci

Fibonacci: productivity in different languages

Measurement of total time with start / stop (use command `time`)

## recursive if-else

| v | # | 30 | 35 | 40 | 45 | 50 |
| --- | --- | --- | --- | --- | --- | --- |
| 1.13.1 | [Go](./go/fibo.go) (compiled) | 0,011 | 0,063 | 0,539 | 0:05,819 | 1:03,44 |
| 1.8.0_192 | [Java](./java/Fibo.java) (compiled) | 0,102 | 0,134 | 0,495 | 0:04,469 | 0:48,290 |
| 1.3.50 | [Kotlin](./kotlin/fibo.kt) (compiled) | 0,107 | 0,143 | 0,509 | 0:04,535 | 0:48,804 |
| gcc 9.2.0 | [C++](./cpp/fibo.cpp) (compiled) | 0,011 | 0,068 | 0,612 | 0:06,557 | 1:12,45 |
| gcc 9.2.0 | [C](./c/fibo.c) (compiled) | 0,011 | 0,068 | 0,615 | 0:06,656 | 1:13,59 |
| 1.13.1 | [Go](./go/fibo.go) | 0,201 | 0,242 | 0,724 | 0:06,031 | 1:04,01 |
| 1.38.0 | [Rust](./rust/fibo.rs) (compiled) | 0,019 | 0,138 | 1,376 | 0:14,989 | 2:45,11 |
| 1.10.1.469 | [Clojure](./clojure-lein/src/fibo.clj) (uberjar) | 0,734 | 0,877 | 2,470 | 0:20,681 | - |
| 1.10.1.469 | [Clojure](./clojure/fibo.clj) | 0,931 | 1,111 | 2,985 | 0:23,637 | - |
| 1.9.2 | [Elixir](./elixir/lib/fibo.ex) (compiled) | 0,170 | 0,480 | 3,881 | 0:41,591 | - |
| 2.13.1 | [Scala](./scala/Fibo.scala) (compiled) | 0,401 | 0,430 | 4,768 | 0:49,292 | - |
| 10.5.3 | [Erlang](./erlang/fibo.erl) (compiled) | 1,153 | 1,423 | 4,255 | 0:36,014 | - |
| 7.1.23 | [PHP](./php/fibo.php) | 0,167 | 1,168 | 12,085 | 2:12,10 | - |
| 2.3.7 | [Ruby](./ruby/fibo.rb) | 0,185 | 1,254 | 12,944 | 2:23,51 | - |
| 7.1.23 | [PHP](./php/fibo_int.php) (f:type) | 0,188 | 1,503 | 14,585 | 2:39,73 | - |
| 5.3.5 | [Lua](./lua/fibo.lua) | 0,156 | 1,598 | 17,018 | 3:07,77 | - |
| 3.7.0 | [Python](./python/fibo.py) | 0,365 | 3,678 | 39,599 | 7:13,63 | - |
| 5.18.4 | [Perl](./perl/fibo.pl) | 0,502 | 5,469 | 59,636 | - | - |
| 10.5.3 | [Erlang](./erlang/fibo.erl) | 2,873 | 31,873 | - | - | - |

## optimization

| v | # | 30 | 35 | 40 | 45 | 50 |
| --- | --- | --- | --- | --- | --- | --- |
| 2.15.05 | [NASM](./asm/fib.asm) (compiled) | 0,001 | 0,001 | 0,001 | 0,001 | 0,001 |
| gcc 9.2.0 | [C++](./cpp/fibo_ex.cpp) (compiled) | 0,002 | 0,002 | 0,002 | 0,001 | 0,002 |
| gcc 9.2.0 | [C](./c/fibo_ex.c) (compiled) | 0,004 | 0,004 | 0,004 | 0,003 | 0,004 |
| 1.38.0 | [Rust](./rust/fibo_ex.rs) (compiled) | 0,004 | 0,004 | 0,004 | 0,004 | 0,004 |
| 5.3.5 | [Lua](./lua/fibo_ex.lua) | 0,005 | 0,004 | 0,004 | 0,005 | 0,005 |
| 1.13.1 | [Go](./go/fibo_ex.go) (compiled) | 0,005 | 0,005 | 0,005 | 0,005 | 0,005 |
| 5.18.4 | [Perl](./perl/fibo_ex.pl) | 0,009 | 0,009 | 0,009 | 0,009 | 0,009 |
| 3.7.0 | [Python](./python/fibo_ex.py) | 0,033 | 0,034 | 0,034 | 0,034 | 0,033 |
| 7.1.23 | [PHP](./php/fibo_ex.php) | 0,069 | 0,069 | 0,069 | 0,070 | 0,069 |
| 2.3.7 | [Ruby](./ruby/fibo_ex.rb) | 0,079 | 0,079 | 0,079 | 0,079 | 0,079 |
| 1.8.0_192 | [Java](./java/FiboEx.java) (compiled) | 0,097 | 0,098 | 0,098 | 0,097 | 0,095 |
| 1.3.50 | [Kotlin](./kotlin/fibo_ex.kt) (compiled) | 0,102 | 0,102 | 0,104 | 0,103 | 0,104 |
| 10.5.3 | [Erlang](./erlang/fibo_ex.erl) | 0,120 | 0,120 | 0,120 | 0,120 | 0,120 |
| 1.9.2 | [Elixir](./elixir/lib/fibo.ex) (compiled) | 0,136 | 0,135 | 0,136 | 0,136 | 0,136 |
| 1.13.1 | [Go](./go/fibo_ex.go) | 0,194 | 0,182 | 0,193 | 0,193 | 0,194 |
| 2.13.1 | [Scala](./scala/FiboEx.scala) (compiled) | 0,396 | 0,396 | 0,396 | 0,396 | 0,396 |
| 1.10.1.469 | [Clojure](./clojure/fibo_ex.clj) | 0,847 | 0,840 | 0,845 | 0,858 | 0,836 |
| 10.5.3 | [Erlang](./erlang/fibo_ex.erl) (compiled) | 1,133 | 1,133 | 1,129 | 1,133 | 1,132 |

#### setting console command 'time'
```
export TIMEFMT=$'\nreal\t%*E\nuser\t%*U\nsys\t%*S'
```
