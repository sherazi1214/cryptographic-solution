## 1. cryptographic-solution , 2. **[Encryption ](https://github.com/sherazi1214/-Encryption)** , 3. **[Hasing ](https://github.com/sherazi1214/-Hashing)**

## What is Cryptography?
### Definition (English):
Cryptography is the science of protecting information by transforming it into an unreadable format, so that only authorized users can access it.

### Urdu Explanation:
Cryptography ka matlab hai data ko encode (encrypt) karna taake wo hacker ya unauthorized person nahi padh sake. Sirf jis ke paas right key ho, wo data ko decrypt kar ke samajh sakta hai.

## Cryptographic Solution
### Definition:
A cryptographic solution is a method or technology that uses cryptography to protect data – such as encryption tools, digital signatures, VPNs, etc.

### Examples:
#### Solution ---------------------------------------	Use

Encryption software -------------------------------	Encrypt files or communication

Digital signatures -------------------------------	Verify sender identity and integrity

SSL/TLS ------------------------------------------	Secure web traffic (HTTPS)

VPN ----------------------------------------------	Encrypt network communication

Email encryption (PGP) ----------------------------	Secure email messages

### Urdu:
Cryptographic solution wo technology ya software hoti hai jo data ko secure banati hai. Jaise aapki banking app ya WhatsApp encryption, sab cryptography use karti hain.

## Cipher
### Definition:
A cipher is a mathematical algorithm used to perform encryption or decryption.

#### Urdu:
Cipher ek formula ya algorithm hota hai jo plain text ko cipher text mein badal deta hai (encrypt karta hai), aur phir usi formula se decrypt bhi karta hai.

### Types of Ciphers:

#### Cipher Type ------------------------------------	Description

Substitution Cipher --------------------------------	Letters are replaced (e.g., A → D)

Transposition Cipher ----------------------------------	Letters are shuffled

Block Cipher----------------------------------------	Encrypts data in fixed-size blocks (e.g., AES)

Stream Cipher--------------------------------------	Encrypts data bit by bit or byte by byte


## What are Keys in Cryptography? 
### Definition:
A key is a string of bits used by a cryptographic algorithm to encrypt and decrypt data.

#### Urdu:
Key ek secret code hoti hai jo encryption/decryption ke process mein use hoti hai. Agar key sahi ho to encrypted data wapas original ban sakta hai.

### Types of Keys:
#### Type --------------------------	Description	-------------------------------------------- Urdu

Symmetric Key -----------------------	Same key used for both encryption & decryption ---------	ایک ہی key dono kaam ke liye

Asymmetric Key --------------	Two keys: public (encrypt), private (decrypt) --------------------	Ek public aur ek private key ka use hota hai

 ## Key Security
### Definition:
Key security means protecting cryptographic keys from unauthorized access, theft, or misuse.

### Urdu:
Agar key leak ho jaye to encryption bekaar ho jata hai. Is liye key ko safely store karna, rotate karna, aur limit access dena bohot zaroori hota hai.

#### Key Security Best Practices:

Use Hardware Security Modules (HSMs)

Apply access control

Regular key rotation

Store keys separately from data

Use multi-factor authentication


## Cryptographic Strength 
#### Definition:
Cryptographic strength means how hard it is for an attacker to break the encryption or guess the key.

#### Urdu:
Cryptographic strength ka matlab hai encryption ki security level — yaani kitna mushkil hai kisi attacker ke liye usay todna.

### Depends On:
Factor	_--------------------------  Description

Key Length -----------------------------	Longer key = stronger encryption (e.g., 128-bit, 256-bit)

Algorithm Strength ---------------------	Some algorithms are outdated (e.g., DES), others are strong (e.g., AES)

Attack Resistance -----------------------	Resistant to brute force, side-channel, cryptanalysis, etc.

#### Example:

AES-256 → Very strong

DES (56-bit) → Weak and breakable


### Summary ------------------------------------------- Table

#### Topic --------------------------------------	Description (Eng + Urdu)

Cryptography ------------------------	Science of protecting information using codes (معلومات کو محفوظ بنانا)

Cryptographic Solution ----------------------	Tools that implement cryptography (جیسے encryption software)

Cipher ------------------------------	Algorithm for encrypting/decrypting data (فارمولا جو ڈیٹا کو بدلتا ہے)

Keys --------------------------------	Secret codes used in encryption (خفیہ کوڈز)

Key Security -----------------	Techniques to protect the keys (چابی کی حفاظت)

Cryptographic Strength -------------	Security level of encryption (طاقت اور حفاظت کا معیار)
