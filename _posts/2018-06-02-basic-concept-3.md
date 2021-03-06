---
layout: post
title:  "ERP 基本概念(三)"
date:   2018-06-02 10:51:00 +0800
categories: ERP
---
# 工作中心定义
工作中心(Working Center, 简称WC)是生产加工单元的统称，在完成
-项加工任务的同时也产生了加工成本。它是由一台或儿台功能相同的设备，
一个或多个工作人员，一个小组或一个工段，一个成组加工单元或一个装配场
地等组成的，甚至一个实际的车间也可作为一个工作中心，在这种情况下大大
简化了管理流程。

工作中心是ERP系统的基本加工单位，是进行物料需求计划与能力需求
计划运算的基本资料。物料需求计划中必须说明物料的需求与产出是在哪个工
作中心，能力需求是指哪个工作中心的能力。同时工作中心也是成本核算时成本发生的基本单元和车间生产作业核实投入与产出情况的基本单元。一个车间
由一个或多个工作中心组成，一条生产线也是由一个或多个工作中心组成。

在工艺路线文件中，一道工序或多道工序对应一个工作中心，经过工作
中心加工的物品要发生加工费用，产生加工成本，因此，可以将一个或多个工
作中心定义为一个成本中心。

## 工作中心作用

工作中心的作用有以下几种。
- 是物料需求计划(MRP)与能力需求计划(CRP)运算的基本单元。
- 是定义物品工艺路线的依据。在定义工艺路线文件前必须先确定工
作中心，并定义好相关工作中心数据。
- 是车间作业安排的基本单元。车间任务和作业进度安排到各个加工
工作中心。
- 是完工信息与成本核算信息的数据采集点。

## 关键工作中心

关键工作中心(critical work center)在ERP系统中是专门进行标识的，
关键工作中心有时也称为瓶颈工序(bottleneck) ，是运行粗能力计划的计算
对象。

根据约束理论(Theory of Constraints,简称TOC)指出关键或瓶颈资源
决定的产量，从这点意义.上说也可以帮助理解ERP系统的主生产计划为什么
只进行粗能力计划的计算。关键工作中心一般具有以下特点:
- 经常加班，满负荷工作。
- 操作技术要求高。工人操作技术要求熟练，短期内无法自由增加工
人(负荷和产量)。
- 使用专用设备，而且设备昂贵。如多坐标数控机床、波峰焊设备等。
- 受多种限制，如短期内不能随便增加负荷和产量(通常受场地、成
本等约束)。

注意，关键工作中心会随着加工工艺、生产条件、产品类型和生产产量
等条件而变化，并非一成不变， 不要混同于重要设备。

## 工作中心数据
工作中心数据包括以下几类数据。
- 工作中心基本数据。如:工作中心代码、工作中心名称、工作中心
简称、工作中心说明、替换工作中心、车问代码、人员每天班次、每班小时数、
工.作中心每班平均人数、设备数(单班、双班、三班等)及是否为关键工作中
心等。
- 工作中心能力数据。指工作中心每日可以提供的工时、机台时或可
加工完工的产品数量。工作中心的标准能力数据是由历史统计数据分析得到。
计算如下:
    工作中心能力=每日班次x每班工作时数x效率x利用率
    其中
    - 效率=完成的标准定额小时数/实际直接工作小时数:或效率=完成的标
    准定额产量/实际完成的产量;
    - 利用率=实际直接工作小时数/计划工作小时数。
    式中的工作小时可以是工人工时、机器台时或者综合考虑的有效时数。企业在
    计算每班工作时数时，应分成下列两种情况统计计算。
        - 并行(分散)作业。此类工作中心相当于一个相同加工工序的群组，
        如车床组、钳工班等，作业特点是物品在该工作中心的加工可以由该工作中心
        的任意一一个加工单元完成。
        此类工作中心的工作小时数，与工艺路线中物品在工作中心的加工工时
        定额及产品提前期都要统一，例如，每车床的日工作小时是8,那么该工作中
        心的日工作小时(能力数据)是3X8=24 小时/日。
        - 流水作业。此类工作中心的作业采用流水式作业，产品在该工作中心的加工工时即为占用该工作中心的工作时数。
- 工作中心成本数据。生产加工在工作中心每小时发生的费用，称为
工作中心费率。工作中心发生的费用有人员工资、直接能源(如电、水、气、
汽)、辅助材料(如机床用润滑油等)、设备维修费和资产折汨费等。在核定
产品的标准成本、进行产品的成本模拟及成本差异分析时都会用到工作中心成
本数据。工作中心费用的单位为元/工时或元/台时，要根据历史统计资料进行
分析得出。计算方法如下:
    工作中心直接费率工作中心日所有发生费用/工作中心日工作时数
    工作中心间接费率=分摊系数x车间发生的间接费用/工作中心日工作时数(或者按直
接费率的百分比来计算)

当能力数据、工作中心费用发生变化时，工作中心的费率也要进行修改。
存储工作中心属性的文件内容(数据文件字段)一般包括单位代码、工
作中心代码、工作中心名称、工作中心简称、 工作中心说明、替换工作中心、
车间代码、人员每天班次、每班小时数、工作中心每班平均人数、设备数、效
率、利用率、超额系数、日标准能力(按设备、按人员)、核算标志(设备1
人双能力)、投入允许误差、产出允许误差、标准工时率、优先级算法、初
始队列、班次标识(YN)、班组标识(Y/N) 、设备标识(YN)及人员标识(YN)，等等。

