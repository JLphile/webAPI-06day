

# webAPIs-06day

1.下面关于正则表达式说法正确的是？（ABCD） 【多选题】

- A. 正则表达式是用于匹配字符串中字符组合的模式
- B. 可以用于表单验证(匹配)
- C. 可以用于过滤敏感词(替换)
- D. 可以用于字符串中提取我们想要的部分(提取)

2.下面声明正则表达式正确的是? （B）

- A. const 变量名 = \表达式\
- B. const 变量名 = /表达式/
- C. const 变量名 = 表达式
- D. const 变量名 = '表达式'

3.下面哪个方法可以用于检测正则表达式与指定的字符串是否匹? （C）

- A. text()
- B. has()
- C. test()
- D. exec()

4.下列关于正则中特殊字符描述正确的是( )? （） 【多选题】

- A： ^和$符号为定界符，用于表示匹配以什么开头或以什么结尾
- B： []表示字符类，用于匹配多个选项中的任意1个
- C： \d和\D是预定义字符，是一种简写字符
- D： *、?、+是量词符，用于表示字符出现的次数

5.关于正则表达式声明6位数字的邮编，以下代码正确的是？（）

- A： const reg = /\d6/
- B： const reg = \d{6}\
- C： const reg = /\d{6}/
- D： const reg = /d6/

5.下列选项能够将字符串str中的"java"、"Java"、"JAVA"替换为"前端"的是（） 【多选题】

- A 

  - ```html
    let str='javascript和JAVA是两个不同的语言，Javascript诞生于1995年'
    str = str.replace(/java/i,'前端')
    console.log(str)
    ```

  

- B

  - ```html
    let str='javascript和JAVA是两个不同的语言，Javascript诞生于1995年'
    str = str.replace(/java/gi,'前端')
    console.log(str)
    ```

- C

  - ```html
    let str='javascript和JAVA是两个不同的语言，Javascript诞生于1995年'
    str = str.replace(/java|JAVA|Java/,'前端')
    console.log(str)
    ```

- D

  - ```html
    let str='javascript和JAVA是两个不同的语言，Javascript诞生于1995年'
    str = str.replace(/java|JAVA|Java/g,'前端')
    console.log(str)
    ```

    