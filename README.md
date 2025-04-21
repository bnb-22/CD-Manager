# Mini CD Manager 📀 (Shell Script)

A simple command-line CD catalog manager built using pure Bash.  
This mini project simulates a basic database using flat files to store CD titles and their track listings. It's an ideal learning exercise for shell scripting, file handling, and building menu-based terminal applications.

# Features

- Add new CDs with track information
- Search CDs by title
- List tracks of a selected CD
- Update track listings
- Delete CDs and associated tracks
- Count total CDs and tracks
- View raw contents of title file
- Input validation & confirmation prompts
- Temporary file cleanup using `trap`

# Technologies Used

- Shell Script (Bash)
- Core Unix commands: `grep`, `cut`, `wc`, `set`, `mv`, `rm`, etc.

# Files Overview

| File Name      | Purpose                          |
|----------------|----------------------------------|
| `title.cdb`    | Stores CD catalog metadata       |
| `tracks.cdb`   | Stores track information         |
| `cdb.sh`       | Main shell script                |
| `/tmp/cdb.$$`  | Temporary file used              |

# How to Run

```bash
chmod +x cdb.sh
./cdb.sh
