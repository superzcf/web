windows10 环境下已经成功实现。
1.通过cmd打开命令行，找到dockfile的所在位置（找到\asdt\prog目录）
2.在prog目录下执行docker build -t thc ，命令，生成docker镜像
3.接着执行docker run -it thc 命令，可以获得结果
