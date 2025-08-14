# Bandit Level 4 → 5

**Goal**  
Identify and open the only human-readable file in a directory of random files.

**Steps**  
1. `cd inhere` to enter the folder.  
2. Run `file ./*` to see file types.  
3. Identify the ASCII text file and read it with `cat`.

**Note**  
The `file` command is perfect for filtering out binary noise.
