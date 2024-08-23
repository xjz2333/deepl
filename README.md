# 需求文件
项目需要的包均在 requirement.txt中
# 配置文件  
配置解释：    
            task对应检测任务类别：air sea sky    
            framework对应深度学习框架：pytorch tensorflow paddle  
            action对应执行操作：训练（train） 转换（convert） 推理（inference）     
            **注意**：action里面有detect（训练后检测），但是由于部分task及framework没有。改功能仅作为开发时测试使用。  
                  ![image text](https://github.com/xjz2333/deepl/blob/main/%E9%85%8D%E7%BD%AE.PNG)
# 项目运行
通过main.py运行。配置文件在check/config/tool.json，若要调用对应模块在里面修改便可！  

***注意***：目前已经开发完成的版块有：Tarin为训练模块，Convert为转换模块（onnx）,Inference为onnx模型推理模块
            ![image text](https://github.com/xjz2333/deepl/blob/main/%E5%AE%8C%E6%88%90%E6%A8%A1%E5%9D%97.png)

