我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# codeform
Go code generation framework.

* Generate output from Go code using templates
* Interact with a simple model (see [Model documentation](https://godoc.org/github.com/matryer/codeform/model))
* Write templates using the [online editor](http://editor.codeform.in/) (with live preview)
* Contribute to a [repository of shared templates](https://github.com/matryer/codeform-templates)

## Get started

To install Codeform, get it:

```bash
go get github.com/matryer/codeform/...
```

This will install the `codeform` tool, as well as make the codeform
packages available to you.

## `codeform` comamnd line tool

The `codeform` tool allows you to generate output using Go templates.

```
-src string
	code source (default ".")
-srcin
	take source from standard in
-template string
	template verbatim
-templatesrc string
	template source
-out string
	output file (defaults to standard out)
	
-timeout duration
	timeout for HTTP requests (default 2s)
-v	verbose logging
-n  suppress final line feed
-version
	print version and exit

-func string
	comma separated list of funcs to include
-interface string
	comma separated list of interfaces to include
-name string
	comma separated list of things to include
-package string
	comma separated list of packages to include
-struct string
	comma separated list of structs to include
```

* See the [sources documentation](https://github.com/matryer/codeform/tree/master/source) for an overview of acceptable values for `src` and `templatesrc`

# Advanced

If you want to generate output using Go code instead of templates, you can
import the `github.com/matryer/codeform/parser` package directly and interact
with the model yourself (see [Model documentation](https://godoc.org/github.com/matryer/codeform/model)).
