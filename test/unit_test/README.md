## Prerrequisites:
* CUnit 2.1.3 available -> http://sourceforge.net/projects/cunit/  

To install CUNit: 
```
autoreconf --install
```
```
autoconf configure.in > configure
```
```
./configure && make && sudo make install
```

CUnit documentation -> http://cunit.sourceforge.net/




## Run tests
* Compile.  
```
make
```
* Set uid (we are testing drop and restore privileges).  
```
sudo make setuid
```

* Run.  
```
 ./test
```

