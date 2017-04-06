**************重要说明******************************
*为了减少程序的体积程序采用了UPX压缩                  *
*大部分的安全软件会拦截,软件不带毒的                  *
*我编译后就把MD5 HASH值放进云                        *
*大小：	397, 312 字节                              *
*修改时间：2017-04-06 09:09:25                      *
*MD5：	6FDCB79BD877421406AB8F0EDE97E4A2           *
*SHA1：	AE28F475D7BECDB9711112AE96177A4983F9A03D   *
*CRC32：4807BAFD                                   *
****************************************************

网盘路径 http://pan.baidu.com/s/1hrO3FDi#list/path=%2F

请先配置好相关数据  当前目录下的cfg.xml(建议用像notepad++这个的编辑工具打开编辑)
在点下面的⊙按钮重新加载 
点下面的E按钮退出程序
按ctrl+shift+1显示隐藏界面
按ctrl+shift+2 设置取消鼠标穿透
按ctrl+shift+<(>) 降低(提高)窗口透明度 
按ctrl+shift+alt+x  退出软件

点击股票名称可以更改股票代码
按C快速清空当前股票代码
按s快速输入600
按z快速输入000

点击股票名称后面的可以显示日k等详情。
快捷键:
1 分时线
2 日K线
3 周K线
4 月K线 
<item NO = 股票代码 Min =提醒最低价 Max = 提醒最高价   >
	<Price count =持股数 p = 成本价 time="购买时间"/>
</item>
<item NO="sh600664" Min="8.25" Max="8.45"/> 

有什么建议或者问题请给我发邮件  canye2008ATgmail.com

如

<?xml version="1.0" encoding="UTF-8"?>
<set> 
    <color crMax="227,23,13" crMin="0,128,0" crMaxEx="178,34,34" crMinEx="0,128,0" Brokerage="0.00025" /> 
    <stock> 
 
        <item NO="600569" Min="3.45" Max="3.65" >
            <Price p="3.50" count="200" time="2017-03-17"/>
            <Price p="3.41" count="200" time="2017-03-20"/>
        </item>
        <item NO="000961" Min="8.36" Max="9.05">
            <Price p="8.37" count="2400" time="2017-03-22" />
        </item>
        <item NO="600664" Min="7.60" Max="8.05">
             <Price p="7.77" count="5000" time="2017-03-27" /> 
        </item>
		
		<item NO="sh600074" Min="13.30" Max="14.05"/>
		 
		<item NO="002437" Min="8.28" Max="8.45" />
		<item NO="000776" Min="17.28" Max="17.80" />
		
        <item NO="sh000001" comment="上证指数"/>  
    </stock>
</set>