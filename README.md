# json-server
## 使用在线json-server服务，存放json数据 

## 一、步骤
1.在GitHub上创建存储库（<your-username>/<your-repo>）
2.建立db.json档案
3.访问https://my-json-server.typicode.com/ <您的用户名> / <您的回购>以访问您的服务器
  例如：https://my-json-server.typicode.com/HaloHan2017/json-server
4.创建db.json数据文件
 
## 二、在线API使用 
// 获取所有用户信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/users

// 获取id为1的用户信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/users/1

// 获取公司的所有信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies

// 获取单个公司的信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies/1

// 获取所有公司id为3的用户
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies/3/users

// 根据公司名字获取信息
http://localhost:3000/companies?name=Microsoft

// 根据多个名字获取公司信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies?name=Microsoft&name=Apple

// 获取一页中只有两条数据
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies?_page=1&_limit=2

// 升序排序 asc升序 desc降序
http://https://my-json-server.typicode.com/HaloHan2017/json-server/companies?_sort=name&_order=asc

// 获取年龄30及以上的
http://https://my-json-server.typicode.com/HaloHan2017/json-server/users?age_gte=30

// 获取年龄在30到40之间
http://https://my-json-server.typicode.com/HaloHan2017/json-server/users?age_gte=30&age_lte=40

// 搜索用户信息
http://https://my-json-server.typicode.com/HaloHan2017/json-server/users?q=h  h指的是查询的首字母
