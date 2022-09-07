## day3 学习vim

## 操作符+动作

## 操作符（d/c/y）
1. d 删除
d+j: 删除当前这行以及下一行，一共两行
d+k: 删除当前这行以及上一行，一共两行
d+h: 删除当前光标(左侧)左边的一位
d+l: 删除当前光标(左侧)右边的一位
d+L: 删除当前光标(左侧)到末尾范围的字符
d+H: 删除当前光标(左侧)到开头范围的字符


2. c 删除并进入到insert模式(意思是可取)
c+j
c+k
c+h
c+l
c+H
c+L
3. y 复制


## 基于单词字符的移动
（左-->右）
e: 来到单词的结尾
w: 来到单词的开头
（右-->左）
b: 移动到上一个单词的开头
ge: 移动到一个单词的结尾

## 组合
cw: 删除当前单词
ea: 在当前单词结尾出添加


###
e: 来到单词的结尾（左=>右）
w: 来到单词的开头（左=>右）
b: 来到单词的开头（右=>左）
ge: 来到单词的结尾（右=>左）

### 进入insert模式的快捷键
1. i : 停在光标的前面
2. a : 停在光标的后面
3. o : 在当前行的下面嵌入 
4. O : 在当前行的上面嵌入
5. 操作符c + 键 组合方式删除时

```js
function listen() {
  aaaaaaaaa
  bbbbbbbbb
  ddddddddd
  eeeeeeeee
  aaaaaaaaa
  aaaaaaaaa
  aaaaaaaaa
  console.log(3333);
  console.log(4444);
  bbbbbbbbb
  console.log(555);
  ccccccccc
  console.log(44);
  ddddddddd
  console.log(555);
  eeeeeeeee
  console.log(666);
  fffffffff
  console.log(777);
  hhhhhhhhh
  console.log(00000);
  iiiiiiiii
  console.log(99999);
  ggggggggg
  console.log(09090909);
}

```