```markdown
# Bandit Level 11 → 12

**Goal**  
Decode a file where all letters have been rotated by 13 places (ROT13).

**Steps**  
1. Run:  
   ```bash
   cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
