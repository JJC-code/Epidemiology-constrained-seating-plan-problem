# Epidemiology-constrained Seating Plan Problem
This repository contains a set of files used during the testing phase. The computational environment
created to solve this problem is described in the [paper](https://github.com/JJC-code/Epidemiology-constrained-seating-plan-problem/blob/master/Epidemiology_constrained_seating_plan_problem.pdf) published in the
[Foundations of Computing and Decision Sciences](http://fcds.cs.put.poznan.pl/fcds/) journal.
The abstract and keywords of this paper are presented below.

**Abstract.** The emergence of an infectious disease pandemic may result in the
introduction of restrictions in the distance and number of employees, as was the case
of COVID-19 in 2020/2021. In the face of fluctuating restrictions, the process of
determining seating plans in office space requires repetitive execution of seat assignments,
and manual planning becomes a time-consuming and error-prone task. In this
paper, we introduce the Epidemiology-constrained Seating Plan problem (ESP), and
we show that it, in general, belongs to the NP-complete class. However, due to some
regularities in input data that could affect computational complexity for practical
cases, we conduct experiments for generated test cases. For that reason, we developed
a computational environment, including the test case generator, and we published
generated benchmarking test cases. Our results show that the problem can be solved
to optimality by CPLEX solver only for specific settings, even in regular cases. Therefore,
there is a need for new algorithms that could optimize seating plans in more
general cases.

**Keywords:** seating plan, office seat allocation, distancing policy, mixed-integer
programming, NP-complete problem
