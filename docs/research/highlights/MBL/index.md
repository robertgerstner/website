# Many-Body Localization

## Brief Description

<figure style="float:right; margin-right:10px; width:400px; text-align:center;">
    <img src="./media/mblgraph.png" alt="graph" style="height:452px; width:400px;">
    <figcaption style="font-size:small;">A graph representing operator growth in the disordered XX model.</figcaption>
</figure>

In 1958, [Anderson](https://journals.aps.org/pr/abstract/10.1103/PhysRev.109.1492) showed that in the presence of disorder in a one-dimensional crystal lattice, single-particle eigenfunctions become localized near a particular site. This phenomeon has become known as Anderson localization. Ever since this result, an open question has remained of whether such localization survives in a many-particle system with interactions: does many-body localization (MBL) exist? If such a phenomenon persisted in the thermodynamic limit, it would go against our normal understanding in statistical mechanics that all systems thermalize. Further, it would imply that the system retains a memory of its initial conditions, allowing for a form of quantum memory.

Many scientists have used perturbative and numerical arguments in favour of MBL, and many have studied the MBL transition (at what disorder strength does a system become localized). Published in 2016, [Imbrie](https://link.springer.com/article/10.1007/s10955-016-1508-x) attempted to provide a proof of MBL for a one-dimensional spin chain, using the mixed-field Ising model with random couplings. However, there has recently been a growing body of evidence that MBL does not exist, and our intuitive notion of thermalization indeed prevails. Our research project contributes to this body of evidence, perhaps most strongly.

In particular, we attacked the problem from a new angle by studying the growth and spreading of local operators under Heisenberg time evolution rather than the evolution of wave functions themselves. We used this to develop benchmarks for localization based on operator norm bounds and the spatial support around the lattice. We find that a representation of the Hamiltonian as an effective form in terms of local conserved charges with terms exponentially suppressed with their length, which is expected for an MBL phase, is likely not possible. Please see our [paper](https://arxiv.org/abs/2401.08031) for more details. The paper, which primarily covers the Heisenberg model, is currently undergoing revisions. More results involving the mixed-field Ising model will come out soon. 

## More Information

<figure style="float:right; margin-right:10px; width:444px; text-align:center;">
    <img src="./media/usra.jpg" alt="usra" style="height:300px; width:444px;">
    <figcaption style="font-size:small;">University of Manitoba, Aug. 17 2023</figcaption>
</figure>

I was involved in this project as a summer student with Prof. [Jesko Sirker](http://drop.physics.umanitoba.ca/~jsirker/Dokuwiki/doku.php?id=home) at the University of Manitoba in 2023, continuing part-time Jan. 2024. I then joined him again in summer 2024 to help revise the paper and get new results in the mixed-field Ising model. Our project was in collaboration with Dr. [Alexander Weiße](https://people.mpim-bonn.mpg.de/weisse/) at the Max Planck Institute for Mathematics in Bonn, Germany. Dr. Weiße was most responsible for the associated numerical work, while Dr. Sirker and I were most responsible for the analytical work. One of my more interesting developments was a way to model operator growth using graph theory.

In 2023, I created a [poster](./media/mblposter.pdf) on this project, and presented it at the University of Manitoba as well as the Canadian Undergraduate Physics Conference in Waterloo, ON. I also gave an [oral presentation](./media/mblslides.pdf) at Dr. Sirker's group seminar. I plan to give another talk at the 2025 APS March Meeting in Anaheim, CA.