# crystal-sim

交互式晶体双折射几何实验室（中英双语单文件网页仿真） / Interactive Crystal Birefringence Geometry Lab (Bilingual Chinese / English single-file HTML5 simulation).

## 简介 / Overview

本仿真从第一性原理的 **3D 布拉维晶格几何** 与 **基元极化率 $\alpha$** 出发，实时通过 $1/r^3$ 偶极子格点求和计算宏观介电张量 $\varepsilon$，再对任意波矢 $\hat{k}$ 实时求解双折射两个本征偏振模的折射率、光轴简并方向与走离角（能流法线 $\mathbf{S}$）。

Starting from a real-space **3D Bravais crystal lattice** and **motif polarizability $\alpha$**, this simulation computes the macroscopic dielectric tensor $\varepsilon$ via $1/r^3$ dipole lattice sums and solves the two eigenmodes, optic axis degeneracies, and Poynting walk-off angles for any wave-normal $\hat{k}$.

## 主要特性 / Features

- **中英双语一键切换 / Bilingual Toggle**：右上角支持实时切换 `中文 / English`。
- **实空间 3D 晶格画布 / Real-Space 3D Lattice**：展示原胞基矢 $(\mathbf{a}_1, \mathbf{a}_2, \mathbf{a}_3)$、基面夹角 $\gamma$（$90^\circ / 120^\circ$）、平面 $\text{CO}_3^{2-}$ 分子团簇以及 $\pm 1/r^3$ 偶极局域场耦合线。
- **3D 折射率面与中心切面 / 3D Refractive Surface & Central Section**：支持在波法线面 $F(\mathbf{k})=0$ 与折射率椭球之间切换，直观定位单轴/双轴光轴简并点与能流走离方向 $\mathbf{S}$。
- **全自由度同步视角 / Synchronized 3D Camera**：左/右键拖拽任一 3D 画布可同步旋转，内置 `3D 默认`、`俯视 xy`、`正视 xz`、`侧视 yz` 一键视角。
- **二维入射面截线 / 2D Incidence-Plane Slice**：直观对比 `xy` 水平面（$\hat{c} \perp$ 入射面，两支均为正圆且走离角为 $0^\circ$）与 `xz` 子午面（出现椭圆与走离）。

## 使用方法 / Quick Start

零构建依赖，直接在浏览器中打开 [`index.html`](./index.html) 即可运行。

No build step required—simply open [`index.html`](./index.html) in any modern web browser.
