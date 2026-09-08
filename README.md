<div align="center">

# 🏰 Mission I: The Fallen Gates of Codoria

### ⚔️ Repair the Royal Server and reopen the kingdom ⚔️

![Status](https://img.shields.io/badge/Kingdom%20Status-Gates%20Locked-8B0000?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-Node.js%20%2B%20Express-355E3B?style=for-the-badge)
![Time](https://img.shields.io/badge/Time-8%20Minutes-B8860B?style=for-the-badge)
![Mode](https://img.shields.io/badge/Formation-Teams%20of%203-4B0082?style=for-the-badge)

</div>

---

## 📜 The Royal Summons

The **Dark Bug** has attacked the Kingdom of Codoria! Its main gates have been sealed, and no messenger can enter or leave the kingdom.

The gate is controlled by an Express route, but the Dark Bug has damaged the Royal Server's code. The King has summoned the realm's finest **Software Knights** to find the bugs, repair the route, and reopen the gates before time runs out.

> **Software Knights, the kingdom is depending on you!**

---

## 🗺️ Mission Brief

| Mission detail | Information |
|---|---|
| ⏳ Time limit | 8 minutes |
| 👥 Formation | Teams of 3 |
| ⚔️ Difficulty | Beginner |
| 🧰 Technology | Node.js and Express |
| 🐛 Main objective | Find and repair 3 bugs |
| ⭐ Bonus quest | Create a second route |
| 🏆 Maximum reward | 20 Kingdom Points |

---

## 👥 Assign Your Royal Roles

Before the timer begins, assign one role to every team member:

| Role | Responsibility |
|---|---|
| ⚔️ **Knight Coder** | Controls the keyboard and writes the team's code |
| 🧭 **Royal Navigator** | Reads the instructions and guides the Knight Coder |
| 🔍 **Bug Hunter** | Tests the server, reads errors, and records each bug |

> All three Software Knights must participate. Your roles will rotate in the next mission.

---

## 🎯 Your Mission

The damaged code contains **three bugs**. Work together to locate and repair them.

When the Royal Server is repaired, visiting the following address should open the gates:

```text
http://localhost:3000/gate
```

The browser must display:

```text
🏰 The gates of Codoria are open!
```

---

## 🐛 Damaged Royal Code

Open `server.js` and inspect the code carefully:

```js
const express = require('express')

const app = express

app.get('gate', function (req, res) {
  res.sent('🏰 The gates of Codoria are open!')
})

app.listen(3000, function () {
  console.log('⚔️ Royal server is running on port 3000')
})
```

Do not rewrite the entire server. Investigate the existing code and repair only what is broken.

---

## 🧪 Test the Royal Server

After repairing the code:

1. Save `server.js`.
2. Start the server:

```bash
node server.js
```

3. Read the terminal message.
4. Open `http://localhost:3000/gate` in the browser.
5. Confirm that the correct message appears.

---

## ✅ Victory Conditions

Your team may declare victory only when:

- [ ] The server starts without errors
- [ ] The terminal confirms that the server is running on port `3000`
- [ ] Visiting `/gate` displays the correct message
- [ ] Your team has identified all three bugs
- [ ] Every Software Knight can explain at least one part of the solution

---

## ⭐ Bonus Quest: Welcome the King

Finished the main mission? Create a second Express route:

```text
/king
```

When the route is visited, it should display:

```text
👑 Welcome, Your Majesty!
```

---

## 🏆 Kingdom Points

Your team can earn up to **20 Kingdom Points**:

| Achievement | Points |
|---|---:|
| The server starts successfully | 3 |
| The `/gate` route works correctly | 5 |
| The team identifies and explains all 3 bugs | 5 |
| Every Software Knight participates | 3 |
| The bonus `/king` route works | 3 |
| The team uses clear code and a meaningful commit | 1 |
| **Maximum score** | **20** |

### 📖 Point Rules

- Every team receives the full eight minutes.
- Finishing first does not automatically earn extra points.
- Each opened hint costs the team **1 Kingdom Point**.
- Teamwork and understanding are more important than speed.
- Code copied from another team earns no points.
- Your team must be able to explain all submitted code.

---

## 🔮 The Royal Book of Hints

Open a hint only if your entire team is stuck. Each opened hint costs **1 Kingdom Point**.

<details>
<summary>🕯️ Open Hint I — The Express Spell</summary>

Look carefully at the line that creates `app`. Are you storing Express itself, or calling it to create an Express application?

</details>

<details>
<summary>🗝️ Open Hint II — The Route Path</summary>

Express route paths begin with a special character.

</details>

<details>
<summary>📯 Open Hint III — The Royal Response</summary>

Check the spelling of the Express response method used to send text to the browser.

</details>

---

## 📤 Declare Your Victory

Before the timer ends:

1. Test the application in the terminal and browser.
2. Make sure every team member understands the repairs.
3. Commit your changes using a meaningful message:

```text
Repair the fallen gates of Codoria
```

4. Select one Software Knight to present the team's solution.

The instructor may ask **any team member** to explain one of the bugs.

---

## 🛡️ The Royal Code

- Work only with your assigned team.
- Let every Software Knight contribute.
- Test before declaring victory.
- Read error messages before requesting help.
- Do not copy code from another team.
- Do not use AI-generated code that you cannot explain.
- Be respectful and support your fellow knights.

---

<div align="center">

## ⚔️ Are You Ready? ⚔️

**The gates are locked. The clock is ticking. Codoria needs its Software Knights!**

🏰 May your code run and your bugs surrender! 🐛

</div>
