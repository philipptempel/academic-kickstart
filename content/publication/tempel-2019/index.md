---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Dynamics of Cable-Driven Parallel Robots with Elastic and Flexible, Time-Varying
  Length Cables
subtitle: ''
summary: ''
authors:
  - philipptempel
tags: []
categories: []
date: '2019-01-01'
lastmod: 2020-09-24T15:46:57+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - simtech-pn37
publishDate: '2020-09-24T13:46:57.365272Z'
publication_types:
  - 5
abstract: >
  Cable-driven parallel robots are a special class of parallel manipulators
  with prismatic rigid-link actuators replaced by flexible and elastic fiber cables.
  However, this in nature simple replacement of motion and force transmitting components,
  results in drastic implications on the kinematics and dynamics of such robots.
  Not only are cables noticeably lighter than their rigid-link counterparts, but
  they are also more elastic and flexible which becomes very apparent when spanning
  a cable between two points: cable sag is induced by the cable's own weight, a
  behavior that cannot be compensated for completely. Incommodiously, these two
  properties---elasticity and flexibility---of fiber cables makes operating cable-driven
  parallel robots more involved than anticipated from their rigidlink counterparts
  and is still an active research field. In this thesis, particular focus is placed
  on the dynamics of cable-driven parallel robots under explicit consideration of
  cables and their spatial and axial dynamics.  For the purpose of designing and
  controlling cable robots, we derive a full multibody model of cable robots describing
  spatial cable motion by means of Cosserat rod theory. Borrowed from classical
  mechanics, Cosserat rods capture large elastic deformations such as strain and
  bending allowing for describing motion of cables in space. The equations of motion
  are discretized using Rayleigh-Ritz's approach to turn the continuum ``cable''
  into a finite-dimensional model. Reference for evaluation of the cable and robot
  model are classical beam theory much like well-established methods of cable robot
  kinetostatics and of cable force distribution calculations. Numerical results
  of the robot dynamics are obtained with an energy and momentum conserving mechanical
  integrator for constrained multibody systems.  Axial stress-strain dynamics of
  fiber cables show hysteretic and nonlinear behavior which cannot be represented
  by a purely linear spring. We propose theoretically and investigate experimentally
  an analogous model based on multiple springs and dampers, that captures hysteretic
  behavior and stress relaxation well. Its elastic and viscous material parameters
  are estimated using transfer function identification.  Both contributions provide
  valid models for further considerations in modeling, simulation, and control of
  cable-driven parallel robots.
publication: '*Fraunhofer Verlag*'
---
