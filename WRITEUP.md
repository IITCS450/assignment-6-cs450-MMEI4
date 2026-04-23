Inodes are allocated from create() then
For the first two tests, tgt symlink is created and successfully reads the content
For the last test, opening the 2 looped symlinks reaches the depth 10 limit and stops to prevent loop.

<img width="816" height="628" alt="Screenshot 2026-04-18 at 8 42 22 PM" src="https://github.com/user-attachments/assets/eae89df7-7b2f-4569-87de-eed9b4467449" />
