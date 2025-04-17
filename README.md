# node18_ubuntu


Here’s how you can upgrade to Node.js 18 on Ubuntu (or most Debian-based Linux systems):

---

## 1. Remove the old Node.js version

```bash
sudo apt-get remove nodejs libnode-dev libnode72
sudo apt-get autoremove
```

---

## 2. Add the NodeSource repository for Node.js 18

```bash
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```

---

## 3. Install Node.js 18

```bash
sudo apt-get install -y nodejs
```

---

## 4. Verify the installation

```bash
node -v
npm -v
```
You should see something like:
```
v18.x.x
```

---

**Summary:**  
Remove the old Node.js, add the NodeSource repo, and install Node.js 18.  
If you run into any errors, please copy and paste them here for further help!


sudo apt-get install -y libgbm1 libnss3 libatk-bridge2.0-0 libx11-xcb1 libxcomposite1 libxdamage1 libxrandr2 libasound2 libpangocairo-1.0-0 libgtk-3-0
