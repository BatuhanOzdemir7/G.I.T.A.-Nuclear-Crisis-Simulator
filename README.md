# ☢️ G.I.T.A. (Global Intelligence & Technical Analysis)
"The worst decision is indecision."

G.I.T.A. is an atmospheric, console-based strategy/thriller game developed in C# that simulates the most tense moments of the Cold War. The player takes on the role of a commander in a Soviet nuclear bunker, forced to make a decision that will determine the fate of millions in the face of incoming (or potentially erroneous) nuclear attack warnings.

This project is heavily inspired by the real-life story of Stanislav Petrov and the "Dead Hand" system.

# ⚠️ LANGUAGE NOTICE / DİL UYARISI
Current Version: The game is currently available in Turkish (v1.0).
Coming Soon: An English localization is in development.

(Oyun şu anda sadece Türkçe dil desteğine sahiptir. İngilizce sürüm yakında eklenecektir.)

# 🎮 Gameplay & Features
- Tension-Based Decision Mechanism: Radar data, seismic sensors, and satellite imagery don't always tell the truth. Is the attack real, or is it a system glitch? A wrong decision leads to M.A.D. (Mutually Assured Destruction).
- Dynamic Narrative System: The dialogue between the hawkish General Volkov and the cautious Captain Smirnov increases the psychological pressure on the player throughout the game.
- Immersive Audio Atmosphere: An engaging experience integrated using the System.Media library, featuring sirens, Soviet anthems, and alarm effects.
- Developer Terminal (Cheat Mode): A hidden command-line interface (CheatTerminal) within the game allows for real-time manipulation of simulation variables. You could open it by pressing the Q key.

# 🏁 4 Distinct Endings
Your choices define history:

🏆 Bloody Victory: The enemy is destroyed; the Motherland survives (but at what cost?).

💀 Total Defeat: We hesitated. The country is wiped off the map without firing back.

☢️ M.A.D. (Mutually Assured Destruction): Both sides annihilate each other. The world returns to the Stone Age.

🕊️ Peace: Composure prevails. The crisis is averted, and World is in peace. For now.

# 🛠️ Technical Details
This project was developed using Object-Oriented Programming (OOP) principles and the .NET Framework.

- Language: C#
- Platform: Windows Console Application
- Architecture:
  - Nation Class: Manages the health, population status, and missile counts of the countries.
  - Narrative Class: Manages the RNG-based dialogue pool and story events.
  - ThreatChance: Dynamically calculates risk levels and game difficulty based on player actions.
  - System.Threading: Used for timed events and creating a fluid countdown timer without input lag.

# 🕹️ How to Run
1. Clone or Download the repository.
2. Open the ForMotherLand.sln file in Visual Studio.
3. Build the project in Debug or Release mode.

# IMPORTANT: Ensure that the .wav audio files are located in the bin/Debug (or bin/Release) folder along with the .exe.

Run the application, set the console to Full Screen, and put on your headphones.

# License
This project is licensed under the MIT License.
Audio files are property of their respective owners and are used for educational/atmospheric purposes only.

# Developer: Batuhan Özdemir
# Year: 2026
