# 🐾 Dog's Linux Secret  
**Dog's Linux Secret** is a handcrafted Linux puzzle challenge built inside a custom Ubuntu 22.04 LTS WSL environment.
Your goal is to progress through a series of users — starting with `dog` and ending with `dogfinal` — by uncovering hidden files, decoding clues, and navigating the filesystem.
Each user contains exactly one path forward, and the final user reveals the completion message.
This challenge is inspired by classic Linux wargames and is designed to be approachable, fun, and fully self‑contained.

---

# 🔑 Starting Credentials
When you launch the challenge, you will begin as the first user:
- **Username:** `dog`
- **Password:** `leg`  
Log in using:
```Bash
su - dog
```

---

# 📦 Installation (WSL Import)
1. Download the release file:  
   `Dogs-Linux-Secret.tar`
2. Import it into WSL using PowerShell:
```PowerShell
wsl --import Dogs-Linux-Secret C:\WSL\DOG Dogs-Linux-Secret.tar
```
You may choose any installation directory you prefer.  
3. Start the challenge:
```PowerShell
wsl -d Dogs-Linux-Secret
```
You will be placed directly into the starting environment as the first user, `dog`.
