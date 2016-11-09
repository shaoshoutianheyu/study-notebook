# study-notebook
tips 1
zipline成交是需要考虑成交量的，因为如果资金量太大，那么很可能zipline会逐日成交。如果没有volume数据，zipline就不会出现逐日成交的情形。相关代码可以查询zipline.finance.blotter 和zipline.finance.slippage 
tips 2 
