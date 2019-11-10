# fibonacci

Fibonacci: productivity in different languages

Measuring the execution time of a function

## recursive if-else

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| 2.13.1 | [Scala](https://github.com/xaoc-303/fibonacci-scala) (compiled) | 0.00403636 | 0.03663815 | 0.39777520 | 4.36548853 |
| 1.3.50 | [Kotlin](https://github.com/xaoc-303/fibonacci-kotlin) (compiled) | 0.00541852 | 0.03712514 | 0.39989920 | 4.41861456 |
| 1.13.1 | [Go](https://github.com/xaoc-303/fibonacci-go) | 0.00559842 | 0.05122938 | 0.53362809 | 5.75826140 |
| 1.13.1 | [Go](https://github.com/xaoc-303/fibonacci-go) (compiled) | 0.00591578 | 0.05948975 | 0.53472273 | 5.80004869 |
| 1.8.0_192 | [Java](https://github.com/xaoc-303/fibonacci-java) (compiled) | 0.01626378 | 0.05006661 | 0.41549475 | 4.47823378 |
| 1.38.0 | [Rust](https://github.com/xaoc-303/fibonacci-rust) (compiled) | 0.01515268 | 0.13358528 | 1.34242942 | 14.76075383 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) (uberjar) | 0.03835653 | 0.20863053 | 2.07542750 | 23.25552847 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) (gen) | 0.04310228 | 0.21264926 | 2.08249994 | 22.87928756 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) | 0.04030636 | 0.22158383 | 2.11186157 | 23.75117631 |
| 1.9.2 | [Elixir](https://github.com/xaoc-303/fibonacci-elixir) (compiled) | 0.03089700 | 0.33613100 | 3.82416200 | 40.77350300 |
| 7.1.23 | [PHP](https://github.com/xaoc-303/fibonacci-php) | 0.09746909 | 1.11300397 | 11.95916796 | 131.70196891 |
| 2.3.7 | [Ruby](https://github.com/xaoc-303/fibonacci-ruby) | 0.10722700 | 1.20770600 | 13.03103300 | 144.01225400 |
| 7.1.23 | [PHP](https://github.com/xaoc-303/fibonacci-php) (f:type) | 0.11967611 | 1.35702896 | 14.67897701 | 155.63229012 |
| 5.3.5 | [Lua](https://github.com/xaoc-303/fibonacci-lua) | 0.15513400 | 1.53598600 | 16.92561700 | 184.62159500 |
| 3.7.0 | [Python](https://github.com/xaoc-303/fibonacci-python) | 0.32678509 | 3.54449487 | 38.80285716 | 478.11391401 |
| 5.18.4 | [Perl](https://github.com/xaoc-303/fibonacci-perl) | 0.48761415 | 5.35093021 | 58.68868995 | 671.45659089 |
| clang 10.0.1 | [C](https://github.com/xaoc-303/fibonacci-c) (compiled) | | | | |
| clang 10.0.1 | [C++](https://github.com/xaoc-303/fibonacci-cpp) (compiled) | | | | |

## optimization

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| 1.13.1 | [Go](https://github.com/xaoc-303/fibonacci-go) | 0.00000020 | 0.00000022 | 0.00000021 | 0.00000022 |
| 1.13.1 | [Go](https://github.com/xaoc-303/fibonacci-go) (compiled) | 0.00000024 | 0.00000019 | 0.00000023 | 0.00000021 |
| 1.3.50 | [Kotlin](https://github.com/xaoc-303/fibonacci-kotlin) (compiled) | 0.00000191 | 0.00000203 | 0.00000217 | 0.00000233 |
| 5.3.5 | [Lua](https://github.com/xaoc-303/fibonacci-lua) | 0.00000200 | 0.00000300 | 0.00000300 | 0.00000300 |
| 1.38.0 | [Rust](https://github.com/xaoc-303/fibonacci-rust) (compiled) | 0.00000255 |  0.00000261 | 0.00000303 | 0.00000330 |
| 2.3.7 | [Ruby](https://github.com/xaoc-303/fibonacci-ruby) | 0.00000400 | 0.00000400 | 0.00000400 | 0.00000500 |
| 3.7.0 | [Python](https://github.com/xaoc-303/fibonacci-perl) | 0.00000501 | 0.00000501 | 0.00000620 | 0.00000691 |
| 5.18.4 | [Perl](https://github.com/xaoc-303/fibonacci-perl) | 0.00001192 | 0.00001216 | 0.00001192 | 0.00001287 |
| 7.1.23 | [PHP](https://github.com/xaoc-303/fibonacci-php) | 0.00001693 | 0.00001812 | 0.00001907 | 0.00001907 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) (uberjar) | 0.00002120 | 0.00001951 | 0.00002130 | 0.00002092 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) (gen) | 0.00002339 | 0.00002321 | 0.0000243 | 0.00002233 |
| 1.10.1.469 | [Clojure](https://github.com/xaoc-303/fibonacci-clojure) | 0.00003731 | 0.00003683 | 0.00003808 | 0.00003701 |
| 2.13.1 | [Scala](https://github.com/xaoc-303/fibonacci-scala) (compiled) | 0.00063741 | 0.00062256 | 0.00062996 | 0.00066500 |
| 1.9.2 | [Elixir](https://github.com/xaoc-303/fibonacci-elixir) (compiled) | 0.00184500 | 0.00180000 | 0.00181200 | 0.00182200 |
| 1.8.0_192 | [Java](https://github.com/xaoc-303/fibonacci-java) (compiled) | 0.01183933 | 0.01229628 | 0.01198657 | 0.01203628 |
| clang 10.0.1 | [C](https://github.com/xaoc-303/fibonacci-c) (compiled) | | | | |
| clang 10.0.1 | [C++](https://github.com/xaoc-303/fibonacci-cpp) (compiled) | | | | |

#### setting console command 'time'
```
export TIMEFMT=$'\nreal\t%*E\nuser\t%*U\nsys\t%*S'
```
