# 第二次作业 #
## 一、数据来源 ##
问题：我国还有哪些关于公共数据开放的条例或法规？国内外有哪些政府开放数据平台？
### 我国关于公共数据开放的条例或法规 ###
[《政务信息资源共享管理暂行办法》](https://baike.baidu.com/item/%E6%94%BF%E5%8A%A1%E4%BF%A1%E6%81%AF%E8%B5%84%E6%BA%90%E5%85%B1%E4%BA%AB%E7%AE%A1%E7%90%86%E6%9A%82%E8%A1%8C%E5%8A%9E%E6%B3%95/19974171?fr=aladdin)  
[《贵阳市政府数据共享开放实施办法》](http://www.gywb.cn/content/2018-05/02/content_5709098.htm)  
[《上海市公共数据开放暂行办法》](http://www.shanghai.gov.cn/nw2/nw2314/nw2319/nw41893/nw42230/u21aw1401306.html)  
### 政府开放数据平台 ###
#### 国内 ####
[中华人民共和国中央人民政府数据公开](http://www.gov.cn/shuju/)  
[中国国家统计局](http://www.stats.gov.cn)  
[中国人民银行数据](http://www.pbc.gov.cn/diaochatongjisi/116219/index.html)  
[中国银行业监督管理委员会数据](http://www.pbc.gov.cn/jinrongshichangsi/147160/147171/index.html)  
[中国经济数据库](https://www.ceicdata.com/zh-hans/products/china-economic-database)  
[中国金融信息网数据](http://dc.xinhua08.com/)  
[中国互联网信息安全中心数据](https://www.cnnic.net.cn/hlwfzyj/hlwxzbg/)  
[山东公共数据开放网](http://data.sd.gov.cn/)  
[德州市公共数据开放网](http://dzdata.sd.gov.cn/)  
[济宁市公共数据开放网](http://jindata.sd.gov.cn/)  
[浙江省公共数据开放网](http://data.zjzwfw.gov.cn/jdop_front/index.do)  
[成都市公共数据开放平台](http://www.cddata.gov.cn/)  
[厦门市大数据开放平台](http://data.xm.gov.cn/)  
信源：  
[知乎](https://www.zhihu.com/question/19969760)  
[探马科技：最全的中国开放数据(Open Data)及政府数据开放平台汇总](http://www.tanmer.com/blog/451)  
#### 国外 ####
[纽约政府开放数据平台](https://opendata.cityofnewyork.us/)
[美国官网数据超市](https://www.data.gov/)
[新加坡政府开放数据平台](https://data.gov.sg/)
[休斯顿市开放数据门户网站](http://data.houstontx.gov/)
[美国人口普查局](http://usgovxml.com/)

信源：
[探马科技：【Open Data】国外开放数据中心及政府数据开放平台汇总](http://www.tanmer.com/blog/537)

## 二、计算增速 ##
题目：	在国家统计局数据库找到全国GDP数据，回答：2012-2018年各季度GDP增速（列出选取的统计指标、数据页面、计算步骤及答案）
### 前期准备 ###
通过查阅资料得知，增长率的计算分为同比（与去年同期相比）和环比（和上一期相比）两个计算方法，而“增速”指的是同比增长率，因此是比较每年同期的GDP。
### 筛选数据 ###
进入国家统计局网站，选择【季度数据】分类http://data.stats.gov.cn/easyquery.htm?cn=B01  
由于需要计算2012年季度增速，因此需要2011年的数据，于是在【时间】的筛选窗口输入条件【2011-】（-需在半角输入模式下输入），获得2011年以来，每年各个季度的GDP值，为了方便观看，在【报表管理】-【编辑】中选择只显示“国内生产总值_当季值”的数据  
![](https://github.com/Chenyu-Li008/Homework/blob/master/1.jpg)
![](https://github.com/Chenyu-Li008/Homework/blob/master/2.jpg)
### 数据页面 ###
整理如下（顺序为第四季度-第三季度-第二季度-第一季度）  
![](https://github.com/Chenyu-Li008/Homework/blob/master/3.jpg)
### 计算步骤 ###
我选择使用EXCEL进行数据计算  
新建一个EXCEL，将数据导入  
以2018年的增速计算为例，按照公式：同比增速%=（当期-去年同期）/去年同期*100%  
在EXCEL里输入公式=(B2-B3)/B3*100%，得出增速  
![](https://github.com/Chenyu-Li008/Homework/blob/master/4.jpg)
得到增速，保留四位数字，同理得到其他六年的增速  
![](https://github.com/Chenyu-Li008/Homework/blob/master/5.jpg)
### 计算结果 ###
<table>
   <tr>
      <td></td>
      <td>第四季度增速</td>
      <td>第三季度增速</td>
      <td>第二季度增速</td>
      <td>第一季度增速</td>
   </tr>
   <tr>
      <td>2018</td>
      <td>9.15%</td>
      <td>9.38%</td>
      <td>10.10%</td>
      <td>10.32%</td>
   </tr>
   <tr>
      <td>2017</td>
      <td>10.71%</td>
      <td>10.82%</td>
      <td>10.73%</td>
      <td>11.45%</td>
   </tr>
   <tr>
      <td>2016</td>
      <td>9.47%</td>
      <td>7.70%</td>
      <td>7.15%</td>
      <td>6.89%</td>
   </tr>
   <tr>
      <td>2015</td>
      <td>6.40%</td>
      <td>6.61%</td>
      <td>7.67%</td>
      <td>7.36%</td>
   </tr>
   <tr>
      <td>2014</td>
      <td>7.40%</td>
      <td>8.33%</td>
      <td>8.64%</td>
      <td>8.36%</td>
   </tr>
   <tr>
      <td>2013</td>
      <td>10.51%</td>
      <td>10.23%</td>
      <td>9.29%</td>
      <td>10.30%</td>
   </tr>
   <tr>
      <td>2012</td>
      <td>10.00%</td>
      <td>9.11%</td>
      <td>10.45%</td>
      <td>12.34%</td>
   </tr>
</table>
### 结论 ###
总的来看，2012年以来，我国的每年GDP季度增速，总体呈现出下降并趋于平稳的趋势，今年稳定在10%左右。
