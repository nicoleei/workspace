### 1.安装node和express，参考[官网](http://expressjs.com/)

    npm install -g express

### 2.找个目录，运行命令，会生成该目录名的文件夹，进入该文件夹，运行 npm install 安装所需组件
    
    express xxxx(目录名)

### 3.启动node express服务器，直接运行 npm start,然后在浏览器里打开 http://localhost:3000, 看到welcome，表示服务器启动成功

### 4.把测试文件放到public目录下，浏览器里打开 http://localhost:3000/文件夹名/文件名，就可以访问该文件了

### 5.到routes目录下，index.js文件是主要代理文件
* req.body 表示接受到的参数
* res.send 要发送的数据