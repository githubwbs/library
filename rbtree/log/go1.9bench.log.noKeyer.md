gc 1 @0.079s 0%: 0.21+0.72+0.10 ms clock, 0.63+0/1.5/0.48+0.32 ms cpu, 4->4->0 MB, 5 MB goal, 16 P
gc 2 @0.139s 0%: 0.12+17+0.084 ms clock, 0.89+16/1.3/0.39+0.58 ms cpu, 4->4->0 MB, 5 MB goal, 16 P
gc 3 @0.202s 0%: 0.087+1.4+0.20 ms clock, 0.78+0.097/2.3/1.2+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
# github.com/cdongyang/library/rbtree
gc 1 @0.008s 2%: 0.18+1.6+0.11 ms clock, 0.72+0.18/3.3/1.8+0.47 ms cpu, 4->4->2 MB, 5 MB goal, 16 P
gc 2 @0.039s 2%: 0.15+4.9+0.17 ms clock, 1.8+0/6.6/5.5+2.1 ms cpu, 5->5->3 MB, 6 MB goal, 16 P
gc 3 @0.090s 1%: 0.096+2.7+0.10 ms clock, 1.3+0.32/6.5/4.0+1.4 ms cpu, 6->7->4 MB, 7 MB goal, 16 P
gc 4 @0.145s 1%: 0.018+2.3+0.17 ms clock, 0.30+0.22/6.1/9.2+2.8 ms cpu, 8->8->4 MB, 9 MB goal, 16 P
gc 5 @0.197s 1%: 0.020+2.5+0.34 ms clock, 0.32+0.22/7.4/11+5.5 ms cpu, 9->9->5 MB, 10 MB goal, 16 P
# github.com/cdongyang/library/rbtree_test
gc 1 @0.005s 7%: 0.48+2.9+0.11 ms clock, 2.9+0.88/6.8/1.0+0.68 ms cpu, 4->4->2 MB, 5 MB goal, 16 P
gc 2 @0.020s 5%: 0.080+2.7+0.21 ms clock, 0.88+0.17/8.1/0.10+2.4 ms cpu, 5->5->4 MB, 6 MB goal, 16 P
gc 3 @0.062s 3%: 0.071+3.6+0.15 ms clock, 0.92+0.25/7.9/15+2.0 ms cpu, 8->8->6 MB, 9 MB goal, 16 P
gc 4 @0.149s 1%: 0.019+3.2+0.18 ms clock, 0.31+0.25/9.0/21+2.9 ms cpu, 11->12->7 MB, 12 MB goal, 16 P
gc 5 @0.247s 1%: 0.019+3.4+0.11 ms clock, 0.31+0.50/10/27+1.8 ms cpu, 13->13->8 MB, 14 MB goal, 16 P
# testmain
gc 1 @0.009s 2%: 0.074+2.8+0.10 ms clock, 0.22+0.17/5.3/3.0+0.30 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
# testmain
gc 1 @0.002s 4%: 0.10+4.6+0.11 ms clock, 0.31+0.17/4.7/0.092+0.35 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 2 @0.031s 2%: 0.063+5.9+0.15 ms clock, 0.44+0/9.9/3.4+1.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 3 @0.065s 4%: 0.098+37+0.12 ms clock, 0.89+37/17/1.5+1.1 ms cpu, 13->13->12 MB, 14 MB goal, 16 P
gc 4 @0.155s 4%: 0.073+9.1+0.11 ms clock, 0.81+0.20/29/12+1.2 ms cpu, 23->24->21 MB, 24 MB goal, 16 P
=== RUN   TestSet
--- PASS: TestSet (0.00s)
gc 1 @0.001s 2%: 0.090+0.18+0.11 ms clock, 0.18+0/0.31/0.12+0.23 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 2 @0.001s 6%: 0.057+0.12+0.12 ms clock, 0.51+0/0.22/0.17+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 191672 HeapInuse: 532480 HeapObjects: 305 HeapIdle 942080 HeapReleased 0 HeapSys 1474560
gc 3 @0.002s 8%: 0.055+0.11+0.093 ms clock, 0.71+0/0.25/0.092+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
goos: linux
goarch: amd64
pkg: github.com/cdongyang/library/rbtree
#BenchmarkSort1E3-16                               	gc 4 @0.003s 10%: 0.013+0.19+0.099 ms clock, 0.20+0/0.33/0.099+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 200360 HeapInuse: 532480 HeapObjects: 326 HeapIdle 712704 HeapReleased 0 HeapSys 1245184
gc 5 @0.004s 11%: 0.009+0.16+0.085 ms clock, 0.15+0/0.12/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 6 @0.004s 11%: 0.006+0.13+0.082 ms clock, 0.099+0/0.19/0.19+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 203768 HeapInuse: 532480 HeapObjects: 332 HeapIdle 647168 HeapReleased 0 HeapSys 1179648
gc 7 @0.005s 12%: 0.009+0.15+0.091 ms clock, 0.15+0/0.21/0.19+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 8 @0.005s 13%: 0.009+0.17+0.090 ms clock, 0.15+0/0.19/0.20+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 205496 HeapInuse: 532480 HeapObjects: 336 HeapIdle 581632 HeapReleased 0 HeapSys 1114112
gc 9 @0.006s 13%: 0.010+0.21+0.090 ms clock, 0.16+0/0.21/0.17+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 10 @0.007s 14%: 0.050+0.15+0.095 ms clock, 0.80+0/0.32/0.12+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 207160 HeapInuse: 532480 HeapObjects: 339 HeapIdle 548864 HeapReleased 0 HeapSys 1081344
gc 11 @0.007s 15%: 0.009+0.15+0.12 ms clock, 0.15+0/0.25/0.19+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 12 @0.008s 16%: 0.027+0.11+0.078 ms clock, 0.43+0/0.22/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 208920 HeapInuse: 532480 HeapObjects: 343 HeapIdle 516096 HeapReleased 0 HeapSys 1048576
gc 13 @0.008s 16%: 0.011+0.13+0.086 ms clock, 0.17+0/0.20/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 14 @0.009s 16%: 0.011+0.18+0.11 ms clock, 0.18+0/0.26/0.21+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 212344 HeapInuse: 532480 HeapObjects: 350 HeapIdle 417792 HeapReleased 0 HeapSys 950272
gc 15 @0.010s 16%: 0.009+0.14+0.10 ms clock, 0.15+0/0.26/0.26+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 16 @0.010s 17%: 0.009+0.18+0.079 ms clock, 0.15+0/0.23/0.24+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 212440 HeapInuse: 532480 HeapObjects: 351 HeapIdle 417792 HeapReleased 0 HeapSys 950272
gc 17 @0.011s 17%: 0.010+0.12+0.083 ms clock, 0.16+0/0.20/0.18+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 18 @0.011s 17%: 0.007+0.11+0.076 ms clock, 0.12+0/0.19/0.21+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 212536 HeapInuse: 532480 HeapObjects: 352 HeapIdle 417792 HeapReleased 0 HeapSys 950272
gc 19 @0.012s 17%: 0.009+0.13+0.12 ms clock, 0.15+0/0.19/0.17+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 20 @0.012s 18%: 0.013+0.14+0.094 ms clock, 0.21+0/0.26/0.25+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 212792 HeapInuse: 532480 HeapObjects: 355 HeapIdle 417792 HeapReleased 0 HeapSys 950272
gc 21 @0.013s 18%: 0.011+0.17+0.11 ms clock, 0.18+0/0.24/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 22 @0.013s 18%: 0.011+0.13+0.089 ms clock, 0.18+0/0.21/0.19+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 212856 HeapInuse: 532480 HeapObjects: 356 HeapIdle 417792 HeapReleased 0 HeapSys 950272
gc 23 @0.014s 18%: 0.009+0.12+0.070 ms clock, 0.14+0/0.19/0.17+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 24 @0.014s 18%: 0.007+0.20+0.085 ms clock, 0.12+0/0.076/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 214776 HeapInuse: 532480 HeapObjects: 362 HeapIdle 385024 HeapReleased 0 HeapSys 917504
gc 25 @0.015s 18%: 0.008+0.14+0.10 ms clock, 0.14+0/0.26/0.30+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 26 @0.015s 18%: 0.010+0.14+0.074 ms clock, 0.16+0/0.17/0.20+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 214872 HeapInuse: 532480 HeapObjects: 363 HeapIdle 385024 HeapReleased 0 HeapSys 917504
gc 27 @0.016s 18%: 0.007+0.13+0.10 ms clock, 0.12+0/0.21/0.25+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 28 @0.017s 18%: 0.023+0.13+0.090 ms clock, 0.36+0/0.18/0.19+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 215128 HeapInuse: 532480 HeapObjects: 366 HeapIdle 385024 HeapReleased 0 HeapSys 917504
gc 29 @0.017s 18%: 0.007+0.12+0.077 ms clock, 0.11+0/0.19/0.17+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 30 @0.018s 18%: 0.009+0.17+0.097 ms clock, 0.15+0/0.28/0.23+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 215224 HeapInuse: 532480 HeapObjects: 367 HeapIdle 385024 HeapReleased 0 HeapSys 917504
gc 31 @0.018s 23%: 1.0+0.15+0.13 ms clock, 16+0/0.29/0.11+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 32 @0.020s 23%: 0.011+0.14+0.093 ms clock, 0.17+0/0.25/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 215320 HeapInuse: 532480 HeapObjects: 368 HeapIdle 385024 HeapReleased 0 HeapSys 917504
gc 33 @0.020s 23%: 0.009+0.14+0.078 ms clock, 0.14+0/0.22/0.30+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	       559 ns/op	      12 B/op	       0 allocs/op
gc 34 @0.021s 22%: 0.013+0.22+0.080 ms clock, 0.21+0/0.23/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 297112 HeapInuse: 614400 HeapObjects: 1874 HeapIdle 270336 HeapReleased 0 HeapSys 884736
gc 35 @0.023s 21%: 0.009+0.17+0.074 ms clock, 0.14+0/0.25/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsert1E3-16                          	gc 36 @0.024s 21%: 0.009+0.15+0.082 ms clock, 0.15+0/0.22/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 297240 HeapInuse: 614400 HeapObjects: 1876 HeapIdle 270336 HeapReleased 0 HeapSys 884736
gc 37 @0.026s 19%: 0.008+0.14+0.076 ms clock, 0.13+0/0.17/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 38 @0.027s 19%: 0.009+0.14+0.075 ms clock, 0.15+0/0.16/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 298888 HeapInuse: 614400 HeapObjects: 1878 HeapIdle 237568 HeapReleased 0 HeapSys 851968
gc 39 @0.029s 18%: 0.008+0.17+0.083 ms clock, 0.13+0/0.29/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 40 @0.029s 18%: 0.010+0.14+0.088 ms clock, 0.16+0/0.24/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 300648 HeapInuse: 614400 HeapObjects: 1882 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 41 @0.032s 17%: 0.009+0.16+0.070 ms clock, 0.14+0/0.28/0.15+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 42 @0.032s 17%: 0.006+0.12+0.067 ms clock, 0.096+0/0.22/0.20+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 300648 HeapInuse: 614400 HeapObjects: 1882 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 43 @0.034s 16%: 0.009+0.15+0.088 ms clock, 0.14+0/0.15/0.30+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 44 @0.035s 16%: 0.008+0.13+0.071 ms clock, 0.13+0/0.26/0.19+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 300840 HeapInuse: 614400 HeapObjects: 1884 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 45 @0.037s 16%: 0.010+0.16+0.072 ms clock, 0.16+0/0.32/0.21+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 46 @0.037s 16%: 0.007+0.14+0.10 ms clock, 0.11+0/0.27/0.28+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 300936 HeapInuse: 614400 HeapObjects: 1885 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 47 @0.040s 15%: 0.010+0.15+0.070 ms clock, 0.16+0/0.27/0.21+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 48 @0.040s 15%: 0.013+0.14+0.080 ms clock, 0.21+0/0.21/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 300936 HeapInuse: 614400 HeapObjects: 1885 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 49 @0.042s 15%: 0.008+0.14+0.067 ms clock, 0.13+0/0.17/0.24+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 50 @0.043s 15%: 0.013+0.15+0.084 ms clock, 0.22+0/0.21/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301192 HeapInuse: 614400 HeapObjects: 1888 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 51 @0.045s 14%: 0.011+0.15+0.085 ms clock, 0.19+0/0.23/0.15+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 52 @0.046s 14%: 0.018+0.16+0.075 ms clock, 0.30+0/0.19/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301288 HeapInuse: 614400 HeapObjects: 1889 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 53 @0.048s 14%: 0.010+0.21+0.085 ms clock, 0.16+0/0.22/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 54 @0.048s 14%: 0.012+0.17+0.079 ms clock, 0.20+0/0.20/0.26+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301384 HeapInuse: 614400 HeapObjects: 1890 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 55 @0.051s 13%: 0.008+0.13+0.084 ms clock, 0.13+0/0.25/0.23+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 56 @0.051s 14%: 0.006+0.12+0.086 ms clock, 0.11+0/0.22/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301576 HeapInuse: 614400 HeapObjects: 1892 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 57 @0.053s 13%: 0.008+0.15+0.071 ms clock, 0.12+0/0.16/0.31+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 58 @0.054s 13%: 0.018+0.16+0.064 ms clock, 0.29+0/0.25/0.26+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301736 HeapInuse: 614400 HeapObjects: 1894 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 59 @0.056s 13%: 0.010+0.13+0.069 ms clock, 0.17+0/0.20/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 60 @0.057s 13%: 0.016+0.14+0.076 ms clock, 0.26+0/0.25/0.28+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301832 HeapInuse: 614400 HeapObjects: 1895 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 61 @0.059s 13%: 0.008+0.14+0.087 ms clock, 0.13+0/0.22/0.20+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 62 @0.059s 13%: 0.012+0.19+0.083 ms clock, 0.19+0/0.30/0.28+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 301928 HeapInuse: 614400 HeapObjects: 1896 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 63 @0.062s 12%: 0.009+0.15+0.10 ms clock, 0.15+0/0.22/0.31+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 64 @0.062s 12%: 0.007+0.13+0.082 ms clock, 0.12+0/0.21/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 302120 HeapInuse: 614400 HeapObjects: 1898 HeapIdle 172032 HeapReleased 0 HeapSys 786432
gc 65 @0.064s 12%: 0.009+0.22+0.095 ms clock, 0.15+0/0.095/0.32+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      2281 ns/op	      90 B/op	       2 allocs/op
gc 66 @0.065s 12%: 0.013+0.15+0.085 ms clock, 0.21+0/0.22/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398296 HeapInuse: 712704 HeapObjects: 3399 HeapIdle 73728 HeapReleased 0 HeapSys 786432
gc 67 @0.069s 12%: 0.008+0.17+0.096 ms clock, 0.13+0/0.27/0.21+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetErase1E3-16                           	gc 68 @0.069s 12%: 0.011+0.15+0.085 ms clock, 0.18+0/0.21/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398424 HeapInuse: 712704 HeapObjects: 3401 HeapIdle 73728 HeapReleased 0 HeapSys 786432
gc 69 @0.073s 11%: 0.008+0.17+0.068 ms clock, 0.13+0/0.26/0.16+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 70 @0.073s 11%: 0.007+0.19+0.10 ms clock, 0.12+0/0.25/0.29+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398408 HeapInuse: 712704 HeapObjects: 3400 HeapIdle 73728 HeapReleased 0 HeapSys 786432
gc 71 @0.077s 11%: 0.007+0.13+0.071 ms clock, 0.12+0/0.20/0.19+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 72 @0.077s 11%: 0.010+0.15+0.10 ms clock, 0.17+0/0.25/0.30+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398504 HeapInuse: 712704 HeapObjects: 3401 HeapIdle 73728 HeapReleased 0 HeapSys 786432
gc 73 @0.081s 11%: 0.009+0.17+0.076 ms clock, 0.15+0/0.24/0.29+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 74 @0.082s 11%: 0.013+0.13+0.086 ms clock, 0.21+0/0.26/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398504 HeapInuse: 712704 HeapObjects: 3401 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 75 @0.085s 10%: 0.010+0.17+0.093 ms clock, 0.17+0/0.28/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 76 @0.086s 11%: 0.010+0.14+0.12 ms clock, 0.17+0/0.25/0.23+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398696 HeapInuse: 712704 HeapObjects: 3403 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 77 @0.090s 10%: 0.021+0.19+0.089 ms clock, 0.34+0/0.36/0.38+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 78 @0.090s 10%: 0.005+0.14+0.086 ms clock, 0.089+0/0.18/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398888 HeapInuse: 712704 HeapObjects: 3405 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 79 @0.094s 10%: 0.007+0.14+0.090 ms clock, 0.12+0/0.22/0.24+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 80 @0.094s 10%: 0.007+0.15+0.090 ms clock, 0.12+0/0.26/0.27+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398888 HeapInuse: 712704 HeapObjects: 3405 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 81 @0.098s 10%: 0.011+0.19+0.10 ms clock, 0.18+0/0.29/0.20+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 82 @0.098s 10%: 0.010+0.15+0.090 ms clock, 0.16+0/0.20/0.29+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398984 HeapInuse: 712704 HeapObjects: 3406 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 83 @0.102s 10%: 0.008+0.16+0.092 ms clock, 0.13+0/0.30/0.18+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 84 @0.102s 10%: 0.010+0.17+0.10 ms clock, 0.16+0/0.35/0.17+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 398984 HeapInuse: 712704 HeapObjects: 3406 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 85 @0.106s 9%: 0.007+0.15+0.084 ms clock, 0.12+0/0.17/0.29+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 86 @0.106s 9%: 0.007+0.15+0.080 ms clock, 0.12+0/0.22/0.18+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399080 HeapInuse: 712704 HeapObjects: 3407 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 87 @0.110s 9%: 0.017+0.15+0.074 ms clock, 0.27+0/0.22/0.23+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 88 @0.111s 9%: 0.030+0.14+0.10 ms clock, 0.48+0/0.25/0.21+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399176 HeapInuse: 712704 HeapObjects: 3408 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 89 @0.115s 9%: 0.008+0.16+0.13 ms clock, 0.13+0/0.22/0.25+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 90 @0.115s 9%: 0.013+0.16+0.076 ms clock, 0.21+0/0.33/0.11+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399176 HeapInuse: 712704 HeapObjects: 3408 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 91 @0.119s 9%: 0.009+0.14+0.13 ms clock, 0.14+0/0.19/0.16+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 92 @0.119s 9%: 0.011+0.16+0.10 ms clock, 0.17+0/0.30/0.19+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399176 HeapInuse: 712704 HeapObjects: 3408 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 93 @0.123s 9%: 0.008+0.17+0.095 ms clock, 0.13+0/0.26/0.19+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 94 @0.124s 9%: 0.011+0.15+0.10 ms clock, 0.18+0/0.22/0.18+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399272 HeapInuse: 712704 HeapObjects: 3409 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 95 @0.127s 9%: 0.014+0.18+0.11 ms clock, 0.23+0/0.26/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 96 @0.128s 9%: 0.015+0.16+0.10 ms clock, 0.24+0/0.25/0.20+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 399368 HeapInuse: 712704 HeapObjects: 3410 HeapIdle 1122304 HeapReleased 0 HeapSys 1835008
gc 97 @0.131s 9%: 0.008+0.16+0.083 ms clock, 0.13+0/0.31/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1776 ns/op	      99 B/op	       2 allocs/op
gc 98 @0.132s 9%: 0.009+0.15+0.10 ms clock, 0.15+0/0.24/0.25+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 311544 HeapInuse: 622592 HeapObjects: 1912 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 99 @0.134s 9%: 0.009+0.14+0.10 ms clock, 0.15+0/0.22/0.21+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndErase1E3-16                  	gc 100 @0.134s 9%: 0.010+0.14+0.090 ms clock, 0.16+0/0.25/0.21+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 311768 HeapInuse: 622592 HeapObjects: 1915 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 101 @0.136s 9%: 0.010+0.18+0.13 ms clock, 0.17+0/0.21/0.27+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 102 @0.136s 9%: 0.014+0.23+0.083 ms clock, 0.23+0/0.33/0.28+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 311848 HeapInuse: 622592 HeapObjects: 1915 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 103 @0.138s 9%: 0.008+0.13+0.10 ms clock, 0.13+0/0.28/0.22+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 104 @0.139s 9%: 0.008+0.15+0.088 ms clock, 0.12+0/0.23/0.28+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 311944 HeapInuse: 622592 HeapObjects: 1916 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 105 @0.140s 9%: 0.009+0.15+0.091 ms clock, 0.15+0/0.24/0.22+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 106 @0.141s 9%: 0.008+0.16+0.083 ms clock, 0.13+0/0.22/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312040 HeapInuse: 622592 HeapObjects: 1917 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 107 @0.143s 9%: 0.009+0.19+0.11 ms clock, 0.14+0/0.30/0.17+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 108 @0.143s 9%: 0.009+0.15+0.066 ms clock, 0.15+0/0.26/0.22+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312136 HeapInuse: 622592 HeapObjects: 1918 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 109 @0.145s 9%: 0.008+0.14+0.081 ms clock, 0.13+0/0.22/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 110 @0.145s 9%: 0.020+0.15+0.085 ms clock, 0.32+0/0.26/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312136 HeapInuse: 622592 HeapObjects: 1918 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 111 @0.147s 9%: 0.009+0.17+0.094 ms clock, 0.15+0/0.14/0.33+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 112 @0.147s 9%: 0.018+0.15+0.10 ms clock, 0.30+0/0.22/0.24+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312232 HeapInuse: 622592 HeapObjects: 1919 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 113 @0.149s 9%: 0.009+0.13+0.084 ms clock, 0.14+0/0.20/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 114 @0.150s 9%: 0.010+0.17+0.090 ms clock, 0.16+0/0.23/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312424 HeapInuse: 622592 HeapObjects: 1921 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 115 @0.151s 9%: 0.008+0.17+0.070 ms clock, 0.13+0/0.22/0.19+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 116 @0.152s 9%: 0.007+0.15+0.11 ms clock, 0.12+0/0.28/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312616 HeapInuse: 622592 HeapObjects: 1923 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 117 @0.153s 9%: 0.008+0.17+0.098 ms clock, 0.13+0/0.25/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 118 @0.154s 9%: 0.014+0.20+0.13 ms clock, 0.22+0/0.19/0.30+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312616 HeapInuse: 622592 HeapObjects: 1923 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 119 @0.156s 9%: 0.008+0.15+0.098 ms clock, 0.13+0/0.26/0.26+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 120 @0.156s 9%: 0.010+0.14+0.083 ms clock, 0.16+0/0.26/0.14+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312616 HeapInuse: 622592 HeapObjects: 1923 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 121 @0.158s 9%: 0.010+0.19+0.11 ms clock, 0.16+0/0.26/0.26+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 122 @0.158s 9%: 0.012+0.14+0.13 ms clock, 0.19+0/0.20/0.21+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312712 HeapInuse: 622592 HeapObjects: 1924 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 123 @0.160s 9%: 0.009+0.15+0.10 ms clock, 0.14+0/0.25/0.21+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 124 @0.161s 9%: 0.048+0.16+0.074 ms clock, 0.77+0/0.30/0.21+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 312904 HeapInuse: 622592 HeapObjects: 1926 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 125 @0.162s 9%: 0.009+0.14+0.10 ms clock, 0.15+0/0.25/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 126 @0.163s 9%: 0.011+0.12+0.090 ms clock, 0.17+0/0.22/0.20+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 313000 HeapInuse: 622592 HeapObjects: 1927 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 127 @0.164s 9%: 0.009+0.14+0.086 ms clock, 0.15+0/0.28/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 128 @0.165s 9%: 0.008+0.15+0.072 ms clock, 0.13+0/0.24/0.23+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 313000 HeapInuse: 622592 HeapObjects: 1927 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 129 @0.167s 9%: 0.009+0.16+0.099 ms clock, 0.15+0/0.30/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1631 ns/op	      99 B/op	       2 allocs/op
gc 130 @0.167s 9%: 0.012+0.13+0.081 ms clock, 0.19+0/0.23/0.20+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275280 HeapInuse: 589824 HeapObjects: 1434 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 131 @0.169s 9%: 0.010+0.16+0.12 ms clock, 0.16+0/0.22/0.20+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndEraseWithPool1E3-16          	gc 132 @0.170s 9%: 0.030+0.16+0.098 ms clock, 0.48+0/0.23/0.27+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275520 HeapInuse: 589824 HeapObjects: 1437 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 133 @0.172s 9%: 0.011+0.15+0.12 ms clock, 0.18+0/0.24/0.26+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 134 @0.172s 9%: 0.008+0.17+0.10 ms clock, 0.12+0/0.31/0.20+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275504 HeapInuse: 589824 HeapObjects: 1436 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 135 @0.174s 9%: 0.007+0.24+0.12 ms clock, 0.12+0/0.21/0.35+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 136 @0.175s 9%: 0.009+0.15+0.080 ms clock, 0.14+0/0.26/0.26+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275600 HeapInuse: 589824 HeapObjects: 1437 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 137 @0.177s 9%: 0.010+0.17+0.076 ms clock, 0.17+0/0.28/0.20+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 138 @0.178s 9%: 0.011+0.30+0.11 ms clock, 0.18+0/0.27/0.27+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275696 HeapInuse: 589824 HeapObjects: 1438 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 139 @0.180s 9%: 0.008+0.15+0.084 ms clock, 0.13+0/0.17/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 140 @0.180s 9%: 0.008+0.17+0.10 ms clock, 0.14+0/0.29/0.17+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275792 HeapInuse: 589824 HeapObjects: 1439 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 141 @0.182s 9%: 0.009+0.16+0.10 ms clock, 0.15+0/0.26/0.22+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 142 @0.183s 9%: 0.007+0.16+0.071 ms clock, 0.11+0/0.24/0.22+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 275888 HeapInuse: 589824 HeapObjects: 1440 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 143 @0.185s 9%: 0.008+0.15+0.099 ms clock, 0.14+0/0.25/0.23+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 144 @0.185s 9%: 0.007+0.14+0.10 ms clock, 0.11+0/0.24/0.30+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276080 HeapInuse: 589824 HeapObjects: 1442 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 145 @0.187s 9%: 0.008+0.23+0.078 ms clock, 0.13+0/0.24/0.18+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 146 @0.188s 9%: 0.008+0.14+0.097 ms clock, 0.13+0/0.26/0.21+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276176 HeapInuse: 589824 HeapObjects: 1443 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 147 @0.190s 9%: 0.015+0.36+0.18 ms clock, 0.25+0/0.35/0.25+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 148 @0.191s 9%: 0.010+0.32+0.38 ms clock, 0.16+0/0.30/0.18+6.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276272 HeapInuse: 589824 HeapObjects: 1444 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 149 @0.194s 9%: 0.014+0.25+0.14 ms clock, 0.23+0/0.36/0.25+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 150 @0.194s 9%: 0.011+0.21+0.10 ms clock, 0.19+0/0.25/0.13+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276464 HeapInuse: 589824 HeapObjects: 1446 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 151 @0.197s 9%: 0.014+0.20+0.099 ms clock, 0.23+0/0.26/0.33+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 152 @0.197s 9%: 0.009+0.17+0.13 ms clock, 0.15+0/0.29/0.10+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276656 HeapInuse: 589824 HeapObjects: 1448 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 153 @0.200s 9%: 0.010+0.23+0.095 ms clock, 0.17+0/0.38/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 154 @0.200s 9%: 0.012+0.17+0.086 ms clock, 0.20+0/0.29/0.19+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276752 HeapInuse: 589824 HeapObjects: 1449 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 155 @0.203s 9%: 0.012+0.23+0.10 ms clock, 0.19+0/0.43/0.25+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 156 @0.203s 9%: 0.011+0.19+0.092 ms clock, 0.17+0/0.23/0.30+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276848 HeapInuse: 589824 HeapObjects: 1450 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 157 @0.206s 9%: 0.009+0.16+0.084 ms clock, 0.15+0/0.28/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 158 @0.206s 9%: 0.007+0.22+0.086 ms clock, 0.11+0/0.24/0.20+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276944 HeapInuse: 589824 HeapObjects: 1451 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 159 @0.208s 9%: 0.011+0.18+0.12 ms clock, 0.17+0/0.31/0.27+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 160 @0.209s 9%: 0.007+0.15+0.070 ms clock, 0.12+0/0.27/0.19+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 276944 HeapInuse: 589824 HeapObjects: 1451 HeapIdle 1245184 HeapReleased 0 HeapSys 1835008
gc 161 @0.211s 9%: 0.007+0.15+0.063 ms clock, 0.12+0/0.21/0.26+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      2085 ns/op	      61 B/op	       1 allocs/op
gc 162 @0.211s 9%: 0.025+0.14+0.067 ms clock, 0.41+0/0.23/0.23+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306600 HeapInuse: 614400 HeapObjects: 1944 HeapIdle 1220608 HeapReleased 0 HeapSys 1835008
gc 163 @0.213s 9%: 0.009+0.16+0.066 ms clock, 0.14+0/0.25/0.28+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsert1E3-16                       	gc 164 @0.214s 9%: 0.036+0.19+0.072 ms clock, 0.58+0/0.34/0.23+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306632 HeapInuse: 614400 HeapObjects: 1945 HeapIdle 1220608 HeapReleased 0 HeapSys 1835008
gc 165 @0.216s 9%: 0.007+0.14+0.080 ms clock, 0.11+0/0.26/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 166 @0.216s 9%: 0.010+0.23+0.076 ms clock, 0.17+0/0.28/0.16+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306712 HeapInuse: 614400 HeapObjects: 1945 HeapIdle 1220608 HeapReleased 0 HeapSys 1835008
gc 167 @0.218s 9%: 0.009+0.19+0.076 ms clock, 0.14+0/0.26/0.24+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 168 @0.219s 9%: 0.017+0.13+0.080 ms clock, 0.27+0/0.28/0.18+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306808 HeapInuse: 622592 HeapObjects: 1946 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 169 @0.221s 9%: 0.009+0.17+0.077 ms clock, 0.15+0/0.28/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 170 @0.221s 9%: 0.007+0.16+0.088 ms clock, 0.11+0/0.30/0.27+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306808 HeapInuse: 622592 HeapObjects: 1946 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 171 @0.223s 9%: 0.009+0.15+0.079 ms clock, 0.15+0/0.27/0.22+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 172 @0.223s 9%: 0.007+0.18+0.10 ms clock, 0.11+0/0.17/0.25+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 306904 HeapInuse: 622592 HeapObjects: 1947 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 173 @0.225s 9%: 0.009+0.15+0.081 ms clock, 0.14+0/0.27/0.26+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 174 @0.226s 9%: 0.007+0.16+0.084 ms clock, 0.12+0/0.24/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307096 HeapInuse: 622592 HeapObjects: 1949 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 175 @0.228s 9%: 0.009+0.16+0.076 ms clock, 0.15+0/0.21/0.21+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 176 @0.228s 9%: 0.009+0.23+0.077 ms clock, 0.15+0/0.24/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307192 HeapInuse: 622592 HeapObjects: 1950 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 177 @0.230s 9%: 0.008+0.20+0.085 ms clock, 0.12+0/0.28/0.31+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 178 @0.231s 9%: 0.006+0.17+0.10 ms clock, 0.098+0/0.27/0.26+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307288 HeapInuse: 622592 HeapObjects: 1951 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 179 @0.233s 9%: 0.009+0.14+0.082 ms clock, 0.14+0/0.28/0.13+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 180 @0.234s 9%: 0.008+0.21+0.076 ms clock, 0.13+0/0.11/0.39+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307480 HeapInuse: 622592 HeapObjects: 1953 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 181 @0.236s 9%: 0.008+0.18+0.089 ms clock, 0.12+0/0.25/0.23+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 182 @0.236s 9%: 0.008+0.17+0.11 ms clock, 0.13+0/0.24/0.32+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307480 HeapInuse: 622592 HeapObjects: 1953 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 183 @0.238s 9%: 0.009+0.15+0.080 ms clock, 0.14+0/0.22/0.16+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 184 @0.239s 9%: 0.005+0.14+0.10 ms clock, 0.092+0/0.26/0.18+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307576 HeapInuse: 622592 HeapObjects: 1954 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 185 @0.241s 9%: 0.007+0.15+0.10 ms clock, 0.12+0/0.27/0.20+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 186 @0.241s 9%: 0.007+0.16+0.096 ms clock, 0.12+0/0.24/0.15+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307672 HeapInuse: 622592 HeapObjects: 1955 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 187 @0.243s 9%: 0.009+0.15+0.096 ms clock, 0.14+0/0.26/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 188 @0.244s 9%: 0.009+0.16+0.076 ms clock, 0.15+0/0.24/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307672 HeapInuse: 622592 HeapObjects: 1955 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 189 @0.246s 9%: 0.009+0.17+0.12 ms clock, 0.14+0/0.28/0.28+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 190 @0.246s 9%: 0.007+0.16+0.095 ms clock, 0.12+0/0.27/0.16+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307864 HeapInuse: 622592 HeapObjects: 1957 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 191 @0.248s 9%: 0.009+0.19+0.10 ms clock, 0.14+0/0.32/0.14+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 192 @0.249s 9%: 0.015+0.18+0.090 ms clock, 0.24+0/0.22/0.32+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 307960 HeapInuse: 622592 HeapObjects: 1958 HeapIdle 1212416 HeapReleased 0 HeapSys 1835008
gc 193 @0.251s 9%: 0.015+0.14+0.093 ms clock, 0.24+0/0.24/0.21+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1920 ns/op	      90 B/op	       2 allocs/op
gc 194 @0.251s 9%: 0.011+0.14+0.086 ms clock, 0.18+0/0.25/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 404328 HeapInuse: 720896 HeapObjects: 3461 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 195 @0.254s 9%: 0.009+0.18+0.11 ms clock, 0.15+0/0.27/0.26+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetErase1E3-16                        	gc 196 @0.255s 9%: 0.011+0.19+0.098 ms clock, 0.18+0/0.16/0.36+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 404552 HeapInuse: 720896 HeapObjects: 3464 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 197 @0.258s 9%: 0.023+0.16+0.10 ms clock, 0.38+0/0.23/0.21+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 198 @0.259s 9%: 0.010+0.18+0.094 ms clock, 0.16+0/0.32/0.18+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 404728 HeapInuse: 720896 HeapObjects: 3465 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 199 @0.263s 9%: 0.009+0.16+0.088 ms clock, 0.15+0/0.32/0.15+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 200 @0.263s 9%: 0.014+0.13+0.096 ms clock, 0.22+0/0.24/0.24+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 404920 HeapInuse: 720896 HeapObjects: 3467 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 201 @0.266s 9%: 0.007+0.17+0.12 ms clock, 0.12+0/0.22/0.15+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 202 @0.267s 9%: 0.007+0.16+0.11 ms clock, 0.12+0/0.22/0.21+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405016 HeapInuse: 720896 HeapObjects: 3468 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 203 @0.270s 9%: 0.018+0.17+0.083 ms clock, 0.29+0/0.073/0.36+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 204 @0.270s 9%: 0.007+0.15+0.11 ms clock, 0.12+0/0.29/0.20+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405016 HeapInuse: 720896 HeapObjects: 3468 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 205 @0.274s 9%: 0.027+0.22+0.081 ms clock, 0.43+0/0.33/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 206 @0.274s 9%: 0.010+0.15+0.11 ms clock, 0.16+0/0.31/0.16+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405208 HeapInuse: 720896 HeapObjects: 3470 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 207 @0.277s 9%: 0.007+0.21+0.11 ms clock, 0.12+0/0.19/0.32+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 208 @0.278s 9%: 0.008+0.17+0.091 ms clock, 0.13+0/0.34/0.19+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405304 HeapInuse: 720896 HeapObjects: 3471 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 209 @0.281s 9%: 0.028+0.17+0.081 ms clock, 0.46+0/0.26/0.14+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 210 @0.282s 9%: 0.009+0.17+0.10 ms clock, 0.14+0/0.27/0.17+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405496 HeapInuse: 720896 HeapObjects: 3473 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 211 @0.285s 9%: 0.007+0.17+0.091 ms clock, 0.12+0/0.22/0.22+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 212 @0.285s 9%: 0.010+0.16+0.086 ms clock, 0.17+0/0.20/0.30+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405592 HeapInuse: 720896 HeapObjects: 3474 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 213 @0.288s 9%: 0.009+0.15+0.10 ms clock, 0.15+0/0.23/0.13+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 214 @0.289s 9%: 0.019+0.21+0.075 ms clock, 0.31+0/0.30/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405784 HeapInuse: 720896 HeapObjects: 3476 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 215 @0.292s 9%: 0.009+0.14+0.10 ms clock, 0.15+0/0.26/0.17+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 216 @0.293s 9%: 0.009+0.15+0.077 ms clock, 0.14+0/0.24/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 405976 HeapInuse: 720896 HeapObjects: 3478 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 217 @0.296s 9%: 0.008+0.16+0.090 ms clock, 0.12+0/0.18/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 218 @0.296s 9%: 0.008+0.16+0.092 ms clock, 0.12+0/0.22/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 406168 HeapInuse: 720896 HeapObjects: 3480 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 219 @0.300s 9%: 0.027+0.18+0.13 ms clock, 0.43+0/0.35/0.11+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 220 @0.300s 9%: 0.011+0.16+0.11 ms clock, 0.17+0/0.21/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 406360 HeapInuse: 720896 HeapObjects: 3482 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 221 @0.303s 9%: 0.023+0.15+0.096 ms clock, 0.37+0/0.28/0.25+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 222 @0.304s 9%: 0.025+0.16+0.10 ms clock, 0.40+0/0.27/0.17+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 406552 HeapInuse: 720896 HeapObjects: 3484 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 223 @0.307s 9%: 0.028+0.17+0.10 ms clock, 0.45+0/0.25/0.12+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 224 @0.308s 9%: 0.010+0.19+0.12 ms clock, 0.16+0/0.35/0.17+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 406744 HeapInuse: 720896 HeapObjects: 3486 HeapIdle 1114112 HeapReleased 0 HeapSys 1835008
gc 225 @0.311s 9%: 0.020+0.17+0.10 ms clock, 0.32+0/0.26/0.24+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1634 ns/op	      99 B/op	       2 allocs/op
gc 226 @0.311s 9%: 0.058+0.16+0.10 ms clock, 0.93+0/0.23/0.18+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318920 HeapInuse: 630784 HeapObjects: 1988 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 227 @0.313s 9%: 0.009+0.25+0.11 ms clock, 0.15+0/0.22/0.14+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndErase1E3-16               	gc 228 @0.314s 9%: 0.010+0.17+0.32 ms clock, 0.16+0/0.26/0.21+5.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318968 HeapInuse: 630784 HeapObjects: 1989 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 229 @0.315s 9%: 0.010+0.21+0.10 ms clock, 0.16+0/0.28/0.30+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 230 @0.316s 9%: 0.012+0.19+0.096 ms clock, 0.19+0/0.27/0.27+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319144 HeapInuse: 630784 HeapObjects: 1990 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 231 @0.318s 9%: 0.010+0.17+0.10 ms clock, 0.16+0/0.23/0.19+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 232 @0.318s 9%: 0.018+0.15+0.10 ms clock, 0.29+0/0.16/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319336 HeapInuse: 630784 HeapObjects: 1992 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 233 @0.320s 9%: 0.010+0.17+0.10 ms clock, 0.17+0/0.28/0.23+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 234 @0.320s 9%: 0.011+0.17+0.091 ms clock, 0.18+0/0.17/0.32+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319432 HeapInuse: 630784 HeapObjects: 1993 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 235 @0.322s 9%: 0.010+0.20+0.093 ms clock, 0.16+0/0.35/0.19+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 236 @0.322s 9%: 0.020+0.15+0.10 ms clock, 0.32+0/0.27/0.17+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319528 HeapInuse: 630784 HeapObjects: 1994 HeapIdle 1204224 HeapReleased 0 HeapSys 1835008
gc 237 @0.324s 9%: 0.008+0.19+0.080 ms clock, 0.14+0/0.17/0.29+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 238 @0.324s 9%: 0.005+0.20+0.085 ms clock, 0.095+0/0.25/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 321384 HeapInuse: 630784 HeapObjects: 1999 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 239 @0.326s 9%: 0.008+0.18+0.10 ms clock, 0.12+0/0.30/0.19+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 240 @0.327s 9%: 0.010+0.18+0.10 ms clock, 0.16+0/0.30/0.24+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 321576 HeapInuse: 630784 HeapObjects: 2001 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 241 @0.328s 9%: 0.009+0.24+0.10 ms clock, 0.15+0/0.30/0.31+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 242 @0.329s 9%: 0.022+0.16+0.090 ms clock, 0.35+0/0.28/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 321672 HeapInuse: 630784 HeapObjects: 2002 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 243 @0.331s 9%: 0.010+0.16+0.079 ms clock, 0.17+0/0.18/0.28+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 244 @0.331s 9%: 0.013+0.20+0.067 ms clock, 0.21+0/0.28/0.23+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 321928 HeapInuse: 630784 HeapObjects: 2005 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 245 @0.333s 9%: 0.008+0.15+0.10 ms clock, 0.14+0/0.25/0.25+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 246 @0.333s 9%: 0.006+0.17+0.10 ms clock, 0.097+0/0.30/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322024 HeapInuse: 630784 HeapObjects: 2006 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 247 @0.335s 9%: 0.020+0.25+0.10 ms clock, 0.33+0/0.24/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 248 @0.335s 9%: 0.011+0.24+0.078 ms clock, 0.17+0/0.26/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322024 HeapInuse: 630784 HeapObjects: 2006 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 249 @0.337s 9%: 0.009+0.20+0.096 ms clock, 0.14+0/0.36/0.32+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 250 @0.338s 9%: 0.015+0.15+0.087 ms clock, 0.24+0/0.29/0.29+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322120 HeapInuse: 630784 HeapObjects: 2007 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 251 @0.339s 9%: 0.009+0.14+0.091 ms clock, 0.15+0/0.27/0.22+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 252 @0.340s 9%: 0.012+0.31+0.10 ms clock, 0.19+0/0.47/0.10+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322312 HeapInuse: 630784 HeapObjects: 2009 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 253 @0.341s 9%: 0.010+0.20+0.12 ms clock, 0.16+0/0.31/0.28+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 254 @0.342s 9%: 0.014+0.16+0.088 ms clock, 0.22+0/0.26/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322504 HeapInuse: 630784 HeapObjects: 2011 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 255 @0.344s 9%: 0.010+0.41+0.10 ms clock, 0.17+0/0.67/0.35+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 256 @0.344s 9%: 0.012+0.15+0.062 ms clock, 0.20+0/0.28/0.32+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 322600 HeapInuse: 630784 HeapObjects: 2012 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 257 @0.346s 9%: 0.010+0.17+0.085 ms clock, 0.16+0/0.24/0.18+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1547 ns/op	      98 B/op	       2 allocs/op
gc 258 @0.346s 9%: 0.025+0.16+0.10 ms clock, 0.41+0/0.31/0.31+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 284864 HeapInuse: 598016 HeapObjects: 1519 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 259 @0.349s 9%: 0.010+0.19+0.088 ms clock, 0.16+0/0.20/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndEraseWithPool1E3-16       	gc 260 @0.349s 9%: 0.013+0.18+0.077 ms clock, 0.21+0/0.25/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285104 HeapInuse: 598016 HeapObjects: 1522 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 261 @0.351s 9%: 0.010+0.17+0.11 ms clock, 0.16+0/0.26/0.15+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 262 @0.352s 9%: 0.018+0.16+0.071 ms clock, 0.29+0/0.24/0.24+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285280 HeapInuse: 598016 HeapObjects: 1523 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 263 @0.354s 9%: 0.011+0.20+0.072 ms clock, 0.18+0/0.34/0.24+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 264 @0.354s 9%: 0.006+0.21+0.12 ms clock, 0.096+0/0.39/0.27+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285472 HeapInuse: 598016 HeapObjects: 1525 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 265 @0.357s 9%: 0.014+0.17+0.10 ms clock, 0.23+0/0.28/0.26+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 266 @0.357s 9%: 0.011+0.16+0.092 ms clock, 0.18+0/0.19/0.23+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285664 HeapInuse: 598016 HeapObjects: 1527 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 267 @0.359s 9%: 0.010+0.17+0.10 ms clock, 0.16+0/0.33/0.21+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 268 @0.360s 9%: 0.011+0.17+0.11 ms clock, 0.19+0/0.28/0.33+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285760 HeapInuse: 598016 HeapObjects: 1528 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 269 @0.362s 9%: 0.010+0.16+0.073 ms clock, 0.16+0/0.27/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 270 @0.362s 9%: 0.011+0.16+0.093 ms clock, 0.19+0/0.23/0.33+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 285856 HeapInuse: 598016 HeapObjects: 1529 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 271 @0.364s 9%: 0.009+0.20+0.085 ms clock, 0.15+0/0.28/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 272 @0.365s 9%: 0.009+0.22+0.10 ms clock, 0.14+0/0.25/0.26+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 286048 HeapInuse: 598016 HeapObjects: 1531 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 273 @0.367s 9%: 0.009+0.26+0.092 ms clock, 0.15+0/0.12/0.33+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 274 @0.367s 9%: 0.008+0.19+0.10 ms clock, 0.13+0/0.28/0.32+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 286240 HeapInuse: 598016 HeapObjects: 1533 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 275 @0.369s 9%: 0.009+0.19+0.098 ms clock, 0.15+0/0.34/0.31+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 276 @0.370s 9%: 0.011+0.17+0.11 ms clock, 0.19+0/0.28/0.31+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 286432 HeapInuse: 598016 HeapObjects: 1535 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 277 @0.372s 9%: 0.009+0.19+0.079 ms clock, 0.14+0/0.29/0.25+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 278 @0.372s 9%: 0.007+0.20+0.13 ms clock, 0.11+0/0.33/0.21+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 286624 HeapInuse: 598016 HeapObjects: 1537 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 279 @0.375s 9%: 0.014+0.17+0.11 ms clock, 0.23+0/0.31/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 280 @0.376s 9%: 0.022+0.18+0.093 ms clock, 0.35+0/0.30/0.21+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 286816 HeapInuse: 598016 HeapObjects: 1539 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 281 @0.378s 9%: 0.016+0.19+0.078 ms clock, 0.26+0/0.24/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 282 @0.378s 9%: 0.013+0.21+0.12 ms clock, 0.22+0/0.29/0.27+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 287008 HeapInuse: 598016 HeapObjects: 1541 HeapIdle 1204224 HeapReleased 0 HeapSys 1802240
gc 283 @0.380s 9%: 0.010+0.18+0.087 ms clock, 0.17+0/0.30/0.31+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 284 @0.381s 9%: 0.010+0.14+0.091 ms clock, 0.16+0/0.32/0.23+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 287200 HeapInuse: 606208 HeapObjects: 1543 HeapIdle 1196032 HeapReleased 0 HeapSys 1802240
gc 285 @0.383s 9%: 0.009+0.19+0.082 ms clock, 0.15+0/0.22/0.18+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 286 @0.383s 9%: 0.007+0.17+0.097 ms clock, 0.12+0/0.29/0.18+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 287200 HeapInuse: 606208 HeapObjects: 1543 HeapIdle 1196032 HeapReleased 0 HeapSys 1802240
gc 287 @0.385s 9%: 0.010+0.16+0.097 ms clock, 0.17+0/0.30/0.18+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 288 @0.386s 9%: 0.007+0.18+0.10 ms clock, 0.12+0/0.35/0.16+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 287392 HeapInuse: 606208 HeapObjects: 1545 HeapIdle 1196032 HeapReleased 0 HeapSys 1802240
gc 289 @0.388s 9%: 0.009+0.19+0.080 ms clock, 0.14+0/0.31/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	      1891 ns/op	      61 B/op	       1 allocs/op
gc 290 @0.388s 9%: 0.010+0.17+0.10 ms clock, 0.16+0/0.26/0.29+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282360 HeapInuse: 655360 HeapObjects: 614 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 291 @0.389s 9%: 0.010+0.17+0.080 ms clock, 0.17+0/0.29/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsert1E3-16                   	gc 292 @0.390s 9%: 0.010+0.27+0.073 ms clock, 0.16+0/0.17/0.38+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 281448 HeapInuse: 655360 HeapObjects: 601 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 293 @0.390s 9%: 0.009+0.21+0.10 ms clock, 0.15+0/0.35/0.25+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 294 @0.391s 9%: 0.011+0.17+0.085 ms clock, 0.17+0/0.19/0.38+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 283104 HeapInuse: 655360 HeapObjects: 619 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 295 @0.392s 9%: 0.008+0.25+0.10 ms clock, 0.13+0/0.38/0.19+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 296 @0.392s 9%: 0.020+0.17+0.076 ms clock, 0.32+0/0.25/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282192 HeapInuse: 655360 HeapObjects: 609 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 297 @0.393s 9%: 0.007+0.17+0.10 ms clock, 0.12+0/0.23/0.33+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 298 @0.394s 9%: 0.010+0.19+0.081 ms clock, 0.16+0/0.25/0.20+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282544 HeapInuse: 655360 HeapObjects: 613 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 299 @0.395s 9%: 0.009+0.16+0.073 ms clock, 0.15+0/0.26/0.33+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 300 @0.395s 9%: 0.009+0.16+0.096 ms clock, 0.15+0/0.27/0.18+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282656 HeapInuse: 655360 HeapObjects: 614 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 301 @0.396s 9%: 0.009+0.16+0.063 ms clock, 0.14+0/0.29/0.11+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 302 @0.396s 9%: 0.007+0.24+0.074 ms clock, 0.12+0/0.30/0.24+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282424 HeapInuse: 655360 HeapObjects: 611 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 303 @0.397s 9%: 0.010+0.15+0.069 ms clock, 0.17+0/0.23/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 304 @0.397s 9%: 0.011+0.23+0.076 ms clock, 0.18+0/0.36/0.17+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 281736 HeapInuse: 655360 HeapObjects: 603 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 305 @0.398s 9%: 0.010+0.17+0.068 ms clock, 0.17+0/0.32/0.30+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 306 @0.399s 9%: 0.007+0.18+0.057 ms clock, 0.12+0/0.33/0.24+0.91 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 283080 HeapInuse: 655360 HeapObjects: 617 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 307 @0.400s 9%: 0.009+0.18+0.089 ms clock, 0.15+0/0.29/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 308 @0.400s 9%: 0.011+0.14+0.058 ms clock, 0.17+0/0.27/0.22+0.93 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 284000 HeapInuse: 655360 HeapObjects: 628 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 309 @0.401s 9%: 0.010+0.16+0.092 ms clock, 0.16+0/0.30/0.18+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 310 @0.401s 9%: 0.012+0.15+0.077 ms clock, 0.20+0/0.23/0.29+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 284696 HeapInuse: 663552 HeapObjects: 635 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 311 @0.402s 9%: 0.010+0.17+0.071 ms clock, 0.16+0/0.27/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 312 @0.403s 9%: 0.008+0.19+0.071 ms clock, 0.14+0/0.30/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 282824 HeapInuse: 655360 HeapObjects: 614 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 313 @0.403s 9%: 0.008+0.16+0.081 ms clock, 0.14+0/0.10/0.42+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 314 @0.404s 9%: 0.014+0.16+0.076 ms clock, 0.23+0/0.22/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 283400 HeapInuse: 655360 HeapObjects: 620 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 315 @0.405s 9%: 0.008+0.15+0.071 ms clock, 0.13+0/0.27/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 316 @0.405s 9%: 0.011+0.17+0.095 ms clock, 0.18+0/0.28/0.28+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 283936 HeapInuse: 655360 HeapObjects: 629 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 317 @0.406s 9%: 0.009+0.17+0.078 ms clock, 0.15+0/0.31/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 318 @0.406s 9%: 0.009+0.19+0.093 ms clock, 0.14+0/0.18/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 283096 HeapInuse: 655360 HeapObjects: 617 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 319 @0.407s 9%: 0.009+0.16+0.084 ms clock, 0.15+0/0.24/0.23+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 320 @0.408s 9%: 0.007+0.16+0.074 ms clock, 0.11+0/0.15/0.27+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 284088 HeapInuse: 655360 HeapObjects: 628 HeapIdle 1146880 HeapReleased 0 HeapSys 1802240
gc 321 @0.408s 9%: 0.007+0.16+0.092 ms clock, 0.12+0/0.32/0.20+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	       742 ns/op	      56 B/op	       0 allocs/op
gc 322 @0.409s 9%: 0.030+0.17+0.079 ms clock, 0.48+0/0.26/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 292248 HeapInuse: 663552 HeapObjects: 632 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 323 @0.410s 9%: 0.009+0.18+0.087 ms clock, 0.14+0/0.31/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapErase1E3-16                    	gc 324 @0.410s 9%: 0.013+0.14+0.11 ms clock, 0.21+0/0.25/0.27+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 291488 HeapInuse: 663552 HeapObjects: 623 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 325 @0.411s 9%: 0.009+0.14+0.078 ms clock, 0.15+0/0.30/0.24+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 326 @0.412s 9%: 0.007+0.16+0.069 ms clock, 0.11+0/0.29/0.23+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 290656 HeapInuse: 663552 HeapObjects: 611 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 327 @0.413s 9%: 0.010+0.15+0.070 ms clock, 0.16+0/0.29/0.31+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 328 @0.413s 9%: 0.011+0.17+0.072 ms clock, 0.18+0/0.28/0.22+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293136 HeapInuse: 663552 HeapObjects: 637 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 329 @0.414s 9%: 0.007+0.14+0.083 ms clock, 0.12+0/0.31/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 330 @0.414s 9%: 0.010+0.16+0.077 ms clock, 0.17+0/0.28/0.32+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 294120 HeapInuse: 671744 HeapObjects: 647 HeapIdle 1130496 HeapReleased 0 HeapSys 1802240
gc 331 @0.415s 9%: 0.008+0.16+0.077 ms clock, 0.12+0/0.30/0.21+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 332 @0.416s 9%: 0.008+0.20+0.073 ms clock, 0.13+0/0.35/0.19+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 291832 HeapInuse: 663552 HeapObjects: 625 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 333 @0.417s 9%: 0.008+0.19+0.064 ms clock, 0.14+0/0.33/0.27+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 334 @0.417s 9%: 0.007+0.15+0.063 ms clock, 0.12+0/0.27/0.23+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 292176 HeapInuse: 663552 HeapObjects: 628 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 335 @0.418s 9%: 0.009+0.16+0.071 ms clock, 0.15+0/0.26/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 336 @0.419s 9%: 0.010+0.19+0.078 ms clock, 0.16+0/0.058/0.37+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 292216 HeapInuse: 663552 HeapObjects: 628 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 337 @0.420s 9%: 0.010+0.16+0.074 ms clock, 0.17+0/0.23/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 338 @0.420s 9%: 0.012+0.22+0.075 ms clock, 0.19+0/0.23/0.37+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293680 HeapInuse: 663552 HeapObjects: 645 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 339 @0.421s 9%: 0.009+0.17+0.081 ms clock, 0.14+0/0.29/0.30+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 340 @0.422s 10%: 0.010+0.26+0.085 ms clock, 0.17+0/0.089/0.41+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293688 HeapInuse: 663552 HeapObjects: 644 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 341 @0.423s 10%: 0.008+0.61+0.15 ms clock, 0.14+0/0.39/0.12+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 342 @0.424s 10%: 0.008+0.19+0.077 ms clock, 0.13+0/0.23/0.35+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 292568 HeapInuse: 663552 HeapObjects: 632 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 343 @0.425s 10%: 0.007+0.19+0.080 ms clock, 0.12+0/0.40/0.28+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 344 @0.425s 10%: 0.012+0.17+0.073 ms clock, 0.20+0/0.30/0.30+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293168 HeapInuse: 663552 HeapObjects: 639 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 345 @0.426s 10%: 0.009+0.16+0.088 ms clock, 0.15+0/0.30/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 346 @0.426s 10%: 0.007+0.15+0.069 ms clock, 0.12+0/0.32/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293040 HeapInuse: 663552 HeapObjects: 639 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 347 @0.427s 10%: 0.007+0.17+0.088 ms clock, 0.12+0/0.29/0.28+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 348 @0.428s 10%: 0.013+0.15+0.082 ms clock, 0.21+0/0.31/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 292864 HeapInuse: 663552 HeapObjects: 637 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 349 @0.429s 10%: 0.010+0.16+0.072 ms clock, 0.16+0/0.26/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 350 @0.429s 10%: 0.011+0.16+0.088 ms clock, 0.18+0/0.30/0.24+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 293448 HeapInuse: 663552 HeapObjects: 640 HeapIdle 1138688 HeapReleased 0 HeapSys 1802240
gc 351 @0.430s 10%: 0.009+0.19+0.093 ms clock, 0.15+0/0.28/0.41+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	       524 ns/op	      10 B/op	       0 allocs/op
gc 352 @0.431s 10%: 0.070+0.19+0.087 ms clock, 1.1+0/0.35/0.20+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237584 HeapInuse: 581632 HeapObjects: 602 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 353 @0.431s 10%: 0.010+0.19+0.083 ms clock, 0.16+0/0.33/0.28+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndErase1E3-16           	gc 354 @0.432s 10%: 0.042+0.22+0.070 ms clock, 0.67+0/0.27/0.22+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237800 HeapInuse: 581632 HeapObjects: 607 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 355 @0.433s 10%: 0.009+0.16+0.078 ms clock, 0.15+0/0.30/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 356 @0.433s 10%: 0.010+0.18+0.086 ms clock, 0.16+0/0.36/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237520 HeapInuse: 581632 HeapObjects: 601 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 357 @0.434s 10%: 0.007+0.20+0.075 ms clock, 0.11+0/0.27/0.36+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 358 @0.434s 10%: 0.006+0.14+0.067 ms clock, 0.10+0/0.29/0.30+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237944 HeapInuse: 581632 HeapObjects: 607 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 359 @0.435s 10%: 0.010+0.15+0.078 ms clock, 0.17+0/0.32/0.18+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 360 @0.435s 10%: 0.007+0.17+0.076 ms clock, 0.12+0/0.32/0.29+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237800 HeapInuse: 581632 HeapObjects: 603 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 361 @0.436s 10%: 0.009+0.16+0.085 ms clock, 0.14+0/0.28/0.25+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 362 @0.436s 10%: 0.011+0.24+0.24 ms clock, 0.18+0/0.28/0.25+3.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237848 HeapInuse: 581632 HeapObjects: 602 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 363 @0.437s 10%: 0.008+0.20+0.080 ms clock, 0.12+0/0.43/0.21+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 364 @0.438s 10%: 0.014+0.16+0.072 ms clock, 0.22+0/0.27/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237160 HeapInuse: 573440 HeapObjects: 596 HeapIdle 1228800 HeapReleased 0 HeapSys 1802240
gc 365 @0.438s 10%: 0.009+0.16+0.080 ms clock, 0.14+0/0.33/0.40+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 366 @0.439s 10%: 0.012+0.16+0.069 ms clock, 0.19+0/0.31/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237816 HeapInuse: 573440 HeapObjects: 606 HeapIdle 1228800 HeapReleased 0 HeapSys 1802240
gc 367 @0.439s 10%: 0.009+0.17+0.079 ms clock, 0.15+0/0.30/0.20+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 368 @0.440s 10%: 0.006+0.18+0.078 ms clock, 0.098+0/0.31/0.32+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 237944 HeapInuse: 581632 HeapObjects: 603 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 369 @0.440s 10%: 0.009+0.25+0.081 ms clock, 0.14+0/0.23/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 370 @0.441s 10%: 0.009+0.17+0.075 ms clock, 0.15+0/0.27/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238384 HeapInuse: 581632 HeapObjects: 610 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 371 @0.441s 10%: 0.008+0.17+0.079 ms clock, 0.13+0/0.28/0.35+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 372 @0.442s 10%: 0.005+0.18+0.074 ms clock, 0.093+0/0.29/0.22+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238160 HeapInuse: 581632 HeapObjects: 604 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 373 @0.443s 10%: 0.007+0.25+0.073 ms clock, 0.12+0/0.14/0.36+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 374 @0.443s 10%: 0.010+0.21+0.076 ms clock, 0.17+0/0.25/0.20+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238336 HeapInuse: 581632 HeapObjects: 609 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 375 @0.444s 10%: 0.007+0.18+0.074 ms clock, 0.12+0/0.29/0.22+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 376 @0.444s 10%: 0.009+0.18+0.096 ms clock, 0.14+0/0.29/0.23+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238360 HeapInuse: 573440 HeapObjects: 612 HeapIdle 1228800 HeapReleased 0 HeapSys 1802240
gc 377 @0.445s 10%: 0.007+0.23+0.075 ms clock, 0.12+0/0.27/0.34+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 378 @0.445s 10%: 0.008+0.16+0.074 ms clock, 0.12+0/0.34/0.35+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238864 HeapInuse: 581632 HeapObjects: 616 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 379 @0.446s 10%: 0.009+0.18+0.081 ms clock, 0.15+0/0.26/0.36+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 380 @0.446s 10%: 0.013+0.18+0.076 ms clock, 0.20+0/0.24/0.36+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 238624 HeapInuse: 581632 HeapObjects: 612 HeapIdle 1220608 HeapReleased 0 HeapSys 1802240
gc 381 @0.447s 10%: 0.009+0.17+0.069 ms clock, 0.15+0/0.28/0.27+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	       531 ns/op	       7 B/op	       0 allocs/op
gc 382 @0.447s 10%: 0.012+0.17+0.077 ms clock, 0.20+0/0.28/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259080 HeapInuse: 565248 HeapObjects: 589 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 383 @0.448s 10%: 0.008+0.18+0.091 ms clock, 0.13+0/0.27/0.29+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndEraseWithBuf1E3-16    	gc 384 @0.449s 10%: 0.011+0.17+0.093 ms clock, 0.18+0/0.28/0.30+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259320 HeapInuse: 565248 HeapObjects: 592 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 385 @0.449s 10%: 0.011+0.17+0.075 ms clock, 0.17+0/0.26/0.29+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 386 @0.450s 10%: 0.012+0.23+0.080 ms clock, 0.20+0/0.35/0.30+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259496 HeapInuse: 565248 HeapObjects: 593 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 387 @0.450s 10%: 0.009+0.21+0.068 ms clock, 0.15+0/0.24/0.37+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 388 @0.451s 10%: 0.012+0.16+0.069 ms clock, 0.20+0/0.29/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259688 HeapInuse: 565248 HeapObjects: 595 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 389 @0.451s 10%: 0.008+0.17+0.077 ms clock, 0.14+0/0.32/0.17+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 390 @0.452s 10%: 0.047+0.18+0.079 ms clock, 0.76+0/0.33/0.36+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259688 HeapInuse: 565248 HeapObjects: 595 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 391 @0.452s 10%: 0.007+0.18+0.082 ms clock, 0.12+0/0.32/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 392 @0.453s 10%: 0.011+0.36+0.066 ms clock, 0.18+0/0.21/0.30+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 259880 HeapInuse: 565248 HeapObjects: 597 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 393 @0.453s 10%: 0.009+0.18+0.081 ms clock, 0.15+0/0.30/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 394 @0.454s 10%: 0.011+0.17+0.089 ms clock, 0.17+0/0.28/0.27+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260072 HeapInuse: 565248 HeapObjects: 599 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 395 @0.455s 10%: 0.009+0.18+0.081 ms clock, 0.14+0/0.32/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 396 @0.455s 10%: 0.007+0.15+0.074 ms clock, 0.12+0/0.29/0.26+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260168 HeapInuse: 565248 HeapObjects: 600 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 397 @0.456s 10%: 0.009+0.18+0.072 ms clock, 0.15+0/0.32/0.34+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 398 @0.456s 10%: 0.009+0.14+0.075 ms clock, 0.15+0/0.33/0.20+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260360 HeapInuse: 565248 HeapObjects: 602 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 399 @0.457s 10%: 0.009+0.19+0.074 ms clock, 0.14+0/0.34/0.32+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 400 @0.457s 10%: 0.010+0.17+0.084 ms clock, 0.17+0/0.27/0.30+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260552 HeapInuse: 565248 HeapObjects: 604 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 401 @0.458s 10%: 0.007+0.23+0.074 ms clock, 0.12+0/0.24/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 402 @0.458s 10%: 0.009+0.18+0.066 ms clock, 0.15+0/0.34/0.16+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260648 HeapInuse: 565248 HeapObjects: 605 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 403 @0.459s 10%: 0.009+0.17+0.076 ms clock, 0.14+0/0.33/0.27+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 404 @0.459s 10%: 0.011+0.21+0.077 ms clock, 0.18+0/0.29/0.17+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260744 HeapInuse: 565248 HeapObjects: 606 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 405 @0.460s 10%: 0.009+0.19+0.074 ms clock, 0.14+0/0.31/0.27+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 406 @0.460s 10%: 0.012+0.21+0.086 ms clock, 0.19+0/0.37/0.21+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260744 HeapInuse: 565248 HeapObjects: 606 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 407 @0.461s 10%: 0.009+0.17+0.074 ms clock, 0.15+0/0.31/0.24+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 408 @0.461s 10%: 0.009+0.17+0.067 ms clock, 0.15+0/0.25/0.28+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260744 HeapInuse: 565248 HeapObjects: 606 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 409 @0.462s 10%: 0.009+0.21+0.071 ms clock, 0.14+0/0.24/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 410 @0.462s 10%: 0.009+0.18+0.076 ms clock, 0.15+0/0.27/0.32+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 260936 HeapInuse: 565248 HeapObjects: 608 HeapIdle 1236992 HeapReleased 0 HeapSys 1802240
gc 411 @0.463s 10%: 0.010+0.17+0.076 ms clock, 0.16+0/0.33/0.28+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
    1000	       511 ns/op	      28 B/op	       0 allocs/op
gc 412 @0.463s 10%: 0.013+0.21+0.094 ms clock, 0.22+0/0.38/0.11+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 317544 HeapInuse: 622592 HeapObjects: 609 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 413 @0.466s 10%: 0.008+0.17+0.088 ms clock, 0.13+0/0.29/0.20+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSort1E4-16                               	gc 414 @0.466s 10%: 0.012+0.17+0.094 ms clock, 0.20+0/0.28/0.31+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 317768 HeapInuse: 622592 HeapObjects: 612 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 415 @0.469s 10%: 0.009+0.21+0.073 ms clock, 0.15+0/0.29/0.35+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 416 @0.470s 10%: 0.009+0.21+0.081 ms clock, 0.15+0/0.37/0.28+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 317944 HeapInuse: 622592 HeapObjects: 613 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 417 @0.472s 10%: 0.012+0.15+0.079 ms clock, 0.20+0/0.30/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 418 @0.473s 10%: 0.013+0.24+0.089 ms clock, 0.21+0/0.31/0.25+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318136 HeapInuse: 622592 HeapObjects: 615 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 419 @0.475s 10%: 0.008+0.16+0.071 ms clock, 0.13+0/0.28/0.34+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 420 @0.476s 10%: 0.007+0.19+0.079 ms clock, 0.12+0/0.28/0.33+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318328 HeapInuse: 622592 HeapObjects: 617 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 421 @0.478s 10%: 0.007+0.20+0.073 ms clock, 0.12+0/0.24/0.31+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 422 @0.479s 10%: 0.007+0.17+0.072 ms clock, 0.11+0/0.30/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318520 HeapInuse: 622592 HeapObjects: 619 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 423 @0.481s 10%: 0.009+0.21+0.084 ms clock, 0.14+0/0.27/0.34+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 424 @0.482s 10%: 0.010+0.21+0.078 ms clock, 0.16+0/0.36/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318520 HeapInuse: 622592 HeapObjects: 619 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 425 @0.485s 10%: 0.009+0.16+0.071 ms clock, 0.14+0/0.29/0.27+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 426 @0.485s 10%: 0.007+0.27+0.090 ms clock, 0.12+0/0.26/0.20+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318520 HeapInuse: 622592 HeapObjects: 619 HeapIdle 1179648 HeapReleased 0 HeapSys 1802240
gc 427 @0.488s 10%: 0.009+0.17+0.080 ms clock, 0.15+0/0.30/0.28+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 428 @0.488s 10%: 0.009+0.16+0.075 ms clock, 0.15+0/0.33/0.22+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318616 HeapInuse: 630784 HeapObjects: 620 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 429 @0.491s 10%: 0.008+0.18+0.11 ms clock, 0.13+0/0.32/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 430 @0.491s 10%: 0.010+0.20+0.10 ms clock, 0.16+0/0.38/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318712 HeapInuse: 630784 HeapObjects: 621 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 431 @0.494s 10%: 0.008+0.19+0.095 ms clock, 0.13+0/0.33/0.28+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 432 @0.494s 10%: 0.010+0.18+0.080 ms clock, 0.16+0/0.31/0.25+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 318904 HeapInuse: 630784 HeapObjects: 623 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 433 @0.497s 10%: 0.026+0.19+0.12 ms clock, 0.42+0/0.30/0.24+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 434 @0.498s 10%: 0.010+0.21+0.11 ms clock, 0.17+0/0.34/0.27+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319000 HeapInuse: 630784 HeapObjects: 624 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 435 @0.500s 10%: 0.026+0.18+0.11 ms clock, 0.42+0/0.35/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 436 @0.501s 10%: 0.007+0.17+0.086 ms clock, 0.12+0/0.29/0.28+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319096 HeapInuse: 630784 HeapObjects: 625 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 437 @0.503s 10%: 0.020+0.18+0.10 ms clock, 0.32+0/0.31/0.23+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 438 @0.504s 10%: 0.011+0.18+0.11 ms clock, 0.17+0/0.29/0.25+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 319288 HeapInuse: 630784 HeapObjects: 627 HeapIdle 1171456 HeapReleased 0 HeapSys 1802240
gc 439 @0.506s 10%: 0.009+0.21+0.092 ms clock, 0.15+0/0.29/0.30+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	       259 ns/op	       8 B/op	       0 allocs/op
gc 440 @0.507s 10%: 0.013+0.21+0.10 ms clock, 0.20+0/0.16/0.41+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117784 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 441 @0.531s 10%: 0.013+0.20+0.12 ms clock, 0.21+0/0.29/0.27+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsert1E4-16                          	gc 442 @0.532s 10%: 0.058+0.21+0.11 ms clock, 0.93+0/0.32/0.15+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117816 HeapInuse: 1433600 HeapObjects: 15632 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 443 @0.555s 9%: 0.033+0.22+0.17 ms clock, 0.54+0/0.41/0.18+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 444 @0.556s 9%: 0.020+0.19+0.10 ms clock, 0.32+0/0.28/0.22+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 445 @0.579s 9%: 0.051+0.23+0.19 ms clock, 0.82+0/0.28/0.27+3.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 446 @0.580s 9%: 0.028+0.21+0.19 ms clock, 0.45+0/0.36/0.15+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 447 @0.604s 9%: 0.009+0.26+0.23 ms clock, 0.15+0/0.35/0.26+3.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 448 @0.605s 9%: 0.019+0.22+0.17 ms clock, 0.31+0/0.37/0.21+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 449 @0.629s 8%: 0.009+0.24+0.18 ms clock, 0.14+0/0.33/0.19+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 450 @0.629s 8%: 0.036+0.21+0.16 ms clock, 0.58+0/0.27/0.25+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 451 @0.654s 8%: 0.009+0.25+0.14 ms clock, 0.15+0/0.35/0.28+2.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 452 @0.654s 8%: 0.025+0.19+0.11 ms clock, 0.40+0/0.35/0.19+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 453 @0.678s 8%: 0.056+0.22+0.21 ms clock, 0.91+0/0.31/0.21+3.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 454 @0.679s 8%: 0.021+0.24+0.17 ms clock, 0.33+0/0.45/0.098+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 455 @0.702s 8%: 0.047+0.21+0.18 ms clock, 0.76+0/0.39/0.17+2.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 456 @0.703s 8%: 0.038+0.26+0.14 ms clock, 0.62+0/0.22/0.27+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 457 @0.727s 7%: 0.016+0.25+0.12 ms clock, 0.25+0/0.41/0.24+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 458 @0.727s 7%: 0.020+0.22+0.19 ms clock, 0.32+0/0.32/0.31+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117800 HeapInuse: 1433600 HeapObjects: 15631 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 459 @0.751s 7%: 0.053+0.33+0.17 ms clock, 0.86+0/0.42/0.22+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 460 @0.752s 7%: 0.020+0.20+0.10 ms clock, 0.32+0/0.35/0.16+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117896 HeapInuse: 1433600 HeapObjects: 15632 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 461 @0.775s 7%: 0.010+0.21+0.20 ms clock, 0.16+0/0.29/0.21+3.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 462 @0.776s 7%: 0.011+0.23+0.14 ms clock, 0.18+0/0.34/0.29+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117992 HeapInuse: 1433600 HeapObjects: 15633 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 463 @0.800s 7%: 0.024+0.25+0.13 ms clock, 0.38+0/0.25/0.32+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 464 @0.801s 7%: 0.012+0.23+0.10 ms clock, 0.19+0/0.34/0.17+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117992 HeapInuse: 1433600 HeapObjects: 15633 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 465 @0.825s 7%: 0.061+0.22+0.21 ms clock, 0.98+0/0.32/0.21+3.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 466 @0.825s 7%: 0.036+0.19+0.15 ms clock, 0.58+0/0.30/0.20+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117992 HeapInuse: 1433600 HeapObjects: 15633 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 467 @0.854s 6%: 0.029+0.64+0.29 ms clock, 0.47+0/0.60/0+4.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 468 @0.855s 6%: 0.007+0.36+0.10 ms clock, 0.12+0/0.34/0.32+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1117992 HeapInuse: 1433600 HeapObjects: 15633 HeapIdle 368640 HeapReleased 0 HeapSys 1802240
gc 469 @0.881s 6%: 0.055+0.25+0.12 ms clock, 0.89+0/0.42/0.18+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 470 @0.882s 6%: 0.016+0.23+0.13 ms clock, 0.26+0/0.27/0.31+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1119656 HeapInuse: 1433600 HeapObjects: 15636 HeapIdle 335872 HeapReleased 0 HeapSys 1769472
gc 471 @0.912s 6%: 0.017+0.25+0.087 ms clock, 0.28+0/0.35/0.30+1.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
   10000	      2974 ns/op	      88 B/op	       2 allocs/op
gc 472 @0.913s 6%: 0.012+0.23+0.10 ms clock, 0.19+0/0.37/0.21+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081560 HeapInuse: 2400256 HeapObjects: 30637 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 473 @0.961s 6%: 0.47+0.27+0.12 ms clock, 7.6+0/0.39/0.30+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetErase1E4-16                           	gc 474 @0.963s 6%: 0.059+0.26+0.11 ms clock, 0.94+0/0.48/0.28+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081592 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 475 @1.009s 6%: 0.009+0.30+0.11 ms clock, 0.15+0/0.48/0.17+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 476 @1.010s 6%: 0.014+0.22+0.12 ms clock, 0.22+0/0.41/0.31+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081576 HeapInuse: 2400256 HeapObjects: 30637 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 477 @1.051s 5%: 0.010+0.22+0.14 ms clock, 0.17+0/0.30/0.22+2.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 478 @1.051s 5%: 0.025+0.18+0.095 ms clock, 0.40+0/0.31/0.19+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 479 @1.091s 5%: 0.022+0.22+0.17 ms clock, 0.36+0/0.28/0.24+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 480 @1.092s 5%: 0.010+0.22+0.17 ms clock, 0.16+0/0.31/0.18+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 481 @1.132s 5%: 0.010+0.24+0.16 ms clock, 0.16+0/0.31/0.21+2.6 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 482 @1.132s 5%: 0.007+0.20+0.12 ms clock, 0.12+0/0.34/0.14+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 483 @1.173s 5%: 0.044+0.22+0.19 ms clock, 0.71+0/0.28/0.21+3.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 484 @1.173s 5%: 0.040+0.20+0.18 ms clock, 0.64+0/0.20/0.19+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 485 @1.213s 5%: 0.026+0.28+0.093 ms clock, 0.43+0/0.43/0.21+1.4 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 486 @1.214s 5%: 0.020+0.20+0.10 ms clock, 0.33+0/0.37/0.25+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 487 @1.253s 5%: 0.040+0.21+0.22 ms clock, 0.64+0/0.27/0.14+3.5 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 488 @1.254s 5%: 0.020+0.28+0.14 ms clock, 0.32+0/0.30/0.41+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 489 @1.293s 4%: 0.008+0.23+0.13 ms clock, 0.14+0/0.30/0.20+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 490 @1.294s 4%: 0.011+0.21+0.11 ms clock, 0.18+0/0.40/0.13+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 491 @1.333s 4%: 0.008+0.20+0.12 ms clock, 0.13+0/0.38/0.10+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 492 @1.334s 4%: 0.017+0.19+0.11 ms clock, 0.27+0/0.36/0.23+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081672 HeapInuse: 2400256 HeapObjects: 30638 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 493 @1.373s 4%: 0.027+0.24+0.15 ms clock, 0.44+0/0.30/0.20+2.4 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 494 @1.374s 4%: 0.025+0.21+0.13 ms clock, 0.40+0/0.32/0.12+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081768 HeapInuse: 2400256 HeapObjects: 30639 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 495 @1.413s 4%: 0.061+0.21+0.13 ms clock, 0.98+0/0.37/0.18+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 496 @1.414s 4%: 0.011+0.21+0.11 ms clock, 0.18+0/0.19/0.19+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081864 HeapInuse: 2400256 HeapObjects: 30640 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 497 @1.454s 4%: 0.041+0.22+0.15 ms clock, 0.66+0/0.42/0.20+2.5 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 498 @1.454s 4%: 0.056+0.22+0.13 ms clock, 0.90+0/0.19/0.21+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2081960 HeapInuse: 2400256 HeapObjects: 30641 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 499 @1.494s 4%: 0.009+0.20+0.17 ms clock, 0.15+0/0.21/0.23+2.7 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 500 @1.495s 4%: 0.008+0.22+0.11 ms clock, 0.13+0/0.35/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2082056 HeapInuse: 2400256 HeapObjects: 30642 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 501 @1.534s 4%: 0.014+0.21+0.17 ms clock, 0.23+0/0.26/0.27+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 502 @1.535s 4%: 0.024+0.27+0.22 ms clock, 0.39+0/0.21/0.23+3.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2082056 HeapInuse: 2400256 HeapObjects: 30642 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 503 @1.574s 4%: 0.009+0.25+0.16 ms clock, 0.15+0/0.37/0.22+2.6 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
   10000	      1638 ns/op	      96 B/op	       2 allocs/op
gc 504 @1.575s 4%: 0.054+0.30+0.12 ms clock, 0.87+0/0.091/0.34+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202040 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 505 @1.591s 4%: 0.009+0.22+0.10 ms clock, 0.15+0/0.42/0.18+1.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndErase1E4-16                  	gc 506 @1.592s 4%: 0.022+0.19+0.12 ms clock, 0.36+0/0.45/0.079+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202072 HeapInuse: 1515520 HeapObjects: 15643 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 507 @1.609s 4%: 0.036+0.18+0.16 ms clock, 0.58+0/0.25/0.13+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 508 @1.610s 4%: 0.022+0.20+0.12 ms clock, 0.35+0/0.35/0.19+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 509 @1.626s 4%: 0.009+0.26+0.13 ms clock, 0.15+0/0.35/0.20+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 510 @1.627s 4%: 0.024+0.21+0.099 ms clock, 0.38+0/0.31/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 511 @1.643s 4%: 0.010+0.23+0.15 ms clock, 0.16+0/0.40/0.19+2.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 512 @1.644s 4%: 0.018+0.23+0.19 ms clock, 0.30+0/0.33/0.44+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 513 @1.661s 4%: 0.068+0.30+0.16 ms clock, 1.0+0/0.34/0.13+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 514 @1.662s 4%: 0.022+0.20+0.11 ms clock, 0.35+0/0.36/0.15+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 515 @1.678s 4%: 0.012+0.24+0.16 ms clock, 0.20+0/0.45/0.17+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 516 @1.679s 4%: 0.058+0.26+0.13 ms clock, 0.94+0/0.39/0.18+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 517 @1.696s 4%: 0.010+0.26+0.15 ms clock, 0.16+0/0.45/0.23+2.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 518 @1.697s 4%: 0.031+0.23+0.10 ms clock, 0.50+0/0.24/0.31+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 519 @1.714s 4%: 0.013+0.21+0.12 ms clock, 0.22+0/0.32/0.17+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 520 @1.714s 4%: 0.039+0.19+0.10 ms clock, 0.62+0/0.31/0.14+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 521 @1.731s 4%: 0.054+0.21+0.19 ms clock, 0.86+0/0.30/0.25+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 522 @1.732s 4%: 0.008+0.24+0.13 ms clock, 0.13+0/0.37/0.20+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202056 HeapInuse: 1515520 HeapObjects: 15642 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 523 @1.748s 4%: 0.022+0.20+0.14 ms clock, 0.35+0/0.31/0.22+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 524 @1.749s 4%: 0.010+0.18+0.13 ms clock, 0.16+0/0.30/0.32+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202152 HeapInuse: 1515520 HeapObjects: 15643 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 525 @1.765s 4%: 0.011+0.24+0.13 ms clock, 0.18+0/0.46/0.17+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 526 @1.766s 4%: 0.020+0.26+0.11 ms clock, 0.33+0/0.34/0.26+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202248 HeapInuse: 1515520 HeapObjects: 15644 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 527 @1.783s 3%: 0.055+0.26+0.12 ms clock, 0.88+0/0.39/0.14+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 528 @1.783s 3%: 0.022+0.19+0.11 ms clock, 0.36+0/0.33/0.12+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202344 HeapInuse: 1515520 HeapObjects: 15645 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 529 @1.800s 3%: 0.020+0.23+0.12 ms clock, 0.32+0/0.39/0.18+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 530 @1.800s 3%: 0.016+0.20+0.11 ms clock, 0.25+0/0.29/0.12+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202440 HeapInuse: 1515520 HeapObjects: 15646 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 531 @1.817s 3%: 0.049+0.22+0.13 ms clock, 0.79+0/0.42/0.17+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 532 @1.817s 3%: 0.013+0.24+0.18 ms clock, 0.20+0/0.31/0.28+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202536 HeapInuse: 1515520 HeapObjects: 15647 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 533 @1.834s 3%: 0.011+0.22+0.17 ms clock, 0.19+0/0.42/0.17+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 534 @1.835s 3%: 0.021+0.19+0.16 ms clock, 0.34+0/0.37/0.34+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1202536 HeapInuse: 1515520 HeapObjects: 15647 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 535 @1.851s 3%: 0.008+0.21+0.12 ms clock, 0.14+0/0.34/0.23+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
   10000	      1648 ns/op	      96 B/op	       2 allocs/op
gc 536 @1.852s 3%: 0.090+0.20+0.11 ms clock, 1.4+0/0.29/0.22+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 804720 HeapInuse: 1122304 HeapObjects: 10653 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 537 @1.873s 3%: 0.011+0.24+0.13 ms clock, 0.17+0/0.33/0.17+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndEraseWithPool1E4-16          	gc 538 @1.874s 3%: 0.055+0.27+0.14 ms clock, 0.88+0/0.31/0.21+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 804864 HeapInuse: 1122304 HeapObjects: 10655 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 539 @1.894s 3%: 0.052+0.21+0.18 ms clock, 0.84+0/0.41/0.079+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 540 @1.895s 3%: 0.020+0.22+0.10 ms clock, 0.32+0/0.36/0.14+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 804848 HeapInuse: 1122304 HeapObjects: 10654 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 541 @1.915s 3%: 0.050+0.23+0.15 ms clock, 0.80+0/0.34/0.13+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 542 @1.916s 3%: 0.026+0.24+0.12 ms clock, 0.43+0/0.36/0.26+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 804848 HeapInuse: 1122304 HeapObjects: 10654 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 543 @1.937s 3%: 0.28+0.25+0.19 ms clock, 4.5+0/0.43/0.18+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 544 @1.938s 3%: 0.014+0.22+0.13 ms clock, 0.23+0/0.36/0.18+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 804944 HeapInuse: 1122304 HeapObjects: 10655 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 545 @1.958s 3%: 0.058+0.20+0.17 ms clock, 0.94+0/0.30/0.18+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 546 @1.958s 3%: 0.017+0.22+0.12 ms clock, 0.28+0/0.30/0.26+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805040 HeapInuse: 1122304 HeapObjects: 10656 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 547 @1.979s 3%: 0.050+0.21+0.14 ms clock, 0.80+0/0.31/0.23+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 548 @1.979s 3%: 0.042+0.28+0.15 ms clock, 0.68+0/0.23/0.18+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805040 HeapInuse: 1122304 HeapObjects: 10656 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 549 @2.000s 3%: 0.053+0.21+0.17 ms clock, 0.86+0/0.40/0.15+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 550 @2.001s 3%: 0.016+0.23+0.11 ms clock, 0.26+0/0.38/0.18+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805136 HeapInuse: 1122304 HeapObjects: 10657 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 551 @2.021s 3%: 0.053+0.24+0.11 ms clock, 0.85+0/0.29/0.18+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 552 @2.022s 3%: 0.018+0.20+0.12 ms clock, 0.28+0/0.29/0.24+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805232 HeapInuse: 1122304 HeapObjects: 10658 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 553 @2.042s 3%: 0.028+0.22+0.15 ms clock, 0.45+0/0.28/0.26+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 554 @2.043s 3%: 0.024+0.21+0.069 ms clock, 0.38+0/0.32/0.20+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805328 HeapInuse: 1122304 HeapObjects: 10659 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 555 @2.063s 3%: 0.020+0.19+0.10 ms clock, 0.33+0/0.31/0.24+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 556 @2.064s 3%: 0.017+0.20+0.094 ms clock, 0.28+0/0.30/0.32+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805424 HeapInuse: 1122304 HeapObjects: 10660 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 557 @2.084s 3%: 0.008+0.23+0.14 ms clock, 0.13+0/0.18/0.33+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 558 @2.084s 3%: 0.010+0.21+0.13 ms clock, 0.16+0/0.35/0.37+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805616 HeapInuse: 1122304 HeapObjects: 10662 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 559 @2.105s 3%: 0.009+0.24+0.11 ms clock, 0.15+0/0.36/0.13+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 560 @2.105s 3%: 0.012+0.22+0.11 ms clock, 0.19+0/0.29/0.16+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805712 HeapInuse: 1122304 HeapObjects: 10663 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 561 @2.126s 3%: 0.010+0.20+0.17 ms clock, 0.16+0/0.39/0.25+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 562 @2.127s 3%: 0.078+0.24+0.13 ms clock, 1.2+0/0.35/0.15+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805808 HeapInuse: 1122304 HeapObjects: 10664 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 563 @2.148s 3%: 0.008+0.37+0.13 ms clock, 0.13+0/0.38/0.48+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 564 @2.148s 3%: 0.017+0.24+0.12 ms clock, 0.28+0/0.32/0.24+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805808 HeapInuse: 1122304 HeapObjects: 10664 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 565 @2.170s 3%: 0.012+0.21+0.17 ms clock, 0.19+0/0.22/0.18+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 566 @2.171s 3%: 0.082+0.23+0.12 ms clock, 1.3+0/0.31/0.12+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 805808 HeapInuse: 1122304 HeapObjects: 10664 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 567 @2.192s 3%: 0.013+0.26+0.12 ms clock, 0.20+0/0.54/0.33+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	      2118 ns/op	      56 B/op	       1 allocs/op
gc 568 @2.193s 3%: 0.072+0.31+0.096 ms clock, 1.1+0/0.32/0.32+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121640 HeapInuse: 1433600 HeapObjects: 15656 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 569 @2.213s 3%: 0.012+0.19+0.083 ms clock, 0.19+0/0.33/0.30+1.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsert1E4-16                       	gc 570 @2.213s 3%: 0.052+0.20+0.12 ms clock, 0.84+0/0.33/0.25+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121768 HeapInuse: 1433600 HeapObjects: 15658 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 571 @2.232s 3%: 0.008+0.20+0.15 ms clock, 0.13+0/0.29/0.15+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 572 @2.233s 3%: 0.026+0.23+0.10 ms clock, 0.42+0/0.34/0.18+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121752 HeapInuse: 1433600 HeapObjects: 15657 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 573 @2.252s 3%: 0.050+0.22+0.15 ms clock, 0.81+0/0.39/0.15+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 574 @2.253s 3%: 0.047+0.28+0.18 ms clock, 0.75+0/0.29/0.18+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121752 HeapInuse: 1433600 HeapObjects: 15657 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 575 @2.272s 3%: 0.008+0.23+0.14 ms clock, 0.14+0/0.36/0.17+2.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 576 @2.272s 3%: 0.029+0.22+0.12 ms clock, 0.47+0/0.25/0.18+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121752 HeapInuse: 1433600 HeapObjects: 15657 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 577 @2.291s 3%: 0.023+0.26+0.16 ms clock, 0.36+0/0.38/0.16+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 578 @2.292s 3%: 0.021+0.21+0.17 ms clock, 0.34+0/0.28/0.21+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121752 HeapInuse: 1433600 HeapObjects: 15657 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 579 @2.311s 3%: 0.013+0.20+0.13 ms clock, 0.21+0/0.41/0.14+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 580 @2.311s 3%: 0.072+0.21+0.11 ms clock, 1.1+0/0.34/0.24+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121848 HeapInuse: 1433600 HeapObjects: 15658 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 581 @2.330s 3%: 0.050+0.21+0.097 ms clock, 0.80+0/0.35/0.14+1.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 582 @2.331s 3%: 0.019+0.18+0.13 ms clock, 0.31+0/0.27/0.20+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1121944 HeapInuse: 1433600 HeapObjects: 15659 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 583 @2.351s 3%: 0.008+0.24+0.12 ms clock, 0.13+0/0.41/0.12+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 584 @2.351s 3%: 0.084+0.25+0.17 ms clock, 1.3+0/0.45/0.15+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122040 HeapInuse: 1433600 HeapObjects: 15660 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 585 @2.370s 3%: 0.052+0.19+0.12 ms clock, 0.83+0/0.34/0.17+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 586 @2.371s 3%: 0.010+0.25+0.14 ms clock, 0.16+0/0.41/0.14+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122040 HeapInuse: 1433600 HeapObjects: 15660 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 587 @2.390s 3%: 0.008+0.26+0.10 ms clock, 0.14+0/0.40/0.22+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 588 @2.390s 3%: 0.010+0.23+0.10 ms clock, 0.17+0/0.31/0.29+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122136 HeapInuse: 1433600 HeapObjects: 15661 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 589 @2.409s 3%: 0.045+0.26+0.17 ms clock, 0.72+0/0.41/0.24+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 590 @2.410s 3%: 0.041+0.24+0.11 ms clock, 0.67+0/0.34/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122232 HeapInuse: 1433600 HeapObjects: 15662 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 591 @2.428s 3%: 0.017+0.22+0.13 ms clock, 0.28+0/0.40/0.14+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 592 @2.429s 3%: 0.011+0.22+0.15 ms clock, 0.19+0/0.34/0.26+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122328 HeapInuse: 1433600 HeapObjects: 15663 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 593 @2.448s 3%: 0.008+0.25+0.16 ms clock, 0.13+0/0.42/0.19+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 594 @2.449s 3%: 0.030+0.27+0.13 ms clock, 0.48+0/0.27/0.21+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122424 HeapInuse: 1433600 HeapObjects: 15664 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 595 @2.467s 3%: 0.044+0.24+0.14 ms clock, 0.71+0/0.41/0.20+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 596 @2.468s 3%: 0.011+0.23+0.15 ms clock, 0.18+0/0.41/0.18+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122424 HeapInuse: 1433600 HeapObjects: 15664 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 597 @2.487s 3%: 0.012+0.22+0.13 ms clock, 0.20+0/0.41/0.11+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 598 @2.488s 3%: 0.025+0.19+0.15 ms clock, 0.41+0/0.33/0.19+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1122424 HeapInuse: 1433600 HeapObjects: 15664 HeapIdle 1384448 HeapReleased 0 HeapSys 2818048
gc 599 @2.507s 3%: 0.010+0.22+0.20 ms clock, 0.16+0/0.38/0.10+3.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
   10000	      1926 ns/op	      88 B/op	       2 allocs/op
gc 600 @2.507s 3%: 0.11+0.31+0.17 ms clock, 1.8+0/0.25/0.15+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084328 HeapInuse: 2400256 HeapObjects: 30665 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 601 @2.541s 3%: 0.040+0.23+0.18 ms clock, 0.64+0/0.37/0.14+2.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetErase1E4-16                        	gc 602 @2.542s 3%: 0.034+0.22+0.11 ms clock, 0.55+0/0.34/0.14+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084360 HeapInuse: 2400256 HeapObjects: 30666 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 603 @2.575s 3%: 0.010+0.21+0.14 ms clock, 0.16+0/0.38/0.21+2.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 604 @2.576s 3%: 0.033+0.26+0.10 ms clock, 0.53+0/0.35/0.27+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084440 HeapInuse: 2400256 HeapObjects: 30666 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 605 @2.609s 3%: 0.010+0.29+0.13 ms clock, 0.17+0/0.44/0.28+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 606 @2.609s 3%: 0.008+0.26+0.14 ms clock, 0.13+0/0.35/0.22+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084536 HeapInuse: 2400256 HeapObjects: 30667 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 607 @2.642s 3%: 0.010+0.26+0.13 ms clock, 0.17+0/0.44/0.26+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 608 @2.643s 3%: 0.020+0.24+0.13 ms clock, 0.32+0/0.42/0.21+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084632 HeapInuse: 2400256 HeapObjects: 30668 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 609 @2.676s 3%: 0.044+0.20+0.12 ms clock, 0.70+0/0.40/0.15+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 610 @2.677s 3%: 0.008+0.23+0.11 ms clock, 0.14+0/0.28/0.21+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084728 HeapInuse: 2400256 HeapObjects: 30669 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 611 @2.710s 3%: 0.014+0.29+0.17 ms clock, 0.22+0/0.36/0.31+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 612 @2.711s 3%: 0.021+0.25+0.089 ms clock, 0.34+0/0.34/0.22+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084824 HeapInuse: 2400256 HeapObjects: 30670 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 613 @2.743s 3%: 0.031+0.49+0.10 ms clock, 0.50+0/0.39/0.36+1.6 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 614 @2.744s 3%: 0.013+0.28+0.11 ms clock, 0.21+0/0.40/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084824 HeapInuse: 2400256 HeapObjects: 30670 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 615 @2.777s 3%: 0.023+0.26+0.21 ms clock, 0.38+0/0.41/0.19+3.4 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 616 @2.778s 3%: 0.011+0.22+0.12 ms clock, 0.18+0/0.27/0.19+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2084920 HeapInuse: 2400256 HeapObjects: 30671 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 617 @2.810s 3%: 0.050+0.25+0.14 ms clock, 0.81+0/0.43/0.22+2.3 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 618 @2.811s 3%: 0.030+0.22+0.15 ms clock, 0.48+0/0.31/0.26+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085016 HeapInuse: 2400256 HeapObjects: 30672 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 619 @2.845s 3%: 0.032+0.21+0.13 ms clock, 0.52+0/0.33/0.27+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 620 @2.845s 3%: 0.012+0.19+0.15 ms clock, 0.20+0/0.35/0.18+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085112 HeapInuse: 2400256 HeapObjects: 30673 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 621 @2.878s 3%: 0.037+0.25+0.19 ms clock, 0.59+0/0.32/0.18+3.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 622 @2.878s 3%: 0.018+0.24+0.15 ms clock, 0.29+0/0.31/0.20+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085208 HeapInuse: 2400256 HeapObjects: 30674 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 623 @2.911s 3%: 0.010+0.26+0.19 ms clock, 0.16+0/0.44/0.21+3.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 624 @2.912s 3%: 0.078+0.21+0.19 ms clock, 1.2+0/0.31/0.15+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085208 HeapInuse: 2400256 HeapObjects: 30674 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 625 @2.944s 3%: 0.010+0.26+0.13 ms clock, 0.16+0/0.39/0.24+2.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 626 @2.945s 3%: 0.022+0.23+0.14 ms clock, 0.36+0/0.27/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085304 HeapInuse: 2400256 HeapObjects: 30675 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 627 @2.978s 3%: 0.029+0.24+0.13 ms clock, 0.47+0/0.30/0.10+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 628 @2.979s 3%: 0.022+0.23+0.12 ms clock, 0.36+0/0.33/0.24+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085400 HeapInuse: 2400256 HeapObjects: 30676 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 629 @3.012s 3%: 0.011+0.26+0.11 ms clock, 0.17+0/0.45/0.26+1.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 630 @3.013s 3%: 0.021+0.21+0.099 ms clock, 0.34+0/0.24/0.21+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 2085400 HeapInuse: 2400256 HeapObjects: 30676 HeapIdle 417792 HeapReleased 0 HeapSys 2818048
gc 631 @3.045s 2%: 0.037+0.24+0.13 ms clock, 0.60+0/0.35/0.15+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
   10000	      1419 ns/op	      96 B/op	       2 allocs/op
gc 632 @3.046s 2%: 0.010+0.29+0.10 ms clock, 0.16+0/0.41/0.24+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205384 HeapInuse: 1515520 HeapObjects: 15676 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 633 @3.062s 2%: 0.008+0.25+0.21 ms clock, 0.13+0/0.30/0.18+3.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndErase1E4-16               	gc 634 @3.063s 2%: 0.020+0.26+0.11 ms clock, 0.33+0/0.19/0.38+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205432 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 635 @3.078s 2%: 0.011+0.25+0.17 ms clock, 0.17+0/0.17/0.45+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 636 @3.078s 2%: 0.016+0.23+0.13 ms clock, 0.26+0/0.34/0.23+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205416 HeapInuse: 1515520 HeapObjects: 15676 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 637 @3.093s 2%: 0.009+0.23+0.12 ms clock, 0.14+0/0.41/0.27+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 638 @3.093s 2%: 0.038+0.21+0.11 ms clock, 0.62+0/0.40/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205512 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 639 @3.109s 2%: 0.008+0.22+0.12 ms clock, 0.13+0/0.30/0.31+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 640 @3.110s 2%: 0.018+0.19+0.10 ms clock, 0.29+0/0.36/0.095+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205512 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 641 @3.124s 2%: 0.050+0.19+0.12 ms clock, 0.81+0/0.38/0.098+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 642 @3.125s 2%: 0.015+0.20+0.11 ms clock, 0.24+0/0.38/0.14+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205512 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 643 @3.139s 2%: 0.014+0.22+0.13 ms clock, 0.23+0/0.30/0.28+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 644 @3.140s 2%: 0.011+0.36+0.12 ms clock, 0.19+0/0.53/0.098+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205512 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 645 @3.154s 2%: 0.056+0.24+0.10 ms clock, 0.89+0/0.46/0.24+1.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 646 @3.155s 2%: 0.020+0.24+0.078 ms clock, 0.32+0/0.30/0.26+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205512 HeapInuse: 1515520 HeapObjects: 15677 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 647 @3.169s 2%: 0.023+0.24+0.12 ms clock, 0.37+0/0.29/0.19+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 648 @3.170s 2%: 0.011+0.21+0.13 ms clock, 0.18+0/0.38/0.15+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205608 HeapInuse: 1515520 HeapObjects: 15678 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 649 @3.192s 2%: 0.012+0.23+0.18 ms clock, 0.19+0/0.49/0.18+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 650 @3.192s 2%: 0.012+0.24+0.066 ms clock, 0.19+0/0.44/0.29+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205704 HeapInuse: 1515520 HeapObjects: 15679 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 651 @3.207s 2%: 0.009+0.20+0.077 ms clock, 0.15+0/0.34/0.36+1.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 652 @3.208s 2%: 0.011+0.18+0.064 ms clock, 0.17+0/0.34/0.35+1.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205800 HeapInuse: 1515520 HeapObjects: 15680 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 653 @3.221s 2%: 0.008+0.24+0.13 ms clock, 0.12+0/0.33/0.23+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 654 @3.222s 2%: 0.007+0.22+0.13 ms clock, 0.12+0/0.35/0.27+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205896 HeapInuse: 1515520 HeapObjects: 15681 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 655 @3.236s 2%: 0.010+0.24+0.12 ms clock, 0.17+0/0.41/0.077+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 656 @3.237s 2%: 0.019+0.22+0.12 ms clock, 0.31+0/0.40/0.14+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205992 HeapInuse: 1515520 HeapObjects: 15682 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 657 @3.251s 2%: 0.008+0.24+0.12 ms clock, 0.13+0/0.27/0.30+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 658 @3.252s 2%: 0.093+0.22+0.15 ms clock, 1.4+0/0.24/0.17+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1205992 HeapInuse: 1515520 HeapObjects: 15682 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 659 @3.266s 2%: 0.010+0.24+0.16 ms clock, 0.16+0/0.29/0.18+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 660 @3.266s 2%: 0.020+0.21+0.13 ms clock, 0.32+0/0.34/0.18+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1206088 HeapInuse: 1515520 HeapObjects: 15683 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 661 @3.280s 2%: 0.028+0.26+0.14 ms clock, 0.45+0/0.47/0.18+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 662 @3.281s 2%: 0.019+0.18+0.15 ms clock, 0.30+0/0.26/0.12+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1206088 HeapInuse: 1515520 HeapObjects: 15683 HeapIdle 1302528 HeapReleased 0 HeapSys 2818048
gc 663 @3.295s 2%: 0.009+0.27+0.13 ms clock, 0.14+0/0.28/0.32+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
   10000	      1417 ns/op	      96 B/op	       2 allocs/op
gc 664 @3.296s 2%: 0.063+0.20+0.10 ms clock, 1.0+0/0.27/0.17+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808352 HeapInuse: 1122304 HeapObjects: 10690 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 665 @3.314s 2%: 0.022+0.32+0.21 ms clock, 0.35+0/0.39/0.19+3.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndEraseWithPool1E4-16       	gc 666 @3.315s 2%: 0.049+0.22+0.14 ms clock, 0.79+0/0.36/0.10+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808496 HeapInuse: 1122304 HeapObjects: 10692 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 667 @3.334s 2%: 0.050+0.25+0.11 ms clock, 0.80+0/0.33/0.21+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 668 @3.335s 2%: 0.019+0.25+0.11 ms clock, 0.30+0/0.34/0.20+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808480 HeapInuse: 1122304 HeapObjects: 10691 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 669 @3.353s 2%: 0.056+0.25+0.12 ms clock, 0.89+0/0.39/0.18+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 670 @3.353s 2%: 0.022+0.19+0.14 ms clock, 0.35+0/0.31/0.15+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808480 HeapInuse: 1122304 HeapObjects: 10691 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 671 @3.371s 2%: 0.050+0.26+0.17 ms clock, 0.81+0/0.26/0.21+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 672 @3.372s 2%: 0.075+0.25+0.11 ms clock, 1.2+0/0.38/0.21+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808576 HeapInuse: 1122304 HeapObjects: 10692 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 673 @3.390s 2%: 0.032+0.27+0.12 ms clock, 0.51+0/0.37/0.25+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 674 @3.390s 2%: 0.019+0.21+0.14 ms clock, 0.30+0/0.26/0.24+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808672 HeapInuse: 1122304 HeapObjects: 10693 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 675 @3.408s 2%: 0.017+0.25+0.17 ms clock, 0.28+0/0.37/0.20+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 676 @3.409s 2%: 0.020+0.21+0.14 ms clock, 0.32+0/0.24/0.22+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808672 HeapInuse: 1122304 HeapObjects: 10693 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 677 @3.427s 2%: 0.008+0.28+0.13 ms clock, 0.14+0/0.39/0.27+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 678 @3.427s 2%: 0.011+0.37+0.17 ms clock, 0.18+0/0.34/0.26+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808768 HeapInuse: 1122304 HeapObjects: 10694 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 679 @3.446s 2%: 0.045+0.25+0.19 ms clock, 0.72+0/0.48/0.093+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 680 @3.446s 2%: 0.040+0.22+0.16 ms clock, 0.64+0/0.32/0.17+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808768 HeapInuse: 1122304 HeapObjects: 10694 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 681 @3.465s 2%: 0.008+0.23+0.19 ms clock, 0.13+0/0.31/0.11+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 682 @3.465s 2%: 0.022+0.20+0.13 ms clock, 0.35+0/0.38/0.16+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808768 HeapInuse: 1122304 HeapObjects: 10694 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 683 @3.483s 2%: 0.021+0.25+0.18 ms clock, 0.34+0/0.40/0.18+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 684 @3.484s 2%: 0.025+0.20+0.10 ms clock, 0.40+0/0.28/0.22+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808864 HeapInuse: 1122304 HeapObjects: 10695 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 685 @3.501s 2%: 0.056+0.24+0.12 ms clock, 0.90+0/0.26/0.17+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 686 @3.502s 2%: 0.019+0.23+0.11 ms clock, 0.30+0/0.45/0.14+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 808960 HeapInuse: 1122304 HeapObjects: 10696 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 687 @3.520s 2%: 0.023+0.23+0.11 ms clock, 0.37+0/0.33/0.14+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 688 @3.521s 2%: 0.065+0.23+0.13 ms clock, 1.0+0/0.40/0.23+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 809056 HeapInuse: 1122304 HeapObjects: 10697 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 689 @3.539s 2%: 0.024+0.29+0.18 ms clock, 0.39+0/0.39/0.092+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 690 @3.539s 2%: 0.012+0.23+0.11 ms clock, 0.19+0/0.37/0.15+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 809056 HeapInuse: 1122304 HeapObjects: 10697 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 691 @3.558s 2%: 0.009+0.19+0.14 ms clock, 0.14+0/0.39/0.13+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 692 @3.558s 2%: 0.050+0.22+0.12 ms clock, 0.81+0/0.33/0.20+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 809056 HeapInuse: 1122304 HeapObjects: 10697 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 693 @3.576s 2%: 0.035+0.24+0.19 ms clock, 0.56+0/0.36/0.23+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 694 @3.577s 2%: 0.017+0.23+0.11 ms clock, 0.28+0/0.28/0.18+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 809056 HeapInuse: 1122304 HeapObjects: 10697 HeapIdle 1695744 HeapReleased 0 HeapSys 2818048
gc 695 @3.595s 2%: 0.031+0.30+0.12 ms clock, 0.50+0/0.56/0.19+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	      1783 ns/op	      56 B/op	       1 allocs/op
gc 696 @3.595s 2%: 0.043+0.21+0.20 ms clock, 0.69+0/0.40/0.13+3.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673760 HeapInuse: 1048576 HeapObjects: 1007 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 697 @3.599s 2%: 0.020+0.23+0.081 ms clock, 0.32+0/0.36/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsert1E4-16                   	gc 698 @3.600s 2%: 0.045+0.23+0.10 ms clock, 0.73+0/0.29/0.13+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673720 HeapInuse: 1056768 HeapObjects: 1030 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 699 @3.604s 2%: 0.025+0.24+0.18 ms clock, 0.41+0/0.39/0.27+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 700 @3.605s 2%: 0.011+0.25+0.11 ms clock, 0.18+0/0.29/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 672440 HeapInuse: 1048576 HeapObjects: 1015 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 701 @3.608s 2%: 0.026+0.22+0.14 ms clock, 0.41+0/0.36/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 702 @3.609s 2%: 0.010+0.21+0.17 ms clock, 0.16+0/0.35/0.16+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 672208 HeapInuse: 1048576 HeapObjects: 1011 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 703 @3.613s 2%: 0.009+0.20+0.10 ms clock, 0.14+0/0.42/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 704 @3.613s 2%: 0.014+0.20+0.10 ms clock, 0.22+0/0.39/0.091+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 674208 HeapInuse: 1056768 HeapObjects: 1031 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 705 @3.617s 2%: 0.030+0.26+0.099 ms clock, 0.48+0/0.43/0.18+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 706 @3.617s 2%: 0.016+0.22+0.11 ms clock, 0.26+0/0.39/0.11+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 670688 HeapInuse: 1048576 HeapObjects: 996 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 707 @3.621s 2%: 0.008+0.19+0.090 ms clock, 0.14+0/0.43/0.091+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 708 @3.621s 2%: 0.011+0.21+0.087 ms clock, 0.17+0/0.37/0.15+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673096 HeapInuse: 1056768 HeapObjects: 1022 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 709 @3.625s 2%: 0.009+0.22+0.091 ms clock, 0.14+0/0.36/0.13+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 710 @3.625s 2%: 0.011+0.26+0.11 ms clock, 0.18+0/0.34/0.28+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 675504 HeapInuse: 1056768 HeapObjects: 1024 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 711 @3.629s 2%: 0.007+0.20+0.099 ms clock, 0.12+0/0.29/0.22+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 712 @3.629s 2%: 0.018+0.20+0.077 ms clock, 0.28+0/0.42/0.21+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673704 HeapInuse: 1056768 HeapObjects: 1029 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 713 @3.633s 2%: 0.009+0.25+0.097 ms clock, 0.15+0/0.25/0.39+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 714 @3.633s 2%: 0.015+0.20+0.094 ms clock, 0.25+0/0.31/0.21+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 672248 HeapInuse: 1048576 HeapObjects: 1013 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 715 @3.637s 2%: 0.010+0.21+0.10 ms clock, 0.17+0/0.41/0.16+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 716 @3.637s 2%: 0.034+0.28+0.12 ms clock, 0.55+0/0.34/0.19+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673720 HeapInuse: 1056768 HeapObjects: 1026 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 717 @3.641s 2%: 0.009+0.22+0.12 ms clock, 0.15+0/0.15/0.40+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 718 @3.641s 2%: 0.019+0.19+0.087 ms clock, 0.31+0/0.45/0.22+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 672968 HeapInuse: 1048576 HeapObjects: 1001 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 719 @3.645s 2%: 0.009+0.25+0.29 ms clock, 0.14+0/0.32/0.24+4.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 720 @3.645s 2%: 0.014+0.18+0.11 ms clock, 0.23+0/0.37/0.13+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673328 HeapInuse: 1056768 HeapObjects: 1023 HeapIdle 1761280 HeapReleased 0 HeapSys 2818048
gc 721 @3.649s 2%: 0.008+0.21+0.10 ms clock, 0.12+0/0.38/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 722 @3.649s 2%: 0.042+0.22+0.12 ms clock, 0.67+0/0.37/0.23+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 673112 HeapInuse: 1048576 HeapObjects: 1022 HeapIdle 1769472 HeapReleased 0 HeapSys 2818048
gc 723 @3.653s 2%: 0.029+0.24+0.11 ms clock, 0.47+0/0.47/0.28+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	       339 ns/op	      42 B/op	       0 allocs/op
gc 724 @3.653s 2%: 0.011+0.19+0.092 ms clock, 0.18+0/0.34/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 755968 HeapInuse: 1130496 HeapObjects: 1015 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 725 @3.658s 2%: 0.025+0.25+0.10 ms clock, 0.41+0/0.37/0.29+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapErase1E4-16                    	gc 726 @3.659s 2%: 0.017+0.21+0.16 ms clock, 0.27+0/0.39/0.30+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 755640 HeapInuse: 1130496 HeapObjects: 1010 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 727 @3.664s 2%: 0.056+0.23+0.13 ms clock, 0.90+0/0.42/0.14+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 728 @3.665s 2%: 0.011+0.21+0.13 ms clock, 0.17+0/0.33/0.11+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 753264 HeapInuse: 1130496 HeapObjects: 1003 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 729 @3.669s 2%: 0.020+0.20+0.099 ms clock, 0.32+0/0.32/0.15+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 730 @3.670s 2%: 0.017+0.21+0.10 ms clock, 0.28+0/0.31/0.18+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 751576 HeapInuse: 1130496 HeapObjects: 988 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 731 @3.674s 2%: 0.009+0.19+0.10 ms clock, 0.15+0/0.29/0.24+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 732 @3.674s 2%: 0.008+0.26+0.11 ms clock, 0.13+0/0.45/0.19+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 755336 HeapInuse: 1130496 HeapObjects: 1027 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 733 @3.679s 2%: 0.027+0.20+0.085 ms clock, 0.43+0/0.39/0.14+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 734 @3.680s 2%: 0.037+0.20+0.11 ms clock, 0.59+0/0.40/0.16+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 754688 HeapInuse: 1130496 HeapObjects: 1016 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 735 @3.684s 2%: 0.022+0.19+0.095 ms clock, 0.35+0/0.39/0.16+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 736 @3.685s 2%: 0.013+0.19+0.18 ms clock, 0.22+0/0.27/0.18+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 754512 HeapInuse: 1130496 HeapObjects: 1016 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 737 @3.689s 2%: 0.008+0.27+0.11 ms clock, 0.13+0/0.38/0.26+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 738 @3.690s 2%: 0.010+0.19+0.16 ms clock, 0.16+0/0.34/0.17+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 755752 HeapInuse: 1130496 HeapObjects: 1011 HeapIdle 1687552 HeapReleased 0 HeapSys 2818048
gc 739 @3.694s 2%: 0.023+0.28+0.096 ms clock, 0.37+0/0.41/0.17+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 740 @3.695s 2%: 0.013+0.22+0.099 ms clock, 0.22+0/0.36/0.26+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 753208 HeapInuse: 1138688 HeapObjects: 1004 HeapIdle 1679360 HeapReleased 0 HeapSys 2818048
gc 741 @3.700s 2%: 0.011+0.29+0.10 ms clock, 0.18+0/0.47/0.29+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 742 @3.700s 2%: 0.011+0.33+0.095 ms clock, 0.18+0/0.35/0.11+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 754328 HeapInuse: 1138688 HeapObjects: 1015 HeapIdle 1679360 HeapReleased 0 HeapSys 2818048
gc 743 @3.705s 2%: 0.009+0.23+0.21 ms clock, 0.15+0/0.32/0.29+3.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 744 @3.706s 2%: 0.017+0.22+0.12 ms clock, 0.27+0/0.33/0.19+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 757480 HeapInuse: 1138688 HeapObjects: 1029 HeapIdle 1679360 HeapReleased 0 HeapSys 2818048
gc 745 @3.710s 2%: 0.009+0.26+0.15 ms clock, 0.15+0/0.50/0.20+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 746 @3.711s 3%: 0.018+0.22+0.10 ms clock, 0.28+0/0.33/0.20+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 758288 HeapInuse: 1138688 HeapObjects: 1035 HeapIdle 1679360 HeapReleased 0 HeapSys 2818048
gc 747 @3.716s 3%: 0.022+0.22+0.12 ms clock, 0.36+0/0.37/0.40+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 748 @3.716s 3%: 0.014+0.20+0.11 ms clock, 0.23+0/0.38/0.23+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 757712 HeapInuse: 1146880 HeapObjects: 1047 HeapIdle 1671168 HeapReleased 0 HeapSys 2818048
gc 749 @3.721s 3%: 0.008+0.24+0.10 ms clock, 0.13+0/0.32/0.14+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	       146 ns/op	       8 B/op	       0 allocs/op
gc 750 @3.721s 3%: 0.012+0.24+0.11 ms clock, 0.19+0/0.45/0.25+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310352 HeapInuse: 688128 HeapObjects: 799 HeapIdle 2129920 HeapReleased 0 HeapSys 2818048
gc 751 @3.723s 3%: 0.009+0.19+0.11 ms clock, 0.15+0/0.29/0.13+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndErase1E4-16           	gc 752 @3.724s 3%: 0.011+0.21+0.099 ms clock, 0.18+0/0.28/0.16+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 308584 HeapInuse: 679936 HeapObjects: 784 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 753 @3.726s 3%: 0.033+0.24+0.097 ms clock, 0.53+0/0.32/0.16+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 754 @3.726s 3%: 0.015+0.19+0.10 ms clock, 0.24+0/0.38/0.33+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 309000 HeapInuse: 679936 HeapObjects: 788 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 755 @3.728s 3%: 0.008+0.27+0.11 ms clock, 0.12+0/0.19/0.30+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 756 @3.728s 3%: 0.010+0.26+0.089 ms clock, 0.17+0/0.33/0.22+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 309568 HeapInuse: 679936 HeapObjects: 794 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 757 @3.730s 3%: 0.008+0.21+0.098 ms clock, 0.12+0/0.38/0.23+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 758 @3.731s 3%: 0.007+0.20+0.089 ms clock, 0.12+0/0.39/0.21+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 309024 HeapInuse: 679936 HeapObjects: 788 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 759 @3.733s 3%: 0.009+0.20+0.097 ms clock, 0.14+0/0.35/0.31+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 760 @3.733s 3%: 0.011+0.20+0.082 ms clock, 0.19+0/0.34/0.18+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 308912 HeapInuse: 679936 HeapObjects: 788 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 761 @3.735s 3%: 0.007+0.20+0.10 ms clock, 0.12+0/0.34/0.17+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 762 @3.735s 3%: 0.009+0.24+0.10 ms clock, 0.15+0/0.38/0.27+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 309376 HeapInuse: 679936 HeapObjects: 792 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 763 @3.737s 3%: 0.009+0.21+0.11 ms clock, 0.14+0/0.38/0.30+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 764 @3.738s 3%: 0.010+0.21+0.075 ms clock, 0.16+0/0.30/0.19+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310008 HeapInuse: 679936 HeapObjects: 797 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 765 @3.740s 3%: 0.009+0.22+0.10 ms clock, 0.14+0/0.39/0.29+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 766 @3.740s 3%: 0.018+0.19+0.073 ms clock, 0.29+0/0.29/0.20+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310624 HeapInuse: 688128 HeapObjects: 800 HeapIdle 2129920 HeapReleased 0 HeapSys 2818048
gc 767 @3.742s 3%: 0.010+0.23+0.091 ms clock, 0.16+0/0.35/0.29+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 768 @3.743s 3%: 0.008+0.23+0.077 ms clock, 0.13+0/0.39/0.22+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310400 HeapInuse: 679936 HeapObjects: 802 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 769 @3.744s 3%: 0.009+0.20+0.11 ms clock, 0.14+0/0.31/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 770 @3.745s 3%: 0.010+0.19+0.080 ms clock, 0.16+0/0.25/0.41+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 311056 HeapInuse: 679936 HeapObjects: 809 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 771 @3.747s 3%: 0.007+0.22+0.090 ms clock, 0.12+0/0.44/0.29+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 772 @3.747s 3%: 0.010+0.46+0.51 ms clock, 0.17+0/0.81/0.17+8.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310400 HeapInuse: 679936 HeapObjects: 802 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 773 @3.750s 3%: 0.008+0.27+0.087 ms clock, 0.13+0/0.30/0.31+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 774 @3.750s 3%: 0.007+0.23+0.083 ms clock, 0.12+0/0.32/0.20+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 310280 HeapInuse: 679936 HeapObjects: 803 HeapIdle 2138112 HeapReleased 0 HeapSys 2818048
gc 775 @3.752s 3%: 0.008+0.22+0.073 ms clock, 0.13+0/0.40/0.23+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	       189 ns/op	       6 B/op	       0 allocs/op
gc 776 @3.753s 3%: 0.010+0.20+0.091 ms clock, 0.16+0/0.35/0.34+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 453416 HeapInuse: 761856 HeapObjects: 731 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 777 @3.754s 3%: 0.008+0.20+0.079 ms clock, 0.13+0/0.38/0.16+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndEraseWithBuf1E4-16    	gc 778 @3.755s 3%: 0.009+0.18+0.084 ms clock, 0.15+0/0.36/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 453656 HeapInuse: 761856 HeapObjects: 734 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 779 @3.756s 3%: 0.008+0.27+0.089 ms clock, 0.13+0/0.28/0.45+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 780 @3.757s 3%: 0.007+0.21+0.12 ms clock, 0.12+0/0.34/0.38+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 453832 HeapInuse: 761856 HeapObjects: 735 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 781 @3.758s 3%: 0.009+0.25+0.078 ms clock, 0.14+0/0.35/0.33+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 782 @3.759s 3%: 0.010+0.20+0.083 ms clock, 0.17+0/0.38/0.27+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454024 HeapInuse: 761856 HeapObjects: 737 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 783 @3.760s 3%: 0.008+0.18+0.095 ms clock, 0.12+0/0.35/0.29+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 784 @3.761s 3%: 0.010+0.19+0.072 ms clock, 0.16+0/0.29/0.27+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454216 HeapInuse: 761856 HeapObjects: 739 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 785 @3.762s 3%: 0.007+0.22+0.087 ms clock, 0.12+0/0.32/0.24+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 786 @3.763s 3%: 0.007+0.22+0.095 ms clock, 0.12+0/0.37/0.29+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454216 HeapInuse: 761856 HeapObjects: 739 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 787 @3.764s 3%: 0.007+0.20+0.081 ms clock, 0.12+0/0.35/0.34+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 788 @3.765s 3%: 0.010+0.24+0.080 ms clock, 0.17+0/0.31/0.37+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454408 HeapInuse: 761856 HeapObjects: 741 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 789 @3.766s 3%: 0.009+0.19+0.079 ms clock, 0.14+0/0.31/0.31+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 790 @3.767s 3%: 0.010+0.18+0.077 ms clock, 0.16+0/0.35/0.39+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454408 HeapInuse: 761856 HeapObjects: 741 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 791 @3.768s 3%: 0.010+0.20+0.084 ms clock, 0.16+0/0.32/0.19+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 792 @3.769s 3%: 0.006+0.32+0.082 ms clock, 0.10+0/0.42/0.26+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454504 HeapInuse: 761856 HeapObjects: 742 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 793 @3.770s 3%: 0.010+0.25+0.099 ms clock, 0.16+0/0.29/0.43+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 794 @3.771s 3%: 0.010+0.21+0.076 ms clock, 0.17+0/0.37/0.34+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454600 HeapInuse: 761856 HeapObjects: 743 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 795 @3.772s 3%: 0.008+0.21+0.074 ms clock, 0.14+0/0.36/0.29+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 796 @3.773s 3%: 0.010+0.29+0.081 ms clock, 0.16+0/0.28/0.16+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454600 HeapInuse: 761856 HeapObjects: 743 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 797 @3.774s 3%: 0.007+0.20+0.076 ms clock, 0.12+0/0.29/0.23+1.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 798 @3.775s 3%: 0.014+0.19+0.073 ms clock, 0.22+0/0.34/0.28+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454792 HeapInuse: 761856 HeapObjects: 745 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 799 @3.776s 3%: 0.007+0.21+0.071 ms clock, 0.12+0/0.41/0.38+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 800 @3.777s 3%: 0.009+0.22+0.072 ms clock, 0.15+0/0.32/0.25+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 454984 HeapInuse: 761856 HeapObjects: 747 HeapIdle 2056192 HeapReleased 0 HeapSys 2818048
gc 801 @3.778s 3%: 0.009+0.23+0.069 ms clock, 0.15+0/0.20/0.39+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
   10000	       140 ns/op	      20 B/op	       0 allocs/op
gc 802 @3.779s 3%: 0.011+0.31+0.072 ms clock, 0.18+0/0.13/0.40+1.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053160 HeapInuse: 1359872 HeapObjects: 748 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 803 @3.812s 3%: 0.009+0.30+0.12 ms clock, 0.14+0/0.36/0.22+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSort1E5-16                               	gc 804 @3.812s 3%: 0.012+0.27+0.17 ms clock, 0.20+0/0.43/0.25+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053384 HeapInuse: 1359872 HeapObjects: 751 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 805 @3.845s 3%: 0.042+0.20+0.19 ms clock, 0.67+0/0.27/0.26+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 806 @3.846s 3%: 0.013+0.27+0.19 ms clock, 0.21+0/0.40/0.23+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053464 HeapInuse: 1359872 HeapObjects: 751 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 807 @3.879s 3%: 0.041+0.25+0.19 ms clock, 0.67+0/0.39/0.15+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 808 @3.880s 3%: 0.053+0.22+0.22 ms clock, 0.86+0/0.29/0.20+3.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053464 HeapInuse: 1359872 HeapObjects: 751 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 809 @3.913s 3%: 0.051+0.26+0.21 ms clock, 0.82+0/0.30/0.18+3.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 810 @3.913s 3%: 0.020+0.26+0.19 ms clock, 0.32+0/0.31/0.27+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053464 HeapInuse: 1359872 HeapObjects: 751 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 811 @3.946s 3%: 0.051+0.22+0.10 ms clock, 0.82+0/0.31/0.17+1.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 812 @3.947s 3%: 0.054+0.20+0.11 ms clock, 0.87+0/0.37/0.36+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053464 HeapInuse: 1359872 HeapObjects: 751 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 813 @3.979s 3%: 0.007+0.22+0.16 ms clock, 0.12+0/0.37/0.12+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 814 @3.980s 3%: 0.013+0.25+0.12 ms clock, 0.21+0/0.43/0.16+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053560 HeapInuse: 1359872 HeapObjects: 752 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 815 @4.013s 3%: 0.008+0.27+0.14 ms clock, 0.13+0/0.38/0.23+2.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 816 @4.013s 3%: 0.049+0.22+0.12 ms clock, 0.78+0/0.45/0.012+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053752 HeapInuse: 1359872 HeapObjects: 754 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 817 @4.046s 3%: 0.044+0.25+0.17 ms clock, 0.71+0/0.35/0.14+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 818 @4.047s 3%: 0.061+0.26+0.12 ms clock, 0.98+0/0.54/0.046+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1053848 HeapInuse: 1359872 HeapObjects: 755 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 819 @4.080s 2%: 0.050+0.20+0.15 ms clock, 0.81+0/0.30/0.19+2.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 820 @4.080s 3%: 0.018+0.24+0.14 ms clock, 0.29+0/0.44/0.087+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1054040 HeapInuse: 1359872 HeapObjects: 757 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 821 @4.113s 2%: 0.008+0.30+0.19 ms clock, 0.13+0/0.41/0.19+3.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 822 @4.113s 2%: 0.018+0.24+0.16 ms clock, 0.29+0/0.27/0.22+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1054040 HeapInuse: 1359872 HeapObjects: 757 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 823 @4.146s 2%: 0.048+0.22+0.15 ms clock, 0.77+0/0.30/0.17+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 824 @4.147s 2%: 0.020+0.22+0.12 ms clock, 0.32+0/0.34/0.22+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1054040 HeapInuse: 1359872 HeapObjects: 757 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 825 @4.180s 2%: 0.045+0.23+0.13 ms clock, 0.72+0/0.39/0.36+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 826 @4.180s 2%: 0.010+0.33+0.12 ms clock, 0.16+0/0.50/0.26+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1054136 HeapInuse: 1359872 HeapObjects: 758 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 827 @4.214s 2%: 0.009+0.27+0.13 ms clock, 0.14+0/0.34/0.25+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 828 @4.214s 2%: 0.010+0.22+0.10 ms clock, 0.16+0/0.38/0.12+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1054232 HeapInuse: 1359872 HeapObjects: 759 HeapIdle 1458176 HeapReleased 0 HeapSys 2818048
gc 829 @4.247s 2%: 0.010+0.24+0.16 ms clock, 0.17+0/0.43/0.22+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
  100000	       328 ns/op	       8 B/op	       0 allocs/op
gc 830 @4.248s 2%: 0.015+0.25+0.10 ms clock, 0.24+0/0.36/0.29+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 831 @4.367s 2%: 0.016+3.2+0.21 ms clock, 0.26+0.24/10/19+3.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 832 @4.488s 2%: 0.016+5.9+0.13 ms clock, 0.26+0.28/21/41+2.1 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051672 HeapInuse: 9388032 HeapObjects: 150763 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 833 @4.511s 2%: 0.035+0.23+0.17 ms clock, 0.56+0/0.30/0.21+2.7 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
#BenchmarkSetInsert1E5-16                          	gc 834 @4.512s 2%: 0.018+0.24+0.17 ms clock, 0.28+0/0.29/0.13+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 835 @4.628s 2%: 0.021+3.4+0.18 ms clock, 0.35+0.33/11/16+2.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 836 @4.750s 2%: 0.019+7.3+0.18 ms clock, 0.30+0.14/26/40+3.0 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051720 HeapInuse: 9412608 HeapObjects: 150765 HeapIdle 745472 HeapReleased 0 HeapSys 10158080
gc 837 @4.771s 2%: 0.009+0.25+0.20 ms clock, 0.14+0/0.32/0.23+3.3 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 838 @4.773s 2%: 0.022+0.22+0.11 ms clock, 0.35+0/0.38/0.20+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 839 @4.889s 2%: 0.015+4.1+0.12 ms clock, 0.24+0.24/12/19+2.0 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 840 @5.011s 2%: 0.017+6.4+0.16 ms clock, 0.28+0.33/21/43+2.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051720 HeapInuse: 9388032 HeapObjects: 150765 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 841 @5.032s 2%: 0.029+0.28+0.18 ms clock, 0.47+0/0.50/0.15+2.9 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 842 @5.034s 2%: 0.012+0.24+0.13 ms clock, 0.19+0/0.35/0.076+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 843 @5.150s 2%: 0.013+3.4+0.17 ms clock, 0.22+0.18/11/19+2.8 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 844 @5.274s 2%: 0.020+7.3+0.15 ms clock, 0.32+0.42/25/30+2.4 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051784 HeapInuse: 9388032 HeapObjects: 150764 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 845 @5.294s 2%: 0.015+0.27+0.11 ms clock, 0.24+0/0.45/0.23+1.8 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 846 @5.296s 2%: 0.008+0.25+0.097 ms clock, 0.14+0/0.47/0.13+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 847 @5.412s 2%: 0.017+3.2+0.14 ms clock, 0.27+0.20/11/10+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 848 @5.535s 2%: 0.017+5.8+0.18 ms clock, 0.27+0.38/20/35+2.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051880 HeapInuse: 9388032 HeapObjects: 150765 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 849 @5.555s 2%: 0.009+0.38+0.14 ms clock, 0.15+0/0.23/0.50+2.2 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 850 @5.557s 2%: 0.012+0.30+0.18 ms clock, 0.19+0/0.37/0.23+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 851 @5.672s 2%: 0.016+2.8+0.15 ms clock, 0.25+0.27/9.5/20+2.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 852 @5.795s 2%: 0.018+6.8+0.19 ms clock, 0.30+0.18/23/45+3.0 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9051976 HeapInuse: 9388032 HeapObjects: 150766 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 853 @5.815s 2%: 0.009+0.25+0.24 ms clock, 0.14+0/0.30/0.26+3.9 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 854 @5.817s 2%: 0.012+0.22+0.13 ms clock, 0.19+0/0.35/0.18+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 855 @5.935s 2%: 0.014+3.8+0.16 ms clock, 0.23+0.17/12/16+2.6 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 856 @6.055s 2%: 0.017+6.0+0.12 ms clock, 0.27+0.14/21/41+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052008 HeapInuse: 9388032 HeapObjects: 150768 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 857 @6.078s 2%: 0.038+0.25+0.12 ms clock, 0.61+0/0.32/0.29+2.0 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 858 @6.079s 2%: 0.011+0.22+0.11 ms clock, 0.18+0/0.26/0.29+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 859 @6.197s 2%: 0.016+3.6+0.10 ms clock, 0.25+0.12/13/25+1.6 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 860 @6.321s 2%: 0.016+5.9+0.12 ms clock, 0.27+1.9/22/40+2.0 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052008 HeapInuse: 9404416 HeapObjects: 150768 HeapIdle 753664 HeapReleased 0 HeapSys 10158080
gc 861 @6.341s 2%: 0.010+0.20+0.10 ms clock, 0.16+0/0.36/0.27+1.7 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 862 @6.342s 2%: 0.020+0.20+0.10 ms clock, 0.33+0/0.31/0.18+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 863 @6.459s 2%: 0.015+3.3+0.10 ms clock, 0.24+0.13/11/17+1.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 864 @6.580s 2%: 0.017+7.1+0.12 ms clock, 0.27+0.21/26/31+1.9 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052136 HeapInuse: 9388032 HeapObjects: 150771 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 865 @6.601s 2%: 0.049+0.29+0.19 ms clock, 0.78+0/0.33/0.32+3.0 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 866 @6.602s 2%: 0.021+0.21+0.11 ms clock, 0.34+0/0.35/0.26+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 867 @6.720s 2%: 0.016+2.9+0.13 ms clock, 0.26+0.19/9.7/19+2.1 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 868 @6.842s 2%: 0.019+5.7+0.10 ms clock, 0.31+0.44/20/47+1.6 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052248 HeapInuse: 9388032 HeapObjects: 150773 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 869 @6.862s 2%: 0.011+0.25+0.12 ms clock, 0.18+0/0.44/0.33+1.9 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 870 @6.863s 2%: 0.009+0.21+0.11 ms clock, 0.14+0/0.39/0.30+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 871 @6.979s 2%: 0.020+3.1+0.13 ms clock, 0.32+0.24/10/22+2.1 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 872 @7.099s 2%: 0.015+5.2+0.18 ms clock, 0.24+0.54/19/45+2.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052312 HeapInuse: 9388032 HeapObjects: 150772 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 873 @7.120s 2%: 0.023+0.26+0.11 ms clock, 0.37+0/0.37/0.14+1.9 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 874 @7.122s 2%: 0.021+0.25+0.12 ms clock, 0.34+0/0.34/0.14+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 875 @7.240s 2%: 0.015+2.8+0.11 ms clock, 0.24+0.16/10/22+1.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 876 @7.362s 2%: 0.022+5.6+0.12 ms clock, 0.36+0.20/21/50+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052280 HeapInuse: 9388032 HeapObjects: 150770 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 877 @7.382s 2%: 0.009+0.29+0.16 ms clock, 0.15+0/0.38/0.25+2.6 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 878 @7.384s 2%: 0.021+0.25+0.17 ms clock, 0.33+0/0.40/0.20+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 879 @7.501s 2%: 0.017+3.1+0.14 ms clock, 0.28+0.47/10/21+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 880 @7.624s 2%: 0.016+5.8+0.17 ms clock, 0.26+0.14/21/43+2.7 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052296 HeapInuse: 9388032 HeapObjects: 150771 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 881 @7.644s 2%: 0.009+0.24+0.10 ms clock, 0.14+0/0.36/0.21+1.7 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 882 @7.645s 2%: 0.008+0.20+0.16 ms clock, 0.14+0/0.20/0.33+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 883 @7.761s 2%: 0.017+3.3+0.14 ms clock, 0.28+0.38/9.8/21+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 884 @7.884s 2%: 0.019+5.4+0.12 ms clock, 0.31+0.42/19/44+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052312 HeapInuse: 9388032 HeapObjects: 150772 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 885 @7.903s 2%: 0.008+0.24+0.19 ms clock, 0.13+0/0.40/0.14+3.1 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 886 @7.904s 2%: 0.010+0.23+0.13 ms clock, 0.16+0/0.45/0.23+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 887 @8.020s 2%: 0.019+3.4+0.15 ms clock, 0.31+0.18/12/18+2.5 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 888 @8.142s 2%: 0.016+5.8+0.12 ms clock, 0.27+0.34/20/29+1.9 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052392 HeapInuse: 9388032 HeapObjects: 150772 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 889 @8.162s 2%: 0.009+0.34+0.19 ms clock, 0.15+0/0.36/0.34+3.1 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 890 @8.164s 2%: 0.018+0.37+0.16 ms clock, 0.29+0/0.39/0.36+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 891 @8.282s 2%: 0.017+3.1+0.16 ms clock, 0.28+0.17/11/20+2.6 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 892 @8.405s 2%: 0.020+6.8+0.12 ms clock, 0.32+0.20/23/32+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052504 HeapInuse: 9388032 HeapObjects: 150774 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 893 @8.427s 2%: 0.010+0.29+0.17 ms clock, 0.17+0/0.54/0.26+2.8 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
gc 894 @8.429s 2%: 0.021+0.23+0.23 ms clock, 0.33+0/0.44/0.12+3.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 895 @8.548s 1%: 0.021+3.2+0.21 ms clock, 0.33+0.26/11/20+3.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 896 @8.670s 1%: 0.023+5.5+0.12 ms clock, 0.36+0.49/20/47+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 9052568 HeapInuse: 9388032 HeapObjects: 150773 HeapIdle 770048 HeapReleased 0 HeapSys 10158080
gc 897 @8.690s 1%: 0.011+0.28+0.12 ms clock, 0.17+0/0.36/0.33+2.0 ms cpu, 8->8->0 MB, 15 MB goal, 16 P (forced)
  100000	      2623 ns/op	      88 B/op	       2 allocs/op
gc 898 @8.692s 1%: 0.070+0.22+0.15 ms clock, 1.1+0/0.35/0.26+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 899 @8.785s 1%: 0.015+2.7+0.12 ms clock, 0.24+0.44/9.2/13+1.9 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 900 @8.925s 1%: 0.015+5.5+0.15 ms clock, 0.24+0.37/19/38+2.4 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 901 @9.093s 1%: 0.020+2.4+0.12 ms clock, 0.32+0.15/8.2/14+1.9 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6060664 HeapInuse: 6381568 HeapObjects: 86092 HeapIdle 11116544 HeapReleased 0 HeapSys 17498112
gc 902 @9.146s 1%: 0.016+0.24+0.14 ms clock, 0.26+0/0.38/0.27+2.2 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
#BenchmarkSetErase1E5-16                           	gc 903 @9.148s 1%: 0.040+0.25+0.095 ms clock, 0.64+0/0.45/0.29+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 904 @9.244s 1%: 0.016+2.7+0.20 ms clock, 0.26+0.27/9.6/10+3.2 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 905 @9.378s 1%: 0.020+5.5+0.17 ms clock, 0.32+0.32/20/43+2.8 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 906 @9.543s 1%: 0.018+2.3+0.17 ms clock, 0.28+0.45/7.8/14+2.7 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5935144 HeapInuse: 6258688 HeapObjects: 83953 HeapIdle 11239424 HeapReleased 0 HeapSys 17498112
gc 907 @9.592s 1%: 0.011+0.30+0.19 ms clock, 0.18+0/0.44/0.30+3.0 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 908 @9.594s 1%: 0.020+0.25+0.15 ms clock, 0.33+0/0.40/0.17+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 909 @9.686s 1%: 0.017+3.1+0.24 ms clock, 0.28+0.38/10/7.8+3.9 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 910 @9.820s 1%: 0.016+5.7+0.20 ms clock, 0.26+0.40/20/45+3.2 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 911 @9.985s 1%: 0.019+3.3+0.15 ms clock, 0.31+0.25/8.0/11+2.5 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5971000 HeapInuse: 6291456 HeapObjects: 84562 HeapIdle 11206656 HeapReleased 0 HeapSys 17498112
gc 912 @10.035s 1%: 0.011+0.27+0.12 ms clock, 0.17+0/0.26/0.35+2.0 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 913 @10.036s 1%: 0.021+0.25+0.098 ms clock, 0.33+0/0.31/0.20+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 914 @10.129s 1%: 0.018+2.8+0.10 ms clock, 0.29+0.27/10/15+1.7 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 915 @10.267s 1%: 0.018+6.0+0.13 ms clock, 0.29+0.24/20/36+2.2 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 916 @10.433s 1%: 0.016+3.4+0.12 ms clock, 0.27+0.17/9.1/13+1.9 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6171720 HeapInuse: 6488064 HeapObjects: 87986 HeapIdle 11010048 HeapReleased 0 HeapSys 17498112
gc 917 @10.491s 1%: 0.009+0.30+0.15 ms clock, 0.15+0/0.43/0.28+2.5 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 918 @10.492s 1%: 0.16+0.26+0.13 ms clock, 2.6+0/0.36/0.16+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 919 @10.587s 1%: 0.016+2.7+0.13 ms clock, 0.26+0.24/8.9/13+2.1 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 920 @10.720s 1%: 0.017+4.4+0.14 ms clock, 0.28+0.21/16/32+2.2 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 921 @10.884s 1%: 0.019+3.7+0.14 ms clock, 0.30+0.19/8.3/10+2.2 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6078936 HeapInuse: 6397952 HeapObjects: 86402 HeapIdle 11100160 HeapReleased 0 HeapSys 17498112
gc 922 @10.936s 1%: 0.009+0.26+0.19 ms clock, 0.14+0/0.39/0.28+3.1 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 923 @10.937s 1%: 0.016+0.23+0.18 ms clock, 0.25+0/0.42/0.10+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 924 @11.030s 1%: 0.018+2.7+0.15 ms clock, 0.30+1.8/9.3/16+2.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 925 @11.164s 1%: 0.020+5.3+0.15 ms clock, 0.32+0.45/17/33+2.4 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 926 @11.328s 1%: 0.019+3.0+0.18 ms clock, 0.30+0.48/8.5/14+2.9 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6312408 HeapInuse: 6635520 HeapObjects: 90381 HeapIdle 10862592 HeapReleased 0 HeapSys 17498112
gc 927 @11.383s 1%: 0.011+0.27+0.15 ms clock, 0.18+0/0.43/0.26+2.5 ms cpu, 6->6->0 MB, 7 MB goal, 16 P (forced)
gc 928 @11.384s 1%: 0.050+0.26+0.16 ms clock, 0.81+0/0.29/0.17+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 929 @11.475s 1%: 0.012+2.5+0.12 ms clock, 0.20+0.31/8.6/15+2.0 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 930 @11.608s 1%: 0.016+4.9+0.14 ms clock, 0.26+0.46/18/37+2.3 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 931 @11.769s 1%: 0.018+2.8+0.15 ms clock, 0.29+0.16/8.9/11+2.5 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6043128 HeapInuse: 6365184 HeapObjects: 85791 HeapIdle 11132928 HeapReleased 0 HeapSys 17498112
gc 932 @11.822s 1%: 0.012+0.28+0.17 ms clock, 0.19+0/0.35/0.18+2.7 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 933 @11.823s 1%: 0.008+0.21+0.17 ms clock, 0.14+0/0.38/0.17+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 934 @11.916s 1%: 0.018+2.5+0.16 ms clock, 0.29+0.47/8.8/14+2.5 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 935 @12.054s 1%: 0.016+4.8+0.18 ms clock, 0.27+0.17/16/34+2.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 936 @12.217s 1%: 0.017+2.6+0.13 ms clock, 0.28+0.14/8.3/13+2.1 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6097064 HeapInuse: 6422528 HeapObjects: 86709 HeapIdle 11075584 HeapReleased 0 HeapSys 17498112
gc 937 @12.268s 1%: 0.040+0.24+0.22 ms clock, 0.64+0/0.25/0.22+3.5 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 938 @12.269s 1%: 0.017+0.24+0.15 ms clock, 0.28+0/0.40/0.13+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 939 @12.362s 1%: 0.019+2.8+0.12 ms clock, 0.30+0.25/9.8/11+2.0 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 940 @12.496s 1%: 0.018+5.7+0.18 ms clock, 0.29+0.12/21/42+2.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 941 @12.658s 1%: 0.016+3.3+0.12 ms clock, 0.25+0.41/11/7.2+2.0 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6312568 HeapInuse: 6635520 HeapObjects: 90381 HeapIdle 10862592 HeapReleased 0 HeapSys 17498112
gc 942 @12.714s 1%: 0.011+0.29+0.11 ms clock, 0.18+0/0.44/0.25+1.8 ms cpu, 6->6->0 MB, 7 MB goal, 16 P (forced)
gc 943 @12.715s 1%: 0.007+0.23+0.098 ms clock, 0.11+0/0.41/0.19+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 944 @12.807s 1%: 0.018+3.4+0.12 ms clock, 0.29+0.22/8.8/14+1.9 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 945 @12.913s 1%: 0.013+4.1+0.10 ms clock, 0.21+0.096/14/31+1.7 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 946 @13.074s 1%: 0.017+2.5+0.10 ms clock, 0.27+0.26/8.1/11+1.7 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6187032 HeapInuse: 6512640 HeapObjects: 88242 HeapIdle 10985472 HeapReleased 0 HeapSys 17498112
gc 947 @13.107s 1%: 0.007+0.18+0.18 ms clock, 0.11+0/0.29/0.14+3.0 ms cpu, 5->5->0 MB, 7 MB goal, 16 P (forced)
gc 948 @13.109s 1%: 0.033+0.20+0.13 ms clock, 0.53+0/0.34/0.11+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 949 @13.201s 1%: 0.015+2.3+0.13 ms clock, 0.25+0.11/8.0/15+2.1 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 950 @13.284s 1%: 0.013+5.5+0.16 ms clock, 0.21+0.15/16/27+2.6 ms cpu, 7->8->8 MB, 8 MB goal, 16 P
gc 951 @13.398s 1%: 0.022+2.3+0.13 ms clock, 0.36+0.16/7.8/11+2.2 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5702424 HeapInuse: 6021120 HeapObjects: 79981 HeapIdle 11476992 HeapReleased 0 HeapSys 17498112
gc 952 @13.445s 1%: 0.009+0.31+0.19 ms clock, 0.15+0/0.58/0.20+3.1 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 953 @13.447s 1%: 0.021+0.64+0.15 ms clock, 0.34+0/0.40/0.67+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 954 @13.541s 1%: 0.016+3.6+0.12 ms clock, 0.26+0.42/5.1/20+1.9 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 955 @13.674s 1%: 0.019+6.2+0.23 ms clock, 0.30+0.15/22/33+3.8 ms cpu, 7->8->8 MB, 8 MB goal, 16 P
gc 956 @13.837s 1%: 0.017+2.7+0.17 ms clock, 0.28+0.27/8.1/10+2.8 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5792264 HeapInuse: 6111232 HeapObjects: 81511 HeapIdle 11386880 HeapReleased 0 HeapSys 17498112
gc 957 @13.885s 1%: 0.008+0.26+0.17 ms clock, 0.14+0/0.40/0.14+2.7 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 958 @13.886s 1%: 0.019+0.23+0.19 ms clock, 0.31+0/0.37/0.25+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 959 @13.979s 1%: 0.017+2.7+0.20 ms clock, 0.28+0.24/8.7/13+3.3 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 960 @14.111s 1%: 0.019+5.5+0.14 ms clock, 0.30+0.20/18/38+2.3 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 961 @14.280s 1%: 0.021+2.9+0.20 ms clock, 0.33+0.26/8.6/13+3.2 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5899992 HeapInuse: 6217728 HeapObjects: 83348 HeapIdle 11280384 HeapReleased 0 HeapSys 17498112
gc 962 @14.330s 1%: 0.010+0.27+0.11 ms clock, 0.16+0/0.43/0.37+1.8 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 963 @14.332s 1%: 0.092+0.33+0.15 ms clock, 1.4+0/0.50/0.070+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 964 @14.432s 1%: 0.020+2.9+0.12 ms clock, 0.33+0.26/8.7/13+1.9 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 965 @14.566s 1%: 0.017+4.9+0.18 ms clock, 0.28+0.25/18/32+2.9 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 966 @14.733s 1%: 0.019+2.7+0.19 ms clock, 0.30+0.20/9.9/7.5+3.0 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 5989752 HeapInuse: 6307840 HeapObjects: 84878 HeapIdle 11190272 HeapReleased 0 HeapSys 17498112
gc 967 @14.783s 1%: 0.010+0.28+0.20 ms clock, 0.16+0/0.40/0.13+3.2 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 968 @14.784s 1%: 0.019+0.24+0.14 ms clock, 0.31+0/0.23/0.19+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 969 @14.877s 1%: 0.016+2.5+0.16 ms clock, 0.27+0.25/8.2/14+2.6 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 970 @15.009s 1%: 0.016+6.7+0.19 ms clock, 0.26+0.20/25/22+3.1 ms cpu, 7->8->7 MB, 8 MB goal, 16 P
gc 971 @15.170s 1%: 0.020+3.0+0.15 ms clock, 0.33+0.24/9.0/10+2.4 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6079544 HeapInuse: 6397952 HeapObjects: 86410 HeapIdle 11100160 HeapReleased 0 HeapSys 17498112
gc 972 @15.224s 1%: 0.010+0.30+0.16 ms clock, 0.16+0/0.40/0.49+2.6 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
gc 973 @15.225s 1%: 0.024+0.26+0.14 ms clock, 0.39+0/0.39/0.24+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 974 @15.317s 1%: 0.016+2.6+0.11 ms clock, 0.26+0.25/8.6/16+1.8 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 975 @15.452s 1%: 0.022+5.3+0.12 ms clock, 0.35+0.40/18/32+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 976 @15.616s 1%: 0.022+4.9+0.20 ms clock, 0.35+0.12/9.6/0.018+3.3 ms cpu, 15->15->3 MB, 16 MB goal, 16 P
HeapAlloc: 6151272 HeapInuse: 6471680 HeapObjects: 87629 HeapIdle 11026432 HeapReleased 0 HeapSys 17498112
gc 977 @15.670s 1%: 0.034+0.29+0.18 ms clock, 0.55+0/0.45/0.20+2.9 ms cpu, 5->5->0 MB, 6 MB goal, 16 P (forced)
  100000	      1859 ns/op	      96 B/op	       2 allocs/op
gc 978 @15.672s 1%: 0.048+0.28+0.13 ms clock, 0.76+0/0.38/0.28+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 979 @15.744s 1%: 0.015+0.71+0.16 ms clock, 0.24+0.19/1.9/1.1+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 980 @15.804s 1%: 0.019+0.76+0.14 ms clock, 0.30+0.15/2.0/2.0+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 981 @15.862s 1%: 0.015+0.80+0.20 ms clock, 0.24+0.18/1.9/1.4+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849464 HeapInuse: 2195456 HeapObjects: 14303 HeapIdle 15302656 HeapReleased 0 HeapSys 17498112
gc 982 @15.870s 1%: 0.010+0.29+0.15 ms clock, 0.17+0/0.48/0.20+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndErase1E5-16                  	gc 983 @15.871s 1%: 0.037+0.27+0.13 ms clock, 0.60+0/0.48/0.23+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 984 @15.942s 1%: 0.015+0.82+0.18 ms clock, 0.25+0.19/1.8/1.8+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 985 @16.001s 1%: 0.014+0.84+0.15 ms clock, 0.23+0.33/1.9/2.1+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 986 @16.060s 1%: 0.015+0.70+0.10 ms clock, 0.25+0.17/1.6/1.6+1.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849496 HeapInuse: 2170880 HeapObjects: 14304 HeapIdle 15327232 HeapReleased 0 HeapSys 17498112
gc 987 @16.068s 1%: 0.009+0.26+0.17 ms clock, 0.15+0/0.44/0.17+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 988 @16.069s 1%: 0.011+0.21+0.17 ms clock, 0.18+0/0.30/0.15+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 989 @16.139s 1%: 0.017+0.79+0.24 ms clock, 0.27+0.42/2.0/1.4+3.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 990 @16.199s 1%: 0.019+0.90+0.11 ms clock, 0.31+0.37/2.3/2.5+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 991 @16.260s 1%: 0.016+0.79+0.20 ms clock, 0.26+0.18/1.8/1.3+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849496 HeapInuse: 2195456 HeapObjects: 14304 HeapIdle 15302656 HeapReleased 0 HeapSys 17498112
gc 992 @16.268s 1%: 0.010+0.22+0.13 ms clock, 0.16+0/0.36/0.33+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 993 @16.269s 1%: 0.024+0.21+0.11 ms clock, 0.39+0/0.36/0.22+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 994 @16.341s 1%: 0.025+0.83+0.18 ms clock, 0.40+0.32/1.8/1.9+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 995 @16.402s 1%: 0.015+0.95+0.11 ms clock, 0.25+0.23/1.9/1.9+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 996 @16.461s 1%: 0.017+0.78+0.13 ms clock, 0.27+0.33/1.6/1.1+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849576 HeapInuse: 2187264 HeapObjects: 14304 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 997 @16.469s 1%: 0.010+0.27+0.18 ms clock, 0.16+0/0.34/0.20+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 998 @16.469s 1%: 0.022+0.24+0.18 ms clock, 0.35+0/0.43/0.29+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 999 @16.543s 1%: 0.016+0.69+0.098 ms clock, 0.26+0.15/2.0/1.8+1.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1000 @16.603s 1%: 0.015+0.75+0.13 ms clock, 0.24+0.17/1.7/2.8+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1001 @16.663s 1%: 0.015+1.0+0.15 ms clock, 0.24+0.23/2.3/0.77+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849576 HeapInuse: 2170880 HeapObjects: 14304 HeapIdle 15327232 HeapReleased 0 HeapSys 17498112
gc 1002 @16.671s 1%: 0.010+0.22+0.11 ms clock, 0.16+0/0.36/0.21+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1003 @16.671s 1%: 0.020+0.24+0.13 ms clock, 0.32+0/0.38/0.26+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1004 @16.743s 1%: 0.015+0.81+0.12 ms clock, 0.24+0.25/1.6/1.1+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1005 @16.803s 1%: 0.014+0.72+0.14 ms clock, 0.23+0.23/1.7/1.9+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1006 @16.862s 1%: 0.016+0.85+0.21 ms clock, 0.25+0.085/2.1/1.3+3.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849688 HeapInuse: 2195456 HeapObjects: 14306 HeapIdle 15302656 HeapReleased 0 HeapSys 17498112
gc 1007 @16.869s 1%: 0.008+0.23+0.14 ms clock, 0.13+0/0.30/0.15+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1008 @16.870s 1%: 0.020+0.28+0.13 ms clock, 0.33+0/0.30/0.33+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1009 @16.942s 1%: 0.017+0.83+0.18 ms clock, 0.27+0.27/1.7/1.1+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1010 @17.001s 1%: 0.016+0.90+0.18 ms clock, 0.27+0.20/2.3/1.1+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1011 @17.060s 1%: 0.017+0.97+0.14 ms clock, 0.28+0.13/2.4/0.81+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849768 HeapInuse: 2170880 HeapObjects: 14306 HeapIdle 15327232 HeapReleased 0 HeapSys 17498112
gc 1012 @17.068s 1%: 0.046+0.20+0.13 ms clock, 0.74+0/0.41/0.26+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1013 @17.069s 1%: 0.022+0.23+0.11 ms clock, 0.35+0/0.38/0.23+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1014 @17.140s 1%: 0.014+0.71+0.15 ms clock, 0.23+0.13/2.1/1.7+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1015 @17.199s 1%: 0.019+2.1+0.12 ms clock, 0.31+0.40/3.1/1.1+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1016 @17.262s 1%: 0.017+0.78+0.14 ms clock, 0.27+0.28/1.7/1.4+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2179072 HeapObjects: 14307 HeapIdle 15319040 HeapReleased 0 HeapSys 17498112
gc 1017 @17.270s 1%: 0.010+0.35+0.21 ms clock, 0.17+0/0.49/0.19+3.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1018 @17.271s 1%: 0.012+0.20+0.10 ms clock, 0.20+0/0.41/0.17+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1019 @17.342s 1%: 0.017+0.83+0.35 ms clock, 0.27+0.32/2.0/1.6+5.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1020 @17.402s 1%: 0.013+0.68+0.16 ms clock, 0.22+0.28/1.9/1.9+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1021 @17.460s 1%: 0.017+0.65+0.096 ms clock, 0.28+0.34/1.9/1.2+1.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2162688 HeapObjects: 14307 HeapIdle 15335424 HeapReleased 0 HeapSys 17498112
gc 1022 @17.468s 1%: 0.009+0.21+0.12 ms clock, 0.14+0/0.34/0.23+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1023 @17.469s 1%: 0.024+0.25+0.15 ms clock, 0.39+0/0.36/0.29+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1024 @17.540s 1%: 0.016+0.74+0.10 ms clock, 0.26+0.19/1.8/1.7+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1025 @17.600s 1%: 0.015+0.89+0.21 ms clock, 0.25+0.41/2.1/1.8+3.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1026 @17.658s 1%: 0.015+0.70+0.12 ms clock, 0.24+0.14/2.0/2.0+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849848 HeapInuse: 2162688 HeapObjects: 14306 HeapIdle 15335424 HeapReleased 0 HeapSys 17498112
gc 1027 @17.666s 1%: 0.067+0.21+0.14 ms clock, 1.0+0/0.43/0.20+2.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1028 @17.666s 1%: 0.011+0.29+0.10 ms clock, 0.18+0/0.53/0.19+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1029 @17.737s 1%: 0.022+0.79+0.16 ms clock, 0.35+0.21/1.6/0.99+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1030 @17.797s 1%: 0.019+1.2+0.13 ms clock, 0.31+0.21/2.5/0.92+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1031 @17.859s 1%: 0.019+1.0+0.15 ms clock, 0.30+0.25/1.0/2.0+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2162688 HeapObjects: 14307 HeapIdle 15335424 HeapReleased 0 HeapSys 17498112
gc 1032 @17.867s 1%: 0.058+0.22+0.21 ms clock, 0.93+0/0.39/0.27+3.3 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1033 @17.867s 1%: 0.021+0.24+0.12 ms clock, 0.35+0/0.46/0.31+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1034 @17.938s 1%: 0.016+0.80+0.17 ms clock, 0.26+0.18/1.8/1.3+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1035 @17.998s 1%: 0.018+1.0+0.13 ms clock, 0.30+0.23/2.4/0.73+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1036 @18.058s 1%: 0.014+0.93+0.14 ms clock, 0.22+0.25/1.8/0.95+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2162688 HeapObjects: 14307 HeapIdle 15335424 HeapReleased 0 HeapSys 17498112
gc 1037 @18.066s 1%: 0.015+0.24+0.18 ms clock, 0.24+0/0.40/0.28+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1038 @18.067s 1%: 0.018+0.19+0.13 ms clock, 0.29+0/0.36/0.28+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1039 @18.138s 1%: 0.013+0.73+0.14 ms clock, 0.22+0.20/2.1/0.95+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1040 @18.199s 1%: 0.018+0.74+0.096 ms clock, 0.30+0.35/1.9/3.4+1.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1041 @18.259s 1%: 0.017+0.77+0.15 ms clock, 0.28+0.18/1.7/1.9+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2170880 HeapObjects: 14307 HeapIdle 15327232 HeapReleased 0 HeapSys 17498112
gc 1042 @18.267s 1%: 0.011+0.24+0.11 ms clock, 0.17+0/0.30/0.25+1.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1043 @18.268s 1%: 0.008+0.25+0.15 ms clock, 0.14+0/0.39/0.23+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1044 @18.338s 1%: 0.015+0.94+0.13 ms clock, 0.25+0.16/2.1/0.83+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1045 @18.398s 1%: 0.016+0.73+0.11 ms clock, 0.27+0.17/2.1/2.0+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1046 @18.456s 1%: 0.015+0.71+0.14 ms clock, 0.24+0.19/1.8/1.7+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849864 HeapInuse: 2154496 HeapObjects: 14307 HeapIdle 15343616 HeapReleased 0 HeapSys 17498112
gc 1047 @18.464s 1%: 0.013+0.24+0.20 ms clock, 0.21+0/0.45/0.23+3.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1048 @18.465s 1%: 0.008+0.24+0.13 ms clock, 0.14+0/0.45/0.11+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1049 @18.536s 1%: 0.017+0.93+0.18 ms clock, 0.28+0.20/2.0/0.95+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1050 @18.595s 1%: 0.013+0.87+0.18 ms clock, 0.22+0.20/2.3/1.7+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1051 @18.654s 1%: 0.014+0.84+0.17 ms clock, 0.22+0.36/1.8/1.4+2.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1849960 HeapInuse: 2154496 HeapObjects: 14308 HeapIdle 15343616 HeapReleased 0 HeapSys 17498112
gc 1052 @18.661s 1%: 0.037+0.24+0.18 ms clock, 0.59+0/0.21/0.22+2.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1053 @18.662s 1%: 0.018+0.28+0.11 ms clock, 0.29+0/0.40/0.24+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1054 @18.733s 1%: 0.015+0.76+0.19 ms clock, 0.25+0.18/1.9/1.5+3.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1055 @18.793s 1%: 0.017+0.91+0.15 ms clock, 0.27+0.12/2.3/2.0+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1056 @18.853s 1%: 0.016+0.83+0.12 ms clock, 0.25+0.13/1.9/1.4+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1850056 HeapInuse: 2170880 HeapObjects: 14309 HeapIdle 15327232 HeapReleased 0 HeapSys 17498112
gc 1057 @18.861s 1%: 0.008+0.26+0.13 ms clock, 0.13+0/0.46/0.082+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
  100000	      1988 ns/op	      96 B/op	       2 allocs/op
gc 1058 @18.862s 1%: 0.036+0.20+0.11 ms clock, 0.57+0/0.38/0.18+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1059 @19.007s 1%: 0.017+0.48+0.10 ms clock, 0.27+0.27/1.1/0.53+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979152 HeapInuse: 3309568 HeapObjects: 40794 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1060 @19.097s 1%: 0.044+0.21+0.12 ms clock, 0.70+0/0.34/0.13+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSetInsertAndEraseWithPool1E5-16          	gc 1061 @19.097s 1%: 0.061+0.23+0.15 ms clock, 0.97+0/0.38/0.18+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1062 @19.246s 1%: 0.018+0.51+0.10 ms clock, 0.30+0.25/1.2/0.51+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979200 HeapInuse: 3301376 HeapObjects: 40795 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1063 @19.333s 1%: 0.012+0.28+0.12 ms clock, 0.20+0/0.38/0.13+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1064 @19.334s 1%: 0.022+0.22+0.095 ms clock, 0.35+0/0.46/0.16+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1065 @19.482s 1%: 0.018+0.51+0.20 ms clock, 0.29+0.25/1.0/0.55+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979200 HeapInuse: 3301376 HeapObjects: 40795 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1066 @19.568s 1%: 0.009+0.32+0.12 ms clock, 0.15+0/0.47/0.26+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1067 @19.569s 1%: 0.013+0.22+0.11 ms clock, 0.21+0/0.35/0.14+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1068 @19.715s 1%: 0.019+0.48+0.17 ms clock, 0.30+0.21/1.0/0.38+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979200 HeapInuse: 3309568 HeapObjects: 40795 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1069 @19.806s 1%: 0.027+0.25+0.18 ms clock, 0.44+0/0.39/0.29+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1070 @19.807s 1%: 0.011+0.21+0.11 ms clock, 0.17+0/0.40/0.097+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1071 @19.956s 1%: 0.020+0.49+0.15 ms clock, 0.32+0.28/0.91/0.78+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979296 HeapInuse: 3301376 HeapObjects: 40796 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1072 @20.045s 1%: 0.011+0.26+0.15 ms clock, 0.18+0/0.36/0.20+2.5 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1073 @20.046s 1%: 0.018+0.24+0.097 ms clock, 0.29+0/0.36/0.21+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1074 @20.194s 1%: 0.022+0.68+0.12 ms clock, 0.35+0.14/2.0/0.030+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979392 HeapInuse: 3301376 HeapObjects: 40797 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1075 @20.286s 1%: 0.013+0.33+0.19 ms clock, 0.21+0/0.45/0.35+3.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1076 @20.287s 1%: 0.021+0.23+0.14 ms clock, 0.34+0/0.37/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1077 @20.413s 1%: 0.017+0.56+0.16 ms clock, 0.27+0.15/0.87/0.40+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979392 HeapInuse: 3301376 HeapObjects: 40797 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1078 @20.501s 1%: 0.011+0.28+0.23 ms clock, 0.18+0/0.46/0.20+3.7 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1079 @20.502s 1%: 0.10+0.25+0.12 ms clock, 1.6+0/0.36/0.19+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1080 @20.593s 1%: 0.015+0.45+0.16 ms clock, 0.25+0.14/0.79/0.27+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979488 HeapInuse: 3301376 HeapObjects: 40798 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1081 @20.680s 1%: 0.009+0.26+0.17 ms clock, 0.15+0/0.41/0.26+2.7 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1082 @20.681s 1%: 0.056+0.27+0.22 ms clock, 0.89+0/0.35/0.21+3.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1083 @20.771s 1%: 0.013+0.41+0.17 ms clock, 0.21+0.12/0.99/0.39+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979472 HeapInuse: 3301376 HeapObjects: 40797 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1084 @20.860s 1%: 0.034+0.26+0.12 ms clock, 0.55+0/0.30/0.17+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1085 @20.861s 1%: 0.021+0.23+0.21 ms clock, 0.34+0/0.44/0.12+3.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1086 @21.007s 1%: 0.017+0.48+0.19 ms clock, 0.28+0.17/1.1/0.58+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979488 HeapInuse: 3309568 HeapObjects: 40798 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1087 @21.094s 1%: 0.035+0.23+0.16 ms clock, 0.56+0/0.34/0.31+2.5 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1088 @21.095s 1%: 0.010+0.22+0.15 ms clock, 0.17+0/0.38/0.20+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1089 @21.241s 1%: 0.018+0.68+0.15 ms clock, 0.30+0.16/1.2/0.81+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979488 HeapInuse: 3309568 HeapObjects: 40798 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1090 @21.328s 1%: 0.083+4.0+0.11 ms clock, 1.3+0/4.4/0.23+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1091 @21.333s 1%: 0.012+0.28+0.093 ms clock, 0.19+0/0.37/0.26+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1092 @21.478s 1%: 0.019+0.58+0.19 ms clock, 0.31+0.26/1.0/0.84+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979504 HeapInuse: 3301376 HeapObjects: 40799 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1093 @21.565s 1%: 0.038+0.28+0.18 ms clock, 0.61+0/0.44/0.24+2.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1094 @21.566s 1%: 0.022+0.26+0.11 ms clock, 0.35+0/0.34/0.15+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1095 @21.713s 1%: 0.016+0.57+0.14 ms clock, 0.26+0.21/0.97/0.42+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979488 HeapInuse: 3309568 HeapObjects: 40798 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1096 @21.799s 1%: 0.012+0.28+0.17 ms clock, 0.20+0/0.52/0.23+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1097 @21.800s 1%: 0.020+0.21+0.13 ms clock, 0.33+0/0.36/0.18+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1098 @21.947s 1%: 0.014+0.62+0.19 ms clock, 0.23+0.19/0.91/0.88+3.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979504 HeapInuse: 3301376 HeapObjects: 40799 HeapIdle 14196736 HeapReleased 0 HeapSys 17498112
gc 1099 @22.034s 1%: 0.039+0.22+0.15 ms clock, 0.62+0/0.49/0.21+2.5 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1100 @22.035s 1%: 0.019+0.24+0.16 ms clock, 0.31+0/0.35/0.32+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1101 @22.181s 1%: 0.016+0.56+0.14 ms clock, 0.26+0.23/0.71/0.48+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979504 HeapInuse: 3309568 HeapObjects: 40799 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1102 @22.268s 1%: 0.011+0.31+0.22 ms clock, 0.18+0/0.27/0.49+3.6 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1103 @22.269s 1%: 0.021+0.30+0.10 ms clock, 0.35+0/0.40/0.081+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1104 @22.420s 1%: 0.018+0.49+0.21 ms clock, 0.29+0.18/1.0/0.42+3.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2979504 HeapInuse: 3309568 HeapObjects: 40799 HeapIdle 14188544 HeapReleased 0 HeapSys 17498112
gc 1105 @22.507s 1%: 0.037+0.27+0.19 ms clock, 0.59+0/0.43/0.28+3.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
  100000	      2383 ns/op	      56 B/op	       1 allocs/op
gc 1106 @22.508s 1%: 0.053+0.22+0.14 ms clock, 0.86+0/0.38/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1107 @22.604s 1%: 0.023+2.9+0.15 ms clock, 0.38+0.58/9.3/11+2.5 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1108 @22.694s 1%: 0.019+7.7+0.19 ms clock, 0.31+0.25/18/23+3.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8365752 HeapInuse: 8699904 HeapObjects: 107748 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1109 @22.716s 1%: 0.010+0.31+0.16 ms clock, 0.16+0/0.52/0.15+2.6 ms cpu, 8->8->0 MB, 14 MB goal, 16 P (forced)
#BenchmarkIntSetInsert1E5-16                       	gc 1110 @22.718s 1%: 0.053+0.25+0.15 ms clock, 0.85+0/0.35/0.15+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1111 @22.811s 1%: 0.016+2.9+0.14 ms clock, 0.26+0.38/9.2/17+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1112 @22.903s 1%: 0.015+4.2+0.17 ms clock, 0.24+0.42/15/33+2.7 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8369864 HeapInuse: 8708096 HeapObjects: 108004 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1113 @22.923s 1%: 0.010+0.31+0.20 ms clock, 0.16+0/0.29/0.31+3.2 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1114 @22.924s 1%: 0.019+0.28+0.17 ms clock, 0.30+0/0.38/0.23+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1115 @23.017s 1%: 0.018+2.8+0.19 ms clock, 0.30+0.28/9.0/11+3.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1116 @23.105s 1%: 0.017+7.1+0.19 ms clock, 0.28+0.22/21/21+3.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8364136 HeapInuse: 8699904 HeapObjects: 107646 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1117 @23.126s 1%: 0.035+0.24+0.17 ms clock, 0.57+0/0.39/0.34+2.7 ms cpu, 8->8->0 MB, 14 MB goal, 16 P (forced)
gc 1118 @23.128s 1%: 0.026+0.20+0.19 ms clock, 0.41+0/0.36/0.10+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1119 @23.220s 1%: 0.019+2.4+0.13 ms clock, 0.31+0.51/8.8/18+2.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1120 @23.308s 1%: 0.017+5.0+0.11 ms clock, 0.28+0.27/18/40+1.8 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8369048 HeapInuse: 8708096 HeapObjects: 107953 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1121 @23.328s 1%: 0.009+0.26+0.15 ms clock, 0.14+0/0.31/0.26+2.4 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1122 @23.330s 1%: 0.012+0.27+0.18 ms clock, 0.20+0/0.42/0.15+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1123 @23.421s 1%: 0.017+2.9+0.17 ms clock, 0.27+0.26/8.5/15+2.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1124 @23.512s 1%: 0.017+5.1+0.11 ms clock, 0.27+0.18/17/30+1.8 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8370664 HeapInuse: 8708096 HeapObjects: 108054 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1125 @23.533s 1%: 0.011+0.24+0.13 ms clock, 0.18+0/0.50/0.21+2.1 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1126 @23.534s 1%: 0.011+0.23+0.15 ms clock, 0.18+0/0.25/0.34+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1127 @23.627s 1%: 0.016+2.9+0.15 ms clock, 0.26+0.28/9.6/14+2.5 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1128 @23.716s 1%: 0.016+5.2+0.16 ms clock, 0.26+0.43/19/27+2.6 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8365768 HeapInuse: 8699904 HeapObjects: 107748 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1129 @23.736s 1%: 0.009+0.29+0.18 ms clock, 0.14+0/0.40/0.24+2.9 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1130 @23.738s 1%: 0.012+0.24+0.14 ms clock, 0.19+0/0.38/0.18+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1131 @23.829s 1%: 0.018+3.2+0.12 ms clock, 0.29+0.17/10/13+2.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1132 @23.918s 1%: 0.016+5.1+0.21 ms clock, 0.26+0.21/18/39+3.4 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8366584 HeapInuse: 8699904 HeapObjects: 107799 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1133 @23.938s 1%: 0.010+0.31+0.18 ms clock, 0.17+0/0.43/0.16+3.0 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1134 @23.940s 1%: 0.020+0.23+0.24 ms clock, 0.32+0/0.39/0.24+3.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1135 @24.032s 1%: 0.017+2.9+0.14 ms clock, 0.27+0.31/9.5/17+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1136 @24.123s 1%: 0.017+4.7+0.16 ms clock, 0.27+0.15/17/37+2.6 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8367432 HeapInuse: 8699904 HeapObjects: 107852 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1137 @24.143s 1%: 0.011+0.26+0.15 ms clock, 0.17+0/0.47/0.30+2.5 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1138 @24.145s 1%: 0.020+0.25+0.16 ms clock, 0.32+0/0.42/0.19+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1139 @24.236s 1%: 0.015+2.7+0.12 ms clock, 0.24+0.14/9.4/16+1.9 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1140 @24.324s 1%: 0.015+4.6+0.12 ms clock, 0.24+0.15/16/37+1.9 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8370680 HeapInuse: 8708096 HeapObjects: 108055 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1141 @24.344s 1%: 0.010+0.24+0.13 ms clock, 0.17+0/0.41/0.30+2.2 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1142 @24.345s 1%: 0.009+0.25+0.14 ms clock, 0.15+0/0.41/0.20+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1143 @24.437s 1%: 0.015+2.5+0.11 ms clock, 0.25+0.28/9.1/16+1.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1144 @24.524s 1%: 0.016+4.1+0.20 ms clock, 0.25+0.21/15/28+3.3 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8372296 HeapInuse: 8708096 HeapObjects: 108156 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1145 @24.546s 1%: 0.009+0.24+0.16 ms clock, 0.14+0/0.35/0.15+2.6 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1146 @24.548s 1%: 0.019+0.27+0.12 ms clock, 0.30+0/0.46/0.13+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1147 @24.638s 1%: 0.015+2.7+0.16 ms clock, 0.24+0.16/9.8/13+2.6 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1148 @24.728s 1%: 0.023+5.3+0.14 ms clock, 0.37+0.13/17/27+2.3 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8366584 HeapInuse: 8699904 HeapObjects: 107799 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1149 @24.748s 1%: 0.011+0.24+0.17 ms clock, 0.18+0/0.38/0.25+2.8 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1150 @24.750s 1%: 0.012+0.26+0.12 ms clock, 0.20+0/0.40/0.16+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1151 @24.845s 1%: 0.019+3.8+0.11 ms clock, 0.31+0.34/1.6/19+1.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1152 @24.934s 1%: 0.017+5.1+0.16 ms clock, 0.28+0.42/17/37+2.5 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8365064 HeapInuse: 8699904 HeapObjects: 107699 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1153 @24.954s 1%: 0.032+0.29+0.16 ms clock, 0.52+0/0.50/0.18+2.6 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1154 @24.956s 1%: 0.010+0.23+0.10 ms clock, 0.16+0/0.37/0.25+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1155 @25.046s 1%: 0.016+2.7+0.17 ms clock, 0.26+0.13/9.8/15+2.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1156 @25.136s 1%: 0.016+5.0+0.18 ms clock, 0.26+0.15/17/34+2.8 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8369928 HeapInuse: 8708096 HeapObjects: 108003 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1157 @25.156s 1%: 0.033+0.24+0.13 ms clock, 0.54+0/0.42/0.17+2.1 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1158 @25.158s 1%: 0.024+0.24+0.16 ms clock, 0.39+0/0.47/0.15+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1159 @25.249s 1%: 0.016+2.6+0.13 ms clock, 0.26+0.22/8.8/15+2.1 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1160 @25.337s 1%: 0.018+5.2+0.10 ms clock, 0.28+4.0/18/27+1.7 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
HeapAlloc: 8369144 HeapInuse: 8708096 HeapObjects: 107954 HeapIdle 8790016 HeapReleased 0 HeapSys 17498112
gc 1161 @25.360s 1%: 0.009+0.23+0.15 ms clock, 0.15+0/0.28/0.27+2.4 ms cpu, 8->8->0 MB, 13 MB goal, 16 P (forced)
gc 1162 @25.361s 1%: 0.025+0.25+0.22 ms clock, 0.40+0/0.44/0.20+3.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1163 @25.452s 1%: 0.018+2.1+0.14 ms clock, 0.28+0.18/7.6/13+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1164 @25.542s 1%: 0.027+5.9+0.12 ms clock, 0.43+0.42/19/31+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8367528 HeapInuse: 8699904 HeapObjects: 107853 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1165 @25.562s 1%: 0.010+0.22+0.10 ms clock, 0.16+0/0.33/0.21+1.6 ms cpu, 8->8->0 MB, 14 MB goal, 16 P (forced)
gc 1166 @25.563s 1%: 0.016+0.21+0.15 ms clock, 0.26+0/0.40/0.17+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1167 @25.654s 1%: 0.019+2.8+0.18 ms clock, 0.30+0.27/9.9/9.7+2.9 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1168 @25.744s 1%: 0.020+5.8+0.15 ms clock, 0.32+0.24/18/23+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8368312 HeapInuse: 8699904 HeapObjects: 107902 HeapIdle 8798208 HeapReleased 0 HeapSys 17498112
gc 1169 @25.764s 1%: 0.011+0.28+0.11 ms clock, 0.18+0/0.42/0.25+1.8 ms cpu, 8->8->0 MB, 14 MB goal, 16 P (forced)
  100000	      2010 ns/op	      88 B/op	       2 allocs/op
gc 1170 @25.765s 1%: 0.083+0.22+0.13 ms clock, 1.3+0/0.36/0.15+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1171 @25.837s 1%: 0.023+2.2+0.10 ms clock, 0.37+0.17/7.9/15+1.6 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1172 @25.932s 1%: 0.015+4.7+0.16 ms clock, 0.24+0.27/16/31+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1173 @26.050s 1%: 0.020+3.1+0.12 ms clock, 0.32+0.39/10/16+2.0 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8199800 HeapInuse: 8527872 HeapObjects: 107080 HeapIdle 8970240 HeapReleased 0 HeapSys 17498112
gc 1174 @26.119s 1%: 0.013+0.30+0.12 ms clock, 0.21+0/0.46/0.37+1.9 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
#BenchmarkIntSetErase1E5-16                        	gc 1175 @26.120s 1%: 0.011+0.27+0.10 ms clock, 0.18+0/0.40/0.34+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1176 @26.193s 1%: 0.016+2.6+0.12 ms clock, 0.26+1.4/8.6/13+2.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1177 @26.292s 1%: 0.017+3.9+0.19 ms clock, 0.27+0.20/14/29+3.1 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
gc 1178 @26.407s 1%: 0.019+7.3+0.18 ms clock, 0.31+0.23/12/11+2.9 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8336904 HeapInuse: 8667136 HeapObjects: 109120 HeapIdle 8830976 HeapReleased 0 HeapSys 17498112
gc 1179 @26.476s 1%: 0.012+0.24+0.18 ms clock, 0.20+0/0.29/0.26+2.9 ms cpu, 8->8->0 MB, 9 MB goal, 16 P (forced)
gc 1180 @26.477s 1%: 0.009+0.26+0.14 ms clock, 0.15+0/0.38/0.38+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1181 @26.550s 1%: 0.014+2.9+0.14 ms clock, 0.23+0.24/7.8/11+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1182 @26.646s 1%: 0.019+4.9+0.12 ms clock, 0.31+0.27/15/30+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1183 @26.762s 1%: 0.019+3.1+0.11 ms clock, 0.30+0.28/11/11+1.8 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8028456 HeapInuse: 8355840 HeapObjects: 104530 HeapIdle 9142272 HeapReleased 0 HeapSys 17498112
gc 1184 @26.824s 1%: 0.010+0.32+0.13 ms clock, 0.17+0/0.49/0.40+2.2 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1185 @26.826s 1%: 0.025+0.23+0.11 ms clock, 0.40+0/0.40/0.31+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1186 @26.898s 1%: 0.012+2.2+0.17 ms clock, 0.20+0.22/7.4/13+2.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1187 @26.993s 1%: 0.019+4.8+0.13 ms clock, 0.30+0.31/16/35+2.1 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1188 @27.110s 1%: 0.019+2.5+0.11 ms clock, 0.31+0.30/8.6/16+1.8 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8182776 HeapInuse: 8511488 HeapObjects: 106826 HeapIdle 8986624 HeapReleased 0 HeapSys 17498112
gc 1189 @27.173s 1%: 0.011+0.28+0.16 ms clock, 0.17+0/0.37/0.27+2.7 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1190 @27.175s 1%: 0.019+0.28+0.15 ms clock, 0.30+0/0.49/0.22+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1191 @27.248s 1%: 0.017+2.4+0.12 ms clock, 0.27+0.14/8.0/15+1.9 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1192 @27.343s 1%: 0.016+4.9+0.11 ms clock, 0.26+0.32/17/31+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1193 @27.459s 1%: 0.016+2.8+0.19 ms clock, 0.25+0.17/9.4/15+3.1 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8148600 HeapInuse: 8478720 HeapObjects: 106317 HeapIdle 9019392 HeapReleased 0 HeapSys 17498112
gc 1194 @27.522s 1%: 0.033+0.27+0.18 ms clock, 0.53+0/0.39/0.21+2.9 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1195 @27.524s 1%: 0.059+0.23+0.11 ms clock, 0.95+0/0.42/0.22+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1196 @27.596s 1%: 0.013+2.4+0.19 ms clock, 0.21+0.18/7.7/14+3.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1197 @27.691s 1%: 0.017+4.7+0.14 ms clock, 0.28+0.15/16/18+2.2 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1198 @27.807s 1%: 0.019+3.0+0.19 ms clock, 0.31+0.18/10/11+3.0 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 7994376 HeapInuse: 8323072 HeapObjects: 104022 HeapIdle 9175040 HeapReleased 0 HeapSys 17498112
gc 1199 @27.869s 1%: 0.010+0.26+0.15 ms clock, 0.17+0/0.44/0.15+2.4 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1200 @27.871s 1%: 0.047+0.24+0.14 ms clock, 0.75+0/0.33/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1201 @27.944s 1%: 0.017+2.6+0.19 ms clock, 0.28+0.24/8.0/11+3.1 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1202 @28.041s 1%: 0.016+4.1+0.17 ms clock, 0.26+0.25/15/30+2.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1203 @28.155s 1%: 0.018+2.8+0.14 ms clock, 0.29+0.47/9.9/15+2.3 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8200040 HeapInuse: 8527872 HeapObjects: 107084 HeapIdle 8970240 HeapReleased 0 HeapSys 17498112
gc 1204 @28.220s 1%: 0.011+0.24+0.085 ms clock, 0.18+0/0.40/0.25+1.3 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1205 @28.221s 1%: 0.007+0.22+0.082 ms clock, 0.11+0/0.34/0.29+1.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1206 @28.294s 1%: 0.014+2.2+0.13 ms clock, 0.23+0.035/7.7/9.9+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1207 @28.389s 1%: 0.015+3.9+0.16 ms clock, 0.25+0.28/14/29+2.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1208 @28.503s 1%: 0.021+3.0+0.13 ms clock, 0.33+1.7/9.6/16+2.2 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8165848 HeapInuse: 8495104 HeapObjects: 106574 HeapIdle 9003008 HeapReleased 0 HeapSys 17498112
gc 1209 @28.567s 1%: 0.011+0.34+0.20 ms clock, 0.18+0/0.24/0.43+3.2 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1210 @28.569s 1%: 0.017+0.25+0.19 ms clock, 0.28+0/0.37/0.28+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1211 @28.640s 1%: 0.015+2.1+0.14 ms clock, 0.25+0.19/7.2/14+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1212 @28.735s 1%: 0.019+3.9+0.17 ms clock, 0.30+0.47/14/34+2.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1213 @28.851s 1%: 0.019+6.1+0.17 ms clock, 0.31+0.20/10/12+2.8 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8217224 HeapInuse: 8544256 HeapObjects: 107337 HeapIdle 8953856 HeapReleased 0 HeapSys 17498112
gc 1214 @28.917s 1%: 0.013+0.28+0.20 ms clock, 0.21+0/0.44/0.31+3.2 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1215 @28.919s 1%: 0.017+0.23+0.20 ms clock, 0.27+0/0.35/0.22+3.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1216 @28.991s 1%: 0.018+3.0+0.12 ms clock, 0.29+0.17/10/7.8+2.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1217 @29.087s 1%: 0.016+5.7+0.15 ms clock, 0.26+0.41/16/23+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1218 @29.204s 1%: 0.023+4.6+0.11 ms clock, 0.37+0.40/14/10+1.8 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8097400 HeapInuse: 8429568 HeapObjects: 105555 HeapIdle 9068544 HeapReleased 0 HeapSys 17498112
gc 1219 @29.270s 1%: 0.010+0.32+0.16 ms clock, 0.16+0/0.59/0.25+2.5 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1220 @29.271s 1%: 0.013+0.38+0.14 ms clock, 0.21+0/0.36/0.28+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1221 @29.342s 1%: 0.016+2.2+0.11 ms clock, 0.25+0.18/7.5/13+1.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1222 @29.439s 1%: 0.021+5.4+0.16 ms clock, 0.34+0.21/19/18+2.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1223 @29.555s 1%: 0.017+2.9+0.15 ms clock, 0.27+0.17/10/11+2.5 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 7874632 HeapInuse: 8208384 HeapObjects: 102240 HeapIdle 9289728 HeapReleased 0 HeapSys 17498112
gc 1224 @29.617s 1%: 0.010+0.33+0.16 ms clock, 0.16+0/0.45/0.26+2.7 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1225 @29.618s 1%: 0.008+0.28+0.22 ms clock, 0.13+0/0.48/0.31+3.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1226 @29.691s 1%: 0.018+2.4+0.14 ms clock, 0.29+0.28/7.6/14+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1227 @29.786s 1%: 0.015+5.4+0.15 ms clock, 0.24+0.27/16/29+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1228 @29.905s 1%: 0.018+2.4+0.14 ms clock, 0.29+0.21/8.6/18+2.3 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8176920 HeapInuse: 8511488 HeapObjects: 106737 HeapIdle 8986624 HeapReleased 0 HeapSys 17498112
gc 1229 @29.969s 1%: 0.010+0.33+0.17 ms clock, 0.16+0/0.47/0.092+2.8 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1230 @29.970s 1%: 0.018+0.23+0.098 ms clock, 0.28+0/0.37/0.12+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1231 @30.041s 1%: 0.015+3.3+0.15 ms clock, 0.24+0.17/8.5/10+2.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1232 @30.138s 1%: 0.017+4.2+0.15 ms clock, 0.28+0.49/15/28+2.4 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1233 @30.254s 1%: 0.021+2.5+0.12 ms clock, 0.34+0.13/9.0/13+1.9 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8125624 HeapInuse: 8462336 HeapObjects: 105974 HeapIdle 9035776 HeapReleased 0 HeapSys 17498112
gc 1234 @30.318s 1%: 0.011+0.30+0.19 ms clock, 0.18+0/0.36/0.44+3.0 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1235 @30.320s 1%: 0.011+0.25+0.12 ms clock, 0.18+0/0.29/0.37+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1236 @30.391s 1%: 0.014+2.2+0.14 ms clock, 0.22+0.46/7.6/11+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1237 @30.486s 1%: 0.017+4.4+0.18 ms clock, 0.28+0.21/15/28+2.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1238 @30.602s 1%: 0.020+2.9+0.20 ms clock, 0.32+0.29/9.5/15+3.2 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8200312 HeapInuse: 8536064 HeapObjects: 107086 HeapIdle 8962048 HeapReleased 0 HeapSys 17498112
gc 1239 @30.667s 1%: 0.028+0.33+0.18 ms clock, 0.45+0/0.41/0.21+2.9 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1240 @30.669s 1%: 0.028+0.28+0.21 ms clock, 0.46+0/0.38/0.21+3.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1241 @30.740s 1%: 0.013+2.4+0.20 ms clock, 0.21+0.17/8.3/13+3.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1242 @30.837s 1%: 0.017+4.0+0.14 ms clock, 0.27+0.41/14/34+2.2 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1243 @30.951s 1%: 0.021+3.0+0.12 ms clock, 0.34+0.16/10/18+1.9 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8183176 HeapInuse: 8519680 HeapObjects: 106831 HeapIdle 8978432 HeapReleased 0 HeapSys 17498112
gc 1244 @31.015s 1%: 0.037+0.33+0.13 ms clock, 0.60+0/0.54/0.17+2.1 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
gc 1245 @31.017s 1%: 0.022+0.24+0.10 ms clock, 0.35+0/0.38/0.19+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1246 @31.089s 1%: 0.016+2.1+0.16 ms clock, 0.26+0.21/6.9/11+2.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1247 @31.184s 1%: 0.020+4.2+0.13 ms clock, 0.32+0.061/15/24+2.1 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1248 @31.299s 1%: 0.022+2.6+0.15 ms clock, 0.36+0.17/9.1/13+2.4 ms cpu, 13->13->4 MB, 14 MB goal, 16 P
HeapAlloc: 8176776 HeapInuse: 8511488 HeapObjects: 106734 HeapIdle 8986624 HeapReleased 0 HeapSys 17498112
gc 1249 @31.364s 1%: 0.010+0.36+0.19 ms clock, 0.16+0/0.51/0.22+3.1 ms cpu, 7->7->0 MB, 8 MB goal, 16 P (forced)
  100000	      1490 ns/op	      96 B/op	       2 allocs/op
gc 1250 @31.366s 1%: 0.025+0.27+0.13 ms clock, 0.40+0/0.39/0.066+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1251 @31.428s 1%: 0.019+0.84+0.15 ms clock, 0.31+0.26/1.6/1.0+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1252 @31.480s 1%: 0.014+0.80+0.20 ms clock, 0.23+0.25/2.0/1.6+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1253 @31.529s 1%: 0.016+0.79+0.11 ms clock, 0.26+0.21/1.3/1.4+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729336 HeapInuse: 2048000 HeapObjects: 10790 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1254 @31.535s 1%: 0.048+0.24+0.12 ms clock, 0.78+0/0.35/0.12+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndErase1E5-16               	gc 1255 @31.535s 1%: 0.025+0.27+0.11 ms clock, 0.40+0/0.42/0.25+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1256 @31.594s 1%: 0.015+0.74+0.17 ms clock, 0.24+0.21/1.9/1.2+2.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1257 @31.644s 1%: 0.017+0.89+0.13 ms clock, 0.28+0.17/2.1/1.7+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1258 @31.692s 1%: 0.014+0.75+0.14 ms clock, 0.23+0.17/1.3/1.1+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729448 HeapInuse: 2064384 HeapObjects: 10790 HeapIdle 15433728 HeapReleased 0 HeapSys 17498112
gc 1259 @31.699s 1%: 0.014+0.31+0.16 ms clock, 0.22+0/0.41/0.27+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1260 @31.700s 1%: 0.032+0.24+0.12 ms clock, 0.51+0/0.27/0.18+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1261 @31.758s 1%: 0.018+1.0+0.15 ms clock, 0.30+0.14/2.0/0.43+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1262 @31.812s 1%: 0.015+0.69+0.25 ms clock, 0.24+0.17/1.8/1.3+4.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1263 @31.861s 1%: 0.015+0.61+0.16 ms clock, 0.25+0.26/1.4/0.82+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729496 HeapInuse: 2064384 HeapObjects: 10793 HeapIdle 15433728 HeapReleased 0 HeapSys 17498112
gc 1264 @31.867s 1%: 0.036+0.24+0.093 ms clock, 0.58+0/0.32/0.25+1.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1265 @31.868s 1%: 0.013+0.27+0.11 ms clock, 0.20+0/0.32/0.34+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1266 @31.927s 1%: 0.018+0.81+0.16 ms clock, 0.30+0.19/1.5/0.85+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1267 @31.978s 1%: 0.016+0.79+0.14 ms clock, 0.26+0.14/2.0/1.4+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1268 @32.025s 1%: 0.017+0.63+0.11 ms clock, 0.27+0.24/1.2/0.82+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2048000 HeapObjects: 10792 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1269 @32.031s 1%: 0.009+0.28+0.15 ms clock, 0.15+0/0.39/0.20+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1270 @32.032s 1%: 0.011+0.27+0.13 ms clock, 0.18+0/0.54/0.29+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1271 @32.090s 1%: 0.015+0.69+0.12 ms clock, 0.24+0.20/1.6/1.2+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1272 @32.140s 1%: 0.014+0.83+0.20 ms clock, 0.23+0.38/1.9/1.3+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1273 @32.187s 1%: 0.013+0.68+0.17 ms clock, 0.22+0.16/1.5/1.0+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2048000 HeapObjects: 10792 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1274 @32.193s 1%: 0.035+0.26+0.18 ms clock, 0.56+0/0.46/0.23+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1275 @32.194s 1%: 0.011+0.26+0.17 ms clock, 0.18+0/0.49/0.22+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1276 @32.254s 1%: 0.017+0.75+0.097 ms clock, 0.28+0.17/1.6/1.4+1.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1277 @32.303s 1%: 0.016+1.0+0.17 ms clock, 0.26+0.23/1.9/1.0+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1278 @32.353s 1%: 0.014+0.68+0.14 ms clock, 0.23+0.22/1.5/0.97+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2048000 HeapObjects: 10792 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1279 @32.359s 1%: 0.008+0.23+0.17 ms clock, 0.13+0/0.36/0.26+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1280 @32.360s 1%: 0.018+0.29+0.13 ms clock, 0.29+0/0.41/0.11+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1281 @32.417s 1%: 0.016+0.81+0.18 ms clock, 0.26+0.19/1.6/1.2+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1282 @32.466s 1%: 0.014+0.74+0.18 ms clock, 0.22+0.41/1.9/1.7+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1283 @32.514s 1%: 0.015+0.71+0.15 ms clock, 0.24+0.15/1.6/0.82+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729576 HeapInuse: 2048000 HeapObjects: 10793 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1284 @32.520s 1%: 0.009+0.28+0.18 ms clock, 0.15+0/0.45/0.28+2.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1285 @32.521s 1%: 0.020+0.24+0.14 ms clock, 0.33+0/0.36/0.28+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1286 @32.579s 1%: 0.024+0.84+0.18 ms clock, 0.39+0.38/1.6/0.48+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1287 @32.629s 1%: 0.017+0.77+0.16 ms clock, 0.27+0.16/2.2/1.0+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1288 @32.677s 1%: 0.014+0.83+0.17 ms clock, 0.23+0.12/2.1/0.34+2.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729576 HeapInuse: 2048000 HeapObjects: 10793 HeapIdle 15450112 HeapReleased 0 HeapSys 17498112
gc 1289 @32.684s 1%: 0.009+0.27+0.16 ms clock, 0.14+0/0.43/0.24+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1290 @32.684s 1%: 0.043+0.31+0.19 ms clock, 0.69+0/0.26/0.22+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1291 @32.742s 1%: 0.016+0.74+0.13 ms clock, 0.26+0.16/1.7/1.3+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1292 @32.792s 1%: 0.014+0.86+0.17 ms clock, 0.23+0.19/1.9/1.5+2.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1293 @32.841s 1%: 0.015+0.65+0.21 ms clock, 0.25+0.17/1.6/1.0+3.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2039808 HeapObjects: 10792 HeapIdle 15458304 HeapReleased 0 HeapSys 17498112
gc 1294 @32.847s 1%: 0.010+0.26+0.18 ms clock, 0.16+0/0.30/0.20+2.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1295 @32.847s 1%: 0.011+0.24+0.16 ms clock, 0.18+0/0.39/0.13+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1296 @32.905s 1%: 0.014+0.79+0.16 ms clock, 0.23+0.14/1.3/1.0+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1297 @32.955s 1%: 0.013+0.81+0.15 ms clock, 0.22+0.26/2.0/1.3+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1298 @33.002s 1%: 0.014+0.71+0.17 ms clock, 0.23+0.10/1.4/0.80+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2072576 HeapObjects: 10792 HeapIdle 15425536 HeapReleased 0 HeapSys 17498112
gc 1299 @33.008s 1%: 0.014+0.25+0.16 ms clock, 0.23+0/0.46/0.28+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1300 @33.009s 1%: 0.024+0.29+0.13 ms clock, 0.39+0/0.38/0.20+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1301 @33.066s 1%: 0.015+1.3+0.12 ms clock, 0.24+0.16/2.0/1.8+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1302 @33.116s 1%: 0.012+0.86+0.15 ms clock, 0.20+0.20/2.0/1.5+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1303 @33.163s 1%: 0.014+0.63+0.30 ms clock, 0.23+0.19/1.5/0.91+4.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729560 HeapInuse: 2039808 HeapObjects: 10792 HeapIdle 15458304 HeapReleased 0 HeapSys 17498112
gc 1304 @33.169s 1%: 0.010+0.26+0.10 ms clock, 0.17+0/0.47/0.18+1.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1305 @33.170s 1%: 0.010+0.29+0.10 ms clock, 0.16+0/0.40/0.16+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1306 @33.231s 1%: 0.018+0.65+0.10 ms clock, 0.29+0.11/1.5/2.3+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1307 @33.281s 1%: 0.015+0.88+0.20 ms clock, 0.25+0.25/1.6/1.3+3.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1308 @33.328s 1%: 0.016+0.73+0.12 ms clock, 0.25+0.15/1.6/1.2+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729576 HeapInuse: 2080768 HeapObjects: 10793 HeapIdle 15417344 HeapReleased 0 HeapSys 17498112
gc 1309 @33.335s 1%: 0.036+0.25+0.13 ms clock, 0.57+0/0.35/0.14+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1310 @33.335s 1%: 0.020+0.29+0.12 ms clock, 0.33+0/0.37/0.25+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1311 @33.394s 1%: 0.013+0.67+0.18 ms clock, 0.21+0.19/1.5/1.1+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1312 @33.443s 1%: 0.013+0.81+0.15 ms clock, 0.22+0.28/2.0/1.7+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1313 @33.491s 1%: 0.014+0.68+0.17 ms clock, 0.23+0.19/1.5/0.72+2.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729688 HeapInuse: 2072576 HeapObjects: 10795 HeapIdle 15425536 HeapReleased 0 HeapSys 17498112
gc 1314 @33.497s 1%: 0.035+0.23+0.13 ms clock, 0.57+0/0.39/0.21+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1315 @33.498s 1%: 0.021+0.24+0.16 ms clock, 0.33+0/0.40/0.23+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1316 @33.555s 1%: 0.013+0.58+0.19 ms clock, 0.21+0.12/1.5/1.6+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1317 @33.605s 1%: 0.019+0.80+0.10 ms clock, 0.31+0.20/1.9/2.2+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1318 @33.653s 1%: 0.013+0.62+0.10 ms clock, 0.21+0.12/1.5/0.99+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729688 HeapInuse: 2064384 HeapObjects: 10795 HeapIdle 15433728 HeapReleased 0 HeapSys 17498112
gc 1319 @33.659s 1%: 0.008+0.24+0.16 ms clock, 0.14+0/0.48/0.25+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1320 @33.659s 1%: 0.012+0.24+0.18 ms clock, 0.19+0/0.41/0.26+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1321 @33.718s 1%: 0.017+0.69+0.13 ms clock, 0.27+0.14/1.9/1.1+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1322 @33.768s 1%: 0.014+0.83+0.15 ms clock, 0.23+0.31/1.7/1.7+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1323 @33.815s 1%: 0.013+0.64+0.12 ms clock, 0.21+0.16/1.5/1.0+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729736 HeapInuse: 2056192 HeapObjects: 10793 HeapIdle 15441920 HeapReleased 0 HeapSys 17498112
gc 1324 @33.821s 1%: 0.010+0.25+0.15 ms clock, 0.17+0/0.53/0.13+2.4 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1325 @33.822s 1%: 0.012+0.29+0.15 ms clock, 0.19+0/0.33/0.20+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1326 @33.880s 1%: 0.016+0.73+0.15 ms clock, 0.26+0.17/1.9/0.049+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1327 @33.931s 1%: 0.015+0.74+0.11 ms clock, 0.24+0.15/2.0/0.51+1.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1328 @33.978s 1%: 0.013+0.89+0.12 ms clock, 0.21+0.16/1.4/0.86+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 1729736 HeapInuse: 2056192 HeapObjects: 10793 HeapIdle 15441920 HeapReleased 0 HeapSys 17498112
gc 1329 @33.984s 1%: 0.008+0.25+0.12 ms clock, 0.13+0/0.37/0.25+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
  100000	      1618 ns/op	      96 B/op	       2 allocs/op
gc 1330 @33.985s 1%: 0.009+0.26+0.11 ms clock, 0.15+0/0.43/0.16+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1331 @34.109s 1%: 0.015+0.49+0.10 ms clock, 0.24+0.25/1.0/0.48+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2961936 HeapInuse: 3293184 HeapObjects: 39643 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1332 @34.183s 1%: 0.009+0.37+0.13 ms clock, 0.14+0/0.64/0.15+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndEraseWithPool1E5-16       	gc 1333 @34.184s 1%: 0.051+0.23+0.12 ms clock, 0.82+0/0.44/0.17+2.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1334 @34.312s 1%: 0.018+0.51+0.15 ms clock, 0.29+0.25/1.0/0.064+2.5 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2962064 HeapInuse: 3284992 HeapObjects: 39644 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1335 @34.385s 1%: 0.036+0.32+0.15 ms clock, 0.57+0/0.39/0.42+2.4 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1336 @34.386s 1%: 0.008+0.25+0.13 ms clock, 0.14+0/0.47/0.19+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1337 @34.509s 1%: 0.015+0.49+0.14 ms clock, 0.24+0.17/1.0/0.33+2.3 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2962064 HeapInuse: 3293184 HeapObjects: 39644 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1338 @34.583s 1%: 0.022+0.24+0.13 ms clock, 0.36+0/0.45/0.15+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1339 @34.584s 1%: 0.044+0.27+0.18 ms clock, 0.71+0/0.46/0.17+2.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1340 @34.708s 1%: 0.018+0.45+0.13 ms clock, 0.29+0.16/0.89/0.50+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2962096 HeapInuse: 3293184 HeapObjects: 39646 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1341 @34.782s 1%: 0.012+0.28+0.15 ms clock, 0.20+0/0.35/0.21+2.4 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1342 @34.783s 1%: 0.016+0.36+0.14 ms clock, 0.26+0/0.25/0.27+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1343 @34.907s 1%: 0.015+0.41+0.11 ms clock, 0.25+0.34/0.83/0.50+1.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2962080 HeapInuse: 3293184 HeapObjects: 39645 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1344 @34.981s 1%: 0.032+0.26+0.12 ms clock, 0.52+0/0.36/0.20+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1345 @34.982s 1%: 0.11+0.28+0.20 ms clock, 1.8+0/0.35/0.17+3.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1346 @35.107s 1%: 0.015+0.47+0.17 ms clock, 0.24+0.20/0.78/0.63+2.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2962192 HeapInuse: 3293184 HeapObjects: 39647 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1347 @35.183s 1%: 0.012+0.31+0.16 ms clock, 0.20+0/0.41/0.23+2.6 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1348 @35.184s 1%: 0.020+0.23+0.11 ms clock, 0.33+0/0.42/0.19+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1349 @35.310s 1%: 0.018+0.55+0.23 ms clock, 0.30+0.21/1.1/0.49+3.8 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963104 HeapInuse: 3284992 HeapObjects: 39699 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1350 @35.383s 1%: 0.041+0.25+0.13 ms clock, 0.67+0/0.42/0.17+2.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1351 @35.384s 1%: 0.021+0.27+0.20 ms clock, 0.34+0/0.37/0.12+3.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1352 @35.510s 1%: 0.017+0.49+0.18 ms clock, 0.27+0.29/0.84/0.68+3.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963184 HeapInuse: 3284992 HeapObjects: 39699 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1353 @35.584s 1%: 0.039+0.29+0.20 ms clock, 0.62+0/0.34/0.32+3.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1354 @35.585s 1%: 0.046+0.26+0.19 ms clock, 0.74+0/0.35/0.25+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1355 @35.711s 1%: 0.018+1.4+0.10 ms clock, 0.30+0.15/2.1/0.46+1.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963184 HeapInuse: 3284992 HeapObjects: 39699 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1356 @35.787s 1%: 0.011+0.29+0.10 ms clock, 0.19+0/0.46/0.29+1.7 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1357 @35.787s 1%: 0.012+0.28+0.14 ms clock, 0.20+0/0.45/0.21+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1358 @35.911s 1%: 0.017+0.60+0.36 ms clock, 0.28+0.23/1.1/0.12+5.7 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963184 HeapInuse: 3293184 HeapObjects: 39699 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1359 @35.985s 1%: 0.035+0.27+0.21 ms clock, 0.56+0/0.43/0.23+3.3 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1360 @35.986s 1%: 0.021+0.22+0.14 ms clock, 0.34+0/0.43/0.28+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1361 @36.112s 1%: 0.019+0.54+0.13 ms clock, 0.31+0.16/1.1/0.40+2.1 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963168 HeapInuse: 3284992 HeapObjects: 39698 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1362 @36.186s 1%: 0.010+0.37+0.12 ms clock, 0.16+0/0.36/0.15+2.0 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1363 @36.187s 1%: 0.021+0.22+0.11 ms clock, 0.34+0/0.34/0.28+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1364 @36.317s 1%: 0.018+0.50+0.13 ms clock, 0.29+0.22/0.78/0.63+2.2 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963264 HeapInuse: 3284992 HeapObjects: 39699 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1365 @36.392s 1%: 0.012+0.26+0.17 ms clock, 0.20+0/0.37/0.22+2.8 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1366 @36.393s 1%: 0.010+0.24+0.13 ms clock, 0.16+0/0.48/0.27+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1367 @36.521s 1%: 0.016+0.47+0.15 ms clock, 0.26+0.14/1.1/0.57+2.4 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963392 HeapInuse: 3293184 HeapObjects: 39702 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1368 @36.595s 1%: 0.011+0.36+0.13 ms clock, 0.18+0/0.37/0.31+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1369 @36.596s 1%: 0.012+0.27+0.14 ms clock, 0.19+0/0.47/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1370 @36.722s 1%: 0.020+0.47+0.12 ms clock, 0.32+0.21/1.0/0.40+1.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963472 HeapInuse: 3284992 HeapObjects: 39702 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1371 @36.796s 1%: 0.036+0.26+0.12 ms clock, 0.58+0/0.38/0.28+1.9 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1372 @36.797s 1%: 0.053+0.26+0.14 ms clock, 0.85+0/0.36/0.25+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1373 @36.921s 1%: 0.016+0.50+0.12 ms clock, 0.26+0.16/1.2/0.36+2.0 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963472 HeapInuse: 3284992 HeapObjects: 39702 HeapIdle 14213120 HeapReleased 0 HeapSys 17498112
gc 1374 @36.995s 1%: 0.012+0.31+0.20 ms clock, 0.20+0/0.33/0.22+3.2 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
gc 1375 @36.995s 1%: 0.012+0.32+0.17 ms clock, 0.19+0/0.44/0.22+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1376 @37.122s 1%: 0.018+0.52+0.10 ms clock, 0.29+0.19/1.0/0.59+1.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
HeapAlloc: 2963472 HeapInuse: 3293184 HeapObjects: 39702 HeapIdle 14204928 HeapReleased 0 HeapSys 17498112
gc 1377 @37.198s 1%: 0.012+0.29+0.13 ms clock, 0.19+0/0.36/0.35+2.1 ms cpu, 2->2->0 MB, 4 MB goal, 16 P (forced)
  100000	      2025 ns/op	      56 B/op	       1 allocs/op
gc 1378 @37.199s 1%: 0.013+0.25+0.16 ms clock, 0.22+0/0.33/0.14+2.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3861552 HeapInuse: 4333568 HeapObjects: 4772 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1379 @37.228s 1%: 0.009+0.27+0.14 ms clock, 0.14+0/0.41/0.42+2.2 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsert1E5-16                   	gc 1380 @37.229s 1%: 0.009+0.23+0.094 ms clock, 0.15+0/0.30/0.16+1.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3881144 HeapInuse: 4333568 HeapObjects: 4785 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1381 @37.258s 1%: 0.010+0.27+0.16 ms clock, 0.16+0/0.45/0.22+2.6 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1382 @37.259s 1%: 0.010+0.26+0.16 ms clock, 0.16+0/0.49/0.19+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3862456 HeapInuse: 4333568 HeapObjects: 4784 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1383 @37.287s 1%: 0.009+0.34+0.16 ms clock, 0.15+0/0.72/0.14+2.6 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1384 @37.288s 1%: 0.079+0.24+0.12 ms clock, 1.2+0/0.45/0.30+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3879128 HeapInuse: 4333568 HeapObjects: 4767 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1385 @37.322s 1%: 0.011+0.47+0.11 ms clock, 0.18+0/0.47/0.18+1.8 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1386 @37.322s 1%: 0.057+0.26+0.14 ms clock, 0.92+0/0.37/0.16+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3856704 HeapInuse: 4325376 HeapObjects: 4723 HeapIdle 13172736 HeapReleased 0 HeapSys 17498112
gc 1387 @37.351s 1%: 0.013+0.31+0.11 ms clock, 0.21+0/0.55/0.44+1.8 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1388 @37.352s 1%: 0.011+0.25+0.13 ms clock, 0.18+0/0.49/0.27+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3855640 HeapInuse: 4325376 HeapObjects: 4713 HeapIdle 13172736 HeapReleased 0 HeapSys 17498112
gc 1389 @37.380s 1%: 0.041+0.30+0.20 ms clock, 0.67+0/0.63/0.23+3.2 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1390 @37.381s 1%: 0.014+0.24+0.10 ms clock, 0.23+0/0.42/0.18+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3887256 HeapInuse: 4341760 HeapObjects: 4851 HeapIdle 13156352 HeapReleased 0 HeapSys 17498112
gc 1391 @37.410s 1%: 0.011+0.41+0.11 ms clock, 0.18+0/0.37/0.27+1.9 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1392 @37.411s 1%: 0.020+0.21+0.11 ms clock, 0.32+0/0.44/0.19+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3879448 HeapInuse: 4333568 HeapObjects: 4765 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1393 @37.441s 1%: 0.037+0.49+0.13 ms clock, 0.60+0/0.33/0.25+2.1 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1394 @37.441s 1%: 0.11+0.27+0.098 ms clock, 1.8+0/0.33/0.16+1.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3881992 HeapInuse: 4333568 HeapObjects: 4793 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1395 @37.471s 1%: 0.039+0.48+0.15 ms clock, 0.62+0/0.094/0.48+2.4 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1396 @37.472s 1%: 0.10+0.26+0.10 ms clock, 1.6+0/0.37/0.056+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3856056 HeapInuse: 4325376 HeapObjects: 4713 HeapIdle 13172736 HeapReleased 0 HeapSys 17498112
gc 1397 @37.501s 1%: 0.009+0.34+0.14 ms clock, 0.15+0/0.67/0.26+2.2 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1398 @37.502s 1%: 0.011+0.30+0.16 ms clock, 0.18+0/0.24/0.43+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3890224 HeapInuse: 4341760 HeapObjects: 4878 HeapIdle 13156352 HeapReleased 0 HeapSys 17498112
gc 1399 @37.530s 1%: 0.010+0.41+0.18 ms clock, 0.17+0/0.42/0.32+2.9 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1400 @37.531s 1%: 0.027+0.28+0.17 ms clock, 0.44+0/0.25/0.34+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3890712 HeapInuse: 4341760 HeapObjects: 4887 HeapIdle 13156352 HeapReleased 0 HeapSys 17498112
gc 1401 @37.560s 1%: 0.013+0.39+0.13 ms clock, 0.21+0/0.37/0.21+2.1 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1402 @37.561s 1%: 0.010+0.23+0.12 ms clock, 0.17+0/0.42/0.20+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3881448 HeapInuse: 4333568 HeapObjects: 4788 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1403 @37.591s 1%: 0.010+0.28+0.13 ms clock, 0.17+0/0.42/0.34+2.1 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
gc 1404 @37.592s 1%: 0.12+0.26+0.17 ms clock, 1.9+0/0.41/0.10+2.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 3881832 HeapInuse: 4333568 HeapObjects: 4789 HeapIdle 13164544 HeapReleased 0 HeapSys 17498112
gc 1405 @37.621s 1%: 0.045+0.30+0.16 ms clock, 0.72+0/0.63/0.23+2.6 ms cpu, 3->3->1 MB, 4 MB goal, 16 P (forced)
  100000	       294 ns/op	      36 B/op	       0 allocs/op
gc 1406 @37.622s 1%: 0.047+0.33+0.15 ms clock, 0.75+0/0.50/0.21+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1407 @37.637s 1%: 0.013+0.24+0.13 ms clock, 0.21+0.081/0.44/0.32+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3723120 HeapInuse: 4177920 HeapObjects: 3592 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1408 @37.664s 1%: 0.015+0.31+0.19 ms clock, 0.25+0/0.37/0.57+3.1 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
#BenchmarkSysHashMapErase1E5-16                    	gc 1409 @37.664s 1%: 0.032+0.26+0.13 ms clock, 0.52+0/0.45/0.14+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1410 @37.680s 1%: 0.011+0.57+0.14 ms clock, 0.18+0.15/0.41/0.33+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3740208 HeapInuse: 4169728 HeapObjects: 3720 HeapIdle 13328384 HeapReleased 0 HeapSys 17498112
gc 1411 @37.706s 1%: 0.012+0.53+0.15 ms clock, 0.19+0/0.19/0.52+2.4 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1412 @37.707s 1%: 0.014+0.25+0.11 ms clock, 0.23+0/0.40/0.20+1.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1413 @37.723s 1%: 0.013+0.36+0.097 ms clock, 0.22+0.17/0.37/0.22+1.5 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3733392 HeapInuse: 4177920 HeapObjects: 3649 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1414 @37.749s 1%: 0.009+0.39+0.13 ms clock, 0.15+0/0.18/0.38+2.1 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1415 @37.749s 1%: 0.017+0.24+0.11 ms clock, 0.28+0/0.38/0.17+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1416 @37.765s 1%: 0.012+0.33+0.097 ms clock, 0.20+0.14/0.24/0.29+1.5 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3726608 HeapInuse: 4169728 HeapObjects: 3629 HeapIdle 13328384 HeapReleased 0 HeapSys 17498112
gc 1417 @37.789s 1%: 0.047+0.25+0.14 ms clock, 0.75+0/0.31/0.32+2.3 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1418 @37.790s 1%: 0.076+0.22+0.11 ms clock, 1.2+0/0.38/0.13+1.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1419 @37.805s 1%: 0.012+0.34+0.14 ms clock, 0.19+0/0.47/0.24+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3735600 HeapInuse: 4194304 HeapObjects: 3672 HeapIdle 13303808 HeapReleased 0 HeapSys 17498112
gc 1420 @37.830s 1%: 0.045+0.44+0.16 ms clock, 0.73+0/0.34/0.20+2.6 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1421 @37.831s 1%: 0.015+0.23+0.16 ms clock, 0.25+0/0.36/0.29+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1422 @37.846s 1%: 0.012+0.77+0.20 ms clock, 0.20+0.14/0.24/0.92+3.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3728624 HeapInuse: 4169728 HeapObjects: 3650 HeapIdle 13328384 HeapReleased 0 HeapSys 17498112
gc 1423 @37.871s 1%: 0.014+0.38+0.18 ms clock, 0.22+0/0.64/0.61+2.9 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1424 @37.871s 1%: 0.022+0.25+0.16 ms clock, 0.35+0/0.45/0.12+2.6 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1425 @37.887s 1%: 0.011+0.33+0.14 ms clock, 0.17+0.19/0.38/0.10+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3738288 HeapInuse: 4177920 HeapObjects: 3700 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1426 @37.912s 1%: 0.008+0.27+0.13 ms clock, 0.13+0/0.46/0.27+2.1 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1427 @37.912s 1%: 0.065+0.21+0.11 ms clock, 1.0+0/0.35/0.22+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1428 @37.927s 1%: 0.013+0.28+0.15 ms clock, 0.22+0.094/0.32/0.26+2.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3733104 HeapInuse: 4186112 HeapObjects: 3646 HeapIdle 13312000 HeapReleased 0 HeapSys 17498112
gc 1429 @37.953s 1%: 0.010+0.49+0.16 ms clock, 0.16+0/0.36/0.29+2.6 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1430 @37.954s 1%: 0.020+0.25+0.10 ms clock, 0.32+0/0.37/0.18+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1431 @37.969s 1%: 0.012+0.31+0.16 ms clock, 0.20+0.14/0.19/0.39+2.5 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3741360 HeapInuse: 4177920 HeapObjects: 3732 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1432 @37.995s 1%: 0.010+0.48+0.13 ms clock, 0.16+0/0.38/0.27+2.1 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1433 @37.996s 1%: 0.018+0.23+0.18 ms clock, 0.28+0/0.32/0.14+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1434 @38.011s 1%: 0.013+0.33+0.21 ms clock, 0.21+0.13/0.32/0.29+3.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3724016 HeapInuse: 4177920 HeapObjects: 3602 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1435 @38.037s 1%: 0.009+0.31+0.17 ms clock, 0.15+0/0.40/0.31+2.8 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1436 @38.038s 1%: 0.018+0.27+0.11 ms clock, 0.29+0/0.42/0.18+1.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1437 @38.053s 1%: 0.013+0.28+0.23 ms clock, 0.21+0.14/0.38/0.39+3.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3725072 HeapInuse: 4161536 HeapObjects: 3613 HeapIdle 13336576 HeapReleased 0 HeapSys 17498112
gc 1438 @38.078s 1%: 0.008+0.27+0.13 ms clock, 0.13+0/0.53/0.18+2.1 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
gc 1439 @38.078s 1%: 0.019+0.25+0.15 ms clock, 0.31+0/0.34/0.16+2.5 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1440 @38.093s 1%: 0.011+0.30+0.13 ms clock, 0.18+0.15/0.42/0.22+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 3736560 HeapInuse: 4177920 HeapObjects: 3682 HeapIdle 13320192 HeapReleased 0 HeapSys 17498112
gc 1441 @38.118s 1%: 0.061+0.30+0.17 ms clock, 0.98+0/0.46/0.41+2.8 ms cpu, 3->3->1 MB, 6 MB goal, 16 P (forced)
  100000	       117 ns/op	       8 B/op	       0 allocs/op
gc 1442 @38.119s 1%: 0.068+0.26+0.14 ms clock, 1.0+0/0.40/0.30+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 814864 HeapInuse: 1204224 HeapObjects: 1500 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1443 @38.133s 1%: 0.024+0.32+0.15 ms clock, 0.39+0/0.28/0.19+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndErase1E5-16           	gc 1444 @38.134s 1%: 0.011+0.26+0.11 ms clock, 0.18+0/0.37/0.14+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 817512 HeapInuse: 1204224 HeapObjects: 1529 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1445 @38.148s 1%: 0.011+0.30+0.10 ms clock, 0.18+0/0.30/0.25+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1446 @38.149s 1%: 0.063+0.21+0.093 ms clock, 1.0+0/0.32/0.26+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 814640 HeapInuse: 1204224 HeapObjects: 1496 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1447 @38.163s 1%: 0.007+0.28+0.094 ms clock, 0.12+0/0.42/0.30+1.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1448 @38.163s 1%: 0.006+0.27+0.12 ms clock, 0.10+0/0.33/0.30+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 815368 HeapInuse: 1204224 HeapObjects: 1505 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1449 @38.178s 1%: 0.011+0.28+0.14 ms clock, 0.18+0/0.39/0.22+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1450 @38.178s 1%: 0.048+0.22+0.10 ms clock, 0.77+0/0.50/0.091+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 814896 HeapInuse: 1204224 HeapObjects: 1499 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1451 @38.192s 1%: 0.023+0.22+0.12 ms clock, 0.37+0/0.42/0.14+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1452 @38.193s 1%: 0.014+0.23+0.17 ms clock, 0.22+0/0.30/0.23+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 815760 HeapInuse: 1204224 HeapObjects: 1509 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1453 @38.208s 1%: 0.014+0.48+0.091 ms clock, 0.22+0/0.29/0.65+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1454 @38.209s 1%: 0.009+0.23+0.10 ms clock, 0.14+0/0.37/0.34+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 820128 HeapInuse: 1204224 HeapObjects: 1557 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1455 @38.225s 1%: 0.009+0.24+0.10 ms clock, 0.15+0/0.37/0.37+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1456 @38.226s 1%: 0.008+0.22+0.093 ms clock, 0.13+0/0.17/0.29+1.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 817896 HeapInuse: 1204224 HeapObjects: 1533 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1457 @38.240s 1%: 0.007+0.28+0.11 ms clock, 0.12+0/0.37/0.16+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1458 @38.240s 1%: 0.046+0.22+0.11 ms clock, 0.74+0/0.48/0.043+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 815824 HeapInuse: 1204224 HeapObjects: 1509 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1459 @38.255s 1%: 0.009+0.26+0.10 ms clock, 0.15+0/0.39/0.15+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1460 @38.255s 1%: 0.017+0.19+0.12 ms clock, 0.27+0/0.33/0.18+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 819496 HeapInuse: 1204224 HeapObjects: 1548 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1461 @38.269s 1%: 0.007+0.26+0.19 ms clock, 0.12+0/0.45/0.30+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1462 @38.270s 1%: 0.046+0.27+0.17 ms clock, 0.74+0/0.26/0.33+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 814808 HeapInuse: 1196032 HeapObjects: 1500 HeapIdle 16302080 HeapReleased 0 HeapSys 17498112
gc 1463 @38.284s 1%: 0.052+0.29+0.11 ms clock, 0.84+0/0.36/0.22+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1464 @38.284s 1%: 0.009+0.21+0.18 ms clock, 0.15+0/0.44/0.10+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 817040 HeapInuse: 1204224 HeapObjects: 1524 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1465 @38.298s 1%: 0.027+0.29+0.12 ms clock, 0.43+0/0.40/0.14+1.9 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1466 @38.299s 1%: 0.020+0.25+0.10 ms clock, 0.32+0/0.46/0.21+1.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 817560 HeapInuse: 1204224 HeapObjects: 1528 HeapIdle 16293888 HeapReleased 0 HeapSys 17498112
gc 1467 @38.313s 1%: 0.019+0.29+0.17 ms clock, 0.31+0/0.27/0.38+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
  100000	       140 ns/op	       5 B/op	       0 allocs/op
gc 1468 @38.314s 1%: 0.050+0.25+0.11 ms clock, 0.80+0/0.35/0.13+1.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872232 HeapInuse: 2187264 HeapObjects: 833 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1469 @38.326s 1%: 0.060+0.19+0.16 ms clock, 0.97+0/0.38/0.21+2.6 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndEraseWithBuf1E5-16    	gc 1470 @38.326s 1%: 0.008+0.27+0.17 ms clock, 0.12+0/0.39/0.19+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872280 HeapInuse: 2187264 HeapObjects: 834 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1471 @38.339s 1%: 0.009+0.28+0.13 ms clock, 0.15+0/0.46/0.16+2.1 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1472 @38.339s 1%: 0.017+0.24+0.13 ms clock, 0.27+0/0.40/0.14+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872360 HeapInuse: 2187264 HeapObjects: 834 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1473 @38.351s 1%: 0.050+0.25+0.15 ms clock, 0.81+0/0.34/0.16+2.5 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1474 @38.351s 1%: 0.011+0.26+0.13 ms clock, 0.18+0/0.44/0.22+2.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872456 HeapInuse: 2187264 HeapObjects: 835 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1475 @38.363s 1%: 0.036+0.30+0.15 ms clock, 0.57+0/0.45/0.23+2.4 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1476 @38.364s 1%: 0.015+0.27+0.14 ms clock, 0.25+0/0.48/0.24+2.2 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872648 HeapInuse: 2187264 HeapObjects: 837 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1477 @38.375s 1%: 0.050+0.27+0.12 ms clock, 0.80+0/0.38/0.072+2.0 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1478 @38.376s 1%: 0.017+0.21+0.12 ms clock, 0.28+0/0.38/0.21+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872744 HeapInuse: 2187264 HeapObjects: 838 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1479 @38.387s 1%: 0.013+0.25+0.19 ms clock, 0.21+0/0.37/0.20+3.0 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1480 @38.388s 1%: 0.11+0.26+0.13 ms clock, 1.8+0/0.37/0.19+2.1 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872744 HeapInuse: 2187264 HeapObjects: 838 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1481 @38.399s 1%: 0.008+0.26+0.15 ms clock, 0.12+0/0.43/0.21+2.4 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1482 @38.400s 1%: 0.013+0.25+0.11 ms clock, 0.21+0/0.44/0.24+1.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872744 HeapInuse: 2187264 HeapObjects: 838 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1483 @38.411s 1%: 0.034+0.21+0.14 ms clock, 0.54+0/0.46/0.17+2.3 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1484 @38.412s 1%: 0.011+0.24+0.10 ms clock, 0.18+0/0.38/0.16+1.7 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872744 HeapInuse: 2187264 HeapObjects: 838 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1485 @38.423s 1%: 0.046+0.26+0.16 ms clock, 0.74+0/0.21/0.22+2.6 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1486 @38.424s 1%: 0.080+0.29+0.17 ms clock, 1.2+0/0.40/0.088+2.8 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872840 HeapInuse: 2187264 HeapObjects: 839 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1487 @38.436s 1%: 0.052+0.26+0.16 ms clock, 0.84+0/0.39/0.26+2.5 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1488 @38.436s 1%: 0.036+0.26+0.12 ms clock, 0.58+0/0.36/0.21+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872840 HeapInuse: 2187264 HeapObjects: 839 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1489 @38.448s 1%: 0.025+0.24+0.10 ms clock, 0.41+0/0.37/0.13+1.7 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
gc 1490 @38.448s 1%: 0.089+0.19+0.12 ms clock, 1.4+0/0.48/0.023+1.9 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
HeapAlloc: 1872936 HeapInuse: 2187264 HeapObjects: 840 HeapIdle 15310848 HeapReleased 0 HeapSys 17498112
gc 1491 @38.460s 1%: 0.013+0.27+0.11 ms clock, 0.22+0/0.42/0.18+1.8 ms cpu, 1->1->1 MB, 4 MB goal, 16 P (forced)
  100000	       114 ns/op	      16 B/op	       0 allocs/op
gc 1492 @38.460s 1%: 0.018+0.25+0.18 ms clock, 0.29+0/0.39/0.15+3.0 ms cpu, 1->1->0 MB, 4 MB goal, 16 P (forced)
gc 1493 @38.463s 1%: 0.011+30+15 ms clock, 0.18+0/0.006/30+242 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8262840 HeapInuse: 8577024 HeapObjects: 840 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1494 @38.912s 1%: 0.012+0.30+0.17 ms clock, 0.20+0/0.41/0.26+2.7 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
#BenchmarkSort1E6-16                               	gc 1495 @38.913s 1%: 0.011+0.25+0.12 ms clock, 0.18+0/0.44/0.17+2.0 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1496 @38.915s 1%: 0.013+44+5.7 ms clock, 0.21+0/29/0.29+92 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8262968 HeapInuse: 8577024 HeapObjects: 842 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1497 @39.365s 1%: 0.013+0.33+0.14 ms clock, 0.21+0/0.50/0.23+2.3 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1498 @39.366s 1%: 0.014+0.25+0.13 ms clock, 0.22+0/0.45/0.22+2.2 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1499 @39.368s 1%: 0.013+46+5.8 ms clock, 0.21+0/0.43/30+93 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263064 HeapInuse: 8577024 HeapObjects: 843 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1500 @39.824s 1%: 0.011+0.32+0.17 ms clock, 0.18+0/0.41/0.17+2.7 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1501 @39.825s 1%: 0.061+0.32+0.12 ms clock, 0.99+0/0.40/0.18+2.0 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1502 @39.827s 1%: 0.013+44+5.6 ms clock, 0.21+0/0.20/29+91 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263160 HeapInuse: 8577024 HeapObjects: 844 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1503 @40.276s 1%: 0.014+0.27+0.19 ms clock, 0.23+0/0.49/0.19+3.1 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1504 @40.277s 1%: 0.013+0.26+0.14 ms clock, 0.21+0/0.47/0.24+2.2 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1505 @40.279s 1%: 0.011+29+15 ms clock, 0.18+0/0.33/29+246 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263160 HeapInuse: 8577024 HeapObjects: 844 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1506 @40.727s 1%: 0.012+0.31+0.18 ms clock, 0.20+0/0.41/0.21+2.9 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1507 @40.728s 1%: 0.054+0.24+0.091 ms clock, 0.87+0/0.40/0.26+1.4 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1508 @40.730s 1%: 0.012+44+5.7 ms clock, 0.20+0/0.23/29+91 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263256 HeapInuse: 8577024 HeapObjects: 845 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1509 @41.182s 1%: 0.013+0.27+0.15 ms clock, 0.21+0/0.47/0.24+2.4 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1510 @41.182s 1%: 0.038+0.20+0.11 ms clock, 0.61+0/0.36/0.17+1.8 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1511 @41.184s 1%: 0.011+45+6.2 ms clock, 0.19+0/0.26/29+99 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263448 HeapInuse: 8577024 HeapObjects: 847 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1512 @41.636s 1%: 0.010+0.28+0.14 ms clock, 0.16+0/0.48/0.27+2.3 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1513 @41.637s 1%: 0.052+0.25+0.084 ms clock, 0.83+0/0.42/0.19+1.3 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1514 @41.639s 1%: 0.010+29+0.16 ms clock, 0.16+0/29/0.44+2.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263640 HeapInuse: 8577024 HeapObjects: 849 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1515 @42.087s 1%: 0.012+0.30+0.23 ms clock, 0.20+0/0.55/0.22+3.6 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1516 @42.088s 1%: 0.052+0.23+0.16 ms clock, 0.83+0/0.38/0.21+2.6 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1517 @42.090s 1%: 0.012+44+5.6 ms clock, 0.20+0/0.16/29+91 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263640 HeapInuse: 8577024 HeapObjects: 849 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1518 @42.538s 1%: 0.013+0.30+0.21 ms clock, 0.22+0/0.43/0.20+3.4 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1519 @42.539s 1%: 0.017+0.24+0.13 ms clock, 0.27+0/0.44/0.10+2.1 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1520 @42.541s 1%: 0.012+31+15 ms clock, 0.20+0/0/31+247 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263736 HeapInuse: 8577024 HeapObjects: 850 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1521 @42.993s 1%: 0.014+0.29+0.20 ms clock, 0.22+0/0.46/0.17+3.2 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1522 @42.994s 1%: 0.11+0.29+0.12 ms clock, 1.8+0/0.45/0.074+2.0 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1523 @42.996s 1%: 0.016+45+5.7 ms clock, 0.26+0.092/29/0.15+91 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263832 HeapInuse: 8577024 HeapObjects: 851 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1524 @43.447s 1%: 0.011+0.33+0.19 ms clock, 0.18+0/0.47/0.23+3.1 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1525 @43.448s 1%: 0.014+0.30+0.094 ms clock, 0.22+0/0.38/0.32+1.5 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1526 @43.450s 1%: 0.010+44+6.1 ms clock, 0.16+0/0.058/29+98 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8263928 HeapInuse: 8577024 HeapObjects: 852 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1527 @43.903s 1%: 0.011+0.34+0.16 ms clock, 0.17+0/0.40/0.29+2.5 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1528 @43.903s 1%: 0.12+0.31+0.13 ms clock, 1.9+0/0.50/0.10+2.2 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1529 @43.906s 1%: 0.013+29+15 ms clock, 0.21+0/0.29/29+246 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8264024 HeapInuse: 8577024 HeapObjects: 853 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1530 @44.354s 1%: 0.067+0.35+0.16 ms clock, 1.0+0/0.58/0.23+2.5 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1531 @44.355s 1%: 0.017+0.26+0.11 ms clock, 0.28+0/0.48/0.20+1.9 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1532 @44.357s 1%: 0.013+44+5.7 ms clock, 0.21+0/0.41/29+91 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8264216 HeapInuse: 8577024 HeapObjects: 855 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1533 @44.804s 1%: 0.026+0.26+0.20 ms clock, 0.42+0/0.48/0.22+3.3 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
gc 1534 @44.805s 1%: 0.10+0.30+0.16 ms clock, 1.7+0/0.37/0.13+2.6 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1535 @44.807s 1%: 0.012+30+15 ms clock, 0.19+0.024/0.29/30+247 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
HeapAlloc: 8264312 HeapInuse: 8577024 HeapObjects: 856 HeapIdle 8921088 HeapReleased 0 HeapSys 17498112
gc 1536 @45.256s 1%: 0.011+0.24+0.12 ms clock, 0.18+0/0.48/0.19+1.9 ms cpu, 7->7->0 MB, 15 MB goal, 16 P (forced)
 1000000	       450 ns/op	       8 B/op	       0 allocs/op
gc 1537 @45.257s 1%: 0.029+0.24+0.14 ms clock, 0.47+0/0.37/0.18+2.2 ms cpu, 0->0->0 MB, 7 MB goal, 16 P (forced)
gc 1538 @45.372s 1%: 0.012+2.6+0.14 ms clock, 0.20+0.11/9.7/10+2.3 ms cpu, 4->4->3 MB, 7 MB goal, 16 P
gc 1539 @45.442s 1%: 0.015+4.1+0.17 ms clock, 0.24+0.39/14/22+2.8 ms cpu, 5->6->5 MB, 7 MB goal, 16 P
gc 1540 @45.509s 1%: 0.014+7.8+0.11 ms clock, 0.23+0.20/26/38+1.8 ms cpu, 10->10->10 MB, 11 MB goal, 16 P
gc 1541 @45.713s 1%: 0.025+14+0.19 ms clock, 0.40+0.31/50/100+3.1 ms cpu, 19->19->19 MB, 21 MB goal, 16 P
gc 1542 @46.070s 1%: 0.020+26+0.16 ms clock, 0.32+0.33/94/223+2.5 ms cpu, 37->37->37 MB, 39 MB goal, 16 P
gc 1543 @47.021s 1%: 0.019+43+0.20 ms clock, 0.31+0.42/170/451+3.2 ms cpu, 73->74->74 MB, 75 MB goal, 16 P
HeapAlloc: 88261144 HeapInuse: 88883200 HeapObjects: 1500870 HeapIdle 966656 HeapReleased 0 HeapSys 89849856
gc 1544 @47.266s 1%: 0.010+0.43+0.15 ms clock, 0.17+0/0.42/0.91+2.4 ms cpu, 84->84->0 MB, 148 MB goal, 16 P (forced)
#BenchmarkSetInsert1E6-16                          	 1000000	      2024 ns/op	      88 B/op	       2 allocs/op
gc 1545 @47.282s 1%: 0.058+0.23+0.10 ms clock, 0.93+0/0.33/0.15+1.6 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1546 @47.284s 1%: 0.014+0.31+0.14 ms clock, 0.22+0.15/0.32/0.16+2.3 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1547 @47.313s 1%: 0.011+1.1+0.12 ms clock, 0.17+0.23/2.8/3.7+1.9 ms cpu, 8->8->8 MB, 15 MB goal, 16 P
gc 1548 @47.442s 1%: 0.019+4.0+0.12 ms clock, 0.31+0.19/14/29+2.0 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1549 @47.664s 1%: 0.019+10+0.12 ms clock, 0.31+0.46/38/70+2.0 ms cpu, 21->21->21 MB, 25 MB goal, 16 P
gc 1550 @48.094s 1%: 0.019+19+0.12 ms clock, 0.31+0.15/76/199+2.0 ms cpu, 40->40->40 MB, 43 MB goal, 16 P
gc 1551 @49.020s 1%: 0.018+42+0.15 ms clock, 0.28+0.34/166/411+2.4 ms cpu, 77->78->78 MB, 81 MB goal, 16 P
gc 1552 @50.513s 1%: 0.052+15+0.12 ms clock, 0.83+0.42/57/133+2.0 ms cpu, 151->152->32 MB, 156 MB goal, 16 P
HeapAlloc: 59102328 HeapInuse: 59596800 HeapObjects: 867417 HeapIdle 101556224 HeapReleased 0 HeapSys 161153024
gc 1553 @50.859s 1%: 0.034+0.29+0.19 ms clock, 0.54+0/0.45/0.28+3.1 ms cpu, 56->56->0 MB, 65 MB goal, 16 P (forced)
#BenchmarkSetErase1E6-16                           	 1000000	      1538 ns/op	      96 B/op	       2 allocs/op
gc 1554 @50.864s 1%: 0.013+0.28+0.14 ms clock, 0.20+0/0.41/0.25+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1555 @50.867s 1%: 0.014+0.26+0.20 ms clock, 0.23+0.093/0.23/0.35+3.2 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1556 @50.896s 1%: 0.014+1.6+0.16 ms clock, 0.23+0.17/4.7/1.0+2.7 ms cpu, 8->8->8 MB, 15 MB goal, 16 P
gc 1557 @51.024s 1%: 0.024+3.9+0.20 ms clock, 0.38+0.24/14/18+3.2 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1558 @51.243s 1%: 0.019+5.1+0.12 ms clock, 0.31+0.26/8.7/12+1.9 ms cpu, 21->21->11 MB, 25 MB goal, 16 P
gc 1559 @51.521s 1%: 0.019+4.5+0.12 ms clock, 0.31+0.19/17/38+2.0 ms cpu, 20->20->14 MB, 22 MB goal, 16 P
gc 1560 @51.834s 1%: 0.019+2.4+0.17 ms clock, 0.30+0.42/8.5/11+2.7 ms cpu, 27->27->10 MB, 28 MB goal, 16 P
gc 1561 @52.116s 1%: 0.019+4.7+0.17 ms clock, 0.31+0.47/14/20+2.7 ms cpu, 20->20->12 MB, 21 MB goal, 16 P
gc 1562 @52.458s 1%: 0.018+5.7+0.20 ms clock, 0.29+0.27/20/45+3.2 ms cpu, 23->23->15 MB, 24 MB goal, 16 P
gc 1563 @52.854s 1%: 0.020+5.5+0.17 ms clock, 0.33+0.42/15/22+2.7 ms cpu, 30->30->13 MB, 31 MB goal, 16 P
HeapAlloc: 25864568 HeapInuse: 26247168 HeapObjects: 300861 HeapIdle 134905856 HeapReleased 0 HeapSys 161153024
gc 1564 @53.109s 1%: 0.010+0.35+0.23 ms clock, 0.17+0/0.66/0.25+3.7 ms cpu, 24->24->0 MB, 26 MB goal, 16 P (forced)
#BenchmarkSetInsertAndErase1E6-16                  	 1000000	      2245 ns/op	      96 B/op	       2 allocs/op
gc 1565 @53.111s 1%: 0.012+0.25+0.18 ms clock, 0.20+0/0.36/0.19+2.8 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1566 @53.113s 1%: 0.011+0.30+0.15 ms clock, 0.17+0.10/0.24/0.27+2.4 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1567 @53.153s 1%: 0.013+1.1+0.16 ms clock, 0.21+0.13/3.6/5.4+2.5 ms cpu, 8->8->8 MB, 15 MB goal, 16 P
gc 1568 @53.318s 1%: 0.021+3.8+0.11 ms clock, 0.34+0.43/12/27+1.8 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1569 @53.819s 1%: 0.020+3.4+0.17 ms clock, 0.32+0.20/11/27+2.8 ms cpu, 21->21->12 MB, 25 MB goal, 16 P
gc 1570 @54.395s 1%: 0.014+3.5+0.10 ms clock, 0.23+0.17/12/29+1.7 ms cpu, 23->23->14 MB, 25 MB goal, 16 P
gc 1571 @54.914s 1%: 0.017+1.0+0.12 ms clock, 0.27+0.18/2.6/3.3+2.0 ms cpu, 26->27->8 MB, 28 MB goal, 16 P
gc 1572 @55.315s 1%: 0.016+3.4+0.17 ms clock, 0.26+0.15/10/22+2.8 ms cpu, 16->16->12 MB, 17 MB goal, 16 P
HeapAlloc: 13121296 HeapInuse: 13516800 HeapObjects: 102003 HeapIdle 147636224 HeapReleased 0 HeapSys 161153024
gc 1573 @55.402s 1%: 0.023+0.29+0.23 ms clock, 0.38+0/0.47/0.25+3.7 ms cpu, 12->12->0 MB, 24 MB goal, 16 P (forced)
#BenchmarkSetInsertAndEraseWithPool1E6-16          	 1000000	      2292 ns/op	      56 B/op	       1 allocs/op
gc 1574 @55.404s 1%: 0.030+0.27+0.19 ms clock, 0.48+0/0.43/0.22+3.0 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1575 @55.495s 1%: 0.017+2.8+0.17 ms clock, 0.27+0.49/9.2/16+2.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1576 @55.584s 1%: 0.016+4.2+0.14 ms clock, 0.26+0.24/14/30+2.2 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
gc 1577 @55.688s 1%: 0.017+8.7+0.18 ms clock, 0.28+0.30/32/73+3.0 ms cpu, 13->13->13 MB, 14 MB goal, 16 P
gc 1578 @55.904s 1%: 0.020+17+0.15 ms clock, 0.33+0.32/63/127+2.4 ms cpu, 25->26->24 MB, 26 MB goal, 16 P
gc 1579 @56.384s 1%: 0.020+29+0.14 ms clock, 0.32+0.21/106/258+2.2 ms cpu, 48->48->46 MB, 49 MB goal, 16 P
HeapAlloc: 83445768 HeapInuse: 84066304 HeapObjects: 1199909 HeapIdle 77086720 HeapReleased 0 HeapSys 161153024
gc 1580 @57.027s 1%: 0.025+0.33+0.19 ms clock, 0.40+0/0.42/0.62+3.1 ms cpu, 79->79->0 MB, 92 MB goal, 16 P (forced)
#BenchmarkIntSetInsert1E6-16                       	 1000000	      1631 ns/op	      88 B/op	       2 allocs/op
gc 1581 @57.036s 1%: 0.015+0.27+0.15 ms clock, 0.24+0/0.35/0.34+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1582 @57.038s 1%: 0.014+0.27+0.13 ms clock, 0.22+0.098/0.18/0.16+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1583 @57.060s 1%: 0.013+1.0+0.14 ms clock, 0.21+0.33/2.5/3.5+2.3 ms cpu, 8->8->8 MB, 15 MB goal, 16 P
gc 1584 @57.155s 1%: 0.016+2.9+0.12 ms clock, 0.26+0.19/10/18+1.9 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1585 @57.257s 1%: 0.018+7.0+0.096 ms clock, 0.28+0.15/25/52+1.5 ms cpu, 20->21->20 MB, 24 MB goal, 16 P
gc 1586 @57.495s 1%: 0.022+18+0.20 ms clock, 0.36+0.20/68/166+3.2 ms cpu, 37->37->36 MB, 40 MB goal, 16 P
gc 1587 @58.212s 1%: 0.022+47+0.13 ms clock, 0.35+0.19/170/326+2.2 ms cpu, 69->70->67 MB, 72 MB goal, 16 P
gc 1588 @59.295s 1%: 0.016+20+0.14 ms clock, 0.27+0.34/81/175+2.3 ms cpu, 130->130->45 MB, 134 MB goal, 16 P
HeapAlloc: 88475896 HeapInuse: 89088000 HeapObjects: 1194481 HeapIdle 72065024 HeapReleased 0 HeapSys 161153024
gc 1589 @59.961s 1%: 0.044+0.35+0.17 ms clock, 0.70+0/0.55/0.73+2.8 ms cpu, 84->84->0 MB, 90 MB goal, 16 P (forced)
#BenchmarkIntSetErase1E6-16                        	 1000000	      1287 ns/op	      96 B/op	       2 allocs/op
gc 1590 @59.968s 1%: 0.015+0.19+0.15 ms clock, 0.24+0/0.24/0.17+2.5 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1591 @59.970s 1%: 0.014+0.37+0.16 ms clock, 0.23+0.11/0.30/0.39+2.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1592 @59.988s 1%: 0.086+0.85+0.14 ms clock, 1.3+0.16/2.7/3.0+2.2 ms cpu, 8->8->8 MB, 15 MB goal, 16 P
gc 1593 @60.086s 1%: 0.017+2.7+0.090 ms clock, 0.27+0.16/9.6/18+1.4 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1594 @60.189s 1%: 0.017+2.6+0.16 ms clock, 0.28+0.29/8.8/12+2.5 ms cpu, 20->21->10 MB, 24 MB goal, 16 P
gc 1595 @60.403s 1%: 0.020+4.5+0.20 ms clock, 0.32+0.41/16/10+3.2 ms cpu, 20->20->13 MB, 21 MB goal, 16 P
gc 1596 @60.635s 1%: 0.018+1.3+0.14 ms clock, 0.29+0.22/4.3/6.8+2.3 ms cpu, 25->25->9 MB, 26 MB goal, 16 P
gc 1597 @60.841s 1%: 0.018+3.5+0.12 ms clock, 0.29+0.23/12/24+1.9 ms cpu, 18->18->13 MB, 19 MB goal, 16 P
gc 1598 @61.203s 1%: 0.021+5.4+0.11 ms clock, 0.34+0.43/20/25+1.8 ms cpu, 26->26->14 MB, 27 MB goal, 16 P
gc 1599 @61.450s 1%: 0.017+1.9+0.11 ms clock, 0.28+0.19/6.2/11+1.8 ms cpu, 27->27->10 MB, 28 MB goal, 16 P
gc 1600 @61.675s 1%: 0.018+2.6+0.11 ms clock, 0.29+0.34/8.5/11+1.8 ms cpu, 21->21->10 MB, 22 MB goal, 16 P
HeapAlloc: 14687256 HeapInuse: 15024128 HeapObjects: 96435 HeapIdle 146128896 HeapReleased 0 HeapSys 161153024
gc 1601 @61.732s 1%: 0.011+0.28+0.16 ms clock, 0.17+0/0.42/0.26+2.6 ms cpu, 14->14->0 MB, 21 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndErase1E6-16               	 1000000	      1763 ns/op	      96 B/op	       2 allocs/op
gc 1602 @61.733s 1%: 0.025+0.14+0.20 ms clock, 0.40+0/0.26/0.082+3.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1603 @61.735s 1%: 0.012+0.30+0.15 ms clock, 0.20+0.14/0.21/0.16+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1604 @61.755s 1%: 0.008+1.0+0.11 ms clock, 0.14+0.27/2.7/3.7+1.8 ms cpu, 8->9->8 MB, 15 MB goal, 16 P
gc 1605 @61.888s 1%: 0.018+3.2+0.14 ms clock, 0.28+0.21/10/24+2.2 ms cpu, 12->12->12 MB, 17 MB goal, 16 P
gc 1606 @62.291s 1%: 0.019+2.8+0.13 ms clock, 0.31+0.16/9.8/23+2.0 ms cpu, 20->20->11 MB, 24 MB goal, 16 P
gc 1607 @62.749s 1%: 0.019+3.5+0.14 ms clock, 0.31+0.20/13/27+2.2 ms cpu, 21->21->12 MB, 23 MB goal, 16 P
gc 1608 @63.272s 1%: 0.019+5.4+0.15 ms clock, 0.31+0.16/19/30+2.5 ms cpu, 23->23->14 MB, 24 MB goal, 16 P
HeapAlloc: 26786384 HeapInuse: 27164672 HeapObjects: 358343 HeapIdle 133988352 HeapReleased 0 HeapSys 161153024
gc 1609 @63.685s 1%: 0.028+0.22+0.18 ms clock, 0.45+0/0.34/0.26+2.9 ms cpu, 25->25->0 MB, 29 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndEraseWithPool1E6-16       	 1000000	      1953 ns/op	      56 B/op	       1 allocs/op
gc 1610 @63.687s 1%: 0.079+0.22+0.13 ms clock, 1.2+0/0.26/0.15+2.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1611 @63.705s 1%: 0.011+0.39+0.18 ms clock, 0.18+0.13/0.37/0.13+2.9 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1612 @63.707s 1%: 0.010+0.26+0.14 ms clock, 0.16+0.17/0.16/0.31+2.3 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1613 @63.741s 1%: 0.019+0.87+0.19 ms clock, 0.31+0/0.90/0.36+3.1 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1614 @63.786s 1%: 0.013+0.57+0.16 ms clock, 0.20+0.49/0.19/0.43+2.6 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1615 @63.897s 1%: 0.022+1.4+0.14 ms clock, 0.35+0.75/0.77/0.35+2.3 ms cpu, 45->45->37 MB, 46 MB goal, 16 P
HeapAlloc: 39270608 HeapInuse: 39739392 HeapObjects: 20058 HeapIdle 121413632 HeapReleased 0 HeapSys 161153024
gc 1616 @64.047s 1%: 0.010+0.32+0.17 ms clock, 0.16+0/0.41/0.47+2.7 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsert1E6-16                   	gc 1617 @64.048s 1%: 0.012+0.39+0.20 ms clock, 0.20+0/0.58/0.10+3.3 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1618 @64.078s 1%: 0.015+0.33+0.13 ms clock, 0.24+0.26/0.41/0.20+2.0 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1619 @64.079s 1%: 0.011+0.29+0.14 ms clock, 0.18+0.22/0.29/0.33+2.2 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1620 @64.111s 1%: 0.016+0.49+0.19 ms clock, 0.27+0.44/0.36/0.48+3.1 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1621 @64.180s 1%: 0.024+0.68+0.22 ms clock, 0.39+0.66/0.43/0.30+3.6 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1622 @64.297s 1%: 0.019+4.9+0.15 ms clock, 0.31+0/1.3/4.0+2.4 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1623 @64.340s 1%: 0.020+1.4+0.13 ms clock, 0.32+0.80/0.92/0.30+2.1 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39272656 HeapInuse: 39723008 HeapObjects: 20080 HeapIdle 121430016 HeapReleased 0 HeapSys 161153024
gc 1624 @64.488s 1%: 0.010+0.37+0.15 ms clock, 0.16+0/0.61/0.24+2.5 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1625 @64.489s 1%: 0.052+0.26+0.16 ms clock, 0.83+0/0.32/0.18+2.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1626 @64.520s 1%: 0.019+0.39+0.13 ms clock, 0.30+0.22/0.41/0.39+2.1 ms cpu, 6->6->4 MB, 8 MB goal, 16 P
gc 1627 @64.552s 1%: 0.017+0.49+0.11 ms clock, 0.27+0.42/0.45/0.39+1.8 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1628 @64.608s 1%: 0.018+2.5+0.14 ms clock, 0.28+0/1.0/1.8+2.3 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1629 @64.622s 1%: 0.018+0.71+0.13 ms clock, 0.29+0.67/0.27/0.38+2.1 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1630 @64.735s 1%: 0.021+5.0+0.14 ms clock, 0.34+0.54/0.80/2.0+2.3 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1631 @64.783s 1%: 0.020+1.3+0.13 ms clock, 0.32+0.74/0.92/0.32+2.2 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39277456 HeapInuse: 39731200 HeapObjects: 20130 HeapIdle 121421824 HeapReleased 0 HeapSys 161153024
gc 1632 @64.934s 1%: 0.012+0.37+0.18 ms clock, 0.19+0/0.61/0.28+2.9 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1633 @64.935s 1%: 0.018+0.34+0.18 ms clock, 0.29+0/0.41/0.070+2.9 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1634 @64.965s 1%: 0.013+0.37+0.12 ms clock, 0.21+0.35/0.36/0.18+1.9 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1635 @64.966s 1%: 0.012+0.31+0.16 ms clock, 0.19+0.16/0.23/0.39+2.6 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1636 @64.999s 1%: 0.017+0.37+0.19 ms clock, 0.27+0.32/0.16/0.34+3.1 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1637 @65.068s 1%: 0.020+0.76+0.14 ms clock, 0.33+0.67/0.29/0.26+2.2 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1638 @65.181s 1%: 0.019+3.3+0.18 ms clock, 0.31+0/1.3/2.6+3.0 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1639 @65.227s 1%: 0.019+1.4+0.089 ms clock, 0.31+0.76/0.82/0.80+1.4 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39259888 HeapInuse: 39714816 HeapObjects: 19947 HeapIdle 121438208 HeapReleased 0 HeapSys 161153024
gc 1640 @65.378s 1%: 0.013+0.33+0.14 ms clock, 0.21+0/0.56/0.30+2.3 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1641 @65.379s 1%: 0.082+0.29+0.14 ms clock, 1.3+0/0.39/0.21+2.3 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1642 @65.414s 1%: 0.020+0.36+0.12 ms clock, 0.32+0.17/0.25/0.28+1.9 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1643 @65.415s 1%: 0.015+0.57+0.15 ms clock, 0.24+0.39/0.27/0.18+2.5 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1644 @65.451s 1%: 0.018+0.37+0.11 ms clock, 0.30+0.32/0.37/0.45+1.7 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1645 @65.522s 1%: 0.020+0.77+0.15 ms clock, 0.32+0.72/0.37/0.43+2.4 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1646 @65.637s 1%: 0.020+3.1+0.11 ms clock, 0.32+0/1.2/2.2+1.7 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1647 @65.680s 1%: 0.024+1.5+0.17 ms clock, 0.38+0.79/0.95/0.34+2.8 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39252688 HeapInuse: 39706624 HeapObjects: 19872 HeapIdle 121446400 HeapReleased 0 HeapSys 161153024
gc 1648 @65.834s 1%: 0.036+0.42+0.20 ms clock, 0.58+0/0.40/0.62+3.3 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1649 @65.835s 1%: 0.020+0.30+0.17 ms clock, 0.33+0/0.46/0.16+2.7 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1650 @65.866s 1%: 0.011+0.44+0.12 ms clock, 0.18+0.096/0.091/0.42+2.0 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1651 @65.867s 1%: 0.019+0.34+0.16 ms clock, 0.31+0.23/0.38/0.32+2.5 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1652 @65.901s 1%: 0.021+0.45+0.13 ms clock, 0.34+0.39/0.27/0.41+2.2 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1653 @65.973s 1%: 0.021+0.69+0.15 ms clock, 0.34+0.66/0.46/0.30+2.4 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1654 @66.088s 1%: 0.023+3.1+0.22 ms clock, 0.37+0.53/0.82/2.0+3.5 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1655 @66.133s 1%: 0.019+1.6+0.19 ms clock, 0.31+0.024/1.8/0.63+3.1 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39276112 HeapInuse: 39739392 HeapObjects: 20116 HeapIdle 121413632 HeapReleased 0 HeapSys 161153024
gc 1656 @66.287s 1%: 0.011+0.40+0.19 ms clock, 0.18+0/0.68/0.31+3.1 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1657 @66.288s 1%: 0.013+0.24+0.13 ms clock, 0.21+0/0.23/0.31+2.1 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1658 @66.318s 1%: 0.015+1.0+0.12 ms clock, 0.24+0.11/0.28/0.47+2.0 ms cpu, 4->6->4 MB, 8 MB goal, 16 P
gc 1659 @66.352s 1%: 0.018+0.46+0.17 ms clock, 0.29+0.41/0.26/0.39+2.8 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1660 @66.408s 1%: 0.017+3.4+0.18 ms clock, 0.28+0.41/0.68/2.7+3.0 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1661 @66.423s 1%: 0.018+0.72+0.12 ms clock, 0.29+0.66/0.35/0.27+2.0 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1662 @66.536s 1%: 0.018+4.7+0.15 ms clock, 0.30+0/1.4/3.7+2.4 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1663 @66.580s 1%: 0.019+1.4+0.15 ms clock, 0.31+0.74/0.85/0.37+2.5 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39266704 HeapInuse: 39723008 HeapObjects: 20018 HeapIdle 121430016 HeapReleased 0 HeapSys 161153024
gc 1664 @66.732s 1%: 0.012+0.33+0.21 ms clock, 0.20+0/0.70/0.37+3.4 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1665 @66.733s 1%: 0.043+0.30+0.13 ms clock, 0.69+0/0.42/0.26+2.1 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1666 @66.763s 1%: 0.015+0.87+0.18 ms clock, 0.25+0.15/0.39/0.091+2.9 ms cpu, 4->6->4 MB, 8 MB goal, 16 P
gc 1667 @66.797s 1%: 0.016+0.38+0.18 ms clock, 0.26+0.32/0.27/0.36+2.8 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1668 @66.855s 1%: 0.019+3.1+0.19 ms clock, 0.30+0/1.0/2.4+3.1 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1669 @66.872s 1%: 0.020+0.85+0.13 ms clock, 0.32+0.74/0.31/0.40+2.1 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1670 @66.983s 1%: 0.020+3.1+0.20 ms clock, 0.32+0/1.4/2.2+3.3 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1671 @67.029s 1%: 0.021+1.3+0.16 ms clock, 0.34+0.75/0.94/0.44+2.6 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39276688 HeapInuse: 39731200 HeapObjects: 20122 HeapIdle 121421824 HeapReleased 0 HeapSys 161153024
gc 1672 @67.177s 0%: 0.011+0.32+0.17 ms clock, 0.19+0/0.64/0.11+2.7 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1673 @67.178s 0%: 0.011+0.34+0.15 ms clock, 0.17+0/0.38/0.21+2.5 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1674 @67.208s 0%: 0.014+0.31+0.22 ms clock, 0.23+0.16/0.28/0.24+3.5 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1675 @67.210s 0%: 0.011+0.30+0.14 ms clock, 0.19+0.28/0.35/0.37+2.3 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1676 @67.243s 0%: 0.021+0.46+0.094 ms clock, 0.33+0.43/0.34/0.33+1.5 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1677 @67.309s 0%: 0.021+0.72+0.18 ms clock, 0.33+0.67/0.28/0.29+2.9 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1678 @67.421s 0%: 0.019+3.1+0.15 ms clock, 0.31+0/1.2/2.2+2.4 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1679 @67.466s 0%: 0.017+1.3+0.20 ms clock, 0.28+0.75/0.94/0.30+3.3 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39283120 HeapInuse: 39739392 HeapObjects: 20189 HeapIdle 121413632 HeapReleased 0 HeapSys 161153024
gc 1680 @67.616s 0%: 0.011+0.32+0.12 ms clock, 0.18+0/0.45/0.27+2.0 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1681 @67.617s 0%: 0.061+0.23+0.11 ms clock, 0.98+0/0.27/0.27+1.8 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1682 @67.648s 0%: 0.018+0.33+0.12 ms clock, 0.30+0.16/0.12/0.51+2.0 ms cpu, 6->6->4 MB, 8 MB goal, 16 P
gc 1683 @67.681s 0%: 0.018+0.40+0.13 ms clock, 0.29+0.33/0.24/0.42+2.1 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1684 @67.737s 0%: 0.020+3.1+0.17 ms clock, 0.32+0/1.2/2.3+2.7 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1685 @67.751s 0%: 0.017+0.73+0.13 ms clock, 0.27+0.69/0.10/0.46+2.0 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1686 @67.866s 0%: 0.018+3.1+0.21 ms clock, 0.29+0/1.4/2.2+3.4 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1687 @67.910s 0%: 0.017+1.5+0.14 ms clock, 0.28+0.89/0.92/0.47+2.3 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39271600 HeapInuse: 39723008 HeapObjects: 20069 HeapIdle 121430016 HeapReleased 0 HeapSys 161153024
gc 1688 @68.059s 0%: 0.024+0.37+0.12 ms clock, 0.38+0/0.46/0.51+2.0 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1689 @68.060s 0%: 0.060+0.24+0.10 ms clock, 0.97+0/0.35/0.21+1.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1690 @68.090s 0%: 0.015+0.36+0.14 ms clock, 0.25+0.095/0.52/0.24+2.3 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1691 @68.091s 0%: 0.013+0.31+0.17 ms clock, 0.21+0.26/0.37/0.27+2.7 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1692 @68.124s 0%: 0.018+0.49+0.12 ms clock, 0.30+0.32/0.25/0.34+2.0 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1693 @68.193s 0%: 0.021+0.69+0.14 ms clock, 0.33+0.66/0.13/0.44+2.2 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1694 @68.307s 0%: 0.019+4.7+0.14 ms clock, 0.31+0/1.4/3.7+2.3 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1695 @68.350s 0%: 0.022+1.4+0.14 ms clock, 0.35+0.86/0.92/0.34+2.3 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39255760 HeapInuse: 39706624 HeapObjects: 19904 HeapIdle 121446400 HeapReleased 0 HeapSys 161153024
gc 1696 @68.503s 0%: 0.011+0.57+0.14 ms clock, 0.18+0/0.55/0.32+2.3 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1697 @68.504s 0%: 0.019+0.27+0.094 ms clock, 0.31+0/0.38/0.22+1.5 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1698 @68.534s 0%: 0.019+0.35+0.15 ms clock, 0.31+0.20/0.33/0.41+2.4 ms cpu, 6->6->4 MB, 8 MB goal, 16 P
gc 1699 @68.566s 0%: 0.023+0.48+0.19 ms clock, 0.37+0.45/0.39/0.41+3.1 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1700 @68.621s 0%: 0.018+3.7+0.19 ms clock, 0.29+0.44/0.69/2.8+3.1 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1701 @68.637s 0%: 0.020+0.79+0.17 ms clock, 0.32+0.70/0.30/0.26+2.8 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1702 @68.750s 0%: 0.023+3.1+0.20 ms clock, 0.37+0/1.3/2.4+3.2 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1703 @68.800s 0%: 0.018+1.7+0.20 ms clock, 0.29+1.0/0.65/0.71+3.3 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39281584 HeapInuse: 39739392 HeapObjects: 20173 HeapIdle 121413632 HeapReleased 0 HeapSys 161153024
gc 1704 @68.948s 0%: 0.011+0.37+0.12 ms clock, 0.19+0/0.45/0.52+2.0 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1705 @68.949s 0%: 0.044+0.26+0.10 ms clock, 0.71+0/0.43/0.15+1.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1706 @68.979s 0%: 0.018+0.45+0.18 ms clock, 0.28+0.30/0.36/0.31+3.0 ms cpu, 6->6->4 MB, 8 MB goal, 16 P
gc 1707 @69.011s 0%: 0.017+0.38+0.14 ms clock, 0.27+0.32/0.19/0.42+2.2 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1708 @69.070s 0%: 0.019+3.7+0.13 ms clock, 0.31+0/1.2/3.1+2.1 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1709 @69.084s 0%: 0.023+0.88+0.17 ms clock, 0.37+0/1.1/0.17+2.7 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1710 @69.195s 0%: 0.017+4.1+0.16 ms clock, 0.28+0/1.3/3.3+2.6 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1711 @69.243s 0%: 0.024+1.3+0.13 ms clock, 0.39+0.76/0.87/0.42+2.0 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39277456 HeapInuse: 39731200 HeapObjects: 20130 HeapIdle 121421824 HeapReleased 0 HeapSys 161153024
gc 1712 @69.394s 0%: 0.027+0.34+0.16 ms clock, 0.43+0/0.61/0.14+2.6 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1713 @69.395s 0%: 0.020+0.26+0.23 ms clock, 0.32+0/0.25/0.20+3.7 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1714 @69.424s 0%: 0.015+0.35+0.14 ms clock, 0.24+0.11/0.48/0.28+2.3 ms cpu, 4->4->1 MB, 8 MB goal, 16 P
gc 1715 @69.425s 0%: 0.014+0.51+0.13 ms clock, 0.22+0/0.71/0.27+2.1 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1716 @69.457s 0%: 0.015+0.52+0.16 ms clock, 0.24+0.49/0.12/0.51+2.7 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1717 @69.524s 0%: 0.020+0.72+0.11 ms clock, 0.33+0.68/0.42/0.35+1.8 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 1718 @69.640s 0%: 0.017+5.1+0.15 ms clock, 0.28+0/1.3/3.7+2.4 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1719 @69.686s 0%: 0.023+1.5+0.18 ms clock, 0.37+0/1.6/0.36+2.9 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39277168 HeapInuse: 39739392 HeapObjects: 20127 HeapIdle 121413632 HeapReleased 0 HeapSys 161153024
gc 1720 @69.833s 0%: 0.012+0.69+0.22 ms clock, 0.19+0/0.74/0.15+3.5 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
gc 1721 @69.835s 0%: 0.010+0.38+0.16 ms clock, 0.17+0/0.42/0.24+2.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1722 @69.864s 0%: 0.011+0.45+0.64 ms clock, 0.18+0.15/0.19/0.39+10 ms cpu, 4->6->4 MB, 8 MB goal, 16 P
gc 1723 @69.898s 0%: 0.016+0.40+0.17 ms clock, 0.26+0.32/0.47/0.38+2.7 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 1724 @69.956s 0%: 0.019+2.3+0.19 ms clock, 0.31+0.41/0.42/1.8+3.1 ms cpu, 10->10->6 MB, 19 MB goal, 16 P
gc 1725 @69.972s 0%: 0.025+0.75+0.13 ms clock, 0.40+0.68/0.43/0.23+2.2 ms cpu, 18->18->18 MB, 19 MB goal, 16 P
gc 1726 @70.089s 0%: 0.017+5.0+0.16 ms clock, 0.28+0/1.3/4.2+2.7 ms cpu, 19->19->12 MB, 37 MB goal, 16 P
gc 1727 @70.132s 0%: 0.018+1.4+0.16 ms clock, 0.29+0.80/0.93/0.29+2.7 ms cpu, 37->37->37 MB, 38 MB goal, 16 P
HeapAlloc: 39263536 HeapInuse: 39714816 HeapObjects: 19985 HeapIdle 121438208 HeapReleased 0 HeapSys 161153024
gc 1728 @70.283s 0%: 0.028+0.40+0.17 ms clock, 0.45+0/0.57/0.37+2.8 ms cpu, 37->37->23 MB, 74 MB goal, 16 P (forced)
 1000000	       448 ns/op	      54 B/op	       0 allocs/op
gc 1729 @70.284s 0%: 0.050+0.24+0.15 ms clock, 0.80+0/0.46/0.14+2.4 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1730 @70.287s 0%: 0.011+0.24+0.11 ms clock, 0.18+0/0.36/0.10+1.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1731 @70.295s 0%: 0.012+0.32+0.14 ms clock, 0.20+0.094/0.42/0.22+2.3 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1732 @70.318s 0%: 0.015+0.48+0.18 ms clock, 0.24+0/0.62/0.48+2.9 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1733 @70.417s 0%: 0.017+2.5+0.17 ms clock, 0.27+0.10/0.93/0.33+2.8 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1734 @70.426s 0%: 0.016+0.71+0.13 ms clock, 0.26+0.67/0.35/0.34+2.1 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1735 @70.587s 0%: 0.026+1.5+0.13 ms clock, 0.42+0.75/1.0/0.29+2.1 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47258928 HeapInuse: 47734784 HeapObjects: 19900 HeapIdle 113418240 HeapReleased 0 HeapSys 161153024
gc 1736 @70.933s 0%: 0.023+0.39+0.25 ms clock, 0.37+0/0.55/0.54+4.1 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
#BenchmarkSysHashMapErase1E6-16                    	gc 1737 @70.934s 0%: 0.012+0.29+0.12 ms clock, 0.19+0/0.56/0.31+2.0 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1738 @70.936s 0%: 0.012+0.28+0.12 ms clock, 0.20+0/0.54/0.23+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1739 @70.944s 0%: 0.013+0.31+0.30 ms clock, 0.20+0.12/0.32/0.24+4.8 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1740 @70.968s 0%: 0.015+0.37+0.12 ms clock, 0.25+0.24/0.45/0.30+1.9 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1741 @71.066s 0%: 0.024+7.6+0.16 ms clock, 0.38+1.0/0/3.9+2.6 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1742 @71.141s 0%: 0.021+0.61+0.21 ms clock, 0.33+0/0.54/0.74+3.4 ms cpu, 26->26->19 MB, 29 MB goal, 16 P
gc 1743 @71.229s 0%: 0.022+1.5+0.10 ms clock, 0.36+0.90/0.96/0.51+1.7 ms cpu, 45->45->44 MB, 46 MB goal, 16 P
HeapAlloc: 47279504 HeapInuse: 47742976 HeapObjects: 20115 HeapIdle 113410048 HeapReleased 0 HeapSys 161153024
gc 1744 @71.563s 0%: 0.012+0.38+0.12 ms clock, 0.19+0/0.48/0.38+2.0 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1745 @71.564s 0%: 0.045+0.25+0.17 ms clock, 0.73+0/0.45/0.11+2.7 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1746 @71.567s 0%: 0.012+0.29+0.13 ms clock, 0.19+0/0.48/0.24+2.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1747 @71.575s 0%: 0.013+0.28+0.13 ms clock, 0.21+0.090/0.24/0.30+2.1 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1748 @71.598s 0%: 0.019+0.35+0.18 ms clock, 0.31+0.16/0.27/0.40+3.0 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1749 @71.695s 0%: 0.020+3.6+0.11 ms clock, 0.32+0/1.4/2.7+1.8 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1750 @71.764s 0%: 0.017+1.1+0.16 ms clock, 0.27+0/1.0/0.49+2.5 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1751 @71.859s 0%: 0.021+1.6+0.22 ms clock, 0.34+1.0/0.97/0.38+3.6 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47274992 HeapInuse: 47734784 HeapObjects: 20068 HeapIdle 113418240 HeapReleased 0 HeapSys 161153024
gc 1752 @72.191s 0%: 0.012+0.61+0.17 ms clock, 0.19+0/0.43/0.46+2.8 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1753 @72.193s 0%: 0.065+0.28+0.19 ms clock, 1.0+0/0.40/0.23+3.1 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1754 @72.195s 0%: 0.009+0.27+0.10 ms clock, 0.14+0/0.40/0.16+1.6 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1755 @72.202s 0%: 0.012+0.36+0.21 ms clock, 0.20+0.12/0.22/0.26+3.3 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1756 @72.227s 0%: 0.017+0.45+0.095 ms clock, 0.27+0/0.62/0.36+1.5 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1757 @72.322s 0%: 0.022+1.6+0.16 ms clock, 0.36+0.13/1.6/0.15+2.6 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1758 @72.376s 0%: 0.016+0.48+0.17 ms clock, 0.26+0/0.52/0.30+2.7 ms cpu, 26->26->19 MB, 29 MB goal, 16 P
gc 1759 @72.468s 0%: 0.021+1.3+0.12 ms clock, 0.35+0.74/0.90/0.35+2.0 ms cpu, 45->45->44 MB, 46 MB goal, 16 P
HeapAlloc: 47283344 HeapInuse: 47742976 HeapObjects: 20155 HeapIdle 113410048 HeapReleased 0 HeapSys 161153024
gc 1760 @72.784s 0%: 0.012+0.32+0.18 ms clock, 0.19+0/0.34/0.42+2.9 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1761 @72.785s 0%: 0.030+0.29+0.12 ms clock, 0.49+0/0.53/0.25+2.0 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1762 @72.787s 0%: 0.013+0.27+0.19 ms clock, 0.21+0/0.46/0.18+3.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1763 @72.795s 0%: 0.014+0.30+0.13 ms clock, 0.22+0.11/0.34/0.32+2.1 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1764 @72.819s 0%: 0.014+0.40+0.13 ms clock, 0.23+0.21/0.45/0.27+2.1 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1765 @72.918s 0%: 0.018+3.5+0.18 ms clock, 0.30+0/1.4/2.6+2.9 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1766 @72.934s 0%: 0.017+0.93+0.11 ms clock, 0.28+0/1.2/0.26+1.8 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1767 @73.077s 0%: 0.020+1.4+0.21 ms clock, 0.32+0.79/0.97/0.33+3.3 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47268464 HeapInuse: 47734784 HeapObjects: 20000 HeapIdle 113418240 HeapReleased 0 HeapSys 161153024
gc 1768 @73.396s 0%: 0.013+0.59+0.30 ms clock, 0.22+0/0.57/0.11+4.9 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1769 @73.398s 0%: 0.049+0.29+0.16 ms clock, 0.79+0/0.47/0.091+2.5 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1770 @73.400s 0%: 0.015+0.29+0.16 ms clock, 0.25+0/0.44/0.18+2.5 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1771 @73.408s 0%: 0.010+0.30+0.15 ms clock, 0.16+0.12/0.41/0.24+2.4 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1772 @73.430s 0%: 0.013+0.35+0.10 ms clock, 0.21+0.24/0.30/0.49+1.7 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1773 @73.521s 0%: 0.017+3.2+0.12 ms clock, 0.28+0/1.4/2.5+2.0 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1774 @73.533s 0%: 0.018+0.92+0.14 ms clock, 0.29+0/0.94/0.43+2.3 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1775 @73.680s 0%: 0.022+1.3+0.13 ms clock, 0.35+0.74/0.92/0.27+2.2 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47283248 HeapInuse: 47751168 HeapObjects: 20154 HeapIdle 113401856 HeapReleased 0 HeapSys 161153024
gc 1776 @73.995s 0%: 0.013+0.60+0.25 ms clock, 0.21+0/0.40/0.38+4.0 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1777 @73.996s 0%: 0.11+0.27+0.20 ms clock, 1.7+0/0.44/0.10+3.3 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1778 @73.999s 0%: 0.012+0.31+0.13 ms clock, 0.20+0/0.44/0.079+2.1 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1779 @74.007s 0%: 0.012+0.31+0.18 ms clock, 0.20+0.097/0.40/0.23+3.0 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1780 @74.030s 0%: 0.020+0.43+0.14 ms clock, 0.33+0.37/0.34/0.30+2.3 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1781 @74.124s 0%: 0.017+4.3+0.21 ms clock, 0.28+0/1.4/3.3+3.4 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1782 @74.177s 0%: 0.021+1.1+0.13 ms clock, 0.35+0/1.0/0.26+2.2 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1783 @74.292s 0%: 0.020+1.5+0.20 ms clock, 0.33+0.91/0.89/0.39+3.2 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47291408 HeapInuse: 47751168 HeapObjects: 20239 HeapIdle 113401856 HeapReleased 0 HeapSys 161153024
gc 1784 @74.623s 0%: 0.026+0.57+0.18 ms clock, 0.42+0/0.38/0.31+2.8 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1785 @74.625s 0%: 0.091+0.26+0.14 ms clock, 1.4+0/0.36/0.20+2.3 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1786 @74.627s 0%: 0.013+0.32+0.19 ms clock, 0.20+0/0.49/0.24+3.0 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1787 @74.635s 0%: 0.012+0.31+0.19 ms clock, 0.20+0.12/0.33/0.19+3.1 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1788 @74.658s 0%: 0.015+0.43+0.16 ms clock, 0.25+0.17/0.30/0.26+2.5 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1789 @74.753s 0%: 0.017+3.2+0.19 ms clock, 0.27+0.55/0.82/2.2+3.0 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1790 @74.774s 0%: 0.016+0.93+0.12 ms clock, 0.26+0/1.0/0.21+2.0 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1791 @74.921s 0%: 0.018+1.4+0.12 ms clock, 0.29+0.82/1.0/0.46+2.0 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47277968 HeapInuse: 47751168 HeapObjects: 20099 HeapIdle 113401856 HeapReleased 0 HeapSys 161153024
gc 1792 @75.257s 0%: 0.011+0.52+0.16 ms clock, 0.18+0/0.61/0.20+2.6 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1793 @75.258s 0%: 0.049+0.24+0.16 ms clock, 0.78+0/0.43/0.18+2.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1794 @75.260s 0%: 0.011+0.24+0.15 ms clock, 0.19+0/0.37/0.20+2.4 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1795 @75.268s 0%: 0.010+0.29+0.14 ms clock, 0.17+0.079/0.40/0.26+2.2 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1796 @75.292s 0%: 0.015+0.37+0.22 ms clock, 0.24+0.18/0.28/0.37+3.5 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1797 @75.386s 0%: 0.019+3.1+0.16 ms clock, 0.31+0/1.2/2.3+2.5 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1798 @75.459s 0%: 0.020+0.46+0.19 ms clock, 0.32+0/0.42/0.54+3.0 ms cpu, 26->26->19 MB, 29 MB goal, 16 P
gc 1799 @75.542s 0%: 0.022+1.4+0.18 ms clock, 0.36+0.85/0.94/0.39+2.9 ms cpu, 45->45->44 MB, 46 MB goal, 16 P
HeapAlloc: 47269040 HeapInuse: 47718400 HeapObjects: 20006 HeapIdle 113434624 HeapReleased 0 HeapSys 161153024
gc 1800 @75.860s 0%: 0.013+0.34+0.19 ms clock, 0.21+0/0.67/0.17+3.0 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1801 @75.861s 0%: 0.016+0.28+0.15 ms clock, 0.26+0/0.26/0.23+2.5 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1802 @75.863s 0%: 0.012+0.30+0.21 ms clock, 0.20+0/0.47/0.17+3.4 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1803 @75.872s 0%: 0.013+0.32+0.12 ms clock, 0.22+0.14/0.26/0.16+2.0 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1804 @75.895s 0%: 0.013+0.46+0.21 ms clock, 0.20+0.18/0.29/0.19+3.3 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1805 @75.991s 0%: 0.017+4.8+0.22 ms clock, 0.27+0/1.2/3.8+3.6 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1806 @76.002s 0%: 0.016+1.0+0.20 ms clock, 0.26+0/0.41/1.0+3.2 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1807 @76.162s 0%: 0.022+1.4+0.20 ms clock, 0.35+0.74/0.80/0.48+3.3 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47261840 HeapInuse: 47734784 HeapObjects: 19931 HeapIdle 113418240 HeapReleased 0 HeapSys 161153024
gc 1808 @76.480s 0%: 0.012+0.33+0.11 ms clock, 0.19+0/0.51/0.22+1.8 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1809 @76.481s 0%: 0.018+0.17+0.11 ms clock, 0.30+0/0.35/0.16+1.9 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1810 @76.483s 0%: 0.012+0.27+0.10 ms clock, 0.20+0/0.51/0.17+1.7 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1811 @76.491s 0%: 0.010+0.38+0.28 ms clock, 0.17+0.15/0.33/0.19+4.4 ms cpu, 8->9->9 MB, 15 MB goal, 16 P
gc 1812 @76.513s 0%: 0.015+0.41+0.20 ms clock, 0.24+0.18/0.46/0.32+3.2 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1813 @76.609s 0%: 0.023+5.1+0.17 ms clock, 0.37+0/1.6/4.1+2.8 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1814 @76.678s 0%: 0.018+1.1+0.21 ms clock, 0.30+0/1.0/0.69+3.3 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1815 @76.772s 0%: 0.019+1.3+0.13 ms clock, 0.30+0.77/0.81/0.41+2.1 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47270768 HeapInuse: 47742976 HeapObjects: 20024 HeapIdle 113410048 HeapReleased 0 HeapSys 161153024
gc 1816 @77.105s 0%: 0.013+0.57+0.13 ms clock, 0.21+0/0.17/0.69+2.1 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1817 @77.107s 0%: 0.007+0.41+0.18 ms clock, 0.12+0/0.50/0.25+3.0 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1818 @77.109s 0%: 0.015+0.29+0.11 ms clock, 0.25+0/0.19/0.49+1.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1819 @77.117s 0%: 0.011+0.34+0.11 ms clock, 0.18+0.060/0.38/0.32+1.8 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1820 @77.141s 0%: 0.019+0.35+0.16 ms clock, 0.30+0.16/0.36/0.37+2.6 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1821 @77.247s 0%: 0.021+1.3+0.11 ms clock, 0.33+0.19/1.4/0.20+1.8 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1822 @77.319s 0%: 0.018+1.1+0.19 ms clock, 0.29+0/1.1/0.33+3.1 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1823 @77.417s 0%: 0.019+1.4+0.12 ms clock, 0.31+0.78/0.98/0.47+2.0 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47277968 HeapInuse: 47742976 HeapObjects: 20099 HeapIdle 113410048 HeapReleased 0 HeapSys 161153024
gc 1824 @77.748s 0%: 0.012+0.33+0.11 ms clock, 0.19+0/0.61/0.29+1.8 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
gc 1825 @77.749s 0%: 0.009+0.25+0.10 ms clock, 0.14+0/0.40/0.15+1.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1826 @77.751s 0%: 0.013+0.27+0.12 ms clock, 0.20+0/0.39/0.14+1.9 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 1827 @77.759s 0%: 0.013+0.31+0.20 ms clock, 0.21+0.12/0.33/0.26+3.3 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 1828 @77.782s 0%: 0.013+0.40+0.16 ms clock, 0.21+0.16/0.29/0.37+2.5 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 1829 @77.876s 0%: 0.018+3.2+0.15 ms clock, 0.30+0/1.3/2.3+2.4 ms cpu, 20->20->14 MB, 25 MB goal, 16 P
gc 1830 @77.937s 0%: 0.017+1.0+0.19 ms clock, 0.28+0/1.2/0.21+3.1 ms cpu, 26->26->26 MB, 29 MB goal, 16 P
gc 1831 @78.032s 0%: 0.018+1.3+0.16 ms clock, 0.29+0.75/0.89/0.25+2.6 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 47270480 HeapInuse: 47742976 HeapObjects: 20021 HeapIdle 113410048 HeapReleased 0 HeapSys 161153024
gc 1832 @78.352s 0%: 0.018+0.54+0.12 ms clock, 0.29+0/0.16/0.60+1.9 ms cpu, 45->45->23 MB, 89 MB goal, 16 P (forced)
 1000000	       172 ns/op	       8 B/op	       0 allocs/op
gc 1833 @78.353s 0%: 0.016+0.25+0.086 ms clock, 0.25+0/0.43/0.40+1.3 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1834 @78.369s 0%: 0.015+0.30+0.27 ms clock, 0.24+0.14/0.40/0.38+4.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4709520 HeapInuse: 5136384 HeapObjects: 10664 HeapIdle 156016640 HeapReleased 0 HeapSys 161153024
gc 1835 @78.511s 0%: 0.028+0.87+0.19 ms clock, 0.46+0/0.11/0.85+3.0 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndErase1E6-16           	gc 1836 @78.512s 0%: 0.058+0.31+0.15 ms clock, 0.93+0/0.58/0.32+2.5 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1837 @78.528s 0%: 0.014+0.40+0.16 ms clock, 0.23+0.20/0.33/0.23+2.6 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4723200 HeapInuse: 5169152 HeapObjects: 10807 HeapIdle 155983872 HeapReleased 0 HeapSys 161153024
gc 1838 @78.671s 0%: 0.037+0.65+0.13 ms clock, 0.59+0/0.40/0.78+2.1 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1839 @78.672s 0%: 0.073+0.26+0.15 ms clock, 1.1+0/0.38/0.34+2.4 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1840 @78.687s 0%: 0.014+0.35+0.14 ms clock, 0.23+0.17/0.17/0.31+2.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4705856 HeapInuse: 5152768 HeapObjects: 10677 HeapIdle 156000256 HeapReleased 0 HeapSys 161153024
gc 1841 @78.829s 0%: 0.033+0.60+0.11 ms clock, 0.53+0/0.91/0.27+1.7 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1842 @78.830s 0%: 0.010+0.31+0.10 ms clock, 0.17+0/0.24/0.34+1.7 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1843 @78.845s 0%: 0.014+0.37+0.12 ms clock, 0.23+0.16/0.34/0.18+1.9 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4704608 HeapInuse: 5136384 HeapObjects: 10664 HeapIdle 156016640 HeapReleased 0 HeapSys 161153024
gc 1844 @78.986s 0%: 0.013+0.85+0.13 ms clock, 0.21+0/0.36/0.58+2.1 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1845 @78.987s 0%: 0.056+0.22+0.097 ms clock, 0.89+0/0.42/0.43+1.5 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1846 @79.003s 0%: 0.013+0.30+0.11 ms clock, 0.22+0/0.40/0.36+1.8 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4724736 HeapInuse: 5152768 HeapObjects: 10823 HeapIdle 156000256 HeapReleased 0 HeapSys 161153024
gc 1847 @79.146s 0%: 0.018+0.67+0.14 ms clock, 0.30+0/1.0/0.28+2.3 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1848 @79.147s 0%: 0.006+0.20+0.12 ms clock, 0.10+0/0.38/0.21+2.0 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1849 @79.162s 0%: 0.013+0.50+0.13 ms clock, 0.21+0.086/0.33/0.33+2.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4715904 HeapInuse: 5169152 HeapObjects: 10731 HeapIdle 155983872 HeapReleased 0 HeapSys 161153024
gc 1850 @79.308s 0%: 0.033+0.69+0.15 ms clock, 0.53+0/0.99/0.37+2.5 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1851 @79.309s 0%: 0.014+0.29+0.11 ms clock, 0.23+0/0.41/0.27+1.7 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1852 @79.325s 0%: 0.011+0.52+0.27 ms clock, 0.19+0.15/0.35/0.23+4.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4701536 HeapInuse: 5169152 HeapObjects: 10632 HeapIdle 155983872 HeapReleased 0 HeapSys 161153024
gc 1853 @79.466s 0%: 0.011+0.92+0.18 ms clock, 0.18+0/0.90/0.093+2.9 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1854 @79.468s 0%: 0.047+0.26+0.16 ms clock, 0.76+0/0.51/0.11+2.6 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1855 @79.483s 0%: 0.013+0.31+0.17 ms clock, 0.21+0.13/0.28/0.21+2.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4707008 HeapInuse: 5152768 HeapObjects: 10689 HeapIdle 156000256 HeapReleased 0 HeapSys 161153024
gc 1856 @79.625s 0%: 0.011+0.88+0.13 ms clock, 0.18+0/0.93/0.20+2.1 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1857 @79.626s 0%: 0.022+0.27+0.13 ms clock, 0.35+0/0.42/0.13+2.1 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1858 @79.642s 0%: 0.013+0.38+0.33 ms clock, 0.21+0.14/0.43/0.22+5.3 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4727904 HeapInuse: 5160960 HeapObjects: 10856 HeapIdle 155992064 HeapReleased 0 HeapSys 161153024
gc 1859 @79.785s 0%: 0.035+0.62+0.20 ms clock, 0.57+0/0.81/0.21+3.2 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1860 @79.786s 0%: 0.021+0.22+0.11 ms clock, 0.34+0/0.34/0.18+1.7 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1861 @79.802s 0%: 0.014+0.33+0.32 ms clock, 0.23+0.18/0.29/0.21+5.2 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4714848 HeapInuse: 5160960 HeapObjects: 10720 HeapIdle 155992064 HeapReleased 0 HeapSys 161153024
gc 1862 @79.943s 0%: 0.036+0.71+0.14 ms clock, 0.58+0/0.58/0.78+2.3 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1863 @79.944s 0%: 0.051+0.26+0.15 ms clock, 0.81+0/0.36/0.12+2.5 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1864 @79.960s 0%: 0.015+0.30+0.17 ms clock, 0.25+0.12/0.35/0.18+2.7 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4717536 HeapInuse: 5160960 HeapObjects: 10748 HeapIdle 155992064 HeapReleased 0 HeapSys 161153024
gc 1865 @80.102s 0%: 0.011+0.70+0.13 ms clock, 0.18+0/0.48/0.94+2.1 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1866 @80.103s 0%: 0.016+0.26+0.13 ms clock, 0.26+0/0.29/0.19+2.2 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1867 @80.118s 0%: 0.015+0.28+0.087 ms clock, 0.24+0.086/0.38/0.27+1.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4708608 HeapInuse: 5144576 HeapObjects: 10655 HeapIdle 156008448 HeapReleased 0 HeapSys 161153024
gc 1868 @80.261s 0%: 0.011+0.89+0.12 ms clock, 0.18+0/0.42/0.65+2.0 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
gc 1869 @80.262s 0%: 0.059+0.23+0.10 ms clock, 0.94+0/0.44/0.14+1.6 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1870 @80.278s 0%: 0.013+0.37+0.21 ms clock, 0.22+0.087/0.27/0.42+3.4 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
HeapAlloc: 4716576 HeapInuse: 5160960 HeapObjects: 10738 HeapIdle 155992064 HeapReleased 0 HeapSys 161153024
gc 1871 @80.419s 0%: 0.010+0.62+0.12 ms clock, 0.16+0/0.95/0.26+2.0 ms cpu, 4->4->2 MB, 6 MB goal, 16 P (forced)
 1000000	       157 ns/op	       5 B/op	       0 allocs/op
gc 1872 @80.420s 0%: 0.059+0.25+0.12 ms clock, 0.94+0/0.34/0.26+1.9 ms cpu, 2->2->0 MB, 5 MB goal, 16 P (forced)
gc 1873 @80.426s 0%: 0.020+0.28+0.10 ms clock, 0.32+0.10/0.47/0.19+1.6 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575128 HeapInuse: 25886720 HeapObjects: 868 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1874 @80.596s 0%: 0.012+0.28+0.19 ms clock, 0.19+0/0.47/0.24+3.1 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndEraseWithBuf1E6-16    	gc 1875 @80.596s 0%: 0.010+0.22+0.11 ms clock, 0.17+0/0.39/0.23+1.8 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1876 @80.602s 0%: 0.019+0.28+0.14 ms clock, 0.30+0.10/0.44/0.33+2.3 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1877 @80.768s 0%: 0.013+0.27+0.23 ms clock, 0.22+0/0.44/0.19+3.8 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1878 @80.769s 0%: 0.043+0.26+0.20 ms clock, 0.69+0/0.47/0.13+3.2 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1879 @80.775s 0%: 0.018+0.35+0.16 ms clock, 0.30+0.13/0.30/0.29+2.6 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1880 @80.945s 0%: 0.011+0.32+0.15 ms clock, 0.18+0/0.57/0.18+2.5 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1881 @80.946s 0%: 0.011+0.25+0.12 ms clock, 0.18+0/0.37/0.23+1.9 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1882 @80.951s 0%: 0.016+0.28+0.16 ms clock, 0.27+0.15/0.30/0.18+2.6 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1883 @81.124s 0%: 0.012+0.32+0.19 ms clock, 0.20+0/0.54/0.24+3.1 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1884 @81.124s 0%: 0.012+0.24+0.17 ms clock, 0.20+0/0.40/0.25+2.8 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1885 @81.130s 0%: 0.016+0.33+0.17 ms clock, 0.26+0.10/0.35/0.19+2.7 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1886 @81.305s 0%: 0.018+0.31+0.14 ms clock, 0.29+0/0.44/0.23+2.3 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1887 @81.306s 0%: 0.008+0.30+0.19 ms clock, 0.13+0/0.44/0.22+3.1 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1888 @81.312s 0%: 0.023+0.39+0.13 ms clock, 0.38+0.19/0.20/0.29+2.1 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1889 @81.487s 0%: 0.013+0.31+0.22 ms clock, 0.21+0/0.30/0.22+3.6 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1890 @81.488s 0%: 0.012+0.27+0.21 ms clock, 0.19+0/0.41/0.16+3.5 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1891 @81.493s 0%: 0.021+0.34+0.16 ms clock, 0.34+0.14/0.39/0.15+2.6 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1892 @81.665s 0%: 0.039+0.33+0.16 ms clock, 0.62+0/0.51/0.19+2.6 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1893 @81.666s 0%: 0.024+0.27+0.15 ms clock, 0.39+0/0.40/0.22+2.4 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1894 @81.671s 0%: 0.018+0.43+0.19 ms clock, 0.29+0.17/0.32/0.20+3.1 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1895 @81.841s 0%: 0.034+0.35+0.23 ms clock, 0.54+0/0.52/0.19+3.7 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1896 @81.842s 0%: 0.089+0.24+0.11 ms clock, 1.4+0/0.34/0.25+1.8 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1897 @81.847s 0%: 0.017+0.28+0.13 ms clock, 0.28+0.16/0.31/0.21+2.2 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575176 HeapInuse: 25886720 HeapObjects: 869 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1898 @82.014s 0%: 0.031+0.25+0.16 ms clock, 0.50+0/0.36/0.26+2.6 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1899 @82.015s 0%: 0.017+0.31+0.12 ms clock, 0.27+0/0.37/0.13+2.0 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1900 @82.020s 0%: 0.015+0.40+0.19 ms clock, 0.25+0.15/0.18/0.21+3.0 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575272 HeapInuse: 25886720 HeapObjects: 870 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1901 @82.190s 0%: 0.026+0.34+0.15 ms clock, 0.43+0/0.44/0.13+2.4 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1902 @82.191s 0%: 0.008+0.24+0.15 ms clock, 0.13+0/0.31/0.21+2.4 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1903 @82.196s 0%: 0.020+0.30+0.17 ms clock, 0.32+0.16/0.34/0.16+2.8 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575464 HeapInuse: 25886720 HeapObjects: 872 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1904 @82.366s 0%: 0.013+0.33+0.14 ms clock, 0.21+0/0.55/0.14+2.2 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1905 @82.367s 0%: 0.017+0.30+0.16 ms clock, 0.28+0/0.24/0.29+2.6 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1906 @82.372s 0%: 0.018+0.29+0.12 ms clock, 0.28+0.14/0.18/0.28+1.9 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575464 HeapInuse: 25886720 HeapObjects: 872 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1907 @82.538s 0%: 0.012+0.30+0.17 ms clock, 0.19+0/0.44/0.32+2.8 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
gc 1908 @82.539s 0%: 0.10+0.30+0.14 ms clock, 1.6+0/0.37/0.21+2.2 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1909 @82.544s 0%: 0.017+0.28+0.12 ms clock, 0.28+0.10/0.48/0.19+1.9 ms cpu, 24->24->24 MB, 25 MB goal, 16 P
HeapAlloc: 25575560 HeapInuse: 25886720 HeapObjects: 873 HeapIdle 135266304 HeapReleased 0 HeapSys 161153024
gc 1910 @82.717s 0%: 0.011+0.34+0.15 ms clock, 0.17+0/0.37/0.24+2.4 ms cpu, 24->24->23 MB, 48 MB goal, 16 P (forced)
 1000000	       178 ns/op	      25 B/op	       0 allocs/op
gc 1911 @82.718s 0%: 0.016+0.26+0.11 ms clock, 0.25+0/0.41/0.13+1.9 ms cpu, 23->23->0 MB, 47 MB goal, 16 P (forced)
gc 1912 @82.735s 0%: 0.018+453+66 ms clock, 0.29+0/296/0.14+1063 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
HeapAlloc: 80265400 HeapInuse: 80568320 HeapObjects: 872 HeapIdle 80584704 HeapReleased 0 HeapSys 161153024
gc 1913 @86.376s 0%: 0.007+0.18+0.10 ms clock, 0.12+0/0.32/0.15+1.7 ms cpu, 76->76->0 MB, 153 MB goal, 16 P (forced)
#BenchmarkSort1E7-16                               	10000000	       365 ns/op	       8 B/op	       0 allocs/op
gc 1914 @86.376s 0%: 0.022+0.19+0.094 ms clock, 0.35+0/0.34/0.14+1.5 ms cpu, 0->0->0 MB, 8 MB goal, 16 P (forced)
gc 1915 @86.494s 0%: 0.020+3.3+0.11 ms clock, 0.32+0.31/10/5.1+1.8 ms cpu, 4->4->3 MB, 8 MB goal, 16 P
gc 1916 @86.537s 0%: 0.012+4.3+0.095 ms clock, 0.19+0.11/16/23+1.5 ms cpu, 5->6->6 MB, 7 MB goal, 16 P
gc 1917 @86.602s 0%: 0.012+7.1+0.10 ms clock, 0.19+0.085/24/37+1.6 ms cpu, 10->10->10 MB, 12 MB goal, 16 P
gc 1918 @86.801s 0%: 0.019+15+0.17 ms clock, 0.31+0.23/45/92+2.8 ms cpu, 19->19->19 MB, 20 MB goal, 16 P
gc 1919 @87.242s 0%: 0.020+24+0.13 ms clock, 0.32+0.54/92/238+2.1 ms cpu, 37->37->37 MB, 39 MB goal, 16 P
gc 1920 @88.079s 0%: 0.016+43+0.12 ms clock, 0.27+0.27/171/429+1.9 ms cpu, 73->73->73 MB, 75 MB goal, 16 P
gc 1921 @89.479s 0%: 0.017+82+0.17 ms clock, 0.28+0.54/320/833+2.8 ms cpu, 143->146->145 MB, 147 MB goal, 16 P
gc 1922 @92.430s 0%: 0.018+160+0.19 ms clock, 0.29+1.0/640/1744+3.1 ms cpu, 284->287->286 MB, 291 MB goal, 16 P
gc 1923 @99.150s 0%: 0.018+346+0.19 ms clock, 0.28+11/1374/3744+3.1 ms cpu, 559->564->563 MB, 573 MB goal, 16 P
HeapAlloc: 880262936 HeapInuse: 883703808 HeapObjects: 15000892 HeapIdle 966656 HeapReleased 0 HeapSys 884670464
gc 1924 @105.081s 0%: 0.010+1.5+0.12 ms clock, 0.17+0/2.3/12+1.9 ms cpu, 840->840->0 MB, 1126 MB goal, 16 P (forced)
#BenchmarkSetInsert1E7-16                          	10000000	      1878 ns/op	      88 B/op	       2 allocs/op
gc 1925 @105.163s 0%: 0.013+0.27+0.17 ms clock, 0.21+0/0.47/0.19+2.7 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1926 @105.179s 0%: 0.029+0.37+0.16 ms clock, 0.46+0.15/0.34/0.070+2.7 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1927 @105.209s 0%: 0.019+1.1+0.11 ms clock, 0.30+0.15/3.5/2.2+1.9 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1928 @106.024s 0%: 0.017+24+0.12 ms clock, 0.28+0.22/96/187+1.9 ms cpu, 115->116->116 MB, 155 MB goal, 16 P
gc 1929 @107.809s 0%: 0.016+75+0.18 ms clock, 0.26+0.29/297/737+2.9 ms cpu, 202->204->203 MB, 232 MB goal, 16 P
gc 1930 @111.382s 0%: 0.016+217+0.18 ms clock, 0.25+0.52/810/1880+2.9 ms cpu, 379->383->382 MB, 407 MB goal, 16 P
gc 1931 @119.062s 0%: 0.018+381+0.14 ms clock, 0.29+1.0/1525/4182+2.3 ms cpu, 736->748->746 MB, 765 MB goal, 16 P
GC forced
gc 4 @121.162s 0%: 0.10+0.54+0.12 ms clock, 0.95+0/1.6/1.7+1.1 ms cpu, 3->3->1 MB, 4 MB goal, 16 P
gc 1932 @133.856s 0%: 0.016+167+0.11 ms clock, 0.26+10/661/1800+1.8 ms cpu, 1453->1455->383 MB, 1493 MB goal, 16 P
HeapAlloc: 718862680 HeapInuse: 721444864 HeapObjects: 10886056 HeapIdle 809148416 HeapReleased 0 HeapSys 1530593280
gc 1933 @139.442s 0%: 0.029+1.0+0.16 ms clock, 0.47+0/1.1/7.4+2.6 ms cpu, 686->686->0 MB, 767 MB goal, 16 P (forced)
#BenchmarkSetErase1E7-16                           	10000000	      1667 ns/op	      96 B/op	       2 allocs/op
gc 1934 @139.505s 0%: 0.055+0.24+0.14 ms clock, 0.89+0/0.43/0.23+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1935 @139.521s 0%: 0.031+0.42+0.12 ms clock, 0.50+0.28/0.28/0.28+2.0 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1936 @139.550s 0%: 0.019+1.2+0.11 ms clock, 0.31+0.22/3.2/4.6+1.9 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1937 @140.459s 0%: 0.016+24+0.14 ms clock, 0.26+0.18/88/191+2.3 ms cpu, 115->116->116 MB, 155 MB goal, 16 P
gc 1938 @142.087s 0%: 0.018+21+0.11 ms clock, 0.29+0.32/83/224+1.8 ms cpu, 202->203->119 MB, 232 MB goal, 16 P
gc 1939 @144.166s 0%: 0.021+39+0.13 ms clock, 0.34+0.57/152/395+2.1 ms cpu, 223->224->139 MB, 239 MB goal, 16 P
gc 1940 @146.266s 0%: 0.019+15+0.10 ms clock, 0.31+0.35/57/89+1.7 ms cpu, 268->269->100 MB, 278 MB goal, 16 P
gc 1941 @148.307s 0%: 0.018+31+0.13 ms clock, 0.28+0.32/119/247+2.0 ms cpu, 196->198->125 MB, 201 MB goal, 16 P
scvg0: inuse: 224, idle: 1235, sys: 1459, released: 0, consumed: 1459 (MB)
gc 1942 @150.367s 0%: 0.018+40+0.16 ms clock, 0.30+0.67/159/399+2.6 ms cpu, 244->245->149 MB, 251 MB goal, 16 P
gc 1943 @153.161s 0%: 0.024+22+0.097 ms clock, 0.38+0.45/88/237+1.5 ms cpu, 291->291->123 MB, 298 MB goal, 16 P
gc 1944 @155.322s 0%: 0.017+3.1+0.14 ms clock, 0.27+0.39/10/24+2.2 ms cpu, 240->240->80 MB, 246 MB goal, 16 P
HeapAlloc: 89095880 HeapInuse: 89432064 HeapObjects: 151391 HeapIdle 1441161216 HeapReleased 0 HeapSys 1530593280
gc 1945 @155.393s 0%: 0.034+0.29+0.15 ms clock, 0.54+0/0.47/0.11+2.4 ms cpu, 85->85->0 MB, 161 MB goal, 16 P (forced)
#BenchmarkSetInsertAndErase1E7-16                  	10000000	      1588 ns/op	      96 B/op	       2 allocs/op
gc 1946 @155.395s 0%: 0.016+0.40+0.14 ms clock, 0.26+0/0.28/0.36+2.3 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1947 @155.411s 0%: 0.022+0.29+0.12 ms clock, 0.35+0.13/0.21/0.27+2.0 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1948 @155.451s 0%: 0.012+1.3+0.10 ms clock, 0.19+0.12/4.5/1.1+1.6 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1949 @156.623s 0%: 0.014+26+0.20 ms clock, 0.22+0.23/95/187+3.2 ms cpu, 115->116->116 MB, 155 MB goal, 16 P
gc 1950 @159.866s 0%: 0.020+19+0.13 ms clock, 0.32+0.60/72/178+2.1 ms cpu, 202->202->110 MB, 232 MB goal, 16 P
gc 1951 @163.675s 0%: 0.014+22+0.10 ms clock, 0.23+0.14/86/205+1.7 ms cpu, 207->207->115 MB, 221 MB goal, 16 P
gc 1952 @167.599s 0%: 0.016+29+0.15 ms clock, 0.26+11/111/291+2.4 ms cpu, 223->224->132 MB, 231 MB goal, 16 P
gc 1953 @173.255s 0%: 0.019+15+0.088 ms clock, 0.31+0.30/56/149+1.4 ms cpu, 257->257->102 MB, 264 MB goal, 16 P
HeapAlloc: 110380592 HeapInuse: 110895104 HeapObjects: 628230 HeapIdle 1419698176 HeapReleased 0 HeapSys 1530593280
gc 1954 @173.836s 0%: 0.039+0.37+0.16 ms clock, 0.63+0/0.45/0.60+2.6 ms cpu, 105->105->0 MB, 205 MB goal, 16 P (forced)
#BenchmarkSetInsertAndEraseWithPool1E7-16          	10000000	      1844 ns/op	      56 B/op	       1 allocs/op
gc 1955 @173.843s 0%: 0.026+0.26+0.19 ms clock, 0.41+0/0.36/0.27+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1956 @173.935s 0%: 0.017+2.7+0.19 ms clock, 0.28+0.43/9.5/15+3.0 ms cpu, 4->4->3 MB, 5 MB goal, 16 P
gc 1957 @174.017s 0%: 0.018+4.4+0.13 ms clock, 0.30+0.41/15/35+2.1 ms cpu, 7->7->6 MB, 8 MB goal, 16 P
gc 1958 @174.117s 0%: 0.020+8.5+0.11 ms clock, 0.32+0.55/31/68+1.9 ms cpu, 13->13->13 MB, 14 MB goal, 16 P
gc 1959 @174.340s 0%: 0.018+16+0.14 ms clock, 0.29+0.25/59/131+2.2 ms cpu, 25->26->25 MB, 26 MB goal, 16 P
gc 1960 @174.826s 0%: 0.020+52+0.14 ms clock, 0.33+0.49/190/1.8+2.3 ms cpu, 48->49->47 MB, 50 MB goal, 16 P
gc 1961 @175.810s 0%: 0.019+60+0.10 ms clock, 0.31+1.0/235/550+1.7 ms cpu, 92->95->90 MB, 95 MB goal, 16 P
gc 1962 @176.988s 0%: 0.017+88+0.17 ms clock, 0.28+0.50/351/941+2.7 ms cpu, 176->180->171 MB, 181 MB goal, 16 P
gc 1963 @179.719s 0%: 0.022+202+0.12 ms clock, 0.35+0.56/805/2012+1.9 ms cpu, 335->339->323 MB, 343 MB goal, 16 P
scvg0: inuse: 2, idle: 2, sys: 5, released: 0, consumed: 5 (MB)
gc 1964 @184.755s 0%: 0.016+308+0.11 ms clock, 0.26+1.2/1230/3350+1.9 ms cpu, 630->640->610 MB, 647 MB goal, 16 P
HeapAlloc: 817199064 HeapInuse: 820658176 HeapObjects: 11059395 HeapIdle 709935104 HeapReleased 0 HeapSys 1530593280
gc 1965 @187.696s 0%: 0.013+1.3+0.097 ms clock, 0.22+0/1.7/10+1.5 ms cpu, 779->779->0 MB, 1221 MB goal, 16 P (forced)
#BenchmarkIntSetInsert1E7-16                       	10000000	      1393 ns/op	      88 B/op	       2 allocs/op
gc 1966 @187.775s 0%: 0.017+0.29+0.13 ms clock, 0.27+0/0.45/0.097+2.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1967 @187.790s 0%: 0.024+0.24+0.14 ms clock, 0.39+0.098/0.27/0.061+2.3 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1968 @187.814s 0%: 0.016+1.0+0.094 ms clock, 0.26+0.24/2.9/3.4+1.5 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1969 @188.465s 0%: 0.015+18+0.21 ms clock, 0.24+0.43/70/163+3.4 ms cpu, 115->116->112 MB, 154 MB goal, 16 P
gc 1970 @189.929s 0%: 0.016+243+0.24 ms clock, 0.26+0.11/465/1.0+3.8 ms cpu, 196->197->189 MB, 225 MB goal, 16 P
gc 1971 @192.866s 0%: 0.017+123+0.17 ms clock, 0.27+0.74/490/1322+2.7 ms cpu, 353->356->340 MB, 378 MB goal, 16 P
gc 1972 @197.743s 0%: 0.023+274+0.12 ms clock, 0.37+0.97/1097/2977+2.0 ms cpu, 655->670->640 MB, 681 MB goal, 16 P
gc 1973 @206.083s 0%: 0.020+207+0.092 ms clock, 0.33+1.6/825/2258+1.4 ms cpu, 1243->1249->499 MB, 1280 MB goal, 16 P
HeapAlloc: 999380184 HeapInuse: 1003126784 HeapObjects: 13678176 HeapIdle 527466496 HeapReleased 0 HeapSys 1530593280
gc 1974 @212.465s 0%: 0.017+1.4+0.11 ms clock, 0.27+0/2.4/10+1.8 ms cpu, 954->954->0 MB, 999 MB goal, 16 P (forced)
#BenchmarkIntSetErase1E7-16                        	10000000	      1147 ns/op	      96 B/op	       2 allocs/op
gc 1975 @212.624s 0%: 0.024+0.23+0.19 ms clock, 0.39+0/0.45/0.20+3.1 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1976 @212.641s 0%: 0.036+0.28+0.17 ms clock, 0.57+0.12/0.25/0.18+2.7 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1977 @212.655s 0%: 0.015+1.1+0.12 ms clock, 0.24+0.13/2.6/2.9+2.0 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1978 @213.216s 0%: 0.020+20+0.20 ms clock, 0.32+0.54/79/200+3.2 ms cpu, 115->116->112 MB, 154 MB goal, 16 P
gc 1979 @214.563s 0%: 0.015+22+0.15 ms clock, 0.24+0.22/82/209+2.4 ms cpu, 196->197->118 MB, 225 MB goal, 16 P
gc 1980 @216.043s 0%: 0.018+26+0.13 ms clock, 0.30+0.22/100/267+2.1 ms cpu, 220->221->129 MB, 236 MB goal, 16 P
gc 1981 @217.875s 0%: 0.015+7.5+0.17 ms clock, 0.25+0.37/23/36+2.7 ms cpu, 250->250->86 MB, 259 MB goal, 16 P
gc 1982 @219.224s 0%: 0.020+35+0.18 ms clock, 0.32+0.30/135/352+2.9 ms cpu, 169->171->145 MB, 173 MB goal, 16 P
gc 1983 @221.171s 0%: 0.019+32+0.11 ms clock, 0.31+0.43/122/321+1.8 ms cpu, 283->284->136 MB, 291 MB goal, 16 P
gc 1984 @223.279s 0%: 0.019+12+0.094 ms clock, 0.30+0.29/46/101+1.5 ms cpu, 266->267->102 MB, 273 MB goal, 16 P
gc 1985 @224.689s 0%: 0.019+17+0.15 ms clock, 0.31+0.38/68/166+2.4 ms cpu, 199->200->116 MB, 204 MB goal, 16 P
HeapAlloc: 165782232 HeapInuse: 166404096 HeapObjects: 1273443 HeapIdle 1364189184 HeapReleased 0 HeapSys 1530593280
gc 1986 @225.341s 0%: 0.038+0.45+0.15 ms clock, 0.61+0/0.69/0.82+2.5 ms cpu, 158->158->0 MB, 232 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndErase1E7-16               	10000000	      1272 ns/op	      96 B/op	       2 allocs/op
gc 1987 @225.350s 0%: 0.016+0.28+0.15 ms clock, 0.26+0/0.40/0.24+2.4 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1988 @225.368s 0%: 0.021+0.30+0.19 ms clock, 0.33+0.098/0.23/0.29+3.1 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 1989 @225.401s 0%: 0.016+1.3+0.21 ms clock, 0.25+0.38/3.7/3.6+3.4 ms cpu, 77->77->77 MB, 153 MB goal, 16 P
gc 1990 @226.445s 0%: 0.016+17+0.096 ms clock, 0.26+0.43/65/162+1.5 ms cpu, 115->116->112 MB, 154 MB goal, 16 P
gc 1991 @229.187s 0%: 0.015+15+0.19 ms clock, 0.24+0.21/56/132+3.1 ms cpu, 195->196->105 MB, 224 MB goal, 16 P
gc 1992 @231.911s 0%: 0.018+20+0.14 ms clock, 0.29+0.18/62/93+2.3 ms cpu, 196->197->105 MB, 210 MB goal, 16 P
gc 1993 @234.731s 0%: 0.019+16+0.15 ms clock, 0.30+0.33/64/165+2.4 ms cpu, 203->203->111 MB, 210 MB goal, 16 P
gc 1994 @237.701s 0%: 0.023+25+0.12 ms clock, 0.38+0.49/96/235+1.9 ms cpu, 217->217->124 MB, 222 MB goal, 16 P
HeapAlloc: 171289696 HeapInuse: 171925504 HeapObjects: 1689732 HeapIdle 1358667776 HeapReleased 0 HeapSys 1530593280
gc 1995 @239.481s 0%: 0.016+0.39+0.19 ms clock, 0.26+0/0.54/0.51+3.0 ms cpu, 163->163->0 MB, 249 MB goal, 16 P (forced)
#BenchmarkIntSetInsertAndEraseWithPool1E7-16       	10000000	      1414 ns/op	      56 B/op	       1 allocs/op
gc 1996 @239.491s 0%: 0.023+0.25+0.20 ms clock, 0.37+0/0.36/0.20+3.2 ms cpu, 0->0->0 MB, 4 MB goal, 16 P (forced)
gc 1997 @239.521s 0%: 0.017+0.35+0.16 ms clock, 0.27+0.13/0.25/0.33+2.6 ms cpu, 4->4->1 MB, 5 MB goal, 16 P
gc 1998 @239.522s 0%: 0.009+0.35+0.13 ms clock, 0.15+0.11/0.31/0.37+2.1 ms cpu, 4->4->4 MB, 5 MB goal, 16 P
gc 1999 @239.542s 0%: 0.013+0.40+0.19 ms clock, 0.21+0.25/0.33/0.23+3.0 ms cpu, 11->11->9 MB, 12 MB goal, 16 P
gc 2000 @239.612s 0%: 0.018+0.72+0.21 ms clock, 0.29+0.66/0.29/0.42+3.4 ms cpu, 22->22->18 MB, 23 MB goal, 16 P
gc 2001 @239.768s 0%: 0.020+1.4+0.19 ms clock, 0.32+0.78/0.91/0.34+3.1 ms cpu, 45->45->37 MB, 46 MB goal, 16 P
gc 2002 @239.957s 0%: 0.018+1.0+0.16 ms clock, 0.29+0.16/0.61/0.94+2.6 ms cpu, 38->38->23 MB, 74 MB goal, 16 P
GC forced
gc 5 @241.163s 0%: 0.12+0.60+0.26 ms clock, 1.6+0/1.7/3.2+3.4 ms cpu, 1->1->1 MB, 4 MB goal, 16 P
gc 2003 @240.070s 0%: 0.019+3.1+0.19 ms clock, 0.31+0.84/2.6/0.39+3.0 ms cpu, 75->75->74 MB, 76 MB goal, 16 P
gc 2004 @240.468s 0%: 0.018+6.2+0.14 ms clock, 0.30+0/2.5/4.3+2.2 ms cpu, 75->75->47 MB, 148 MB goal, 16 P
gc 2005 @240.792s 0%: 0.024+5.5+0.14 ms clock, 0.38+0.77/5.0/0.43+2.2 ms cpu, 151->151->148 MB, 152 MB goal, 16 P
gc 2006 @241.441s 0%: 0.015+7.0+0.14 ms clock, 0.24+0/2.4/5.0+2.3 ms cpu, 149->149->94 MB, 296 MB goal, 16 P
gc 2007 @242.284s 0%: 0.020+10+0.090 ms clock, 0.33+0.76/10/0.67+1.4 ms cpu, 303->303->296 MB, 304 MB goal, 16 P
gc 2008 @243.336s 0%: 0.021+11+0.11 ms clock, 0.34+0/8.1/3.2+1.7 ms cpu, 297->297->297 MB, 593 MB goal, 16 P
HeapAlloc: 315041656 HeapInuse: 315400192 HeapObjects: 154672 HeapIdle 1215193088 HeapReleased 0 HeapSys 1530593280
gc 2009 @243.882s 0%: 0.010+3.2+0.15 ms clock, 0.17+0/3.2/0.16+2.4 ms cpu, 300->300->188 MB, 594 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsert1E7-16                   	10000000	       439 ns/op	      44 B/op	       0 allocs/op
gc 2010 @243.888s 0%: 0.021+0.30+0.12 ms clock, 0.35+0/0.34/0.27+2.0 ms cpu, 188->188->0 MB, 376 MB goal, 16 P (forced)
gc 2011 @243.906s 0%: 0.024+0.38+0.13 ms clock, 0.39+0/0.49/0.27+2.1 ms cpu, 76->76->76 MB, 77 MB goal, 16 P
gc 2012 @243.911s 0%: 0.009+0.47+0.15 ms clock, 0.15+0.086/0.21/0.095+2.5 ms cpu, 77->78->77 MB, 153 MB goal, 16 P
gc 2013 @244.102s 0%: 0.017+1.0+0.14 ms clock, 0.27+0.56/0.60/0.32+2.3 ms cpu, 128->128->113 MB, 155 MB goal, 16 P
gc 2014 @245.042s 0%: 0.020+3.3+0.12 ms clock, 0.32+0.41/3.1/0.48+1.9 ms cpu, 271->271->224 MB, 272 MB goal, 16 P
gc 2015 @246.475s 0%: 0.019+6.6+0.10 ms clock, 0.30+0.43/6.3/0.50+1.7 ms cpu, 434->434->372 MB, 449 MB goal, 16 P
HeapAlloc: 395673648 HeapInuse: 396189696 HeapObjects: 154321 HeapIdle 1134403584 HeapReleased 0 HeapSys 1530593280
gc 2016 @249.969s 0%: 0.009+3.0+0.19 ms clock, 0.14+0/3.2/0.25+3.0 ms cpu, 377->377->188 MB, 745 MB goal, 16 P (forced)
#BenchmarkSysHashMapErase1E7-16                    	10000000	       184 ns/op	       8 B/op	       0 allocs/op
gc 2017 @249.975s 0%: 0.046+0.23+0.19 ms clock, 0.75+0/0.36/0.18+3.1 ms cpu, 188->188->0 MB, 376 MB goal, 16 P (forced)
gc 2018 @249.977s 0%: 0.011+0.31+0.17 ms clock, 0.18+0.11/0.26/0.28+2.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 2019 @249.985s 0%: 0.012+0.34+0.18 ms clock, 0.20+0.12/0.37/0.29+3.0 ms cpu, 9->9->9 MB, 15 MB goal, 16 P
gc 2020 @250.009s 0%: 0.014+0.34+0.17 ms clock, 0.22+0.23/0.21/0.33+2.8 ms cpu, 14->14->12 MB, 18 MB goal, 16 P
gc 2021 @250.067s 0%: 0.015+2.7+0.14 ms clock, 0.24+0/1.2/2.0+2.2 ms cpu, 19->20->14 MB, 25 MB goal, 16 P
gc 2022 @250.077s 0%: 0.013+0.45+0.13 ms clock, 0.21+0.40/0/0.45+2.1 ms cpu, 26->26->26 MB, 28 MB goal, 16 P
gc 2023 @250.179s 0%: 0.029+0.86+0.18 ms clock, 0.46+0.48/0.72/0.37+2.9 ms cpu, 52->52->44 MB, 53 MB goal, 16 P
HeapAlloc: 48396784 HeapInuse: 48857088 HeapObjects: 24420 HeapIdle 1481736192 HeapReleased 0 HeapSys 1530593280
gc 2024 @251.919s 0%: 0.009+1.1+0.15 ms clock, 0.14+0/1.3/0.14+2.4 ms cpu, 46->46->24 MB, 89 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndErase1E7-16           	10000000	       194 ns/op	       6 B/op	       0 allocs/op
gc 2025 @251.921s 0%: 0.012+0.24+0.089 ms clock, 0.20+0/0.31/0.18+1.4 ms cpu, 24->24->0 MB, 48 MB goal, 16 P (forced)
gc 2026 @251.923s 0%: 0.009+0.21+0.17 ms clock, 0.15+0.16/0.21/0.098+2.8 ms cpu, 7->7->7 MB, 8 MB goal, 16 P
gc 2027 @251.961s 0%: 0.018+0.39+0.13 ms clock, 0.29+0.14/0.10/0.28+2.0 ms cpu, 194->194->194 MB, 195 MB goal, 16 P
HeapAlloc: 204350200 HeapInuse: 204668928 HeapObjects: 879 HeapIdle 1325924352 HeapReleased 0 HeapSys 1530593280
gc 2028 @254.065s 0%: 0.007+0.23+0.11 ms clock, 0.12+0/0.34/0.15+1.7 ms cpu, 194->194->187 MB, 389 MB goal, 16 P (forced)
#BenchmarkSysHashMapInsertAndEraseWithBuf1E7-16    	10000000	       214 ns/op	      20 B/op	       0 allocs/op
gc 2029 @254.066s 0%: 0.039+0.28+0.16 ms clock, 0.62+0/0.35/0.30+2.6 ms cpu, 187->187->0 MB, 374 MB goal, 16 P (forced)
#BenchmarkIntSetInsert-16                          	gc 2030 @254.067s 0%: 0.015+0.32+0.13 ms clock, 0.24+0/0.54/0.27+2.2 ms cpu, 0->0->0 MB, 8 MB goal, 16 P (forced)
gc 2031 @254.068s 0%: 0.050+0.22+0.089 ms clock, 0.80+0/0.44/0.18+1.4 ms cpu, 0->0->0 MB, 8 MB goal, 16 P (forced)
gc 2032 @254.087s 0%: 0.046+0.21+0.15 ms clock, 0.74+0/0.40/0.18+2.4 ms cpu, 1->1->0 MB, 8 MB goal, 16 P (forced)
gc 2033 @254.171s 0%: 0.019+2.7+0.17 ms clock, 0.30+0.22/8.2/10+2.7 ms cpu, 4->4->3 MB, 8 MB goal, 16 P
gc 2034 @254.202s 0%: 0.008+3.6+0.18 ms clock, 0.13+0.095/13/21+3.0 ms cpu, 5->5->5 MB, 7 MB goal, 16 P
gc 2035 @254.248s 0%: 0.011+5.5+0.13 ms clock, 0.18+0.17/19/33+2.1 ms cpu, 9->9->9 MB, 10 MB goal, 16 P
gc 2036 @254.366s 0%: 0.020+10+0.14 ms clock, 0.33+0.44/38/87+2.3 ms cpu, 16->16->16 MB, 18 MB goal, 16 P
gc 2037 @254.628s 0%: 0.018+19+0.16 ms clock, 0.28+0.26/69/129+2.5 ms cpu, 30->31->29 MB, 32 MB goal, 16 P
gc 2038 @255.202s 0%: 0.019+35+0.15 ms clock, 0.31+0.43/133/312+2.4 ms cpu, 57->57->55 MB, 59 MB goal, 16 P
 1000000	      1666 ns/op	      88 B/op	       2 allocs/op
PASS
ok  	github.com/cdongyang/library/rbtree	255.940s