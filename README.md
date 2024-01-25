n = int(input()): Takes an integer input n, which represents the number of test cases.

for i in range(n):: Iterates over each test case.

c = 0: Initializes a counter variable c to count the number of players taller than the given height m in each test case.

n, m = list(map(int, input().split())): Takes two space-separated integer inputs n and m. Here, n is the number of players, and m is the height threshold.

heights = list(map(int, input().split())): Takes a list of space-separated integers representing the heights of each player.

for i in heights:: Iterates over each player's height in the list.

if i > m:: Checks if the height of the current player is greater than the threshold m.

c += 1: If the condition is true, increments the counter c.

print(c): Prints the final count for each test case, indicating the number of players taller than the given height m
