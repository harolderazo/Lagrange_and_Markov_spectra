# Lagrange_and_Markov_spectra
This project contains several tools to study the Lagrange and Markov spectra, with special emphasis on studying the difference set.
For an introduction to these fractal sets, see the book "Classical and Dynamical Markov and Lagrange Spectra".
All the code included here is python and uses [SageMath](https://www.sagemath.org).

This repository contains code used to test if some non semisymmetric word of odd length satisfies local uniqueness and self-replication.
In case the test is positive, the program proofs these properties rigourously and determines the region of the difference set explicitly.
Based on this code, an implementation to study examples in $M\setminus L$ that contain intruder sets. This code proves rigourously if points of $M\setminus L$ can be separated from the intruder sets.

The repository also contains some datasets containing all nonsemisymmetric orbits of odd minmial period up to certain length in the alphabets {1,2} and {1,2,3} that additionally have Markov values below Hall's ray.
From these previous orbits, the subset of those orbits for which we can confirm that points of $M\setminus L$ exists are also stored in different datasets.


Some tools developed in this project:
* Compute Markov values of doubly periodic sequences [Appendix A](https://doi.org/10.4064/aa240821-26-5).
* Compute Markov values of purely periodic sequences [Lemma 17](https://doi.org/10.1016/j.exmath.2006.10.002).
* Find sequences whose Markov values lie in a certain interval. This function is an improvement of the algorithm presented in [Appendix B](https://doi.org/10.5802/jtnb.1280).
* Minimize and maximize continued fractions in a finite alphabet given some finite word restrictions.
* Simplify a finite set of forbidden words describing subshift of finite type to find the simplest representation.
* Minimize and maximize Markov values of finite strings.
* Find explicitly the endpoints of a Markov gap.
* Find maximum and minimum of Markov values of sequences in a finite type subshift.
 
