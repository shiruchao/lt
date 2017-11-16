# lt
## server使用的是koaJS
````````````````````
* 在启动前，应该先建立数据库，数据结构在data文件夹里面
* 还有把server/route/fn.js里面的数据库链接改成自己的，因为这个写的也是我的
````````````````````
## web用的是VUE 
````````````````````
* 在使用时，建议 vue run build 以后放到server根目录下面，因为我没有处理，跨域登录问题
* 顺便把/src/data/store.js里面的url改掉，因为那里面写的是我的本地IP
````````````````````
## 数据库用的是mysql
````````````````````
* 建立好数据库，执行data/*.sql 这里面保存的是server所需要的sql结构
````````````````````


