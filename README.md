# AI_checkers
AI Checkers Player built in Python using minimax with alpha-beta pruning. The AI anticipates opponent moves, values kings and captures, and plays competitively against humans on an 8x8 board. Tested across multiple depths, it showcases search algorithms, evaluation heuristics, and game AI design.

---

## ✨ Features  
- ✅ Full implementation of **checkers rules** (diagonal moves, captures, king promotion)  
- 🤖 **AI opponent** using minimax with alpha-beta pruning  
- 🔍 Adjustable **search depth** to increase difficulty  
- 🏆 Evaluation function that rewards captures and king pieces  
- 🛑 Detection of invalid human moves with helpful prompts  
- 🎨 Interactive board visualization with **Pygame**  

---

## ⚙️ How It Works  
- The **human player** controls red pieces, the **AI** controls white pieces.  
- The AI recursively simulates possible moves:  
  - **Maximizer (AI):** Chooses moves that maximize its score.  
  - **Minimizer (Human):** Assumed to minimize the AI’s score.  
- **Alpha-beta pruning** skips branches that cannot affect the outcome, making the search more efficient.  
- The **evaluation function** scores board states by:  
  - Assigning higher weight to king pieces  
  - Applying a “capture bonus” to encourage aggressive play  

---

## 🧪 Example Scenarios  
1. **Depth 3 minimax:** Defensive playstyle; AI wins by blocking valid moves  
2. **Depth 5 minimax:** More offensive, with multiple kings and captures  
3. **Naive human moves:** AI still wins decisively, showcasing adaptability  

---
