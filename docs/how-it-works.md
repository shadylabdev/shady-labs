# How It Works

Shady Labs uses a **stealth address protocol** that hides the link between sender and receiver on Solana.

1️⃣ **Receiver creates Meta Key** — a combination of a View Key and a Spend Key.  
2️⃣ **Sender generates a unique stealth address** from that Meta Key.  
3️⃣ **Transaction is encrypted locally** and sent to Solana as ciphertext.  
4️⃣ **Receiver’s wallet scans and decrypts** to find incoming private funds.  
5️⃣ **Funds are claimed** with the Spend Key — and the stealth address self-destructs.

Each transfer is private, unlinkable, and encrypted — ensuring no one can trace who sent or received funds.
