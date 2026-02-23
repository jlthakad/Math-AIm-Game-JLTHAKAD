# MATH AIM — Solve & Shoot

**Where Mathematics Meets Marksmanship**

> "Every genius was once a student who refused to stop sharpening their mind. The reason I built MATH AIM is rooted in a simple truth, that the fastest thinker and the steadiest hand belong to the same person. Train your brain to calculate under pressure, train your reflexes to strike with precision, and you will discover that intelligence is not just what you know, but how quickly and decisively you act on it."
>
> *~ JLTHAKAD*

---

## What is MATH AIM?

MATH AIM is a browser-based arcade game that fuses fast mental arithmetic with precision target shooting. Every round challenges the player to solve a randomly generated math problem, then immediately shoot down moving targets on screen. The number of targets you must destroy equals the answer to the math problem you just solved.

No installation required. Open a single HTML file in any modern browser and play.

---

## Features

- **25 Difficulty Levels** scaling from simple addition to multi-step expressions with exponents, roots, and nested parentheses
- **15 Independent Scoring Systems** including precision, flick velocity, combo chains, heartbeat rhythm, path efficiency, clutch factor, and more
- **Answer = Targets** the math answer directly determines how many targets you face each round
- **Configurable Target Cap** with a difficulty modifier that shrinks, speeds up, and randomizes target patterns when answers exceed your cap
- **No Countdown Timer** a count-up stopwatch measures performance against hidden par times so players are never punished for thinking
- **Duplicate Answer Prevention** consecutive rounds always present different problems and answers
- **Combo System** that carries between rounds with multipliers up to 3x
- **Mastery Grading** from F to S+ across a 0-1000 composite score
- **Personal Best Tracking** stored locally with ghost race comparisons and a +500 bonus for new records
- **AI Demo Mode** watch an intelligent computer player work through six showcase levels with a visible golden crosshair
- **Endurance Scaling** performance is compared across first and second half of the game with multipliers rewarding improvement
- **Zero Dependencies** single HTML file, no frameworks, no build step, no server

---

## How to Play

1. Open `Math_AIm.html` in any modern browser
2. Set your difficulty level (1-25), round count, and target cap
3. Click **START**
4. **Phase 1:** Solve the math problem from four multiple-choice answers
5. **Phase 2:** Shoot down all targets with your crosshair
6. Review your round stats across 15 scoring dimensions
7. Repeat until all rounds are complete and view your final mastery grade

---

## Difficulty Levels

| Levels | Math | Targets |
|--------|------|---------|
| 1-3 | Addition, subtraction (1-15) | Large, slow, linear movement |
| 4-6 | Multiplication, larger numbers (up to 60) | Moderate size, varied patterns |
| 7-10 | Division, mixed operations (up to 100) | Circles, figure-eight paths |
| 11-15 | Multi-step, squares (up to 300) | Zigzag, spiral patterns |
| 16-20 | Square roots, cubes, parentheses (up to 500) | Teleporting, erratic movement |
| 21-25 | Exponents, nested operations, triple multiplication | Chaotic, dashing, smallest targets |

---

## The 15 Scoring Systems

1. **Math Speed Bonus** — solve time vs calculated par time
2. **Confidence Multiplier** — speed-based round score multiplier (up to 1.5x)
3. **Streak Multiplier** — consecutive hit combo chain (up to 3x)
4. **Flick Score** — cursor velocity in the 80ms before each click
5. **First Blood** — reaction time to first hit after targets spawn
6. **Bullseye Chain** — consecutive 85%+ precision hits with doubling bonus
7. **Efficiency Rating** — hits divided by total clicks
8. **Pressure Performance** — multiplier based on math problem complexity
9. **Path Efficiency** — cursor distance vs optimal path between targets
10. **Heartbeat Score** — click rhythm consistency (standard deviation)
11. **Recovery Score** — landing precision hits immediately after a miss
12. **Target Priority** — average time between consecutive hits
13. **Endurance Scaling** — first half vs second half performance comparison
14. **Clutch Factor** — performance under high-pressure moments
15. **Composite Mastery** — weighted 0-1000 grade from F to S+

---

## Target Cap Modifier

When the math answer exceeds your configured target cap, fewer targets spawn but they become harder to compensate:

- **Smaller radius** (minimum 12px to stay humanly clickable)
- **Faster movement** (up to 2.5x base speed)
- **Harder patterns** (chaos, teleport, dash at high modifiers)
- **Score multiplier** applied to the entire round as reward (up to 2.5x)

---

## Visual Feedback

MATH AIM uses a consistent color language throughout:

| Color | Meaning |
|-------|---------|
| Pink | Exceptional performance (95%+ precision, top ranks) |
| Green | Good, solid performance (80%+ precision) |
| Cyan | On-pace, neutral |
| Yellow | Acceptable but improvable |
| Orange | Below average |
| Red | Poor performance or penalties |

Every hit produces floating labels showing precision percentage, speed, combo status, and active bonuses. Muzzle flash effects appear at each click.

---

## AI Demo Mode

Click **WATCH DEMO** from the main menu to observe an AI player complete six showcase levels (1, 5, 10, 15, 20, 25). The AI uses prediction-based targeting with a visible golden crosshair labeled "AI" and adapts its skill to each difficulty level. Full scoring results are displayed after the demo completes.

---

## Tech Stack

- Pure HTML, CSS, JavaScript
- No external dependencies or frameworks
- Canvas API for the shooting arena
- CSS animations and gradients for the neon aesthetic
- localStorage for personal best tracking

---

## Browser Support

Any modern browser with JavaScript and Canvas support: Chrome, Firefox, Safari, Edge.

---

## Who Is This For?

- **Students** looking for a fun way to practice mental arithmetic across all skill levels
- **Gamers** who want a deep scoring system to optimize and compete against
- **Teachers and parents** who need a supplementary tool where random generation prevents memorization
- **Anyone** who wants a quick brain workout that is genuinely fun to play

---

## License

Created by **JLTHAKAD**
