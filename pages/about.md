<!--
.. title: About
.. slug: about
.. type: text
.. pagekind: front_page
-->

# pyMOR School and User Meeting

pyMOR School is an annual event for future and current pyMOR users and
developers.
The seventh iteration of pyMOR School will take place in Zagreb, Croatia, from
Monday morning, September 8 to Friday noon, September 12.
Experienced users of pyMOR and related software packages are especially invited
to join us for the integrated user meeting sessions.
A code sprint will take place on Thursday evening.

The School will offer interactive introductory lectures on some of the most
important MOR methods and how to use these methods with pyMOR.
We will also discuss pyMOR's technical design, how to contribute to pyMOR and
present some more advanced applications.
In the interactive sessions, participants will have the opportunity to either
get more hands-on experience with pyMOR through exercise problems or to work on
integrating pyMOR into their own projects with the help of the pyMOR developers.

The user meeting sessions will feature user-contributed talks showcasing
pyMOR-related projects and discussion sessions to shape pyMOR's future
development.
The code sprint is an opportunity to get involved in pyMOR development with the
help of the pyMOR developers.
Of course, existing users and previous School participants are also invited to
join us for the whole week of pyMOR School.

## Organizers

The pyMOR School 2025 is organized by:

- Hendrik Kleikamp (University of Graz)
- Petar Mlinarić (University of Zagreb)
- Stephan Rave (University of Münster)
- Jens Saak (MPI Magdeburg)

## Previous Editions

1. [Magdeburg (2019)](https://2019.school.pymor.org/)
2. [Online (2020)](https://2020.school.pymor.org/)
3. [Münster (2021)](https://2021.school.pymor.org/)
4. [Magdeburg (2022)](https://2022.school.pymor.org/)
5. [Berlin (2023)](https://2023.school.pymor.org/)
6. [Münster (2024)](https://2024.school.pymor.org/)

# pyMOR

[pyMOR](https://pymor.org) is a free software library for building model order
reduction applications with the Python programming language.
Implemented algorithms include reduced basis methods as well as system-theoretic
methods.
Some of the available methods are:

- Greedy basis generation,
- Proper Orthogonal Decomposition (POD),
- Discrete Empirical Interpolation Method (DEIM),
- POD-Greedy,
- Balanced Truncation,
- Iterative Rational Krylov Algorithm (IRKA),
- models based on artificial neural networks,
- Dynamic Mode Decomposition (DMD).

All algorithms in pyMOR are formulated in terms of abstract interfaces for
seamless integration with external PDE solver packages.
Currently, there is support for [deal.II](https://dealii.org),
[DUNE](https://dune-project.org), [FEniCS](https://fenicsproject.org), and
[NGSolve](https://ngsolve.org).
Custom (domain specific) solvers can be easily integrated with pyMOR.
Moreover, pure Python implementations of FEM (Finite Element Method) and FVM
(Finite Volume Method) discretizations using the
[NumPy](https://numpy.org)/[SciPy](https://scipy.org) scientific computing stack
are provided for getting started quickly.

# Model Order Reduction

The numerical simulation of mathematical models described by partial
differential equations (PDEs) or large systems of ordinary differential
equations (ODEs) is nowadays an important tool for research in almost every
scientific discipline.
Yet, the use of such models is often limited by the available computational
resources.

Over the last decade, a variety of algorithms have been developed which compute,
for a given numerical ODE/PDE model, a mathematically certified surrogate that
can be simulated in a small fraction of the time required for the solution of
the original model.
These techniques, known as model order reduction (MOR), are now becoming an
integral part in many simulation workflows which otherwise would be infeasible,
even on the largest available supercomputers.

See the [MOR Wiki](https://morwiki.mpi-magdeburg.mpg.de/morwiki) for more
information.
