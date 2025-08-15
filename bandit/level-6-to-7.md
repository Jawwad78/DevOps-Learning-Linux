
# Bandit Level 6 → 7

**Goal**  
Find a file anywhere on the server that’s owned by `bandit7`, group `bandit6`, and exactly 33 bytes long.

**Steps**  
1. Use:  
   ```bash
   find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
2. Read it with cat.
