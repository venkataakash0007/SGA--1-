# Question 3 Explanation

- I created a regular file, a hard link, and a symbolic link to compare how Linux handles each object type.
- I used inode information and metadata to show that hard links share the same inode while symbolic links point to a separate path entry.
- I deleted the original file and observed that the hard link still worked, while the symbolic link broke because it referenced the removed target.
- This experiment demonstrates the difference between hard links and symbolic links in Linux file systems.
