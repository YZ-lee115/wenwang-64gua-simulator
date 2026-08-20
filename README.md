# 文王六十四卦金钱卦模拟器
# Wen Wang 64 Hexagrams Coin Divination Simulator

> 一个基于传统金钱卦起卦方式制作的 Windows 模拟程序。  
> A Windows simulator based on the traditional Chinese coin divination method.

---

## 📖 简介 | Introduction

《周易》是中国传统文化的重要经典之一，其中八卦与六十四卦体系具有重要地位。

六十四卦由八卦两两重叠组合而成，每一卦都有对应的卦象、卦名、卦辞以及传统解释。

传统金钱卦是一种以铜钱或硬币投掷结果作为取象方式的起卦方法，通过硬币正反面的组合形成六爻卦象，再根据卦象对应到六十四卦。

本项目将这一传统起卦方式进行程序化模拟，通过计算机模拟硬币正反面，并结合用户输入的信息及系统时间，生成对应的卦象与传统解卦内容。

**The I Ching (《周易》, Book of Changes) is one of the most important classics of traditional Chinese culture.**

The Sixty-Four Hexagrams are formed by combining the Eight Trigrams, with each hexagram having its own name, image, traditional texts, and interpretations.

Traditional Chinese coin divination uses the results of tossing coins to form six lines and determine the corresponding hexagram.

This project provides a digital simulation of this traditional divination method. It simulates coin results using a computer and generates a corresponding hexagram and traditional interpretation based on the simulated results, user information, and system time.

---

## 🪙 起卦方法 | Traditional Method

传统金钱卦的一般流程如下：

1. 占卜者净手静心，思考所问之事。
2. 将铜钱或硬币放在手中，集中精神思考所问问题。
3. 摇动硬币，使其自然翻动。
4. 根据硬币正反面的组合确定一爻。
5. 连续进行六次，按照**自下而上**的顺序形成六爻。
6. 根据六爻组合确定对应的六十四卦，并参考传统卦辞及相关解释。

The traditional coin divination process can be summarized as follows:

1. Clear the mind and focus on the question.
2. Hold the coins while concentrating on the subject of inquiry.
3. Shake and toss the coins naturally.
4. Determine one line according to the combination of heads and tails.
5. Repeat the process six times, forming the six lines **from bottom to top**.
6. Identify the corresponding hexagram and refer to traditional interpretations.

---

## 💻 程序功能 | Features

### 🪙 金钱卦模拟 | Coin Divination Simulation

程序通过随机模拟硬币正反面，代替实际铜钱投掷过程。

The program simulates the heads and tails of coins digitally instead of using physical coins.

### ☯️ 六十四卦判断 | Hexagram Identification

根据生成的卦象自动匹配对应的六十四卦。

Automatically identifies the corresponding hexagram based on the generated lines.

### 👤 用户信息 | User Information

程序支持输入：

- 姓名 | Name
- 出生日期 | Date of Birth
- 性别 | Gender

### 🕐 时间信息 | Time Information

程序自动获取当前系统时间，并显示对应的农历及干支信息。

The program automatically retrieves the current system time and displays the corresponding Chinese lunar calendar and traditional Heavenly Stems and Earthly Branches information.

### 📜 卦象与解卦 | Interpretation

程序根据生成结果显示：

- 卦象
- 卦序
- 卦名
- 吉凶等级
- 对应的传统解卦内容

The generated result may include:

- Hexagram pattern
- Hexagram number
- Hexagram name
- Traditional fortune classification
- Traditional interpretation

---

## 🧭 说明 | Project Notes

- 本应用是一个个人兴趣应用，旨在探索传统文化与现代计算机程序之间的结合。
- This is a personal interest project exploring the combination of traditional Chinese culture and modern software development.

- 欢迎对《周易》、六十四卦以及相关程序开发感兴趣的朋友交流。
- Feedback and discussion are welcome from anyone interested in the I Ching, the Sixty-Four Hexagrams and related software development.
