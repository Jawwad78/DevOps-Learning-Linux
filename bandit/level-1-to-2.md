
```markdown
# Bandit Level 1 → 2

**Goal**  
Open a file literally named `-` and get the password for the next level.

**Steps**  
1. Log in as `bandit1`.  
2. Check the directory contents with `ls`.  
3. Use `./-` to treat the dash as a filename:  
   ```bash
   cat ./-

