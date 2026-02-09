# Story Wars - GenLayer AI Battle Arena

Competitive creative writing game powered by GenLayer's Intelligent Contracts and Optimistic Democracy.

Features
- AI-generated prompts using `gl.exec_prompt()`
- AI story judging (creativity, coherence, theme)
- Optimistic Democracy challenge system
- Weekly rotating themes
- Difficulty-based XP rewards (1x, 1.5x, 2x)
- 8-minute timed battles

 Deployed Contract
Address: `0x9E016151f494a7105e8744405273Aa9737Fa8992`

**Network:** GenLayer Studio Testnet

 How to Run

1. Install dependencies:
```bash
npm install genlayer-js
```

2. Update contract address in `index.html` (line ~784)

3. Run development server:
```bash
npx vite
```

4. Open browser:
```
http://localhost:5173/
```

 Game Flow
1. Connect MetaMask wallet
2. Select difficulty (Beginner/Intermediate/Expert)
3. Receive AI-generated creative prompt
4. Write story in 8 minutes (50-500 words)
5. AI judges on creativity, coherence, theme
6. Earn XP based on score and difficulty
7. Challenge unfair scores via Optimistic Democracy

 GenLayer Features Demonstrated
- Intelligent Contracts: AI prompt generation and story evaluation
- Optimistic Democracy: Community-validated challenge system
- Consensus Mechanisms: `gl.eq_principle_strict_eq()` and `gl.eq_principle_leader_mode()`
- Weekly Content: Automatic theme rotation every 7 days

 Tech Stack
- GenLayer Intelligent Contracts (Python)
- genlayer-js SDK
- Vite
- MetaMask
- Pure HTML/CSS/JS (no frameworks)

 Scoring System
- Creativity (40%): Originality and imagination
- Coherence (30%): Story structure and flow
- Theme Alignment (30%): Relevance to prompt

 XP Rewards
- Score 90-100: 100 XP base
- Score 75-89: 75 XP base
- Score 60-74: 50 XP base
- Score <60: 25 XP base

Multiplied by difficulty:
- Beginner: 1x
- Intermediate: 1.5x
- Expert: 2x

Challenge System
Think the AI judged unfairly?
1. Click "Challenge" button
2. Validators review via Optimistic Democracy
3. If upheld: +10 points, bonus XP
4. If rejected: original score stands


## 🤝 Contributing
Built for GenLayer's community gatherings. Contributions welcome!
