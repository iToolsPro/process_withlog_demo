## process_withlog_demo
A demo of [https://github.com/iToolsPro/progressbar](https://github.com/iToolsPro/progressbar).

> tested on go1.15.

## usage
1. clone this repo.
2. go run run.go

output eg:
```bash
> go run run.go
2020-12-06 16:39:43 sample log ---> 0                                                      
2020-12-06 16:39:44 sample log ---> 1                                                       
2020-12-06 16:39:45 sample log ---> 2                                                        
2020-12-06 16:39:46 sample log ---> 3                                                         
2020-12-06 16:39:47 sample log ---> 4                                                         
logWriter demo   5% [==>                                                         ] 
```

## notice
add 
```
replace github.com/schollz/progressbar/v3 v3.7.2 => github.com/iToolsPro/progressbar/v3 v3.7.6
```
in go.mod
