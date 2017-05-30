# sina_stock_market

### 新浪股票数据接口
-----
#### 深股 http://hq.sinajs.cn/list=sz0***** 

#### 新股 http://hq.sinajs.cn/list=sz3*****

#### 沪股 http://hq.sinajs.cn/list=sh6******

#### 端口举例 600000 浦发银行
打开 http://hq.sinajs.cn/list=sh600000 网页

#### 得到以下数据
var hq_str_sh600000="浦发银行,12.810,12.930,12.840,12.910,12.540,12.830,12.840,176456630,2246593329.000,68403,12.830,458808,12.820,717851,12.810,276467,12.800,369280,12.790,591587,12.840,754091,12.850,437189,12.860,242782,12.870,406420,12.880,2017-05-26,15:00:00,00";
#### 其格式为 
var hq_str_sh股票代码="股票名称,今日开盘价,昨日收盘价,今日收盘价,今日最高价,今日最低价,买一报价,卖一报价,成交数量,成交金额,买一数量,买一报价,买二数量,买二报价,买三数量,买三报价,买四数量,买四报价,买五数量,买五报价,卖一数量,卖一报价,卖二数量,卖二报价,卖三数量,卖三报价,卖四数量,卖四报价,卖五数量,卖五报价,日期,时间,00";

### 爬虫运行
-----
1. 运行 sina_stock_market.py 文件
2. 将结果复制至文本编辑器，例如 Sublime 等，保存为.csv文件
3. 使用 Excel 导入（MacOS Excel 文本编码使用 Unicode UTF-8）
