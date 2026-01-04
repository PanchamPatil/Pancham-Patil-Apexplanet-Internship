# OpenSSL Encryption & Decryption Demo

OpenSSL is an open-source toolkit used for cryptographic operations such as encryption, decryption, and certificate management.

---

## Step 1: Create a Sample Text File

```bash
echo "This is a secret message" > secret.txt
Step 2: Encrypt the File (AES-256)
bash
Copy code
openssl enc -aes-256-cbc -salt -in secret.txt -out encrypted.txt
You will be prompted to set a password.

Step 3: Decrypt the File
bash
Copy code
openssl enc -aes-256-cbc -d -in encrypted.txt -out decrypted.txt
Enter the same password used during encryption.

Step 4: Verify the Decryption
bash
Copy code
cat decrypted.txt
You should see the original message.

Security Notes
Never share encryption keys

Use strong passwords

Prefer modern encryption algorithms like AES-256

Conclusion
This hands-on OpenSSL demo shows how encryption and decryption help protect sensitive data.

yaml
Copy code

