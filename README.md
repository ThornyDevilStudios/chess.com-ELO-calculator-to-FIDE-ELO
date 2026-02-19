FIDE Elo Simulator

This tool estimates your FIDE rating based on your Chess.com PGN game history. It is designed for players who may not have an official FIDE rating.

Features

Calculates your estimated FIDE rating from your Chess.com games.

Shows minimum (worst-case) and maximum (best-case) FIDE ratings, with high confidence based on tested players.

Calculates performance rating and expected points.

Works for any player without an official FIDE rating.

Standalone Windows executable – no Python installation required.

Important Notes

The final rating is only an estimate. Actual FIDE ratings may vary due to official calculations and tournament conditions.

The min and max FIDE ratings are calculated to reflect bounds with 100% confidence based on historical testing of multiple players. This means your real FIDE rating should fall within this range, but small deviations are still possible.

Do not use quotation marks (" ") around the PGN file path. This is a current limitation and will be fixed in future updates.

The program supports all game types but calculates a single overall rating.

How to Use

Double-click the EloCalc.exe file.

Enter the path to your PGN file (without quotes).

Enter your exact player name as shown in the PGN.

Enter your starting rating (from Chess.com or another source).

Enter your K-factor (40 = new player, 20 = normal, 10 = 2400+).

The program will simulate each game and output:

Final estimated FIDE rating

Minimum (worst-case) FIDE rating

Maximum (best-case) FIDE rating

Total points and expected points

Performance rating

Example Output
Final estimated FIDE rating: 3092.8
Min FIDE rating (Worst-Case): 2941.0
Max FIDE rating (Best-Case): 3099.7
Total points: 30.0/50
Expected points: 10.93
Performance rating: 3093.6

License

This project is released under the Creative Commons Attribution-NonCommercial (CC BY-NC 4.0)
