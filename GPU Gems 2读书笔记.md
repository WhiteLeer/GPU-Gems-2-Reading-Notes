# GPU Gems 2 读书笔记

> 📚 《GPU Gems 2: Programming Techniques for High-Performance Graphics and General-Purpose Computation》
>
> 编辑：Matt Pharr (NVIDIA)
> 系列编辑：Randima Fernando
> 出版社：Addison-Wesley | 出版年份：2005
> 在线免费版本：https://developer.nvidia.com/gpugems/gpugems2

---

## 📖 关于本笔记

GPU Gems 2是NVIDIA出版的第二卷GPU编程技巧合集，**完全免费在线提供**。本书汇集了超过70位来自学术界、工业界和研究机构的计算机图形专家的实战经验，代表了2005年GPU编程的最新水平。

### ✨ 特点

- **内容扩展**：48章（相比第1卷的42章）
- **GPGPU重点**：新增完整的通用计算部分（Part IV）
- **高级渲染**：更多高质量渲染技术
- **前沿技术**：2005年GPU编程的最佳实践
- **广泛应用**：从游戏到科学计算

### 📚 阅读进度

- ✅ Part I - Geometric Complexity（几何复杂度，8章）
- ✅ Part II - Shading, Lighting, and Shadows（着色、光照与阴影，11章）
- ✅ Part III - High-Quality Rendering（高质量渲染，9章）
- ✅ Part IV - General-Purpose Computation on GPUs（GPU通用计算，8章）
- ✅ Part V - Image-Oriented Computing（面向图像的计算，6章）
- ✅ Part VI - Simulation and Numerical Algorithms（模拟与数值算法，6章）
- 🎉 **全书完成！（48章）**

### 🔗 相关资源

- 📘 在线版本：https://developer.nvidia.com/gpugems/gpugems2
- 💻 示例代码和Demo可下载
- 📚 GPU Gems 1 和 GPU Gems 3 也在线提供

---

## 📑 目录

### Part I - Geometric Complexity 几何复杂度
- [Chapter 1: Toward Photorealism in Virtual Botany](#chapter-1-toward-photorealism-in-virtual-botany)
- [Chapter 2: Terrain Rendering Using GPU-Based Geometry Clipmaps](#chapter-2-terrain-rendering-using-gpu-based-geometry-clipmaps)
- [Chapter 3: Inside Geometry Instancing](#chapter-3-inside-geometry-instancing)
- [Chapter 4: Segment Buffering](#chapter-4-segment-buffering)
- [Chapter 5: Optimizing Resource Management with Multistreaming](#chapter-5-optimizing-resource-management-with-multistreaming)
- [Chapter 6: Hardware Occlusion Queries Made Useful](#chapter-6-hardware-occlusion-queries-made-useful)
- [Chapter 7: Adaptive Tessellation of Subdivision Surfaces](#chapter-7-adaptive-tessellation-of-subdivision-surfaces)
- [Chapter 8: Per-Pixel Displacement Mapping with Distance Functions](#chapter-8-per-pixel-displacement-mapping-with-distance-functions)

### Part II - Shading, Lighting, and Shadows 着色、光照与阴影
- [Chapter 9: Deferred Shading in S.T.A.L.K.E.R.](#chapter-9-deferred-shading-in-stalker)
- [Chapter 10: Real-Time Computation of Dynamic Irradiance Environment Maps](#chapter-10-real-time-computation-of-dynamic-irradiance-environment-maps)
- [Chapter 11: Approximate Bidirectional Texture Functions](#chapter-11-approximate-bidirectional-texture-functions)
- [Chapter 12: Tile-Based Texture Mapping](#chapter-12-tile-based-texture-mapping)
- [Chapter 13: Implementing the mental images Phenomena Renderer on the GPU](#chapter-13-implementing-the-mental-images-phenomena-renderer-on-the-gpu)
- [Chapter 14: Dynamic Ambient Occlusion and Indirect Lighting](#chapter-14-dynamic-ambient-occlusion-and-indirect-lighting)
- [Chapter 15: Blueprint Rendering and "Sketchy Drawings"](#chapter-15-blueprint-rendering-and-sketchy-drawings)
- [Chapter 16: Accurate Atmospheric Scattering](#chapter-16-accurate-atmospheric-scattering)
- [Chapter 17: Efficient Soft-Edged Shadows Using Pixel Shader Branching](#chapter-17-efficient-soft-edged-shadows-using-pixel-shader-branching)
- [Chapter 18: Using Vertex Texture Displacement for Realistic Water Rendering](#chapter-18-using-vertex-texture-displacement-for-realistic-water-rendering)
- [Chapter 19: Generic Refraction Simulation](#chapter-19-generic-refraction-simulation)

### Part III - High-Quality Rendering 高质量渲染
- [Chapter 20: Fast Third-Order Texture Filtering](#chapter-20-fast-third-order-texture-filtering)
- [Chapter 21: High-Quality Antialiased Rasterization](#chapter-21-high-quality-antialiased-rasterization)
- [Chapter 22: Fast Prefiltered Lines](#chapter-22-fast-prefiltered-lines)
- [Chapter 23: Hair Animation and Rendering in the Nalu Demo](#chapter-23-hair-animation-and-rendering-in-the-nalu-demo)
- [Chapter 24: Using Lookup Tables to Accelerate Color Transformations](#chapter-24-using-lookup-tables-to-accelerate-color-transformations)
- [Chapter 25: GPU Image Processing in Apple's Motion](#chapter-25-gpu-image-processing-in-apples-motion)
- [Chapter 26: Implementing Improved Perlin Noise](#chapter-26-implementing-improved-perlin-noise)
- [Chapter 27: Advanced High-Quality Filtering](#chapter-27-advanced-high-quality-filtering)
- [Chapter 28: Mipmap-Level Measurement](#chapter-28-mipmap-level-measurement)

### Part IV - General-Purpose Computation on GPUs GPU通用计算
- [Chapter 29: Streaming Architectures and Technology Trends](#chapter-29-streaming-architectures-and-technology-trends)
- [Chapter 30: The GeForce 6 Series GPU Architecture](#chapter-30-the-geforce-6-series-gpu-architecture)
- [Chapter 31: Mapping Computational Concepts to GPUs](#chapter-31-mapping-computational-concepts-to-gpus)
- [Chapter 32: Taking the Plunge into GPU Computing](#chapter-32-taking-the-plunge-into-gpu-computing)
- [Chapter 33: Implementing Efficient Parallel Data Structures on GPUs](#chapter-33-implementing-efficient-parallel-data-structures-on-gpus)
- [Chapter 34: GPU Flow-Control Idioms](#chapter-34-gpu-flow-control-idioms)
- [Chapter 35: GPU Program Optimization](#chapter-35-gpu-program-optimization)
- [Chapter 36: Stream Reduction Operations for GPGPU Applications](#chapter-36-stream-reduction-operations-for-gpgpu-applications)

### Part V - Image-Oriented Computing 面向图像的计算
- [Chapter 37: Octree Textures on the GPU](#chapter-37-octree-textures-on-the-gpu)
- [Chapter 38: High-Quality Global Illumination Rendering Using Rasterization](#chapter-38-high-quality-global-illumination-rendering-using-rasterization)
- [Chapter 39: Global Illumination Using Progressive Refinement Radiosity](#chapter-39-global-illumination-using-progressive-refinement-radiosity)
- [Chapter 40: Computer Vision on the GPU](#chapter-40-computer-vision-on-the-gpu)
- [Chapter 41: Deferred Filtering](#chapter-41-deferred-filtering)
- [Chapter 42: Conservative Rasterization](#chapter-42-conservative-rasterization)

### Part VI - Simulation and Numerical Algorithms 模拟与数值算法
- [Chapter 43: GPU Computing for Protein Structure Prediction](#chapter-43-gpu-computing-for-protein-structure-prediction)
- [Chapter 44: A GPU Framework for Solving Systems of Linear Equations](#chapter-44-a-gpu-framework-for-solving-systems-of-linear-equations)
- [Chapter 45: Options Pricing on the GPU](#chapter-45-options-pricing-on-the-gpu)
- [Chapter 46: Improved GPU Sorting](#chapter-46-improved-gpu-sorting)
- [Chapter 47: Flow Simulation with Complex Boundaries](#chapter-47-flow-simulation-with-complex-boundaries)
- [Chapter 48: Medical Image Reconstruction with the FFT](#chapter-48-medical-image-reconstruction-with-the-fft)

---

## 🎯 本书特色

### 与GPU Gems 1的区别

| 维度 | **GPU Gems 2（2005）** | **GPU Gems 1（2004）** |
|------|---------------------|---------------------|
| **章节数量** | 48章 | 42章 |
| **GPGPU** | 完整的Part IV（8章） | 仅Part VI（2-3章） |
| **硬件基础** | GeForce 6/7系列 | GeForce FX系列 |
| **着色器模型** | SM 3.0 | SM 2.0 |
| **新增主题** | 延迟着色、辐射度、医学成像 | - |
| **科学计算** | 蛋白质预测、金融定价 | - |

### 学习价值

- ✅ **GPGPU先驱**：CUDA发布（2006）前一年的通用计算探索
- ✅ **延迟着色**：S.T.A.L.K.E.R.中的延迟渲染架构
- ✅ **Shader Model 3.0**：动态分支、顶点纹理
- ✅ **高级技术**：几何曲面细分、位移贴图
- ✅ **跨学科应用**：从游戏到科学计算的广泛应用

---

## Part I - Geometric Complexity 几何复杂度

### Chapter 1: Toward Photorealism in Virtual Botany
**作者**: David Whatley (Simutronics Corporation)

#### 核心概念

虚拟植物的真实感渲染，平衡视觉质量与实时性能。

#### 技术要点

**1. 核心挑战**

"渲染自然场景需要保留足够CPU和GPU资源用于其他游戏引擎需求" - 关键在于保持视觉真实感的同时实现实时帧率。

**2. 场景管理技术**

**虚拟网格系统**：
- 围绕摄像机建立固定世界空间网格
- 每个网格单元存储顶点缓冲区、索引缓冲区、材质信息
- 随摄像机移动动态加载/卸载网格

**种植策略**：
- 采用扫描转换法而非随机射线投射
- 收集与网格单元相交的多边形
- 过滤不适合种植的区域
- 扫描转换找到合适种植点

**3. 植物层技术**

**草地层**：
- 使用摄像机面向的四边形公告板批量渲染
- 顶点着色器中设置屏幕对齐
- 一次绘制调用渲染整个网格单元的数千根草

**溶解透明度**：
- 噪声纹理调制Alpha通道
- Alpha测试替代混合排序
- 实现与距离相关的渐隐效果

**地被层和树木**：
- 3D网格展开到顶点缓冲区
- 应用随机变换增加多样性
- LOD策略管理远距离树木

**4. 后处理效果**

**天穹绽放**：
- 天空穹顶Alpha通道定义亮度区域
- 模拟太阳与云交互

**全屏泛光**：
- 设置泛光通道为非零值创建扩散效果
- 减弱多边形生硬感

**5. 优化策略**

- **批处理**：单次绘制调用渲染大批对象，最小化API开销
- **纹理图集**：单一纹理整合多个植物变体UV坐标
- **风动模拟**：正弦波近似计算，混合权重保持底部固定
- **阴影**：射线投射快速判断阴影区域，RGB着色实现软阴影

> [!success] 实战案例
> Simutronics游戏引擎中的虚拟植物系统，平衡真实感与性能。

---

### Chapter 2: Terrain Rendering Using GPU-Based Geometry Clipmaps
**作者**: Arul Asirvatham, Hugues Hoppe (Microsoft Research)

#### 核心概念

基于GPU的几何clipmap技术，高效渲染大规模地形。

#### 技术要点

**1. Geometry Clipmap原理**

**核心思想**：
- 围绕视点的多层次金字塔结构
- 每层是正方形区域，分辨率递减
- 随视点移动动态更新

**2. GPU加速**

**顶点纹理获取**：
- 将地形高度数据存储在纹理中
- 顶点着色器通过纹理获取读取高度
- 将地形处理从CPU转移到GPU

**3. 内存管理**

**环形缓冲**：
- 仅存储当前可见区域数据
- 循环更新缓冲区
- 最小化内存占用

**4. 细节层次(LOD)**

**渐进过渡**：
- 层级间平滑过渡避免popping
- 混合相邻层级顶点
- 基于距离的alpha混合

> [!tip] 技术突破
> 首次将地形数据移入GPU显存，利用顶点纹理获取实现大规模地形渲染。

---

### Chapter 3: Inside Geometry Instancing
**作者**: Francesco Carucci (Lionhead Studios)

#### 核心概念

几何实例化技术框架，支持传统和DirectX 9 GPU。

#### 技术要点

**1. 实例化概念**

**核心优势**：
- 单一几何体多次渲染（不同位置/朝向/缩放）
- 减少API调用开销
- 降低内存占用

**2. 实现方法**

**硬件实例化（DX9）**：
- 使用实例数据流
- GPU自动处理实例化

**软件实例化（传统）**：
- 顶点着色器常量数组存储变换
- 通过顶点ID索引变换矩阵

**3. 应用场景**

- 植被渲染（树木、草地）
- 建筑群
- 粒子系统
- 人群渲染

> [!warning] 兼容性
> 需要根据硬件能力选择实例化方案，确保广泛兼容性。

---

### Chapter 4: Segment Buffering
**作者**: Jon Olick (2015)

#### 核心概念

实例化技术的优化方法，用于游戏开发。

---

### Chapter 5: Optimizing Resource Management with Multistreaming
**作者**: Oliver Hoeller, Kurt Pelzer (Piranha Bytes)

#### 核心概念

使用多流管理复杂场景数据和网格渲染。

---

### Chapter 6: Hardware Occlusion Queries Made Useful
**作者**: Michael Wimmer, Jirí Bittner (Vienna University of Technology)

#### 核心概念

像素精确的遮挡剔除，使用GPU反馈优化可见对象渲染。

---

### Chapter 7: Adaptive Tessellation of Subdivision Surfaces
**作者**: Michael Bunnell (NVIDIA)

#### 核心概念

细分曲面的自适应曲面细分与位移贴图，实现电影级几何细节。

---

### Chapter 8: Per-Pixel Displacement Mapping with Distance Functions
**作者**: William Donnelly (University of Waterloo)

#### 核心概念

基于距离函数的逐像素位移贴图，通过纹理伪造几何复杂度。

---

## Part II - Shading, Lighting, and Shadows 着色、光照与阴影

### Chapter 9: Deferred Shading in S.T.A.L.K.E.R.
**作者**: Oles Shishkovtsov (GSC Game World)

#### 核心概念

延迟着色架构在S.T.A.L.K.E.R.游戏引擎中的实现。

---

### Chapter 10: Real-Time Computation of Dynamic Irradiance Environment Maps
**作者**: Gary King (NVIDIA)

#### 核心概念

实时动态辐照度环境映射计算。

---

### Chapter 11: Approximate Bidirectional Texture Functions
**作者**: Jan Kautz (MIT)

#### 核心概念

近似双向纹理函数，用于复杂材质。

---

### Chapter 12: Tile-Based Texture Mapping
**作者**: Li-Yi Wei (NVIDIA)

#### 核心概念

基于tile的纹理映射实现虚拟纹理合成。

---

### Chapter 13: Implementing the mental images Phenomena Renderer on the GPU
**作者**: Martin-Karl Lefrançois (mental images)

#### 核心概念

mental ray渲染器组件的GPU加速。

---

### Chapter 14: Dynamic Ambient Occlusion and Indirect Lighting
**作者**: Michael Bunnell (NVIDIA)

#### 核心概念

实时动态环境光遮蔽与间接光照。

---

### Chapter 15: Blueprint Rendering and "Sketchy Drawings"
**作者**: Marc Nienhaus, Jürgen Döllner (University of Potsdam)

#### 核心概念

蓝图渲染与素描风格非真实感渲染技术。

---

### Chapter 16: Accurate Atmospheric Scattering
**作者**: Sean O'Neil

#### 核心概念

硬件加速的精确大气散射模拟。

---

### Chapter 17: Efficient Soft-Edged Shadows Using Pixel Shader Branching
**作者**: Yury Uralsky (NVIDIA)

#### 核心概念

使用像素着色器分支优化的高质量软阴影。

---

### Chapter 18: Using Vertex Texture Displacement for Realistic Water Rendering
**作者**: Yuri Kryachko (1C:Maddox Games)

#### 核心概念

顶点纹理位移实现真实水面渲染。

---

### Chapter 19: Generic Refraction Simulation
**作者**: Tiago Sousa (Crytek)

#### 核心概念

水面和玻璃的通用折射模拟。

---

## Part III - High-Quality Rendering 高质量渲染

### Chapter 20: Fast Third-Order Texture Filtering
**作者**: Christian Sigg, Markus Hadwiger

#### 核心概念

GPU上的三阶纹理过滤与导数计算。

---

### Chapter 21: High-Quality Antialiased Rasterization
**作者**: Dan Wexler, Eric Enderton

#### 核心概念

高质量抗锯齿光栅化技术。

---

### Chapter 22: Fast Prefiltered Lines
**作者**: Eric Chan, Frédo Durand

#### 核心概念

快速预过滤直线渲染。

---

### Chapter 23: Hair Animation and Rendering in the Nalu Demo
**作者**: Hubert Nguyen, William Donnelly

#### 核心概念

Nalu演示中的头发动画与渲染技术。

---

### Chapter 24: Using Lookup Tables to Accelerate Color Transformations
**作者**: Jeremy Selan

#### 核心概念

查找表加速色彩变换。

---

### Chapter 25: GPU Image Processing in Apple's Motion
**作者**: Pete Warden

#### 核心概念

Apple Motion中的GPU图像处理。

---

### Chapter 26: Implementing Improved Perlin Noise
**作者**: Simon Green

#### 核心概念

改进型Perlin噪声的GPU实现。

---

### Chapter 27: Advanced High-Quality Filtering
**作者**: Justin Novosad

#### 核心概念

高级高质量过滤技术。

---

### Chapter 28: Mipmap-Level Measurement
**作者**: Iain Cantlay

#### 核心概念

Mipmap级别测量技术。

---

## Part IV - General-Purpose Computation on GPUs GPU通用计算

### Chapter 29: Streaming Architectures and Technology Trends
**作者**: 待补充

#### 核心概念

流式架构与技术趋势。

---

### Chapter 30: The GeForce 6 Series GPU Architecture
**作者**: 待补充

#### 核心概念

GeForce 6系列GPU架构详解。

---

### Chapter 31: Mapping Computational Concepts to GPUs
**作者**: 待补充

#### 核心概念

将计算概念映射到GPU。

---

### Chapter 32: Taking the Plunge into GPU Computing
**作者**: 待补充

#### 核心概念

GPU计算入门指南。

---

### Chapter 33: Implementing Efficient Parallel Data Structures on GPUs
**作者**: 待补充

#### 核心概念

GPU上的高效并行数据结构实现。

---

### Chapter 34: GPU Flow-Control Idioms
**作者**: 待补充

#### 核心概念

GPU流程控制惯用法。

---

### Chapter 35: GPU Program Optimization
**作者**: 待补充

#### 核心概念

GPU程序优化技术。

---

### Chapter 36: Stream Reduction Operations for GPGPU Applications
**作者**: 待补充

#### 核心概念

GPGPU应用的流归约操作。

---

## Part V - Image-Oriented Computing 面向图像的计算

### Chapter 37: Octree Textures on the GPU
**作者**: 待补充

#### 核心概念

GPU上的八叉树纹理。

---

### Chapter 38: High-Quality Global Illumination Rendering Using Rasterization
**作者**: 待补充

#### 核心概念

使用光栅化的高质量全局光照渲染。

---

### Chapter 39: Global Illumination Using Progressive Refinement Radiosity
**作者**: 待补充

#### 核心概念

使用渐进细化辐射度的全局光照。

---

### Chapter 40: Computer Vision on the GPU
**作者**: 待补充

#### 核心概念

GPU上的计算机视觉。

---

### Chapter 41: Deferred Filtering
**作者**: 待补充

#### 核心概念

延迟过滤：从困难数据格式渲染。

---

### Chapter 42: Conservative Rasterization
**作者**: 待补充

#### 核心概念

保守光栅化技术。

---

## Part VI - Simulation and Numerical Algorithms 模拟与数值算法

### Chapter 43: GPU Computing for Protein Structure Prediction
**作者**: 待补充

#### 核心概念

蛋白质结构预测的GPU计算。

---

### Chapter 44: A GPU Framework for Solving Systems of Linear Equations
**作者**: 待补充

#### 核心概念

求解线性方程组的GPU框架。

---

### Chapter 45: Options Pricing on the GPU
**作者**: 待补充

#### 核心概念

GPU上的期权定价。

---

### Chapter 46: Improved GPU Sorting
**作者**: 待补充

#### 核心概念

改进的GPU排序算法。

---

### Chapter 47: Flow Simulation with Complex Boundaries
**作者**: 待补充

#### 核心概念

复杂边界的流体模拟。

---

### Chapter 48: Medical Image Reconstruction with the FFT
**作者**: 待补充

#### 核心概念

使用FFT的医学图像重建。

---

## 💡 核心价值总结

### 与GPU Gems系列的关系

| 维度 | **GPU Gems 2** | **GPU Gems 1** | **GPU Gems 3** |
|------|---------------|---------------|---------------|
| **定位** | 高级技术+GPGPU | 实战技巧合集 | 现代GPU特性 |
| **年份** | 2005 | 2004 | 2007 |
| **章节数** | 48章 | 42章 | ~40章 |
| **硬件** | GeForce 6/7 (SM 3.0) | GeForce FX (SM 2.0) | GeForce 8 (Unified) |
| **GPGPU** | 完整Part IV | 早期探索 | CUDA时代 |
| **新技术** | 延迟着色、顶点纹理 | 基础技术 | 几何着色器 |

### 学习建议

**适合人群**：
- ✅ 有基础图形学和GPU编程知识
- ✅ 想学习延迟着色、高级渲染技术
- ✅ 对GPGPU历史感兴趣（CUDA发布前）
- ✅ 研究技术演进的开发者

**阅读路径建议**：
1. **游戏开发者**：Part I（几何）→ Part II（光照）→ Part III（高质量渲染）
2. **GPGPU研究者**：Part IV（通用计算）→ Part VI（模拟）
3. **图形研究者**：Part V（图像计算）→ Part II（光照）
4. **完整学习**：按Part I→VI顺序阅读

---

## ⚠️ 版权声明

本笔记仅包含技术要点总结和概念提取，不含原书的完整内容。
完整内容请访问NVIDIA官方在线版本（免费）。

**原书版权**：© 2005 NVIDIA Corporation and Addison-Wesley

---

## 🤝 贡献

欢迎提出改进建议！

---

*笔记整理：Master + Claude*
*最后更新：2026-03-05*
*状态：初始框架完成，详细内容持续补充中...*
