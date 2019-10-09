# 第二次作业 #
## 一、数据来源 ##
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
      <td>19.50%</td>
      <td>19.84%</td>
      <td>19.04%</td>
      <td>18.66%</td>
   </tr>
</table>
### 结论 ###
总的来看，2012年以来，我国的每年GDP季度增速，总体呈现出下降并趋于平稳的趋势，今年稳定在10%左右。
