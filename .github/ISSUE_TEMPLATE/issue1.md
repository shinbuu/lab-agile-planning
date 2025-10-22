---
name: issue1
about: " Loading and encrypting data on the client"
title: ''
labels: ''
assignees: ''

---

---

## 🧩 USER STORIES 

---

### 
**As a** data owner  
**I need** to encrypt my local data using homomorphic encryption before sending it to the cloud  
**So that** my sensitive information remains confidential during cloud computation  

### Details and Assumptions
* Используется библиотека Microsoft SEAL (CKKS/BFV)  
* Ключи генерируются локально (pk, sk)  
* Шифрование выполняется до передачи на сервер  

### Acceptance Criteria
```gherkin
Given the user has local data
When they select a file and click "Encrypt"
Then the ciphertext is created and stored locally or uploaded securely
