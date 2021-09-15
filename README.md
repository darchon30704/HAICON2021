# HAICON2021

[Title]

AI Challenge for Industrial Control System Threat Detection


[Subject]

Industrial Control System Security Threat Detection


[Background]

Recently, cybersecurity threats to the control systems of national infrastructure and industrial facilities are continuously increasing. Cyberattacks on critical national facilities can cause enormous irreparable damage to countries and societies, and they are concentrating on developing security technologies to prevent the threats.
The industrial control system security dataset that has the characteristics of on-site control systems and includes various control system cyber attacks is an essential element for AI-based security technology research.
In response to the needs of these research sites, the National Security Research Institute established a testbed for a power generation control system using industrial control devices, sensors, and actuators from GE, Emerson, and Siemens in 2019.
The National Security Research Institute is continuously developing industrial control system security data sets (HAI) using the testbed and has released HAI 20.07 and HAI 21.03 data sets to solve data shortages in research sites.
HAICon 2021 will be held for the second time following the first competition HAICon 2020 to activate AI-based security threat detection research and dissemination of technology using HAI security dataset.
We intend to continuously raise the level of related skills by sharing the model of the winning team, and an improved version of the competition dataset will be released through feedback from participants.


[Host/Organizer/Support/Operation]

Host and organizers: National Intelligence Service and National Security Research Institute, South Korea
Support: Korea Institute of Information Security & Cryptology, South Korea
Operation: Dacon


https://dacon.io/en/competitions/official/235757/data


[Current Work]

Used a 3-layer Stacked GRU model (with 50 units in each layers), and a threshold (for the anomaly score) of 0.04
An F1 score defined by the contest was used for evaluation.
F1: 0.120 (TaP: 0.127, TaR: 0.115)
# of detected anomalies: 2

![E(50)__88_50_3_256_0 04_evaluation](https://user-images.githubusercontent.com/36047953/133432916-413182c9-c178-4c83-ab2c-a14663eb2a00.png)



[Future Plans]
Some parameter tuning for the Stacked GRU model. Perhaps using 200 units, changing the window size, changing the threshold, or remove features to be normalize could increase the performance.

Another idea is to use a completely different architecture, such as transformers.
