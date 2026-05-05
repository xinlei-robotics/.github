<div align="center">

# xinlei-robotics

**Mobile robotics — localization, mapping, planning, control.**

A portfolio of mobile-robot engineering projects in modern C++ —
designed in simulation, unit-tested, and deployed on real hardware.

</div>

---

## Focus areas

This organization is built around the four classic problems of mobile-robot navigation:

| Area | Techniques targeted across the projects |
|---|---|
| **Localization & state estimation** | Wheel odometry · IMU integration · EKF / UKF sensor fusion |
| **Mapping & perception** | Occupancy grids · 2D lidar SLAM |
| **Planning** | A\* · Hybrid A\* · local planning |
| **Control** | Pure Pursuit · PID · trajectory tracking |

Every project follows the same workflow: **design → simulate → unit-test → run on real hardware.**

---

## Projects

| Project | Status | Summary |
|---|---|---|
| [**MiniNav**](https://github.com/xinlei-robotics/MiniNav) | 🟢 V0 complete · V1 next | Indoor mobile-robot localization & navigation on a Raspberry Pi 5 + 4WD differential-drive platform. Built incrementally from kinematic simulation to on-device deployment. **C++23, Eigen, EKF, A\*, Pure Pursuit.** |

> The roadmap favors **depth over breadth** — each project ships a working artifact (sim + hardware) before the next one starts. More projects will land here over time.

---

## Tech stack

|  |  |
|---|---|
| **Languages & build** | C++23 modules · CMake 3.28 · Ninja · Clang 18 |
| **Math & libraries** | Eigen · GoogleTest · Rerun.io |
| **Robotics frameworks** | ROS 2 (Jazzy) |
| **Hardware** | Raspberry Pi 5 · 4WD differential-drive platform |

---

## Engineering principles

- **Modular** — every algorithm is a unit-testable component, not a monolith.
- **Sim-first** — every behavior is reproducible in simulation before the wheels move.
- **Open/Closed evolution** — new versions extend, they don't rewrite.
- **Observable** — CSV traces, Rerun viewer, and static figures for every run.

---

<div align="center">

📍 France &nbsp;·&nbsp; ✉️ [xinleizhu.cn@gmail.com](mailto:xinleizhu.cn@gmail.com)

</div>
