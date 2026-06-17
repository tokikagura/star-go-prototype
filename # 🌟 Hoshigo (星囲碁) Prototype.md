# 🌟 Hoshigo (星囲碁) Prototype  
  
> **"A device that generates a margin of interpretation on the board."**  
> A new board game variant that injects unexpected tactical depth into the absolute silence of Go using a once-per-game, game-breaking "Starstone."  
  
Play the live web prototype on GitHub Pages:  
👉 [Insert your GitHub Pages URL here, e.g., https://tokikagura.github.io/star-go/]  
  
---  
  
## 🌌 Concept  
  
Hoshigo (星囲碁) is a tactical experiment based on traditional 9x9 Go, granting players a single-use special asset called the **"Starstone"** that transcends standard rules.  
  
The core design centers around the psychological warfare of **"The Pressure of the Unused Hand"** and the bluffing potential of the Free-Color declaration. It aims to bypass purely rational AI optimization, creating a space where spectators ask, *"Why did they play there?"*  
  
---  
  
## 📜 Starstone Core Rules  
  
1. **Once-per-Game Summon**  
   Each player can deploy a "Starstone" instead of a regular stone exactly once per match.  
2. **Free-Color Declaration**  
   Even on your own turn, you can freely declare your Starstone to be placed as either **Black or White**.  
3. **Expiration Conditions**  
   Depending on the match settings, the right to summon the Starstone expires during the endgame (when empty squares ≤ 25) or after the first Pass, amplifying the tension of timing.  
  
---  
  
## 🛠️ Changelog  
  
### 🚀 v1.2 (Latest Stable) - *June 18, 2026*  
- **"Sewing Machine" Exploitation Fix**: Implemented `computeDiagonalSewingPenalty` to penalize hollow, zig-zag formations connected only diagonally without solid orthagonal links.  
- **Vulnerability Simulation**: Upgraded the AI's core evaluation to actively fear and detect "critical gaps" that allow immediate opponent cuts or Ataris.  
- **Starstone Guardrails**: Taught the AI resource management; if it can safely escape an Atari using a standard stone, it will hoard the precious Starstone.  
  
### ⚔️ v1.1 - *June 17, 2026*  
- **Tactical Combat Awakening**: Fixed a critical typo bug within the 3-ply lookahead loop. The CPU now accurately fears losing stones and switches to an aggressive, high-performance combat mode.  
  
### 🧪 v1.0 (Initial Prototype) - *June 17, 2026*  
- **First Build Completed**: Integrated a lightweight MCTS (Monte Carlo Tree Search) engine tailored for 9x9 Go, alongside the core implementation of the Free-Color Starstone mechanics.  
  
---  
  
## 👥 Credits & License  
  
- **Concept & Design**: Tokikagura ([@_tokikagura](https://x.com/_tokikagura))  
- **Development**: AI-assisted Prototyping Project  
- *This project is a private experimental build. The custom rules are layered on top of optimized open-source heuristic algorithms.*  
