DataPie

功能：支持SQL server、SQLite、ACCESS数据库的导入、导出、存储过程调用，支持EXCEL2007、EXCEL2003、ACCESS2007、
CSV文件导入数据库，支持EXCEL、CSV文件方式导出，支持数据拆分导出及自定义SQL查询与导出。

作者及开发背景：yfl8910，从事财务管理工作，主要是出具集团的内部财务报表，随着公司精细化管理的需求，管理报表的数据量急速增长，
依赖EXCEL加工处理数据已经变得极为困难，因此团队全面转向关系数据库进行数据处理，为减少财务人员使用数据库的难度，因此专门针对财务
报表核算需要，开发了该工具。目前，我月度报表处理的数据量超过5G，最大的单次运算量记录接近千万，该工具主要发挥的作用就是将收集到的数据，
导入SQL SERVER数据库，进行报表运算，并且输出各类财务报表，对于几十万级的数据输入、输出基本上能够轻松应付。

联系方式：yfl8910@qq.com

更新
DataPieV3.5  2013年1月25日
大幅提升CSV方式导数效率，增加异步方式操作，防止界面假死，运行环境升级到.NET Framework 4.5。

DataPieV3.6  2013年5月16日
修正异步情况下，导入导出无法捕获错误的bug，添加自定义sql双击自动生成sql的事件。添加遍历文件夹下所有csv文件，并合并到excel中。

DataPieV3.6.1  2013年7月24日
添加批量csv导出功能，自定义sql导出，添加csv方式导出。

DataPieV3.6.2  2013年9月3日
添加数据分拆功能。

DataPieV3.7  2014年5月30日
支持SQLite,移除对ORACLE的支持，删除CSV转EXCEL的功能，大幅提升EXCEL导入ACCESS的效率。