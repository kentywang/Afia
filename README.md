## Afia

### Decentralized Personal Health Record Application
Afia is a webapp prototype that gives individuals the power to own and control their personal health records (PHR) and securely share them with health care providers upon request. Afia's API allows users to selectively export health records to providers' proprietary systems in the industry standard CCR format. Trusted providers can append additional information to the person's PHR through signing using their own Blockstack ID, ensuring accountability and allowing future verification. The PHR is encrypted and stored onto existing HIPPA-compliant cloud infrastructures. Access to the information can only be granted and decrypted with the owner's Blockstack ID private key.

![](https://github.com/kentywang/Afia/blob/master/afia.gif)

### Blockstack and Afia
[Blockstack](https://blockstack.org/intro) is a decentralized DNS that can be built up on existing blockchains, allowing for unhosted applications that run through user-owned identities.

Afia is an extension of that identity system known as Blockchain ID, allowing users to own their personal health records in a decentralized manner and share them with trusted health care providers through its API.

### Securely Sharing Data
With Afia, users have the ability to share their health records with other users, such as health care providers or family members. Access can be selectively granted such that requesters may only see certain portions of the user's health record, or they may be prohibited from appending additional information to the user's records.

To access a patient's data, health care providers use Afia's API integrated into their proprietary systems to request access to a patient's records using the providers' own Blockstack ID. Once access has been granted by the patient, the API then allows the records to be exported in the industry standard CCR format. Through the API, providers can also append new information to the patient's record. Appending any new data requires a digital signature from the author's Blockstack ID, to allow for verification.

Users can check the digital signature and ID of the author to ensure that the appended record was added by the trusted individual.

### Pitch Deck and Live Demo
A brief presentation introducing Afia can be found [here](http://slides.com/aganita/afia#/), and an online prototype of Afia (with annotations) can be found [here](https://invis.io/PXAF8L8YJ).

### Credits
Logo created with: http://logomakr.com
