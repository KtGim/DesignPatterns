#### 编译上下文
    - 用来给文件分组，让ts识别有用和无用的文件，除了有效文件携带的信息外，还包含有正在被使用的编译选项信息
    - 手动运行ts 编译器的方式
        - tsc, 会在当前目录或者父级目录查找tsconfig.json 文件
        - tsc -p 文件路径
        - tsc -w 自定检测文件的更新并且自动更新

#### 基础概念
    - 元祖:
        ```
            let x: [string, number];
            x = ['10', 10]
        ```