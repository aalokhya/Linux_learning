# 🐧 Day 3: Advanced File Interactions & Filtering

### `cat` — Concatenate

Displays the complete contents of a file.

```bash
cat file.txt
```


### `less`

Opens a file page-by-page, which is useful for large files. Use the arrow keys to move through the file.

```bash
less file.txt
```

Press:

```text
q
```

to exit.


### `head`

Displays the beginning of a file.

```bash
head file.txt
```

By default, it shows the first **10 lines**.



### `tail`

Displays the end of a file.

```bash
tail file.txt
```

By default, it shows the last **10 lines**.


### `grep`

Searches for a specific word or pattern inside files.

```bash
grep "error" file.txt
```

### `wc` — Word Count

Counts information such as lines, words, and characters.

```bash
wc file.txt
```

To count only the number of lines:

```bash
wc -l file.txt
```

---

### `cp` — Copy

Creates a copy of a file.

```bash
cp file.txt backup.txt
```


---

### `mv` — Move / Rename

Moves a file to another location.

```bash
mv file.txt folder/
```

It can also rename a file:

```bash
mv old.txt new.txt
```


---

### `rm` — Remove

Deletes a file. Be careful with `rm`. Linux normally does not provide a Recycle Bin for files deleted this way. Permanently deletes a file.

```bash
rm file.txt
```

---

### `history`

Displays commands that you previously entered in the terminal.

```bash
history
```


# 📌 Quick Revision Table

| Command / Operator | Meaning                 | Easy Explanation              |
| ------------------ | ----------------------- | ----------------------------- |
| `pwd`              | Print Working Directory | Shows where you are           |
| `mkdir`            | Make Directory          | Creates a folder              |
| `ls`               | List                    | Shows files and folders       |
| `cd`               | Change Directory        | Moves between folders         |
| `touch`            | —                       | Creates an empty file         |
| `nano`             | —                       | Edits a file in terminal      |
| `>`                | Overwrite               | Replaces file content         |
| `>>`               | Append                  | Adds to existing content      |
| `cat`              | Concatenate             | Shows entire file             |
| `less`             | —                       | Reads file page-by-page       |
| `head`             | —                       | Shows beginning of file       |
| `tail`             | —                       | Shows end of file             |
| `grep`             | —                       | Searches for text             |
| `wc`               | Word Count              | Counts lines/words/characters |
| `cp`               | Copy                    | Copies a file                 |
| `mv`               | Move                    | Moves or renames a file       |
| `rm`               | Remove                  | Deletes a file                |
| `history`          | —                       | Shows previous commands       |

---

## 📸 Proof of Output
![Day 3 Command Pipeline](./images/day3_screenshot.png)
