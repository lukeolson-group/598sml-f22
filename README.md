# CS/ME 598 SML, Fall 2022: Scientific Machine Learning

## Course info:
* Mondays and Wednesdays, 11-12:15
* Location:
  * Mondays: CIF 2025
  * Wednesdays: SC 4403
* Instructors:
  * Prof. Luke Olson, http://lukeo.cs.illinois.edu/
  * Prof. Matt West, https://lagrange.mechse.illinois.edu/
* <span style="color:red">Are you looking to join the class?</span>   Unfortunately the class is full!  Auditing and sitting in on the class cannot be accommodated.  Sorry! (In future semesters we are hoping to expand the offering.)

## Course links:
* Public access repo: https://github.com/lukeolson-group/598sml-f22
* Private class repo: https://github.com/lukeolson-group/598sml-f22-internal
* Slack: https://598sml-f22.slack.com/

## Course blurb

Familiarity with introductory numerical methods (e.g., CS 357 or TAM 470) and
the basics of machine learning and neural networks (e.g., CS 446). Theory and
practice of Scientific Machine Learning (SciML), which leverages machine
learning tools for scientific computing. Topics include learning-based methods
for differential equations, neural ODEs and PDEs, physics-informed networks and
model discovery, interpretable and explainable learning, differentiable and
probabilistic programming for scientific computing, and uncertainty
quantification via learning. Efficient parallel implementation of algorithms on
scalable computing architectures will be emphasized.

## What to expect

The course requires some background in numerical methods (e.g. CS357, CS450, or
TAM 470 type courses), but no prior knowledge of machine learning or experience
with neural networks.  As such, the course will build the necessary tools through
the semester, with a focus on scientific applications.

The course is project based, particularly the last half.  You will use `git`,
`pytorch`, and `latex` to develop various examples and steps toward your final
project.

Assignments will be submitted on the [internal GitHub repository](https://github.com/lukeolson-group/598sml-f22-internal)

## On COVID and the class

While face coverings are not required in classrooms (current as of 08/22) we
fully support your decision to wear one if you wish.

If you test positive for COVID, then you should not attend class.

If you have any cold-like symptoms or do not feel well, then you should not
attend class, regardless of testing negative or positive for COVID.

In either case, your missed attendance due to illness will not impact
your grade in the course and we will work with you to cover the material
missed in class (via Zoom).

## Schedule

- W01 (0822)
  - Topic: What is Sci ML? And what is this course?
  - Topic: Overview of tools
- W02 (0829)
  - Topic: All about derivatives
  - Topic: Approximating functions
  - https://arxiv.org/pdf/1502.05767.pdf
  - http://colah.github.io/posts/2015-08-Backprop/
  - https://openreview.net/pdf?id=BJJsrmfCZ
  - https://datahacker.rs/004-computational-graph-and-autograd-with-pytorch/
  - PINNs
    - https://www.brown.edu/research/projects/crunch/sites/brown.edu.research.projects.crunch/files/uploads/Nature-REviews_GK.pdf
    - https://www.sciencedirect.com/science/article/pii/S0021999118307125
- W04 (0905)
   - Topic: survey of networks, what to use when and where
   - Topic: optimizers
   - Themes: hierarchy, invariance (CNNs are translationally invariant, e.g.)
   - M/W: PINNs
- W05 (0912)
   - M/W: GNNs/Resnets
- W06 (0919)
  - M: Domain decomposition and elliptic problems
  - M: readings
    - Scientific Machine Learning Through Physics–Informed Neural Networks: Where we are and What’s Next
      - Cuomo, Di Cola, Giampaolo, Rozza, Raissi, Piccialli, 2022
      - https://link.springer.com/article/10.1007/s10915-022-01939-z
    - hp-VPINNs: variational physics-informed neural networks with domain decomposition
      - Li, Tang, Wu, and Liao, 2019.
      - https://ieeexplore.ieee.org/document/8918421
    - Parallel Physics-Informed Neural Networks via Domain Decomposition
      - Khemraj Shukla, Ameya D. Jagtap, George Em Karniadakis, 2021
      - https://www.sciencedirect.com/science/article/pii/S0021999121005787
    - Conservative physics-informed neural networks on discrete domains for conservation laws: Applications to forward and inverse problems
      - Ameya D. Jagtap Ehsan Kharazmi George Em Karniadakis 2020
      - https://www.sciencedirect.com/science/article/pii/S0045782520302127
    - Physics-informed neural networks for high-speed flows
      - Zhiping MaoAmeya D. JagtapGeorge Em Karniadakis, 2019
      - https://www.sciencedirect.com/science/article/pii/S0045782519306814
    - RESPECTING CAUSALITY IS ALL YOU NEED FOR TRAINING PHYSICS-INFORMED NEURAL NETWORKS
      - Wang, Sankaran, Perdikaris, 2022
      - https://arxiv.org/pdf/2203.07404.pdf
    - hp-VPINNs: Variational physics-informed neural networks with domain decomposition
      - Ehsan KharazmiZhongqiang ZhangGeorge E.M. Karniadakis 2021
      - https://www.sciencedirect.com/science/article/pii/S0045782520307325
    - DGM: A deep learning algorithm for solving partial differential equations
      - Sirignano, Spiliopoulos, 2018
  - W: PyTorch on HAL
- W07 (0926)
  - M: selecting a topic
    - `prj00`: selecting a topic + peer feedback
    - `prj01`: topic write-up (< 1page)
  - W: Data workflows
- W26 (1003)
  - M: `prj02`: project goals, a list
  - W: Optimizers
- W09 (1010)
  - M (10/10): `proj00`, `proj01`, `proj02` due
  - M (10/10): What are your key references?  What is the objective of your project?
  - W (10/12): `hw04` and `hw05` due
  - W (10/12): neural ODEs
- W10 (1017)
  - M: Setting up the simulation
- W11 (1024)
  - M: Training results
  - W: Specialized talk
- W12 (1031)
  - M: Training results
  - W: Specialized talk
- W13 (1107)
  - M: Training results
  - W: Specialized talk
- W14 (1114)
  - M: Preliminary results, pretty picture
  - W: Specialized talk
- (1121) ~~Thanksgiving~~
- W15 (1128) Presentations M/W
- W16 (1205) Presentations M/W

## Grading

Final course scores will be computed as 40% weekly Homeworks and 60% Final Project.

Grades will use the standard 10-point scale, so 90-100 is A-/A/A+, 80-90 is B-/B/B+, etc.
