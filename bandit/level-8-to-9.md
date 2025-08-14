k```markdown
# Bandit Level 8 → 9

**Goal**  
Get the only line in `data.txt` that appears once.

**Steps**  
1. Sort the file:  
   ```bash
   sort data.txt | uniq -u
