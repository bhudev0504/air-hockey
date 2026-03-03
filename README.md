#  Hand Gesture Air Hockey

Ever wanted to play Air Hockey without touching anything? That's exactly what this is. Two players, one webcam, and your hands — that's all you need. Just wave your hand to move your paddle and try to get the puck past your opponent!

---

##  How the Game Works

- Both players sit or stand in front of the webcam
- **Player 1** controls the **left paddle** with their left hand
- **Player 2** controls the **right paddle** with their right hand
- The puck spawns at a random position in the center and starts moving
- It bounces off paddles and walls just like real air hockey
- If the puck slips past your paddle, your opponent gets a point
- **First to 5 points wins!**

---

##  Features

-  Control paddles using real-time hand gesture detection
-  Physics-based puck bouncing off paddles and walls
-  Live score tracking for both players
-  Match ends automatically when someone hits 5 points
-  Puck spawns at a random position every round

---

##  Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Hand Detection | OpenCV (HSV Color Masking + Contour Detection) |
| Game Rendering | OpenCV (cv2) |
| Physics | Custom Collision Module |

---

##  Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhudev0504/hand-gesture-air-hockey.git
   cd hand-gesture-air-hockey
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the game**
   ```bash
   python main.py
   ```

---

##  How to Play

1. Launch the game and allow webcam access
2. Both players get in front of the camera
3. Move your hand up and down to control your paddle
4. Hit the puck past your opponent's paddle to score
5. First to **5 points** wins the match!
6. Press **`Q`** to quit the game at any time

---

##  Screenshots
- here is a screenshot of the game, how it looks

> <img width="1247" height="964" alt="image" src="https://github.com/user-attachments/assets/a1bb3a1b-fe95-443d-8f45-e80d0c5cbbf1" />


---

## What's Next

A few things I'd love to add in the future:

- [ ] Sound effects for hits and scoring
- [ ] Adjustable ball speed / difficulty levels
- [ ] Single-player mode against an AI
- [ ] Customizable winning score
- [ ] Animations on scoring and match end

---

## Contributing

Got an idea or found a bug? Contributions are always welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

**Bhudev Singh**  
GitHub: [@bhudev0504](https://github.com/bhudev0504)
