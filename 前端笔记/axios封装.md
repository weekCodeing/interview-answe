二次封装详细的说说，主要包括请求之前、返回响应以及使用等。

// 请求拦截
axios.interceptors.request.use((config) => {
  //....省略代码
  config.headers.x_access_token = token
  return config
}, function (error) {
  return Promise.reject(error)
})

axios-get

axios.get('url', {
	params: {}, // 接口参数
}).then(function(res){
	console.log(res)
}).catch(function(error){
	console.log(error)//错误处理 相当于error
})

axios.post('url',{
  data:xxx//参数
  },{
  headers:xxxx,//请求头信息
}).then(function(res){
  console.log(res);//处理成功的函数 相当于success
}).catch(function(error){
  console.log(error)//错误处理 相当于error
})

用vite来初始化项目

直接初始化项目

npm init @vitejs/app
复制代码
下载axios依赖。

npm install axios

比如请求超时、不同HTTP状态码、各种响应的数据结构等等。








