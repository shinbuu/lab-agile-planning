---
name: issue1
about: Client-Side Data Encryption
title: ''
labels: ''
assignees: ''

---

# Client-Side Data Encryption

**As a** data owner  
**I need** to encrypt my local data using homomorphic encryption before sending it to the cloud  
**So that** my sensitive information remains confidential during cloud computation  

### Details and Assumptions  
* The Microsoft SEAL library (CKKS/BFV) is used  
* Keys (pk, sk) are generated locally  
* Encryption occurs before data transmission to the server
