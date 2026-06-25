# English Keyboard Spelling Trainer 5000

大题库版英文键盘拼写训练软件。

## 当前题量

- 10 个训练分类
- 5000 个单词/短语拼写题
- 2000 个句子拼写题

说明：本版本为了满足大题量训练，采用“分类词根 + 场景词组 + 句子模板”的方式生成题库，适合键盘拼写和输入肌肉记忆训练。若需要完全人工精选词库，可以继续替换 `src/data/index.js` 中的数据生成逻辑。

## 目录结构

```text
src
├── main.jsx
├── styles.css
└── data
    └── index.js
```

## 运行

```bash
npm install
npm run dev
```

## 构建

```bash
npm run build
```

## 题库位置

题库位于：

```text
src/data/index.js
```

主程序 `src/main.jsx` 只负责读取题库，不再写死具体题目。
