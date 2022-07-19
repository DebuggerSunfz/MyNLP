- [目录](#目录)
- [项目概述](#项目概述)
- [涉及技术](#涉及技术)
- [使用方法](#使用方法)
- [Tips](#tips)
# 目录
> 代码结构：
> 
    +---data_util
    |   +---logs
    +---static
    |   +---css
    |   |   \---font
    |   +---data
    |   +---font
    |   +---images
    |   \---js
    +---templates //存放html文件
    +---test_data  //测试文本
    +---text_analysis_tools   //调用的api
    |   \---api
    +---sql.py   //数据库文件
    +---main.py   //后端代码
    +---model.py   //深度学习模型
    +---eval.py    //使用训练好的模型，接口在main.py调用
    +---data_helper.py  
    +---beam_seacher.py
    +---train_util.py

# 项目概述
> 这是一个关于自然语言处理的项目，鉴于要开发一个系统方便和用户进行交互，我们将文本数据可视化的一些知识加以结合运用。
> - 主线任务涉及使用深度学习模型实现文章标题和摘要生成。
> - 目前支线任务包括：文章热词/关键词提取（南丁格尔图/气泡图）、主题抽取（树状图）、知识图谱（网状图）
# 涉及技术
>Flask+ajax+Echarts
# 使用方法
```python  
pip install -r requirements.txt 
```
```
python main.py
```
# Tips
- 模型得自己重新训练
- 使用live Server打开
- 或许清除浏览器缓存可以解决你的一些莫名其妙的问题
