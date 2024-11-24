# SOC_UKF_User_Define
基于UKF原理，在simulink中搭建用于电池SOC计算的UKF模块导出为Matlab2017a版本：
1. 以simulink基本模块搭建UKF算法，用于计算电池SOC；
2. 电池为NCM电池，标称容量为2.9Ah，测试工况为UDDS工况，由于数据为电池初期数据，实际可用容量为3.1Ah左右；
3. 电池模型为二阶RC模型；
4. 电池模型参数采用的式AFFRLS算法辨识后取平均值；
5. 真值采用Ah积分法配合真实容量计算。
