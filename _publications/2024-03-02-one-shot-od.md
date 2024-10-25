---
title: "One-shot Initial Orbit Determination in Low-Earth Orbit"
collection: publications
permalink: /publication/2024-03-02-one-shot-od
excerpt: ''
date: 2024-03-02
paperurl: ''
citation: 'R. Ferreira, M. Guimar˜aes, F. Valdeira, and C. Soares, “One-shot Initial Orbit Determination in Low-Earth Orbit", 2024 IEEE Aerospace Conference. IEEE, pp. 1–11, 2024'
paperoglink: 'https://ieeexplore.ieee.org/abstract/document/10521177'
---

Abstract 
--------

Due to the importance of satellites for society and the exponential increase in the number of objects in orbit, whether they are space debris or functional satellites, it is important to accurately determine the state (e.g., position and velocity) of these Resident Space Objects (RSOs) at any time and in a timely manner. State-of-the-art methodologies for initial orbit determination consist of Kalman-type filters that process sequential data over time and return the state and associated uncertainty of the object, as is the case of the Extended Kalman Filter (EKF). However, these methodologies are dependent on a good initial guess for the state vector and usually simplify the physical dynamical model, due to the difficulty of precisely modeling perturbative forces, such as atmospheric drag and solar radiation pressure. Other approaches do not require assumptions about the dynamical system, such as the trilateration method, and require simultaneous measurements, such as three measurements of range and range-rate for the particular case of trilateration. We consider the same setting of simultaneous measurements (one-shot), resorting to time delay and Doppler shift measurements. Based on recent advancements in the problem of moving target localization for sonar multistatic systems, we are able to formulate the problem of initial orbit determination as a Weighted Least Squares. With this approach, we are able to directly obtain the state of the object (position and velocity) and the associated covariance matrix from the Fisher’s Information Matrix (FIM). We demonstrate that, for small noise, our estimator is able to attain the Cramér-Rao Lower Bound accuracy, i.e., the accuracy attained by the unbiased estimator with minimum variance. We also numerically demonstrate that our estimator is able to attain better accuracy on the state estimation than the trilateration method and returns a smaller uncertainty associated with the estimation.
