# 项目简介 #
本项目为阿里云开放存储服务（OSS）提供了一套完整易用的 C++ SDK，取名为OSSCPP.
目前OSSCPP提供了OSS开放接口中所描述的所有功能, 基本特点包括：
	1. Bucket所有操作，如创建 bucket, 删除bucket，设置ACL，获取bucket的信息等。
	2. Object所有操作，如创建 object，获取object，拷贝object，删除object，删除多个object，
		上传下载文件等。
	3. Multipart Upload操作，如初始化Multipart Upload，上传Part，终止Multipart Upload，
		查看Multipart Upload等。
	4. Object Group操作，如创建Object Group，获取Object Group，删除Object Group等。
更多文档请参考 doc/html目录中的页面

# 安装与体验 #
  ## 编译步骤 ##
      1. 安装CMake。
      2. 创建 build 目录，进入到该目录，执行 cmake ../.
      3. 编译和安装 make && make install 

# 关于作者 #
傅海平：中国科学院计算技术研究所(haipingf@gmail.com)
王  维：中国科院学计算技术研究所(wangwei881116@gmail.com)
