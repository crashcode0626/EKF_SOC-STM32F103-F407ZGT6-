# EKF_SOC-STM32F103-F407ZGT6-
STM32F103+LTC6811作为采集板，F407ZGT6作为EKF SOC计算板
项目分为5个部分，STM32F103+LTC6811作为采集板,F407ZGT6作为EKF SOC计算板,上位机python采集脚本，matlab算法验证，数据结果统计分析。
上位机python采集脚本：多线程同时采集电子负载和BMS中SOC计算结果。记录在CSV文件中。
F407ZGT6作为EKF SOC计算板：串口收集采集板数据，处理好后发送到上位机
STM32F103+LTC6811采集板：采集电芯电压电流，均衡，过流过压检测，低压检测
