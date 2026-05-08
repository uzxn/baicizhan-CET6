# baicizhan-CET6

> 本项目基于 [lyc8503/baicizhan-word-meaning-API](https://github.com/lyc8503/baicizhan-word-meaning-API) 整理，将百词斩六级词汇提取为独立 JSON 文件，每个单词一个文件，可通过 HTTP 直接访问。

## 目录结构

```
words/
├── abandon.json
├── ability.json
└── ...
list.json
```

## 单词 JSON 示例

```
{
  "word": "abandon",
  "accent": "/əˈbændən/",
  "mean_cn": "v.放弃；舍弃，废弃",
  "mean_en": "to leave somebody, especially somebody you are responsible for, with no intention of returning",
  "sentence": "The girl has totally abandoned the use of computer for her homework.",
  "sentence_trans": "这个女生彻底放弃使用电脑做作业了。",
  "sentence_phrase": "",
  "word_etyma": "ab去 + ban被命令 + don表名词 → 一直被别人命令，放弃自我 → abandon抛弃，放弃 "
}
```

## API 使用

**通过 GitHub Raw 访问：**

```
https://raw.githubusercontent.com/uzxn/baicizhan-CET6/main/words/abandon.json
```

**通过 jsDelivr CDN 访问（推荐）：**

```
https://cdn.jsdelivr.net/gh/uzxn/baicizhan-CET6/words/abandon.json
```

**获取单词列表：**`list.json` 包含所有单词的索引。
