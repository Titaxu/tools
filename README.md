# tools
	自己写的小工具集</br>
	beian.py                    备案查询小工具 beian.py baidu.com</br>
	baiducrawler.py             百度关键字爬取小工具 baiducrawler.py 大黑客</br>
	scanTitle.py                批量获取域名标题 scanTitle.py urls.txt 10 (线程)</br>
	bingC.py                    用bing搜索的ip指令进行ip到域名的反查 bingC.py 127.0.0.1</br>
	shodan.py                   用shadan接口查询ip开放端口，shodan.py 127.0.0.1 支持C段shodan.py 127.0.0.0/24</br>	
	getKeyword.py               获取网页内容，生成关键字，和passf0j0f项目可以一起用，生成密码字典；需要pypinyin,jieba,tldextract库
	ip138.py		    用ip138接口实现ip历史解析记录与子域名查询 ip138.py 127.1.1.1或github.com 
	dns.py			    copy以前乌云的代码。加一个A记录xxxx.domain.com指向服务器ip,再加一个ns记录dnslog.domain.com,指向xxxx.domain.com。test.dnslog.domain.com
	domain2ip.py		    使用socket.gethostbyname 查询域名对应ip。domain2ip.py domains.dict
	portScan.py		    如果目标是windows且将所有未开放的端口全转发到一个端口上，NMAP将显示说有端口开放。portScan.py -t 127.0.0.1-100 -p 80,8000-10000 -n 100  
	/dirScan		    目录扫描项目
	/passf0j0f                  根据关键字生成密码</br>
	/cmd_bash                   常用的命令语句	
	/workflows                  Alfred workflows插件</br>
		/strencode.py           alfred workflows,字符编码/解码小插件,支持Md5,Base64,Hex,ASCII的编码与解码</br>

