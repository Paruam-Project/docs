# 百度网盘URL跳转API使用文档

FAQ：

- [x] 隐藏明显链接
- [ ] 隐藏地址栏URL
- [ ] 跳转URL加密

使用方法：

`源链接：https://pan.baidu.com/s/1He9_7lhX3Q6gYfWluOhqRQ`

提取`/s/`后面的字符串`1He9_7lhX3Q6gYfWluOhqRQ`并拼接在api后面

### API

```text
https://paruam-project.github.io/api/getURL
```

请保证getURL的大小写正确

| 参数 |              实例              | 可选 |                             实例                             |
| :--: | :----------------------------: | :--: | :----------------------------------------------------------: |
| url  | 你的百度网盘链接中提取的标识符 |  否  | https://paruam-project.github.io/api/getURL?url=1He9_7lhX3Q6gYfWluOhqRQ |
|      |                                |      |                                                              |

