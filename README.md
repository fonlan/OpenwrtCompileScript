序言

  降低编译难度，减少重复的步骤，但不利于学习，此脚本适用于有点openwrt编译的基础的最佳，完全没有编译基础的请去补充相关知识 
          
 想学点东西请走这里： https://www.right.com.cn/forum/thread-324501-1-1.html
          
 此脚本并不是无脑脚本，这个脚本对新手是无脑的但要点基础，起码你要会选择机型与插件，有点基础的可以说是辅助，加快你的编译速度，写这个脚本的初衷就是编译的过程重复太多，所以写了脚本 
               
                感谢@学渣 @sjz等帮助        

脚本作用
		用于辅助Openwrt编译，但不会帮你完成整个编译过程，需要一点Openwrt编译基础


目前支持系统：
	
	1.Ubuntu 16.4  
	2.Ubuntu 18.4
	3.win10子系统（ubuntu 18.04 LTS）
			  

使用方法
 1. git clone https://github.com/openwrtcompileshell/OpenwrtCompileScript.git
 
 2. cd OpenwrtCompileScript
  
 3. bash openwrt.sh
 
 
脚本执行一次以后会自动添加变量，第二次执行脚本 bash $openwrt



脚本使用办法：https://www.right.com.cn/forum/thread-345378-1-1.html


交流技术适当吹水群：667491026   （拒绝大爷公子伸手党）


脚本版本


++2.7版本

  	1.修改脚本名字为《openwr.sh》不再以版本命名，以后执行脚本sh openwrt.sh即可
  
  	2.加入if判断是否源码下载成功
  
  	3.Dl服务器下载增加一个参数，解决证书不信任问题
  
  	4.增加脚本描述文本
  
 	5. 文件夹创建提前
  
  	6.加入时间计算让自己更加直观看到编译耗时

  	7.增加多线程编译可以自己决定以多少线程进行编译

  	8.增加脚本自检程序

  	9.新增选项 9.更新脚本
    
	10.优化一下代码

	11.增加一个ls函数模块
    
	12.适配win10子系统（ubuntu 18.04 LTS）
	
	13.删除无用的5.选项替换DNS

++2.6版本

  	1.支持不在home底下也能正常运行，因为服了一下小白老是报错
  
  	2.只需要执行脚本就可以操作你任意的openwrt文件夹
  
 	 3.新增国内DL服务器（感谢LGA1150）
  
  	4.新增选择( 6.其他选项)，可以单独使用个别模块，如：支持单独只搭建编译环境，而不进行编译
  
  	5. 创建文件时加入判断，防止覆盖之前的目录
  
  	6.删除之前的个别文件，脚本执行目录随意没有要求了，但Home目录底下的Openwrt目录禁止改名移动 


++2.5版本

  	1.简化之前目录 2.代码的重写  3.一个目录方便管理 4.加入Lean_R9_source and Openwrt17.01_source"


++2.4版本

  	增加config文件保存与调用（家里机型较多的可以更省事）   此建议由@兔巴哥提供"


++2.3版本

  	合并功能按键并增加第5.HOST选项"
