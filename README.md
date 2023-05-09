# MATLAB-Simulation-
Simulation of the learning process of gait retraining using real-time feedback in patients with medial knee osteoarthritis


The aim of this study was to investigate the gait retraining process of patients with knee osteoarthritis (KOA) to change their foot advancement angle (FPA) during a six-week walking training program. Sixteen patients with KOA underwent a six-week gait training program with real-time biofeedback. Patients walked on a treadmill while receiving real-time feedback from the foot advancement angle (FPA) pointing to a target angle. The difference is FPA (angle difference between target and actual). The possible modes are: (a) natural walking, (b) walking with feedback, (c) walking without feedback, (d) walking with a dual task at the beginning and end of the training program with stroop test.

(A): The FPA difference during normal walking decreased significantly from a mean of 6.9 to a mean of 3.6 degrees, i.e., a mean difference of 3.3 degrees at week 6.
That is, there is a 14.7% improvement in natural walking.

(b) By adding feedback the FPA difference becomes almost zero. That is, FPA in the first week reaches from 0.7 to 0.1 in the sixth week.
That is, there is 90.8% improvement in walking by adding feedback.

(c) Walking without feedback, the FPA difference goes from 1.3 to 0.5.
That is, there is 80.9% improvement in walking by adding feedback.

(d) walking with a dual task at the beginning and end of the training program, the FPA difference goes from 2.5 to 0.7.
That is, there is a 77.8% improvement in walking by adding feedback.
As a result, in patients with internal KOA, they can reduce the FPA difference during normal walking after walking retraining. But sometimes it may be necessary to support more permanent feedback using wearable technologies.

![knee](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/dfb40003-b655-405c-8317-15257e4037c6)


Introduction

In people with internal knee arthrosis (KOA), a knee extension moment (KAM) often occurs, which increases more rapidly as the disease progresses.
Correcting the foot advancement angle (FPA) during walking can reduce KAM [2–9]. Real-time biofeedback can be used to teach gait changes [3–5,8–10]. There is evidence that patients can learn to cope with gait changes in the short term. Gait changes have beneficial short-term biomechanical effects [2,5,8,9]. However, there is limited evidence to show whether corrections can actually be learned.
Cognitive load can be measured using near-infrared functional spectroscopy [1] or electroencephalography.
However, experiments show that walking is not fully automatic [11] and that movement control via a central pattern generator is possible. The paradigm represents many of the important distractions while walking that one encounters every day, for example talking while walking, can affect the walking pattern and can be corrected with a little awareness. did


![knee matlab](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/bec24324-d23a-439d-b050-c09712a80ee8)


Data analysis
Considering that the knee angle is between 8 and 9 degrees in a normal state, and in people with internal knee osteoarthritis (KOA), a knee extension moment (KAM) often occurs, which is accompanied by a faster increase with the progression of the disease. . And this increase has been measured using near-infrared functional spectroscopy [1] or electroencephalography, and it is corrected by using the process of training the walking pattern by the orthopedist by the aforementioned methods. We generate data accordingly.

![knee rehab](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/03bc944a-a72d-4550-8040-98de335b004f)


In the data generation code, the upper knee angle x can be based on the upper and lower limits in the first or sixth week of four correction patterns: normal walking, walking with feedback, walking without feedback, walking with two actions. The number of records selected is 1000.
Simulation with Matal software
Here we inject the data generated in the data analysis section into the simulated knee and observe its movement.
For simulation, we referred to SimMechanics documentation [12]
Animated modes
Common blocks provide two moving parameters. These parameters, Force/Torque and Motion, control how the joint behaves during simulation. Depending on the parameter settings you choose, a common block can accept the excitation parameter as input or automatically calculate its value during simulation. An additional setting allows you to set the actuation force/torque directly to zero. The initial connection joint is free during simulation, but has no actuator input. Indirect motion is due to forces and moments acting elsewhere in the model or directly to the velocity state targets.
Blocks used

![knee blocks](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/b0167d91-82d2-40e8-aef5-942dfc76d8c6)

![knee blocks properties](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/438dc6f3-6929-4437-9df0-523eec366bd3)

Simscape > Multibody > Joints

![knee blocks MATLAB](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/4af9f61e-0858-48a2-92bf-efe9582e0482)


![knee blocks MATLAB axis](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/baf7d198-0d1e-445c-9ce6-3fbd176512c4)


![knee blocks MATLAB length](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/7806fc10-62b7-4be9-8d6d-4447d68ca53c)


![knee blocks MATLAB variables](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/fc4a39b6-18ca-4d57-abda-f9248d8474a4)


Charts and results



The difference in foot advancement angle (FPA) in week 1 (start of training) and week 6 (end of training). A positive difference indicates that the FPA has more external rotation compared to the target angle, while a negative difference indicates that the FPA has rotated more compared to the target angle. The patient's own perception of difficulty and awkwardness in using the modifications may affect the ability to learn the modifications.


Charts and results



Discuss


In this study, we investigated the learning process during toe walking retraining in patients with medial KOA of the knee during a six-week walking training program. Firstly, performance accuracy, expressed by FPA difference, and secondly, performance stability has been analyzed, in four phases (natural walking, feedback, retention and dual task conditions) the percentage of target steps is expressed. Accuracy and consistency of performance during the training period were observed with a large decrease in FPA difference and an increase in the percentage of target steps in all conditions. This suggests that patients with internal KOA are not only able to adapt their gait pattern during a session, but also can learn and adopt gait changes over several sessions.
Conclusion
In conclusion, KOA patients reduced FPA difference and increased target steps after a six-week gait training program. Better performance accuracy and reduced dual-task interference at week six show reduced cognitive demand and evidence of slow learning. However, the altered walking pattern after the training program was not completely independent. Future studies should consider home training with wearable technology to encourage full autonomy of the altered walking pattern.
![knee blocks MATLAB result plot](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/3dbac823-cf0a-40a5-aba3-013b8f2edb03)

![knee blocks MATLAB result](https://github.com/RoshaSoft/MATLAB-Simulation-/assets/85801966/b9f2ee36-ed0f-450e-bc84-57c706e231cd)



References
[1] F. Herold, P. Wiegel, F. Scholkmann, A. Thiers, D. Hamacher, L. Schega, Functional near-infrared spectroscopy in movement science: a systematic review on cortical activity in postural and walking tasks, Neurophotonics 4 (2017) Available online.
[2] P.B. Shull, R. Shultz, A. Silder, J.L. Dragoo, T.F. Besier, M.R. Cutkosky, et al., Toe-in gait reduces the first peak knee adduction moment in patients with medial compartment knee osteoarthritis, J. Biomech. 46 (2013) 122–128. 
[3] P.B. Shull, A. Silder, R. Shultz, J.L. Dragoo, T.F. Besier, S.L. Delp, et al., Six-week gait retraining program reduces knee adduction moment, reduces pain, and improves function for individuals with medial compartment knee osteoarthritis, J. Orthop. Res. 31 (2013) 1020–1025. 
[4] M.A. Hunt, J. Takacs, Effects of a 10-week toe-out gait modification intervention in people with medial knee osteoarthritis: a pilot, feasibility study, Osteoarthr. Cartil. 22 (2014) 904–911. 
[5] M. Simic, T.V. Wrigley, R.S. Hinman, M.A. Hunt, K.L. Bennell, Altering foot progression angle in people with medial knee osteoarthritis: the effects of varying toein and toe-out angles are mediated by pain and malalignment, Osteoarthr. Cartil. 21 (2013) 1272–1280. 
[6] H.J. Bennett, S. Zhang, G. Shen, J.T. Weinhandl, M.R. Paquette, J. Reinbolt, et al. Effects of toe-in and wider step width in stair ascent with different knee alignments, Med. Sci. Sports Exerc. 49 (2017) 563–572. 
[7] M.R. Paquette, G. Klipple, S. Zhang, Greater step widths reduce internal knee abduction moments in medial compartment knee osteoarthritis patients during stair ascent, J. Appl. Biomech. 31 (2015) 229–236. 
[8] R. Richards, J.C. van den Noort, J. Dekker, J. Harlaar, Gait retraining with realTime biofeedback to reduce knee adduction moment: systematic review of effects and methods used, Arch. Phys. Med. Rehabil. 98 (2017) 137–150. 
[9] R.E. Richards, J.C. van den Noort, M. van der Esch, M.J. Booij, J. Harlaar, Effect of real-time biofeedback on peak knee adduction moment in patients with medial knee osteoarthritis: is direct feedback effective? Clin. Biomech. (Bristol, Avon) (2017).
[10] J.C. van den Noort, F. Steenbrink, S. Roeles, J. Harlaar, Real-time visual feedback for gait retraining: toward application in knee osteoarthritis, Med. Biol. Eng. Comput. 53 (2015) 275–286.
[11] N. Shkuratova, M.E. Morris, F. Huxham, Effects of age on balance control during walking, Arch. Phys. Med. Rehabil. 85 (2004) 582–588.
[12] 1994-2021 The MathWorks, Inc. Available online. https://www.mathworks.com/help/physmod/sm/ug/joint-actuation.html.
