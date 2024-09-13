###Git

##git提交message规范
```
    <type>(<scope>):<subject>
    <blank line>
    <body>
    <blank line>
    <footer>
```

type:
```type
    feat: 新功能
    fix:修复bug
    docs:文档
    style:格式 不影响代码的运行的变动
    refactor:重构 不增加功能 也不修改bug的代码变动
    test:增加测试
    chore:构建过程或辅助工具的变动
```
```scope
    说明影响的范围 范围广用* 类名 函数名
```
```subject
    简短描述 不超过50字 不换行
```
```body
    详细描述本次提交 第二行空行 代码变动原因
    
```
```footer
    1.不兼容变动注释
    以BREAKING CHANGE开头 后面接变动的描述 以及变动的理由和迁移方法
    2.关闭关联的issue
    Closes #xxx
```

```revert
    
```





