# PMSM_FOC_LTID_SMO
FOC control of a PMSM motor with a Sliding Mode Load Observer (SMO). It was implemented in MATLAB/Simulink 2018b.

The estimated load is used for feedforward load-torque compensation. The used Sliding Mode Observer is of first-order.

A short design documentation is attached, however, this algorithm is in pre-alpha release. So, the documentation is not complete as of now.
The design is heavily based / inspired by the following publication: A New Load Torque Identification Sliding Mode Observer for Permanent Magnet Synchronous Machine Drive System. Published by an AAU (Denmark) / Zhejiang Sci-Tech University (Hangzhou, China) based research group. You can find it in IEEE Transactions on Power Electronics, vol. 34, no. 8, journal.

Initialization is done in: Model Properties / Callbacks / InitFcn*
