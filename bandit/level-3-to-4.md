```markdown
# Bandit Level 3 → 4

**Goal**  
Find a hidden file inside a hidden directory and read it.

**Steps**  
1. Use `ls -a` to reveal all entries, including hidden ones.  
2. `cd inhere` to go into the hidden folder.  
3. Run `ls -a` again to reveal `.hidden`.  
4. `cat .hidden` to view the password.

**Note**  
Got used to `ls -a` to catch files that normal `ls` misses.
