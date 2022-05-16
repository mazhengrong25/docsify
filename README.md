<!--
 * @Description:
 * @Author: mzr
 * @Date: 2022-05-06 15:03:52
 * @LastEditTime: 2022-05-11 09:28:39
 * @LastEditors: mzr
-->
<!-- 副标题未实现 -->

### 分类 {忽略副标题}

包行内代码`this is ****`使用反引号

---

<!-- 引用内容 在整个段落前面加 > -->

> 引用内容

> 1. This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> 2. consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> 3. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 4. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> 5. id sem consectetuer libero luctus adipiscing.
> 6. 有序列表 段落开头是 一个制表符 (数字+英文句点)

- [内嵌文件](/charty.md ":include :type=code")

<!--  ``` 代码块 ```  -->

```
.childPage {
  background-color: beige;
  display: flex;
  flex-direction: column;
}
.childPage .test_clip {
  width: 100px;
  height: 100px;
  background-color: pink;
  border: 2px solid hsla(0, 0%, 100%, 0.5);
  /* background-clip: border-box; */
  /* background-clip: padding-box; */
  background-clip: content-box;
}
.childPage .test_hover {
  height: 50px;
  background-color: blanchedalmond;
  text-align: center;
  /* 悬停效果 */
  position: sticky;
  top: 0;
}
```

<!-- 引号内作为提示 -->

##### [baidu](http://baidu.com/ "链接")

###### [图表](/charty.md "练习")
