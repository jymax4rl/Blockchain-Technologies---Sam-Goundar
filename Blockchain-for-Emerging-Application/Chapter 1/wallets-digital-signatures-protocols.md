# Wallets, Digital Signatures, and Protocols

> *"A blockchain wallet is similar to a digital wallet in that it allows participants
to manage their cryptocurrency... Every transaction that is executed on the
blockchain is digitally signed by the sender using their private key. SSL is an
example of a digital signature."*  
— Xu et al., 2017

## Takeaway

### Wallets
- A **blockchain wallet** manages cryptocurrency by generating:
  - **Private Key**: a secret key used to sign transactions (like a PIN).  
  - **Public Address**: a visible identifier used to receive funds.  
- Only the public address is visible on the blockchain. No names or identities are stored.  

### Types of Wallets
- **Paper wallet** — private/public keys written on paper.  
- **Web wallet** — accessed through a browser.  
- **Mobile wallet** — smartphone app.  
- **Desktop wallet** — local application on PC.  
- (Others not listed in the book: **hardware wallets**, which store keys on physical devices).

### Digital Signatures
- Work like handwritten signatures, but use **cryptography**.  
- Created with the sender’s **private key**.  
- Verified by the recipient using the sender’s **public key**.  
- Guarantee:
  - **Authenticity**: the sender is who they claim to be.  
  - **Integrity**: the message/transaction wasn’t altered.  

### Protocol Example
- **SSL (Secure Sockets Layer)** — also uses digital signatures to secure communication between websites and users.


>[!IMPORTANT]
>## Key Takeaway
Blockchain **wallets** don’t store money directly, but rather **keys** that control access to funds.  
Digital signatures ensure secure, verifiable transactions without revealing the real-world identity of the participants.
