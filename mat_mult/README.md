# mat_mult

Compile using `./make.sh`.

```shell
$ export OMP_NUM_THREADS=8
$ ./mat_mult                                                                                                                                                                                                     [13/99]
---- a ----
0.00 0.00 0.00 0.00 0.00 
0.00 0.00 0.00 0.00 0.00 


---- b ----
0.00 0.00 0.00 
0.00 0.00 0.00 
0.00 0.00 0.00 
0.00 0.00 0.00 
0.00 0.00 0.00 


---- c ----
0.00 0.00 0.00 
0.00 0.00 0.00 


---- init a ----
3.00 8.00 4.00 9.00 1.00 
3.00 4.00 6.00 6.00 9.00 


---- init b ----
3.00 8.00 4.00 
9.00 1.00 3.00 
4.00 6.00 6.00 
9.00 8.00 5.00 
9.00 1.00 5.00


---- init c ----
0.00 0.00 0.00 
0.00 0.00 0.00 


Number of threads = 1
---- mat mult c ----
187.00 129.00 110.00 
204.00 121.00 135.00 


```
