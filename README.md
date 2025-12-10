e-klase Study Helper Bot for Latvian students
A smart, fun, and honest homework assistant that pulls your real tasks from e-klase.lv, motivates you in Latvian, and NEVER gives direct answers — only smart hints so you actually learn and level up.
| “Learn. Win. Be proud.” — with gamification as the engine. |
What It Does
1.  Securely logs in to your e-klase.lv account (only you and the bot see your credentials)
2.  Instantly shows today’s and upcoming homework with /homework
3.  Gives powerful Latvian motivational messages with /motivation
4.  When you ask for help → answers with guiding questions and hints (never copies answers)
5.  Awards +10 points every time you say “done”, “paldies”, “izdevās”, etc.
6.  Levels you up automatically (Level 1 → Level 2 → …) with fireworks and trophies
Why It Matters
Problem
Too many tasks, zero motivation
Students want to cheat / copy
answers
Homework feels boring
Parents/ teachers worry about cheating
Solution (this bot)
Daily reminders + Latvian motivational quotes
Forces you to think → only hints and questions
Turns studying into a real game with points & levels
100 % honest - you learn for
How to Run (5 Minutes)
Step 1: Install Python real
1.  Go to https://www.python.org/downloads/
2.  Click “Download Python 3.12” (or latest)
3.  Run the installer
4.  Important: Check the box “Add Python to PATH”
5.  Click “Install Now”
Verify: Open Command Prompt (Win + R → cmd) → type: python --version
Should show Python 3.11+ or 3.12+
Step 2: Download & Install Dependencies
1.  Download this repository (Code → Download ZIP or clone)
2.  Unzip → open the folder in terminal/cmd
3.  Run once: pip install aiogram requests beautifulsoup4
Step 3: Add Your Bot Token
1.  Talk to @BotFather → /newbot → create bot → copy the token
2.  Open bot.py → replace

TOKEN = "YOUR_BOT_TOKEN_HERE"

Step 4: Start the Bot
In the same folder run:

python bot.py

You will see “Bot is running…”
Step 5: Test in Telegram
1.  Open Telegram
2.  Search your bot by username (e.g. @my_eklase_helper_bot)
3.  Press /start → /login → enter your e-klase credentials
4.  Try /homework and /motivation
Done! Your personal study hero is now live.
Commands
•  /start – Main menu & your current level
•  /login – Securely connect your e-klase account
•  /homework – Show today’s tasks
•  /motivation – Instant Latvian motivation
Just write “help”, “kā risināt”, “palīdzi” → bot gives smart hints only.
Future Ideas (Roadmap)
Feature V
Description =
Streak & badges
7 days in a row = fire badge
Photo → OCR
Send a photo of a task → bot reads and helps
Parent summary
Weekly report (anonymous)
Leaderboard with friends
Who has the highest level this week?
Daily 17:00
reminders
Auto-message with today's unfinished tasks
