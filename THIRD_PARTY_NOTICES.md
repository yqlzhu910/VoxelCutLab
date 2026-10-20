# 第三方组件与算例说明

VoxelCutLab 的 Windows 运行包包含以下第三方组件。它们保留各自的版权与许可；本项目不对这些组件重新授权。

| 组件 | 用途 | 许可与来源 |
|---|---|---|
| OpenSceneGraph 3.6.5 / OpenThreads | 三维绘制、场景、文字、插件和线程支持 | [许可全文](licenses/OpenSceneGraph.txt) · [对应上游源码](https://github.com/openscenegraph/OpenSceneGraph/tree/OpenSceneGraph-3.6.5) |
| FreeType | 字体插件中的字体处理 | [FreeType License](licenses/FreeType.txt) · [项目与源码](https://freetype.org/) |
| libpng 1.6.47 | PNG 图像处理 | [许可全文](licenses/libpng.txt) · [对应上游源码](https://github.com/pnggroup/libpng/tree/v1.6.47) |
| zlib 1.3.1 | 压缩支持 | [许可全文](licenses/zlib.txt) · [对应上游源码](https://github.com/madler/zlib/tree/v1.3.1) |
| Microsoft Visual C++ / MFC / OpenMP Runtime | C++、窗口和并行运行支持 | [Visual Studio 2022 可再发行文件说明](https://learn.microsoft.com/en-us/visualstudio/releases/2022/redistribution) |

Portions of this software are copyright © The FreeType Project (www.freetype.org). All rights reserved.

FreeType 随字体插件提供，现有插件没有提供可核对的 FreeType 版本标识；此处不根据 OSG 版本推断其版本。附带的 FTL 文本取自 FreeType 官方 VER-2-13-3 标签。

Windows 系统 DLL 和系统中文字体不随包分发。程序从操作系统读取已有字体。

## 内置数据

- **原项目四工序、工件 2：** 来自本项目已有加工输入，用于随软件运行展示。
- **球头刀加工：** 来自本项目已有加工输入经解析转换的四工序数据，随软件提供 62378 个刀位及所需砂轮轮廓；不附带解析器源码或内部来源记录。
- **文献参数派生螺旋槽：** 根据 [Fang 等，2020，Applied Sciences 10(12), 4223](https://doi.org/10.3390/app10124223) 的部分参数在项目中构造的示范刀路。该数据不是论文作者发布的原始刀路，也不是论文 F4 算例的复现。
- **教学算例：** 用于讲解的小规模刀具和加工路径。

程序包提供运行所需输入。本页不为算例数据另行指定开源许可证。
