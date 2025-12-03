## 输入输出

### 格式化输入输出

当 输入/输出的数据 $\geq$ 100 万 时，要用 scanf 和 printf
```cpp
printf("%占位符",变量名)；
scanf("%占位符",&变量名)；
```
> 占位符：
int ---> d  
char ---> c  
float ---> f  
long long ---> lld  
double ---> lf   
换行 ---> \n

### 保留小数点后n位
```cpp
cout<<fixed<<setprecision(n)<<num;
```

### 控制 n 个 间距/场宽
```cpp
cout<<setw(n)<<...;
```