# ��ӭʹ�� Markdown���߱༭�� MdEditor

**Markdown��һ���������ġ�������ԡ�**


![markdown](https://www.mdeditor.com/images/logos/markdown.png "markdown")


Markdown��һ�ֿ���ʹ����ͨ�ı��༭����д�ı�����ԣ�ͨ���򵥵ı���﷨��������ʹ��ͨ�ı����ݾ���һ���ĸ�ʽ������������ʹ���׶���д�Ĵ��ı���ʽ��д�ĵ���Ȼ��ת���ɸ�ʽ�ḻ��HTMLҳ�棬Markdown�ļ��ĺ�׺�����ǡ�.md��


## MdEditor��һ�����߱༭Markdown�ĵ��ı༭��

*MdEditor��չ��Markdown�Ĺ��ܣ����񡢽�ע����ǶHTML�ȵȣ�����ʹ��Markdownת���ɸ���ĸ�ʽ���͸��ḻ��չʾЧ������Щ����ԭ����Markdown�в��߱���*

> Markdown��ǿ���бȽ���������Markdown Extra��MultiMarkdown�� Maruku�ȡ���Щ�����汾Ҫô���ڹ��ߣ���~~Pandoc~~��Pandao��Ҫô������վ����GitHub��Wikipedia�����﷨�ϻ������ݣ�����һЩ�﷨����ȾЧ�����иĶ���

MdEditorԴ��Pandao��JavaScript��Դ��Ŀ����Դ��ַ[Editor.md](https://github.com/pandao/editor.md "Editor.md")������MIT��ԴЭ�����ɷ�Χ�ڽ������Ż�������Ӧ����û�Ⱥ��������������markdown��Դ�༭��ԭ����Pandao�¾���


![Pandao editor.md](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png "Pandao editor.md")



## MdEditor�Ĺ����б���ʾ

# ����H1

## ����H2

### ����H3

#### ����H4

##### ����H5

###### ����H5

### �ַ�Ч���ͺ��ߵ�
----

~~ɾ����~~ <s>ɾ���ߣ�����ʶ��HTML��ǩʱ��</s>

*б����*      _б����_

**����**  __����__

***��б��*** ___��б��___

�ϱ꣺X<sub>2</sub>���±꣺O<sup>2</sup>

**��д(ͬHTML��abbr��ǩ)**
> �������ĵ��ʻ�������д��ʽ��ǰ���ǿ���ʶ��HTML��ǩʱ����Ĭ�Ͽ���

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.
### ���� Blockquotes

> �����ı� Blockquotes

���õ����ڻ�� Blockquotes

> ���ã������Ҫ����հ׻���`��<br />��ǩ`���ڲ��봦�ȼ����������ϵĿո�Ȼ��س����ɣ�[��ͨ����](https://www.mdeditor.com/)��

### ê�������� Links
[��ͨ����](https://www.mdeditor.com/)
[��ͨ���Ӵ�����](https://www.mdeditor.com/ "��ͨ���Ӵ�����")
ֱ�����ӣ�<https://www.mdeditor.com>
[ê������][anchor-id]
[anchor-id]: https://www.mdeditor.com/
[mailto:test.test@gmail.com](mailto:test.test@gmail.com)
GFM a-tail link @pandao
�����ַ�Զ����� test.test@gmail.com  www@vip.qq.com
> @pandao

### �����Դ������ Codes

#### ���ڴ��� Inline code


ִ�����`npm install marked`

#### �������

�������ĸ��ո�Ҳ��Ϊʵ������ `<pre>` Ԥ��ʽ���ı� ( Preformatted Text ) �Ĺ��ܡ�

    <?php
        echo "Hello world!";
    ?>
Ԥ��ʽ���ı���

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS����
```javascript
function test() {
	console.log("Hello world!");
}
```

#### HTML ���� HTML codes
```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <meta name="keywords" content="Editor.md, Markdown, Editor" />
        <title>Hello world!</title>
        <style type="text/css">
            body{font-size:14px;color:#444;font-family: "Microsoft Yahei", Tahoma, "Hiragino Sans GB", Arial;background:#fff;}
            ul{list-style: none;}
            img{border:none;vertical-align: middle;}
        </style>
    </head>
    <body>
        <h1 class="text-xxl">Hello world!</h1>
        <p class="text-green">Plain text</p>
    </body>
</html>
```
### ͼƬ Images

ͼƬ������ (Image + Link)��


[![](https://www.mdeditor.com/images/logos/markdown.png)](https://www.mdeditor.com/images/logos/markdown.png "markdown")

> Follow your heart.

----
### �б� Lists

#### �����б����ţ�Unordered Lists (-)

- �б�һ
- �б��
- �б���

#### �����б��Ǻţ�Unordered Lists (*)

* �б�һ
* �б��
* �б���

#### �����б��Ӻź�Ƕ�ף�Unordered Lists (+)
+ �б�һ
+ �б��
    + �б��-1
    + �б��-2
    + �б��-3
+ �б���
    * �б�һ
    * �б��
    * �б���

#### �����б� Ordered Lists (-)

1. ��һ��
2. �ڶ���
3. ������

#### GFM task list

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2

----

### ���Ʊ�� Tables

| ��Ŀ        | �۸�   |  ����  |
| --------   | -----:  | :----:  |
| �����      | $1600   |   5     |
| �ֻ�        |   $12   |   12   |
| ����        |    $1    |  234  |

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |

----

#### ������� HTML Entities Codes

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

[========]

### Emoji���� :smiley:

> Blockquotes :star:

#### GFM task lists & Emoji & fontAwesome icon emoji & editormd logo emoji :editormd-logo-5x:

- [x] :smiley: @mentions, :smiley: #refs, [links](), **formatting**, and <del>tags</del> supported :editormd-logo:;
- [x] list syntax required (any unordered or ordered list supported) :editormd-logo-3x:;
- [x] [ ] :smiley: this is a complete item :smiley:;
- [ ] []this is an incomplete item [test link](#) :fa-star: @pandao;
- [ ] [ ]this is an incomplete item :fa-star: :fa-gear:;
    - [ ] :smiley: this is an incomplete item [test link](#) :fa-star: :fa-gear:;
    - [ ] :smiley: this is  :fa-star: :fa-gear: an incomplete item [test link](#);

#### ��б�� Escape

\*literal asterisks\*

[========]
### ��ѧ��ʽ TeX(KaTeX)

$$E=mc^2$$

���ڵĹ�ʽ$$E=mc^2$$���ڵĹ�ʽ�����ڵ�$$E=mc^2$$��ʽ��

$$x > y$$

$$\(\sqrt{3x-1}+(1+x)^2\)$$

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

���й�ʽ��

```math
\displaystyle
\left( \sum\_{k=1}^n a\_k b\_k \right)^2
\leq
\left( \sum\_{k=1}^n a\_k^2 \right)
\left( \sum\_{k=1}^n b\_k^2 \right)
```
```katex
\displaystyle
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        }
    }
```
```latex
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
```
### ��ҳ�� Page break

> Print Test: Ctrl + P

[========]

### ��������ͼ Flowchart

```flow
st=>start: �û���½
op=>operation: ��½����
cond=>condition: ��½�ɹ� Yes or No?
e=>end: �����̨

st->op->cond
cond(yes)->e
cond(no)->op
```
[========]

### ��������ͼ Sequence Diagram

```seq
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```
### End