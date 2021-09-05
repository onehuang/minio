
初始化创建目录：   
{fsPath}/.minio.sys  
{fsPath}/.minio.sys/tmp  
{fsPath}/.minio.sys/config  
{fsPath}/.minio.sys/config/config.json   
{fsPath}/.minio.sys/config/iam  
{fsPath}/.minio.sys/config/iam/format.json   
{fsPath}/.minio.sys/buckets  
{fsPath}/.minio.sys/multipart  
{fsPath}/.minio.sys/format.json  

对象存放路径：{fsPath}/{bucketName}/{object}  
对象元数据存放路径: {fsPath}/.minio.sys/buckets/{bucketName}/{objectName}/fs.json  
桶数据存放路径：{fsPath}/{bucketName}
桶元数据存放目录： {fsPath}/.minio.sys/buckets/{bucketName}/.metadata.bin   
桶元数据存放临时目录： {fsPath}/.minio.sys/tmp/实例UUID/临时uuid   
桶的使用情况： {fsPath}/.minio.sys/buckets/.usage.json  

什么文件： {fsPath}/.minio.sys/buckets/.usage-cache.bin   
什么文件： {fsPath}/.minio.sys/buckets/{objectName}/.usage-cache.bin   
什么文件： {fsPath}/.minio.sys/buckets/.tracker.bin   
什么文件： {fsPath}/.minio.sys/buckets/.bloomcycle.bin   
什么文件： {fsPath}/.minio.sys/buckets/.usage.json    
什么文件： {fsPath}/.minio.sys/buckets/.minio.sys/* ????  存放什么信息  

管理项目在console模块中  

