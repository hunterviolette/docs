# 2024 Spring

## [Chemical Process Simulation App](https://github.com/hunterviolette/24spring/tree/simulator)
A foundational chemical process simulator designed to calculate steady-state flows and easily incorporate additional complexity. Built over 2024 spring break, this simulator focuses on iterative flow convergence and thermodynamic modeling

- [core.py](https://github.com/hunterviolette/24spring/blob/simulator/crate/src/steady_state.py): Computes flows through unit operations and applies process thermodynamics to evaluate unit performance and overall flow behavior.

- [steady_state.py](https://github.com/hunterviolette/24spring/blob/simulator/crate/src/steady_state.py): Converges flows iteratively. If convergence is achieved, iterates until reaching steady-state flow set-point.

- webpages in [crate/pages](https://github.com/hunterviolette/24spring/tree/simulator/crate/pages): Provides a user-friendly interface for interacting with the simulator via a generated web application.

## [Microscopy Segmentation App](https://github.com/hunterviolette/24spring/tree/simulator)
Developed a computer vision solution to exponentially enhance segmentation efficiency of microscopy data leveraging pre-trained U-Net models. The project established a comprehensive workflow for training, evaluating, and deploying U-Net architectures, enabling precise and efficient batch segmentation of microscopy datasets


[Example video](https://youtu.be/auEXBbj1-G0) uploading and predicting raw micrscopy data

- [core.py](https://github.com/hunterviolette/24spring/blob/Kelley-lab/src/pages/util/core.py): Train and evaluate U-net models for micrscopy segmenation

- webpages in [src/pages](https://github.com/hunterviolette/24spring/tree/Kelley-lab/src/pages): Allow users to fully interface with [core.py](https://github.com/hunterviolette/24spring/blob/Kelley-lab/src/pages/util/core.py) from generated web application

# 2023 Fall


## [Simulation Project One](https://github.com/hunterviolette/23fall/blob/main/478/LevelOneProj/README.md)
Programmatic [solution](https://github.com/hunterviolette/23fall/blob/main/478/LevelOneProj/lvl1_balance.py) to a [chemical engineering simulation problem](https://github.com/hunterviolette/23fall/blob/main/478/LevelOneProj/Problem_Statement.pdf)