class POBG_Game:
    def __init__(self):
        self.mode = "Arcade Shooter"
        self.style = "16-bit Retro"
        self.enemies = ["Angry Chickens", "Mega Rooster Bosses"]
        self.weapons = ["Shotgun", "Uzi", "Grenade Launcher", "Frying Pan"]
        self.maps = ["Pixel Karakin", "Retro Vikendi"]
        self.vibes = "Chaotic Chicken-Crushing Fun"

    def start_game(self):
        print("🎮 Loading POBG: PlayerOmNom's Battlegrounds...")
        self._load_assets()
        self._spawn_chickens()
        self._play_synth_music()
        print("💥 WELCOME TO THE CHICKEN APOCALYPSE 💥")

    def _load_assets(self):
        print("🗺️ Loading pixel maps...")
        print("🔫 Equipping absurd weapons...")
        print("🐔 Initializing cluckin' enemies...")

    def _spawn_chickens(self):
        print("🐥 Wave 1 incoming: Angry Chickens detected!")
        print("⚠️ WARNING: Giant Boss Chicken charging attack!")

    def _play_synth_music(self):
        print("🎶 Playing retro battle theme at max volume...")

    def game_over(self):
        print("☠️ You got pecked to death.")
        print("💾 Retry? Y/N")

# Let's play
pobg = POBG_Game()
pobg.start_game()

