# c2veril
* 採用https://github.com/cccbook/c2verilog
```
git clone https://github.com/cccbook/c2verilog.git
cd c2verilog/src
```
* if use Mac
```
$make clean
$make
```
* Window MinGW maybe need to install make
* Window msys2 no doubt need to install make (git clone後要將bin中所有沒副檔名的資料都刪除)
```
pacman -Ss make //查詢完整的make包
pacman -S msys/make //直接安裝

```
* When you done install make enviornment, you can start learning
```
* 在c2verilog/bin/
1.as0 //組譯器 (Assembler)
2.cc0 //編譯器 (Compiler)
3.ma0 //巨集處理器 (Macro Processor)	
4.vm0 //虛擬機 (Virtual Machine)
```

執行
```
$cd /c2verilog/src
$make c0run file=../test/c/sum

```

