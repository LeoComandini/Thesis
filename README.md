# *sign-to-contract*: how to achieve digital notarization with zero marginal cost

This thesis has been realized for the obtention of the Master's in Mathematical Engineering at the Politecnico di Milano. 

## Abstract

Proving that data existed prior to a certain time is helpful in several situations.
Thanks to systems achieving distributed consensus without relying on a trusted third party, like Bitcoin, it is possible to enhance the security of such timestamps.
[OpenTimestamps](https://opentimestamps.org) is a protocol defining a standard for creating timestamps and, in addition, it provides a scalability solution.
Currently, an improvement concerning elliptic curve commitments has been [proposed](https://github.com/opentimestamps/python-opentimestamps/pull/14). 
We aim to give an exhaustive overview upon this new scheme, its implications and motivations, culminating in the development of a real world application.

## Related material

- [Blog post](https://blog.eternitywall.com/2018/04/13/sign-to-contract/) on *sign-to-contract*;
- [Electrum timestamp plugin](https://github.com/LeoComandini/electrum-timestamp-plugin) (switch to branch `s2c` to include *sign-to-contract* timestamping).
