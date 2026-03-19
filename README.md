# Python Learning Log 🚀

This repository tracks my progress in learning Python through various projects, including space-related simulations.
（複数のプロジェクトを通じたPython学習ログ）

---

## Projects

### 1. Gravity Simulation (Space Project)

A project focused on simulating orbital mechanics and flyby trajectories.
（軌道力学やフライバイを扱うシミュレーションプロジェクト）

#### Step 1: 2D Orbit Simulation

* Simulated spacecraft motion under central gravity
  （中心重力下での軌道運動をシミュレーション）
* Explored how initial velocity affects orbit shape
  （初速度による軌道の違いを検証）
* Observed circular, elliptical, and escape trajectories
  （円軌道・楕円軌道・脱出軌道を確認）

#### Step 2: Basic Flyby (Fixed Central Body)

* Simulated a spacecraft passing near a fixed celestial body
  （固定天体近傍を通過する運動を再現）
* Investigated how the incoming angle affects the outgoing trajectory
  （入射角による軌道変化を分析）
* Found that gravity significantly changes the **direction of motion**
  （重力によって進行方向が大きく変化することを確認）

#### Step 3: Jupiter Swing-by (Gravity Assist) *(in progress)*

* Introduce a moving planet (Jupiter)
  （運動する天体を導入）
* Study how energy exchange affects spacecraft speed
  （エネルギー交換による速度変化を分析）
* Explore acceleration and deceleration cases
  （加速・減速の両ケースを検証）

---

## Project Structure

```text id="y4j2y4"
mini_projects/
└── gravity_simulation/
    ├── step1_2d_orbit.ipynb
    ├── step2_basic_flyby.ipynb
    ├── step3_jupiter_gravity_assist.ipynb
    └── archive/
```

---

## Key Insights

* Gravity can redirect motion, not just attract objects
  （重力は引き寄せるだけでなく進行方向も変える）
* A basic flyby mainly changes **direction**, not speed
  （フライバイでは主に進行方向が変化する）
* A swing-by (gravity assist) changes both **direction and energy**
  （スイングバイでは方向とエネルギーの両方が変化する）

---

## Future Projects

* Space debris simulation
  （宇宙デブリのシミュレーション）
* Asteroid interception simulation
  （小惑星迎撃シミュレーション）
* Data analysis using real space datasets
  （実データを用いた解析）

---

## Next Steps

* Complete Step 3 (Jupiter swing-by)
  （Step3の完成）
* Improve visualization and documentation
  （可視化とREADMEの強化）
