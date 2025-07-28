# 变量
## 创建项目
```cs
//引用命名空间
using System;
//命名空间
namespace lesson_2变量
{
    //类
    internal class Program
    {
        //主函数，程序主入口
        static void Main(string[] args)
        {
            //函数语句块
            Console.WriteLine("变量");
            #region 折叠代码
            //让我们编程时逻辑更加清晰，#region和#endregion将中间包裹的代码折叠
            //本质是编辑器提供给我们的预处理指令，只会在编辑时有用
            //代码发布后或者执行代码，它会自动被删除
            #endregion
        }
    }
}

```

## 变量的定义
- 申明变量
> 变量类型 变量名 = 初始值;
```cs
int a = 1;
int b = 2, c = 3,  d = 4;//声明多个变量
```

## 变量命名规则
1.不能重名或者用关键字
2.不能含有除下划线的特殊符号以及数字开头

- Main和print在C#中不属于关键字，Main为主函数名称，print不属于C#关键字

# 常量
- 常量的申明：
- const 变量类型 变量名 = 变量值;
`const float PI = 3.1415926;`
1. 必须初始化
2. 不能被修改