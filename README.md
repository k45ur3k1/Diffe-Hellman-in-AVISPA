# Diffe-Hellman-in-AVISPA
Diffie Hellman is used to exchange keys between 2 people &amp; The security of DH relies on the difficulty of computing discretelogarithm over a large prime order cyclic group.
#no exchange of keys happen, only some public variable are shared.
DH is asymmetric because each side has a different key to start with and they end up with the same secret key.
Here, we have implemented DH in AVISPA tool which resulted unsafe. After implementing Digital Signatures in the protocol and checking against CL-AtSe and OFMC backend for security proofs we finally got the result as safe.

Overview of AVISPA tool 
Avispa stands for Automated Validation of Internet
Security-sensitive Protocols and Applications. To devise and analyze a protocol, Avispa provides its own High-Level Protocol Specification Language (HLSPL). The file is saved with an extension of HLSPL. To check security,  Avispa translates the provided HLSPL specification in the intermediate format IF, which then can be passed through any of the 4 different verification machines i.e. OFMC, CL-ATSE, SATMC, TA4MC. 
– CL-AtSe: Constraint-Logic-based Attack Searcher. 
– OFMC: the On-the-Fly Model-Checker.
–   SATMC: the SAT-based Model-Checker.
– TA4SP: the Tree Automata tool based on Automatic Approximations for the Analysis of Security 

AtSe:

![DHAtSe](https://user-images.githubusercontent.com/55327652/131326752-f4a4ed4b-740d-4be8-a8ef-d5f40880f215.png)

OFMC:

![DHOFMC](https://user-images.githubusercontent.com/55327652/131326773-0ca8b44c-07e4-46e2-95c8-fdeab2f1f4b5.png)

Intruder Simulation:

![DHIntruderSimulation](https://user-images.githubusercontent.com/55327652/131326778-c3b65230-bf37-4669-9fdb-40d2e420606b.png)

Protocol Simulation: 

![DHprotocolSimulation](https://user-images.githubusercontent.com/55327652/131326793-19c065ff-4865-4d38-856c-2da1f8caeae7.png)
