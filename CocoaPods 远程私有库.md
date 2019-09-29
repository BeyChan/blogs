## 创建远程索引库和私有库

将远程索引库添加到本地 pod repo add 索引库名称 索引库地址

在本地创建一个pod模板库 pod lib create 组件名称 
将框架的核心代码添加到Classes目录下 
本地安装测试核心代码是否可用 pod install 
修改Spec描述文件 
将修改好的模板库上传至远程私有库

上传代码和打标签
git init
git add .
git commit -m "提交描述"
git remote add origin 远程私有库地址
git push origin master
git tag '0.1.0'
git push --tags

提交spec至私有索引库
pod lib lint --private
pod spec lint --verbose --allow-warnings
pod repo push 索引库的本地名称 xx.podspec

使用
source 官方索引库url
source 私有索引库url
pod '组件名称'
pod install

提交到cocoapods 
注册
pod trunk register beychan@qq.com 'BeyChan' --description='My Name is Melody Chan ' --verbose
查看
pod trunk me
添加其他维护者（如果你的pod是由多人维护的，你也可以添加其他维护者）
pod trunk add-owner XPRACSignal wangxx@cocoapods.org
提交
pod trunk push