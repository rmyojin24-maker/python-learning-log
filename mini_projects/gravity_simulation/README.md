# Gravity Simulation 🚀

This project is a collection of simulations designed to understand orbital motion and gravity assist step by step.
（重力による軌道変化と重力アシストの仕組みを段階的に理解するためのシミュレーション集）

Starting from simple 2D orbits, it gradually develops into flyby dynamics, Jupiter gravity assist, and visualization improvements.
（単純な2次元軌道から始めて、フライバイ、木星による重力アシスト、可視化の強化へと発展）

---

## Project Goal

The goal of this project is to understand the following concepts through implementation:

（このプロジェクトの目標は、以下を自分の手で理解すること）

* How gravity determines orbital motion
  （重力で軌道がどのように決まるか）
* How trajectories bend during a flyby
  （フライバイで軌道がどのように曲がるか）
* Why acceleration and deceleration occur when using moving bodies
  （動いている天体を使うと、なぜ加速・減速が起こるのか）
* How to visualize and physically interpret simulation results
  （シミュレーション結果を可視化し、物理的に解釈する）

In particular, this project emphasizes understanding gravity assist not only as a method of acceleration, but also as a mechanism that can be used for deceleration depending on conditions.
（特に、重力アシストを「加速」だけでなく「減速にも使える現象」として理解することを重視）

---

## Roadmap

This project is developed in the following steps:
（以下のステップで段階的に進める）

---

### Step 1: 2D Orbit under Central Gravity

`step1_2d_orbit.ipynb`

Simulate spacecraft motion under a central gravitational field (e.g., the Sun).
（中心天体の重力のみを考えた基本軌道のシミュレーション）

Main objectives:

* Understand circular, elliptical, falling, and escape trajectories
  （円軌道・楕円軌道・落下・脱出の違いを理解）
* Explore how initial conditions affect motion
  （初期条件による軌道変化を確認）
* Build a foundation for flyby simulations
  （フライバイの土台を作る）

---

### Step 2: Basic Flyby around a Fixed Body

`step2_basic_flyby.ipynb`

Simulate a spacecraft passing near a fixed celestial body.
（固定天体近傍を通過する運動のシミュレーション）

Main objectives:

* Investigate how incoming angle affects outgoing trajectory
  （入射角による最終進行方向の変化を調べる）
* Understand the basic mechanism of flyby
  （フライバイの基本構造を理解）

Experiment setup:

* Fix initial position and speed magnitude
  （初期位置と速度の大きさを固定）
* Vary only the incoming angle
  （入射角のみを変化）
* Compare multiple cases
  （複数ケースを比較）

Results:

* Small changes in incoming angle lead to large differences in final direction
  （入射角の違いで進行方向が大きく変化）
* Closer approaches produce stronger trajectory bending
  （接近距離が小さいほど曲がりが大きい）
* Flyby enables directional control using gravity
  （重力による進行方向の制御が可能）

---

### Step 3: Jupiter Gravity Assist (Swing-by)

`step3_jupiter_gravity_assist.ipynb`

Introduce Jupiter as a moving body and simulate spacecraft motion under both solar and planetary gravity.
（太陽＋木星の重力を考慮した運動）

This step focuses on **true gravity assist (swing-by)**.
（本格的なスイングバイを扱う）

Main objectives:

* Observe trajectory changes during Jupiter flyby
  （木星フライバイによる軌道変化）
* Confirm both acceleration and deceleration
  （加速・減速の両方を確認）
* Understand sensitivity to initial conditions
  （初期条件依存性の理解）

---

### Step 4: Visualization and Comparison *(planned)*

（今後追加予定）

* Compare multiple initial conditions
  （条件比較）
* Analyze closest approach distances
  （最接近距離の比較）
* Compare velocity changes
  （速度変化の比較）
* Add animation
  （アニメーション化）

---

### Step 5: Extensions *(planned)*

（今後追加予定）

* Extend to 3D simulations
  （3次元化）
* Generalize conditions
  （条件の一般化）
* Apply to other planets
  （他惑星への応用）
* Explore optimal acceleration/deceleration conditions
  （最適条件探索）

---

## Current Status

* [x] Step 1: 2D orbit simulation
  （2次元中心力軌道）
* [x] Step 2: Basic flyby
  （固定天体フライバイ）
* [x] Step 3: Initial Jupiter gravity assist prototype
  （木星重力アシスト試作）
* [ ] Step 4: Visualization improvements
  （可視化強化）
* [ ] Step 5: Extensions
  （拡張）

---

## Why this structure?

Initially, I started with a Jupiter-based simulation.
（最初は木星モデルから着手）

However, I realized that:

* It is better to first understand flyby using a fixed body
  （まず固定天体で理解すべき）
* Then move to gravity assist with moving bodies
  （その後にスイングバイへ進むべき）

Therefore, this project is structured to build understanding step by step, starting from the simplest model.
（最小モデルから段階的に理解する構成に再設計）

---

## Files

```text id="uy7y7x"
gravity_simulation/
├── README.md
├── archive/
│   └── step2_jupiter_flyby_original.ipynb
├── step1_2d_orbit.ipynb
├── step2_basic_flyby.ipynb
└── step3_jupiter_gravity_assist.ipynb
```
