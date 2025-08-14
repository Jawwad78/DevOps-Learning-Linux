
```markdown
# Bandit Level 12 → 13

**Goal**  
Extract the password from a file (`data.txt`) that is a hexdump of a repeatedly compressed file.

**Steps**  
1. Create a temporary working directory:  
   ```bash
   mktemp -d

2. Copy data.txt into it:

cp ~/data.txt .


3. Reverse the hexdump back into binary:

xxd -r data.txt > file

4. Use file to identify the compression type, then decompress with the correct tool (gzip, bzip2, tar, etc.).

5. Repeat the file check and decompression until you reach a plain text file.

6. Read the final file with cat to get the password.
