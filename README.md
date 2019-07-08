# awesome-English-for-IT

## 背景

从事 IT 行业，不可避免的要阅读英文文档。有些单词经常看到，于是总结一些常用的词汇。记住了单词，往往也就记住了知识点！这对理解一些编程知识点很有帮助。

## 规则

单词：
- 音标：`[xxx]` 英式
- 例句：`xxx`
- 关联单词：`xxx`

## 单词列表

delimiter
- `[dɪ'lɪmɪtə]` n. [计] 定界符
```
join(CharSequence delimiter, Iterable<? extends CharSequence> elements)
Returns a new String composed of copies of the CharSequence elements joined together with a copy of the specified delimiter.
```

---

daemon
-  `['diːmən]` n. 守护进程；后台程序
关联: mysqld mongod

---

dump 
- `[dʌmp]`; vt 倾倒、抛弃；
- `json.dumps` 编码
- `json.loads` 解码，将一个JSON编码的字符串转换回一个Python数据结构 [src-cookbook-读写JSON数据](https://python3-cookbook.readthedocs.io/zh_CN/latest/c06/p02_read-write_json_data.html)

关联：tcpdump

---

flush 
- `[flʌʃ]`; 清除，冲，使齐平 
- `flush privileges;` MySQL 刷新权限

---

invert 
- `[ɪn'vɜːt]`; 反置，倒转 
- `grep -v/--invert-match .git` ，搜索不包括xx之后的内容

---

invoke 
- `[ɪn'vəʊk]`; 调用；祈求 
- `invoke script to do sth` 

---

metric
- `['metrɪk]` n. 度量标准

---

prefix 
- `['priːfɪks]`; n/vt 前缀

```
startsWith(String prefix)
Tests if this string starts with the specified prefix.
```

关联: suffix  `['sʌfɪks]` `endsWith(String suffix)`

---

scale
- ` [skeɪl]` CHANGE SIZE 改变大小

```
scale_out_k8s 
scale_in_k8s 
scaleunit 步长
```

---

threshold 阈值
- `['θreʃəʊld]` 临界值，阈值


---

upside 
- `['ʌpsaɪd]` n.优势，上面 
- `The upside is that the software will work` [src-Packaging Python software with pbr](https://julien.danjou.info/packaging-python-with-pbr/)

关联: downside  `/'daʊnsaɪd/` n.劣势，负面 

---

vendor 
- `['vendɔː]` 发行商或打包组织，RPM打包相关 [来源](http://hlee.iteye.com/blog/343499)

---

wildcard 
- `['waɪldkɑrd]` 通配符 
- 来源-Gitlab-设置保护分支名，可以使用通配符

## 其他

ctrl shift alt
- [src-从 Ctrl、Shift、Alt 键看中外差别（用哲学角度解释）](https://mp.weixin.qq.com/s?__biz=MzI5MDM4NTYwOA==&mid=2247486712&idx=1&sn=6c1503b9338f082e298df075bd260ae8&chksm=ec21f75fdb567e49a94b3ab0a46df255189c835acb0a8ea6b45bafd23f98026c5b2ce7269403&mpshare=1&scene=1&srcid=#rd)

## 最后

如果你有什么推荐的单词，欢迎提交 PR

## 参考

- [Linux中常用的命令都是哪些单词的缩写？](https://www.zhihu.com/question/49073893)
- [most-frequent-technology-english-words](https://github.com/Wei-Xia/most-frequent-technology-english-words) 推荐
