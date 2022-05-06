# fast_protocol_decoder_engine
一款基于llvm的高性能的解码器引擎

# 思路
设计一款类似python的描述性语言来定义协议

# 性能保证
使用llvm作为后端编译描述性语言

# 目标
提供一个高性能，高度可定制化的解码引擎

# 目录说明
pcaps       存放给test测试的数据包文件夹
scripts     存放各种协议解码描述的文件夹
test        保证解码器测试正确性的文件夹