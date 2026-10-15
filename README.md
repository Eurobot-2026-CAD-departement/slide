# Slide — final Eurobot 2026 robot

This repository contains the **official and final CAD** of the Eurobot 2026 Aerobotix robot.

The full assembly of the robot is `Slide final CAD.SLDASM` (stored with Git LFS). Each section of the design is in its own folder inside the assembly; folder and part names should be self-explanatory from there.

> For future reference: **zo7li9a = Slide** :)

## Contents
- `Slide final CAD.SLDASM`, `slide left/right.SLDASM`, `single slide complete.SLDASM`, `hinge left side.SLDASM` — assemblies
- `piece util/` — **most useful folder**: CAD of common pieces (motors, wheels, pumps, pneumatic fittings, ...). It will probably save you a lot of time. (Also available on its own as [slide-piece-util](https://github.com/Eurobot-2026-CAD-departement/slide-piece-util).)
- `3d printing/` — files for 3D printed parts
- `CNC lazer cutting/`, `CNC machining/` — laser-cutting and machining files / drawings
- `PCBs/` — KiCad projects of the electronics (MOSFET board, relay board, servo board, distribution board, ESP motors 2.0, PAMI ESP32, programming board, ...)
- `lidar support/`, `hinges/`, `pulley double action/`, `prototype/`, `essay 1/`, `missing_parts/` — sub-mechanisms and trials
- `slide urdf files/`, `URDFExporter/` — URDF export of the robot (SW2URDF)

Questions? Contact **Jihed Silini**.

Thank you for your attention to this file!

---

Part of the CAD work of the **Aerobotix (INSAT, Tunisia) Eurobot 2026 team** — see the [organization](https://github.com/Eurobot-2026-CAD-departement) for the other repositories. Files are mainly SolidWorks (`.SLDPRT` / `.SLDASM`) with STEP / STL / DXF exports. Released under the [MIT License](LICENSE). Questions about anything unclear? Contact a team member.
