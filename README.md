# Eat-n-Split

A small React app to keep track of friends and split bills — built while I was learning React.

> **Note:** This project stores data in memory (React state). Refreshing the page will reset friends and balances.

---

## Features

- Add friends with a name and avatar URL
- Select a friend to view their balance (you owe / they owe / even)
- Split a bill with the selected friend and choose who pays
- Update the selected friend's balance after splitting
- Simple, clean UI built with plain CSS and React functional components

---

## Getting started

1. **Clone repo**

```bash
git clone https://github.com/raghadislam/Eat-n-Split.git
cd Eat-n-Split
```

2. **Install dependencies**

```bash
npm install
```

3. **Run**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) (or the port shown in the terminal).

---

## Usage

1. Click **Add friend** to open the add-friend form (enter name and an image URL).
2. Click **Select** on a friend to open the split-bill form for that friend.
3. Enter total bill and your share, choose who paid, then click **Split bill**.
4. The friend's `balance` will update: a positive value means they owe you; a negative value means you owe them.

---

## Project structure (suggested)

```
/Eat-n-Split
├─ /public
├─ /src
│  ├─ App.js
│  ├─ index.js
│  └─ index.css
├─ .gitignore
├─ package-lock.json
├─ package.json
└─ README.md
```
