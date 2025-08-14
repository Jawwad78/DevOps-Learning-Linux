# Bandit Level 5 → 6

**Goal**  
Find a file in `/var/lib/dpkg/info` that’s owned by `bandit6` and group `bandit5`.

**Steps**  
1. Use `find` with ownership filters:  
   ```bash
   find /var/lib/dpkg/info -user bandit6 -group bandit5 2>/dev/null
2. Open the matching file with cat.
