# Linux Command Reference Sheet

## Project 2 — Command-Line Operations Laboratory

This reference sheet documents fundamental Linux commands, their functions and practical examples.

### 1. echo

**Function:** Displays text in the terminal.

**Syntax:** `echo [text]`

**Example:**
```bash
echo "Welcome to Linux Administration"
```

### 2. date

**Function:** Displays the current local date and time.

**Example:**
```bash
date
```

### 3. date -u

**Function:** Displays the current date and time in UTC.

**Example:**
```bash
date -u
```

### 4. cal

**Function:** Displays the current month's calendar.

**Example:**
```bash
cal
```

### 5. cal -y

**Function:** Displays the calendar for the entire current year.

**Example:**
```bash
cal -y
```

### 6. pwd

**Function:** Displays the current working directory.

**Example:**
```bash
pwd
```

### 7. ls

**Function:** Lists visible files and directories.

**Example:**
```bash
ls
```

### 8. ls -l

**Function:** Displays directory contents in long listing format.

**Example:**
```bash
ls -l
```

### 9. ls -la

**Function:** Displays a detailed listing, including hidden entries.

**Example:**
```bash
ls -la
```

### 10. ls -lh

**Function:** Displays a detailed listing with human-readable file sizes.

**Example:**
```bash
ls -lh
```

### 11. ls -lah /etc

**Function:** Displays all entries in `/etc` in long format with human-readable file sizes.

**Example:**
```bash
ls -lah /etc
```

### 12. man

**Function:** Opens the manual page for a command.

**Example:**
```bash
man date
```

### 13. date --help

**Function:** Displays help information and available options for the date command.

**Example:**
```bash
date --help
```

### 14. man ls

**Function:** Opens the manual page for the ls command.

**Example:**
```bash
man ls
```

### 15. ls --help

**Function:** Displays help information for the ls command.

**Example:**
```bash
ls --help
```

### 16. type

**Function:** Identifies how the shell interprets a command.

**Example:**
```bash
type ls
```

### 17. command -v

**Function:** Identifies how the shell resolves a command.

**Example:**
```bash
command -v ls
```

## Command Syntax Summary

General structure:

`command [options] [arguments]`

Example:

`ls -lah /etc`

- Command: `ls`
- Options: `-l`, `-a`, `-h`
- Argument: `/etc`

## Important Notes

- Options modify command behaviour.
- Arguments identify the target or input.
- Short options commonly begin with one hyphen.
- Long options commonly begin with two hyphens.
- Multiple compatible short options can be combined.
- Manual pages and help options provide command documentation.

## Practical Competency

A Linux administrator should be able to select appropriate commands, interpret their output, identify options and arguments, and consult documentation when unfamiliar with a command.
