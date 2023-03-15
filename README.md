# Total-points
# Enter the points of a team during 30 games and get the total points and the number of wins respectively

total = 0
wins = 0

for i in range(1,31):
    Score = int(input())
    if Score == 3:
        wins += 1
    total += Score

print(total, wins)
