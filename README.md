# easy-for-webscan
根据WebBatchRequest图形化二次开发  
1增加了指纹识别模块，可识别大概上千条指纹  
2增加了IP段处理,支持C段和B段处理  
3增加了301处理  
4增加了去重空节点的功能，可节省内存消耗,推荐勾选此选项  
5修改了在Jtable中排序后浏览器打开索引错误

#实际效果
<img width="1204" alt="图片" src="https://user-images.githubusercontent.com/86775430/124108013-62a81980-da98-11eb-93b6-bc1c29324ce8.png">

<img width="1211" alt="图片" src="https://user-images.githubusercontent.com/86775430/124109097-5e303080-da99-11eb-8475-0189b1be059d.png">


去除空节点，建议勾选此选项，可节约内存
<img width="1208" alt="图片" src="https://user-images.githubusercontent.com/86775430/124411298-d5f2a980-dd7e-11eb-9a0b-faac2d5aad87.png">
在相同目标扫描下，勾选前后用5线程扫描对比，锯齿形为未勾选空节点，线性的为勾选去空节点
<img width="546" alt="图片" src="https://user-images.githubusercontent.com/86775430/124412472-2ff46e80-dd81-11eb-95ab-3d7e02facb21.png">

参考了
https://github.com/ScriptKid-Beta/WebBatchRequest 以及 AlliN.py(未找到github地址)
