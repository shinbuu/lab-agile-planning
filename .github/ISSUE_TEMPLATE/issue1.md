## Loading and encrypting data on the client

### 
**As a** data owner  
**I need** to encrypt my local data using homomorphic encryption before sending it to the cloud  
**So that** my sensitive information remains confidential during cloud computation  

### Details and Assumptions
* The Microsoft SEAL library (CKKS/BFV) is used  
* Keys (pk, sk) are generated locally  
* Encryption occurs before data transmission to the server  

### Acceptance Criteria
```gherkin
Given the user has local data  
When they select a file and click "Encrypt"  
Then the ciphertext is created and stored locally or securely uploaded to the cloud
 ```
