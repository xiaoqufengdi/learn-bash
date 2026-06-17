<!--
 * @Author: xiaoqufengdi 1776394122@qq.com
 * @Date: 2026-06-17 21:37:16
 * @LastEditors: xiaoqufengdi 1776394122@qq.com
 * @LastEditTime: 2026-06-17 21:47:49
 * @FilePath: \learn-bash\base\base2-模式扩展.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# 模式扩展
```text
Shell 接收到用户输入的命令以后，会根据空格将用户的输入，拆分成一个个词元（token）。然后，Shell 会扩展词元里面的特殊字符，扩展完成后才会调用相应的命令。这种特殊字符的扩展，称为模式扩展
```
```text
波浪线扩展
? 字符扩展
* 字符扩展
方括号扩展
大括号扩展
变量扩展
子命令扩展
算术扩展
```
```bash
# close 
$ set -o noglob
$ set -f

# open
$ set +o noglob
$ set +f

```

## 波浪线扩展
> 当前用户的主目录
```bash
$ echo ~
# /home/min

```