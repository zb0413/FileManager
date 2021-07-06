# FileManager
功能：1.导出文件信息 2.查找重复文件（基于大小和修改时间的判断方式，
以及基于文件 hash 值的判断方式）3.文件还原与备份（增量备份、文件同步、
文件还原）4.根据样本或者记录删除文件或者还原文件 5.一键清空目录下所有空
文件夹 6.搜索文件或者文件夹（可搜索隐藏文件）7.拷贝目录结构（导出到文件、
从文件恢复目录结构、导出目录结构到新目录下）8.比对文本文件内容（比对文
章、文档、代码的差异并将结果输出，可批量比对）9.计算文件 hash 值 10.校
对字符串（校对两个字符串是否一致，包含忽略大小写，前后空格，以及忽略所
有空格）11.提取视频帧图像（可以批量快速提取指定视频的某一帧或者某一秒
的图像）12.查找相似图片（根据算法计算图片的相似度，并将满足相似度阈值
的图片移动到指定目录，可以有效找出不同分辨率、不同大小甚至是经过裁剪或
者加过水印的相似图片）13.查找相似视频（比对视频帧图像的相似度找出相似
视频并导出）14.以图搜图（选中图片在另一任意目录中搜索与之相似的图片）
15.以视频搜相似视频（选中视频在另一任意目录中搜索与之相似的视频，主要
用于找出内容一样但是分辨率不同，或者内容一样只是水印有差异的视频）16.
批量重命名 17.合并视频（将选中的视频合并为一个视频，可以指定视频帧率）
18.裁剪视频（集合了之前 video_cut 项目的代码）19.批量裁剪视频（选中多个
视频批量裁剪，用于去除视频片头片尾特别好用）20.提取音频和转换音频格式
（可以从视频中提取音频，也可以进行音频格式转换，可以指定音频帧率格式，
不一定支持所有音频格式）21.找出损坏或者不完整的视频（基于 ffmpeg）22.
获取时间戳（时间与时间戳之间相互转换）以及修改文件的时间戳
所有的文件删除、文件更新操作进行防呆保护，最大限度保证数据安全！所
有操作都有日志，方便追溯和还原。涉及程序配置内容修改的操作会有权限验证


以下为部分程序功能界面：
![文件去重hash方式](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E6%96%87%E4%BB%B6%E5%8E%BB%E9%87%8D%EF%BC%88hash%E6%A8%A1%E5%BC%8F%EF%BC%89%202021-07-07_044228.jpg)
![计算hash值](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E8%AE%A1%E7%AE%97hash%E5%80%BC%202021-07-07_051638.jpg)
![以图搜图](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E4%BB%A5%E5%9B%BE%E6%90%9C%E5%9B%BE%202021-07-07_052708.jpg)
![搜索文件](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E6%90%9C%E7%B4%A2%E6%96%87%E4%BB%B6%202021-07-07_045750.jpg)
![文件同步还原](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E6%96%87%E4%BB%B6%E5%90%8C%E6%AD%A5%E4%B8%8E%E5%A4%87%E4%BB%BD%202021-02-18_154423.jpg)
![视频裁剪](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E8%A7%86%E9%A2%91%E8%A3%81%E5%89%AA%202021-07-07_054637.jpg)
![查找重复文件](https://github.com/codecyou/FileManager/blob/main/FileManager%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/%E6%9F%A5%E6%89%BE%E9%87%8D%E5%A4%8D%E6%96%87%E4%BB%B6%202021-07-07_043605.jpg)
