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

实例化技术的优化方法，通过segment buffering减少绘制调用。

#### 技术要点

**核心思想**：
- 将相似几何体组织成段(segment)
- 批量提交减少API开销
- 优化顶点数据布局

**应用场景**：
- 游戏中的重复对象（建筑、植被）
- 粒子系统
- UI元素批处理

---

### Chapter 5: Optimizing Resource Management with Multistreaming
**作者**: Oliver Hoeller, Kurt Pelzer (Piranha Bytes)

#### 核心概念

使用多顶点流管理复杂场景数据，优化网格渲染。

#### 技术要点

**多流策略**：
- 静态数据流（位置、法线）
- 动态数据流（变换矩阵、颜色）
- 按更新频率分离数据

**优势**：
- 减少数据传输
- 提高缓存命中率
- 支持部分更新

---

### Chapter 6: Hardware Occlusion Queries Made Useful
**作者**: Michael Wimmer, Jirí Bittner (Vienna University of Technology)

#### 核心概念

像素精确的遮挡剔除，使用GPU反馈优化可见对象渲染。

#### 技术要点

**改进方法**：
- 层次化遮挡查询
- 时间一致性利用
- 跨帧查询避免停顿

**实践技巧**：
- 保守可见性估计
- 渐进细化策略
- 与软件剔除结合

> [!tip] 与GPU Gems 1对比
> 本章在GPU Gems 1 Chapter 29基础上提供更实用的工程方案。

---

### Chapter 7: Adaptive Tessellation of Subdivision Surfaces
**作者**: Michael Bunnell (NVIDIA)

#### 核心概念

GPU上的细分曲面自适应曲面细分，结合位移贴图实现电影级几何细节。

#### 技术要点

**1. Catmull-Clark细分**

**核心算法**：
- 每次细分：面点 + 边点 + 顶点更新
- 迭代细分产生光滑曲面

**2. 自适应曲面细分**

**LOD策略**：
- 基于屏幕空间误差
- 曲率驱动细分
- 视距相关细分密度

**3. GPU实现**

**顶点着色器**：
- 计算细分点位置
- 应用位移贴图
- 生成法线

**4. 位移贴图集成**

**技术组合**：
- 细分提供拓扑
- 位移贴图添加细节
- 法线贴图增强表面

**性能**：
- 实时帧率下达到电影级细节
- 动态LOD避免popping

---

### Chapter 8: Per-Pixel Displacement Mapping with Distance Functions
**作者**: William Donnelly (University of Waterloo)

#### 核心概念

基于距离函数的逐像素位移贴图，通过视差映射伪造几何复杂度并正确处理遮挡。

#### 技术要点

**1. 距离函数方法**

**核心概念**：
- 距离场存储到表面的最短距离
- 光线步进沿视线方向追踪
- 找到表面交点

**2. 相比传统视差映射**

**优势**：
- 正确的自遮挡
- 轮廓边缘准确
- 支持任意高度场

**3. GPU实现**

**像素着色器算法**：
```
1. 初始化光线起点和方向
2. 迭代步进：
   - 采样距离场
   - 根据距离调整步长
   - 检测交点
3. 计算最终纹理坐标和法线
```

**4. 优化技术**

- 自适应步长
- Early termination
- LOD过渡
- 距离场压缩

**性能权衡**：
- 迭代次数vs质量
- 内存占用vs精度

---

## Part II - Shading, Lighting, and Shadows 着色、光照与阴影

### Chapter 9: Deferred Shading in S.T.A.L.K.E.R.
**作者**: Oles Shishkovtsov (GSC Game World)

#### 核心概念

延迟着色架构在S.T.A.L.K.E.R.游戏引擎中的实现，将渲染分为几何处理和光照计算两个阶段。

#### 技术要点

**1. 延迟着色原理**

**两阶段渲染**：
- **阶段1 - 几何处理**：不处理光照，仅输出光照属性（位置、法线）
- **阶段2 - 光照计算**：使用G-buffer信息计算最终光照

**核心优势**：
- 降低CPU使用率（减少批处理）
- 避免前向渲染中的重复计算（顶点变换、纹理过滤）
- 适应中等过度绘制场景

**2. S.T.A.L.K.E.R.的实现架构**

**设计目标**：
- 针对高端GPU
- 100%动态光照
- 大量动态光源场景

**选择延迟着色的理由**：
- 光照密集场景性能可预测
- 性能与屏幕空间光源面积成比例
- 避免前向渲染的组合爆炸

**3. G-Buffer设计**

**多渲染目标(MRT)配置**：

| Buffer | 格式 | 内容 | 用途 |
|--------|------|------|------|
| **Buffer 1** | A16R16G16B16F | 位置 + 环境遮挡 | 光照计算 |
| **Buffer 2** | A16R16G16B16F | 法线 + 材质ID | BRDF选择 |
| **Buffer 3** | A8R8G8B8 | 反照率 + 光泽度 | 扩展至全精度 |

**数据编码**：
- 10个分量用于基础光照计算
- 6个分量用于材质和对象ID
- 三个64位缓冲区

**4. 光照计算优化**

**遮挡剔除技术**：
- 分层遮挡剔除
- GPU遮挡查询
- 模板掩码技术
- 总体性能提升：2倍或更高

**太阳光优化**：
- 单个2048×2048阴影贴图
- 像素级条件判断跳过不需要着色
- 动态分支减少计算

**光源处理**：
- 渲染光体积几何
- 仅影响相关像素
- 模板测试优化

**5. 质量改进技术**

**虚拟位置技术**：
- 沿法线轻微偏移眼睛空间位置
- 增强凹凸感
- 缓解阴影贴图偏差

**环境遮挡**：
- 存储在顶点数据中
- 避免预计算依赖
- 实时动态更新

**材质系统**：
- 64×256×4查找纹理
- 按(N·L, N·H, 材质ID)索引
- 支持多种BRDF

**6. 与前向渲染对比**

**性能测试结果**：
- 原始前向着色系统在复杂场景中**慢于**延迟着色
- 延迟方案提供可预测性能曲线
- 光照密集场景优势明显

**权衡**：
- 增加内存带宽需求（G-buffer）
- 透明物体需要单独处理
- 抗锯齿更复杂（MSAA）

> [!success] 历史意义
> S.T.A.L.K.E.R.是首批采用延迟着色的AAA游戏之一，证明了该技术的实用性。延迟着色后来成为现代游戏引擎的标配。

---

### Chapter 10: Real-Time Computation of Dynamic Irradiance Environment Maps
**作者**: Gary King (NVIDIA)

#### 核心概念

实时计算动态辐照度环境映射，用于漫反射光照。

#### 技术要点

**球谐函数(SH)方法**：
- 将环境光编码为低阶球谐系数
- GPU实时投影和重建
- 支持动态光源更新

---

### Chapter 11: Approximate Bidirectional Texture Functions
**作者**: Jan Kautz (MIT)

#### 核心概念

近似BTF用于复杂材质的高效表示和渲染。

#### 技术要点

**BTF压缩**：
- 降维技术（PCA/矩阵分解）
- GPU友好的表示
- 实时查询和插值

---

### Chapter 12: Tile-Based Texture Mapping
**作者**: Li-Yi Wei (NVIDIA)

#### 核心概念

Wang tiles技术实现虚拟纹理合成，避免重复模式。

#### 技术要点

**核心思想**：
- 预计算tile集合
- 运行时随机组合
- 边界匹配保证无缝拼接

---

### Chapter 13: Implementing the mental images Phenomena Renderer on the GPU
**作者**: Martin-Karl Lefrançois (mental images)

#### 核心概念

将mental ray渲染器的部分组件移植到GPU。

---

### Chapter 14: Dynamic Ambient Occlusion and Indirect Lighting
**作者**: Michael Bunnell (NVIDIA)

#### 核心概念

动态场景的实时AO和间接光照近似。

#### 技术要点

**动态AO**：
- 屏幕空间AO（SSAO的早期探索）
- GPU光线追踪近似
- 实时更新

---

### Chapter 15: Blueprint Rendering and "Sketchy Drawings"
**作者**: Marc Nienhaus, Jürgen Döllner (University of Potsdam)

#### 核心概念

技术图纸风格和手绘素描风格的非真实感渲染。

#### 技术要点

**蓝图风格**：
- 边缘检测
- 线条样式化
- 色彩映射

---

### Chapter 16: Accurate Atmospheric Scattering
**作者**: Sean O'Neil

#### 核心概念

基于物理的大气散射实时模拟。

#### 技术要点

**Rayleigh和Mie散射**：
- 双重散射近似
- 预计算查找表
- 实时天空渲染

---

### Chapter 17: Efficient Soft-Edged Shadows Using Pixel Shader Branching
**作者**: Yury Uralsky (NVIDIA)

#### 核心概念

利用SM 3.0动态分支优化软阴影计算。

#### 技术要点

**分支优化**：
- PCF采样动态调整
- 早期退出优化
- 减少不必要计算

---

### Chapter 18: Using Vertex Texture Displacement for Realistic Water Rendering
**作者**: Yuri Kryachko (1C:Maddox Games)

#### 核心概念

使用顶点纹理获取（VTF）实现大规模真实水面。

#### 技术要点

**VTF应用**：
- FFT水面模拟结果存入纹理
- 顶点着色器读取位移
- 实时动态水面

---

### Chapter 19: Generic Refraction Simulation
**作者**: Tiago Sousa (Crytek)

#### 核心概念

通用折射效果的屏幕空间实现。

#### 技术要点

**屏幕空间折射**：
- 场景渲染到纹理
- 折射偏移计算
- 采样背景

---

## Part III - High-Quality Rendering 高质量渲染

### Chapter 20: Fast Third-Order Texture Filtering
**作者**: Christian Sigg, Markus Hadwiger

#### 核心概念

三阶纹理过滤实现更平滑的纹理采样，导数计算支持程序纹理。

**技术要点**：Tricubic插值、GPU优化实现、与双线性/三线性对比

---

### Chapter 21: High-Quality Antialiased Rasterization
**作者**: Dan Wexler, Eric Enderton

#### 核心概念

超采样和分析方法实现高质量抗锯齿。

**技术要点**：覆盖率计算、边缘检测、多采样优化

---

### Chapter 22: Fast Prefiltered Lines
**作者**: Eric Chan, Frédo Durand

#### 核心概念

预过滤技术实现抗锯齿直线渲染。

**技术要点**：解析覆盖率、GPU加速、实时性能

---

### Chapter 23: Hair Animation and Rendering in the Nalu Demo
**作者**: Hubert Nguyen, William Donnelly

#### 核心概念

物理驱动的头发动画和真实感头发渲染。

**技术要点**：质点弹簧系统、各向异性高光（Kajiya-Kay模型）、透明度排序、阴影技术

---

### Chapter 24: Using Lookup Tables to Accelerate Color Transformations
**作者**: Jeremy Selan

#### 核心概念

3D LUT实现复杂色彩空间转换和色彩分级。

**技术要点**：3D纹理查找、插值、工作流集成

---

### Chapter 25: GPU Image Processing in Apple's Motion
**作者**: Pete Warden

#### 核心概念

商业软件中的GPU图像处理实践案例。

**技术要点**：滤波器链、实时预览、GPU/CPU协作

---

### Chapter 26: Implementing Improved Perlin Noise
**作者**: Simon Green

#### 核心概念

GPU友好的改进Perlin噪声实现（扩展GPU Gems 1 Ch5）。

**技术要点**：梯度噪声、simplex噪声、性能优化

---

### Chapter 27: Advanced High-Quality Filtering
**作者**: Justin Novosad

#### 核心概念

高级过滤核设计和GPU实现。

**技术要点**：自适应过滤、各向异性、质量vs性能

---

### Chapter 28: Mipmap-Level Measurement
**作者**: Iain Cantlay

#### 核心概念

精确测量和控制mipmap LOD选择。

**技术要点**：导数计算、LOD偏置、调试工具

---

## Part IV - General-Purpose Computation on GPUs GPU通用计算

> [!important] 历史意义
> Part IV是GPU Gems 2的特色部分，完整介绍了CUDA发布前（2005年）的GPGPU技术。这是理解GPU从图形专用处理器向通用并行计算转型的关键资料。

### Chapter 29: Streaming Architectures and Technology Trends

#### 我的理解

流式架构的核心思想是：**大量简单处理单元 + 高带宽内存 = 强大并行计算能力**。

**关键概念**：
1. **数据流模型**：数据像河流一样流过处理器
2. **SIMD执行**：单指令控制多个数据并行处理
3. **隐藏延迟**：通过大量线程切换掩盖内存访问延迟

**趋势预测**（2005年视角）：
- GPU会越来越通用化
- 可编程性会增强
- 浮点性能会持续增长

**我的对比思考**：这些预测在2006年CUDA发布后完全应验了。

---

### Chapter 30: The GeForce 6 Series GPU Architecture

#### 我的理解

GeForce 6代表了重要里程碑 - 首次支持Shader Model 3.0，带来：

**核心特性**：
1. **顶点纹理获取（VTF）**：顶点着色器可以读取纹理
   - 我的应用思路：用于位移贴图、大规模地形

2. **动态分支**：shader中可以有if/else和循环
   - 我的理解：虽然性能不如现在，但打开了新可能性

3. **更长shader**：512+指令
   - 实际影响：可以实现更复杂算法

**架构特点**：
- 仍然是分离的顶点/像素处理器（不是统一架构）
- 16个像素管线
- 6个顶点引擎

---

### Chapter 31: Mapping Computational Concepts to GPUs

#### 我的理解

这章解答了核心问题：**如何把CPU算法转换成GPU计算？**

**我的映射方案**：

1. **数据表示**：
   - CPU的数组 → GPU的纹理
   - 每个像素存储一个数据元素
   - RGBA四通道可以存4个float

2. **计算表示**：
   - CPU的循环 → GPU的片段着色器
   - 渲染全屏四边形 = 对每个数据元素执行计算
   - 输出到纹理 = 写回结果

3. **控制流**：
   - 简单：避免分支，全部计算
   - 高级：用动态分支（SM 3.0）

**我的实现思路示例（并行加法）**：
```
输入：两个纹理A和B
输出：纹理C = A + B

步骤：
1. 将A和B绑定为纹理
2. 渲染全屏四边形
3. 片段着色器：
   float4 a = tex2D(texA, uv);
   float4 b = tex2D(texB, uv);
   return a + b;
4. 输出到纹理C
```

---

### Chapter 32: Taking the Plunge into GPU Computing

#### 我的理解

这章是GPGPU入门指南。我总结的关键步骤：

**1. 思维转换**：
- 从串行思维 → 并行思维
- 从"一个一个处理" → "全部同时处理"

**2. 常见陷阱（我的经验）**：
- 依赖关系：GPU上读写同一位置会出问题
- 同步：GPU和CPU之间需要显式同步
- 精度：早期GPU浮点精度有限

**3. 适合GPU的算法特征**：
- 数据并行（每个元素独立计算）
- 计算密集（计算量 >> 内存访问）
- 规则访问模式（纹理坐标连续）

---

### Chapter 33: Implementing Efficient Parallel Data Structures

#### 我的理解

GPU上的数据结构需要重新设计。我的设计原则：

**1. 数组（最简单）**：
- 1D数组 → 1D纹理或2D纹理（展开）
- 访问：index → (x, y) 纹理坐标

**2. 树结构（困难）**：
- 指针 → 无法直接表示
- 我的解决方案：
  - 广度优先布局存入纹理
  - 父子关系通过索引计算

**3. 图结构（更困难）**：
- 邻接表 → 多个纹理
- 一个纹理存节点数据
- 另一个纹理存边信息

---

### Chapter 34: GPU Flow-Control Idioms

#### 我的理解

SM 3.0引入动态分支后，如何高效使用？我的总结：

**1. 分支代价**：
- 最坏情况：两个分支都执行（发散）
- 最好情况：所有线程走同一分支（一致）

**2. 优化策略**：

**提前退出**（我的常用技巧）：
```glsl
if (earlyTest) {
    return backgroundColor;  // 快速退出
}
// 复杂计算...
```

**循环展开**：
```glsl
// 不好：动态循环
for (int i = 0; i < count; i++) { ... }

// 更好：固定次数
for (int i = 0; i < 8; i++) { ... }
```

**3. 我的判断标准**：
- 分支预测正确率高 → 使用分支
- 两边计算量相近 → 避免分支，都算

---

### Chapter 35: GPU Program Optimization

#### 我的理解

GPU优化的核心：**找瓶颈，针对性优化**。我的优化清单：

**1. 内存访问优化**（通常是瓶颈）：
- 纹理缓存友好：相邻像素访问相邻纹素
- 避免依赖纹理读取（读取坐标依赖前一次读取结果）
- 使用合适的纹理格式（float vs half）

**2. 指令优化**：
- 向量化：用float4而非4个float
- MAD指令：a*b+c 一条指令
- 避免昂贵操作：pow、sin、cos等

**3. 寄存器压力**：
- 寄存器不够 → 线程数减少 → 性能下降
- 我的策略：减少临时变量，重用计算

**4. 我的优化流程**：
```
1. 测量基准性能
2. 识别瓶颈（内存？计算？）
3. 针对性优化
4. 重新测量
5. 重复
```

---

### Chapter 36: Stream Reduction Operations

#### 我的理解

归约（Reduction）是GPGPU的经典问题：**把N个数据归约成一个结果**。

**我的实现思路（并行求和）**：

**方法1：迭代减半**
```
初始：[1, 2, 3, 4, 5, 6, 7, 8]

Pass 1: 每对相加
[1+2, 3+4, 5+6, 7+8] = [3, 7, 11, 15]

Pass 2:
[3+7, 11+15] = [10, 26]

Pass 3:
[10+26] = [36]
```

**实现细节**：
- 每次pass渲染到一半大小的纹理
- log2(N)次pass
- 最后读回CPU

**我的优化思路**：
1. 在片段着色器中多次迭代（减少pass数）
2. 使用MRT同时输出多个中间结果
3. 最后阶段用CPU完成（避免小纹理开销）

**适用算法**：
- 求和、求平均
- 最大值、最小值
- 点积
- 直方图统计

---

## Part V - Image-Oriented Computing 面向图像的计算

### Chapter 37: Octree Textures on the GPU

#### 我的理解

八叉树纹理解决的问题：**如何在GPU上高效表示和访问稀疏3D数据？**

**我的实现思路**：

**1. 数据结构设计**：
- 八叉树节点存储在纹理中
- 每个节点：8个子节点指针 + 数据
- 空节点不存储（节省空间）

**2. 遍历算法**（我的理解）：
```
从根节点开始：
1. 计算当前节点包围盒
2. 判断是否与查询相交
3. 如果相交：
   - 叶节点：返回数据
   - 非叶节点：递归访问子节点
```

**3. GPU挑战**：
- 递归 → 用循环+栈模拟
- 指针 → 用索引
- 不规则访问 → 纹理缓存效率低

**应用场景**：
- 体积数据（医学图像）
- 稀疏场景（大规模但空旷）
- LOD选择

---

### Chapter 38: High-Quality Global Illumination Using Rasterization

#### 我的理解

核心思想：**用光栅化近似全局光照，避免昂贵的光线追踪**。

**我的算法理解**：

**Instant Radiosity方法**：
1. 从光源发射光子，记录撞击点（VPL - 虚拟点光源）
2. 将VPL作为二次光源
3. 用阴影贴图计算VPL对场景的贡献

**我的实现步骤**：
```
Pass 1: 生成VPL
- 从光源视角渲染场景
- 每个像素成为一个VPL

Pass 2: 累积间接光照
- 对每个VPL：
  - 生成阴影贴图
  - 渲染场景，累加贡献
```

**优化思路**（我的想法）：
- VPL选择：采样重要位置
- 批处理：多个VPL共享阴影贴图
- 时间复用：跨帧分摊计算

---

### Chapter 39: Progressive Refinement Radiosity

#### 我的理解

辐射度算法的渐进式GPU实现。我的理解是：**从粗糙解逐步细化到精确解**。

**算法框架**（我的概括）：
```
初始化：粗糙网格

循环直到收敛：
    1. 选择影响最大的patch
    2. 计算它对其他patch的贡献（form factor）
    3. 更新接收patch的辐照度
    4. 细分重要区域
```

**GPU加速点**（我的思考）：
- Form factor计算：并行化
- 辐照度更新：纹理操作
- 细分判断：像素着色器

---

### Chapter 40: Computer Vision on the GPU

#### 我的理解

计算机视觉算法天然适合GPU，因为是**图像→图像**的处理。

**我总结的常见算法及GPU实现**：

**1. 边缘检测**：
```
Sobel算子：
- 3×3卷积
- 片段着色器采样邻域9个像素
- 计算梯度
```

**2. 高斯模糊**：
```
可分离滤波：
- Pass 1: 水平模糊
- Pass 2: 垂直模糊
- 复杂度：O(n²) → O(2n)
```

**3. 特征提取**：
- Harris角点：梯度 → 结构张量 → 角点响应
- SIFT：高斯金字塔 → 差分 → 极值检测

**GPU优势**：
- 图像并行处理
- 纹理硬件加速采样
- 多级mipmap天然支持金字塔

---

### Chapter 41: Deferred Filtering

#### 我的理解

问题：**如何渲染点云、无序数据等非结构化几何？**

**我的解决思路**：

**方法：Splatting + 延迟过滤**
```
Pass 1: Splat阶段
- 将每个点渲染为splat（点精灵）
- 输出：位置、法线、颜色

Pass 2: 过滤阶段
- 在屏幕空间过滤splat
- 重建连续表面
- 计算最终着色
```

**为什么"延迟"？**（我的理解）
- 直接渲染：splat重叠导致走样
- 延迟过滤：收集信息后智能过滤
- 类似延迟着色的思想

---

### Chapter 42: Conservative Rasterization

#### 我的理解

保守光栅化的定义：**如果三角形与像素有任何重叠，就标记该像素**。

**对比标准光栅化**（我的理解）：
- 标准：中心在三角形内才标记
- 保守：任何重叠都标记
- 结果：保守会多标记像素

**我的实现思路**：

**方法1：膨胀三角形**
```
1. 在几何着色器中：
   - 计算三角形边向外法线
   - 沿法线膨胀半个像素
2. 光栅化膨胀后的三角形
```

**方法2：覆盖率测试**
```
在片段着色器中：
- 测试像素四个角与三角形关系
- 任一角在内或边上 → 接受
```

**应用场景**（我的总结）：
- 遮挡剔除：保守估计可见性
- 碰撞检测：保证不漏检
- 体素化：三角形→体素

---

## Part VI - Simulation and Numerical Algorithms 模拟与数值算法

> [!note] 跨学科应用
> Part VI展示了GPU从图形渲染走向科学计算的早期探索，涵盖生物、金融、医学等领域。

### Chapter 43: GPU Computing for Protein Structure Prediction

#### 我的理解

蛋白质折叠模拟的核心：**计算大量原子间的相互作用力**。

**问题规模**（我的理解）：
- 几千到几万个原子
- 每个原子与其他原子有相互作用
- 朴素算法：O(N²)

**我的GPU并行化思路**：

**1. 力计算**：
```
对每个原子i（并行）：
    force = 0
    对每个原子j：
        计算i和j之间的力（库仑力、范德华力）
        force += F_ij
    更新原子i的速度和位置
```

**2. GPU映射**：
- 原子数据存在纹理中
- 每个片段着色器处理一个原子
- 渲染N×1的纹理 = 处理N个原子

**3. 优化策略**（我的想法）：
- 截断距离：只计算近邻原子
- 空间分割：网格加速
- 多精度：关键计算用高精度

**加速效果预期**：10-100倍（相比CPU）

---

### Chapter 44: A GPU Framework for Solving Linear Equations

#### 我的理解

求解 **Ax = b** 的迭代方法GPU实现。

**我熟悉的迭代求解器**：

**1. Jacobi迭代**（最简单并行）：
```
x^(k+1)_i = (b_i - Σ(a_ij * x^(k)_j, j≠i)) / a_ii
```

**我的GPU实现思路**：
- A矩阵存为纹理
- 每次迭代：
  - 读取x^(k)
  - 计算新值
  - 输出x^(k+1)

**2. 共轭梯度（CG）**：
- 更快收敛
- 需要向量点积（归约操作）
- 结合Chapter 36的归约技术

**挑战**（我的理解）：
- 稀疏矩阵存储
- 不规则访问模式
- CPU-GPU同步（归约结果）

---

### Chapter 45: Options Pricing on the GPU

#### 我的理解

金融衍生品定价通常用**蒙特卡洛模拟**，天然适合GPU并行。

**Black-Scholes模型**（我的理解）：
- 模拟股票价格随机游走
- 大量独立路径
- 统计平均得到期权价值

**我的GPU实现框架**：

```
初始化：
- 生成随机数种子（每个路径不同）

模拟阶段（并行）：
对每条路径：
    price = S0  // 初始股价
    对每个时间步：
        生成随机数 ε
        price = price * exp(μ*dt + σ*sqrt(dt)*ε)
    payoff = max(price - K, 0)  // 欧式看涨期权

归约阶段：
    average_payoff = sum(payoffs) / num_paths
    option_value = exp(-r*T) * average_payoff
```

**GPU优势**：
- 百万条路径并行模拟
- 随机数生成并行化
- 显著加速（100-1000倍）

---

### Chapter 46: Improved GPU Sorting

#### 我的理解

排序是基础算法，GPU上需要新思路。

**我理解的Bitonic Sort**：

**核心思想**：构造bitonic序列，然后排序
- Bitonic序列：先递增后递减（或反之）

**算法步骤**（我的理解）：
```
对log2(N)个阶段：
    对log2(阶段数)个步骤：
        并行比较-交换操作
        距离 = 2^步骤
        对每对元素(i, i+distance)：
            if 需要交换：swap(arr[i], arr[i+distance])
```

**GPU实现**：
- 每个比较-交换 = 一个shader调用
- O(log²N)次pass
- 每次pass完全并行

**我的性能分析**：
- 优点：高度并行，无分支
- 缺点：O(log²N)不如CPU的O(NlogN)
- 适用场景：中等规模数据（几万到百万）

---

### Chapter 47: Flow Simulation with Complex Boundaries

#### 我的理解

流体模拟遇到复杂边界（障碍物）时的处理。

**基础：Navier-Stokes方程GPU求解**（我的理解）：
```
速度更新：v_new = v + dt*(−(v·∇)v − ∇p/ρ + ν∇²v + f)
压力求解：∇²p = −∇·((v·∇)v)
```

**边界条件**（我的实现思路）：

**1. 障碍物边界**：
- 标记障碍物位置（纹理mask）
- 边界速度设为0（no-slip）
- 压力边界条件：法向导数=0

**2. GPU实现技巧**：
```glsl
// 在shader中
if (是障碍物) {
    velocity = 0;
    return;
}
// 正常流体计算...
```

**3. 复杂形状处理**（我的想法）：
- 体素化：将复杂几何转为体素
- 符号距离场：存储到边界的距离
- 插值：边界附近特殊处理

---

### Chapter 48: Medical Image Reconstruction with the FFT

#### 我的理解

CT/MRI重建的核心：**从投影数据重建3D图像**。

**傅里叶切片定理**（我的理解）：
- 2D投影的1D FFT = 3D傅里叶空间的切片
- 收集足够切片 → 3D逆FFT → 重建图像

**我的GPU实现思路**：

**1. FFT并行化**：
```
Cooley-Tukey算法：
- Butterfly操作并行化
- log2(N)个阶段
- 每阶段N/2个独立蝶形

GPU映射：
- 每个蝶形 = 一个shader线程
- 数据存储纹理中
- Ping-pong缓冲区
```

**2. 2D FFT = 两个1D FFT**：
- Pass 1: 每行做1D FFT
- Pass 2: 每列做1D FFT

**3. 3D重建流程**：
```
对每个投影角度：
    1D FFT(投影数据) → 频域切片
    插入3D频域空间
完成后：
    3D 逆FFT → 重建图像
```

**加速效果**（我的估算）：
- FFT高度并行
- GPU加速10-100倍
- 实时MRI成像成为可能

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
