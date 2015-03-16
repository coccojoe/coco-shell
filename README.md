# coco-shell
一些常用的shell小脚本。

## ab(Apache benchmark)批量测试脚本
useage:<br/>
b-test-tools.sh<br/>
-N|--count 总请求数，缺省 : 5w<br/>
-C|--clients 并发数, 缺省 : 100<br/>
-R|--rounds 测试次数, 缺省 : 10 次<br/>
-S|-sleeptime 间隔时间, 缺省 : 10 秒<br/>
-I|--min 最小并发数,　缺省: 0<br/>
-X|--max 最大并发数，缺省: 0<br/>
-J|--step 次递增并发数<br/>
-R|--runtime 总体运行时间,设置此项时最大请求数为5w<br/>
-P|--postfile post数据文件路径<br/>
-U|--url 测试地址<br/>

详情参见:http://blog.163.com/sujoe_2006/blog/static/3353151201492085618154/<br/>
