# Practical Assessment Report

## Project 2 — Linux Command-Line Operations Laboratory

### 1. Assessment Overview

This assessment documents the practical execution and understanding of fundamental Linux command-line operations in an Ubuntu environment.

The exercise focused on command syntax, command options, arguments, directory inspection and command documentation.

### 2. Practical Activities Completed

The following command-line activities were performed:

| Area | Commands |
|---|---|
| Text output | `echo` |
| Date and time | `date`, `date -u` |
| Calendar | `cal`, `cal -y` |
| Directory identification | `pwd` |
| Directory inspection | `ls`, `ls -l`, `ls -la`, `ls -lh` |
| System directory inspection | `ls -lah /etc` |
| Manual documentation | `man date`, `man ls` |
| Help documentation | `date --help`, `ls --help` |
| Command identification | `type ls`, `command -v ls` |

### 3. Command Syntax Assessment

Linux commands generally follow this structure:

`command [options] [arguments]`

The practical syntax challenge used:

`ls -lah /etc`

The command was analysed as follows:

- Command: `ls`
- Option 1: `-l` — long listing format.
- Option 2: `-a` — include hidden entries.
- Option 3: `-h` — human-readable file sizes.
- Argument: `/etc` — target directory.

This demonstrates how multiple options can modify one command's behaviour while an argument identifies the target.

### 4. Comparison of Listing Commands

**`ls`**

Lists visible files and directories in the default format.

**`ls -l`**

Displays detailed file and directory information, including permissions, ownership, sizes and modification timestamps.

**`ls -la`**

Combines long listing format with visibility of hidden entries.

**`ls -lh`**

Displays detailed file information with human-readable sizes. Hidden entries remain excluded unless `-a` is added.

### 5. Documentation Assessment

Two documentation methods were examined.

**Manual pages**

The `man` command provides detailed documentation about command usage and options.

Examples:
- `man date`
- `man ls`

**Help options**

The `--help` option provides a concise summary of command usage and available options.

Examples:
- `date --help`
- `ls --help`

### 6. Command Identification

The following commands were used:

- `type ls` to identify how the shell interprets the command.
- `command -v ls` to identify how the shell resolves the command.

These are useful when investigating command behaviour and executable locations.

### 7. Evidence Collected

The following practical evidence files were prepared:

1. `evidence/01_basic_commands.txt`
2. `evidence/02_command_options.txt`
3. `evidence/03_command_documentation.txt`
4. `evidence/04_syntax_analysis.txt`

The evidence records contain command output and syntax analysis from the practical exercises.

### 8. Skills Demonstrated

The project develops the following competencies:

- Linux command-line literacy.
- Basic terminal operations.
- Directory inspection.
- Understanding command options and arguments.
- Reading command documentation.
- Identifying command types and executable resolution.
- Technical documentation and evidence management.

### 9. Challenges and Observations

The exercises demonstrated that commands can produce different outputs depending on the options supplied.

Combining options makes commands more efficient, while documentation tools provide a reliable way to investigate unfamiliar commands.

The distinction between visible and hidden files is also important when inspecting Linux directories.

### 10. Conclusion

The Command-Line Operations Laboratory established a foundation in Linux command syntax and basic administrative inspection.

The practical exercises developed the ability to execute commands, interpret their behaviour, use documentation tools and distinguish commands, options and arguments.

These competencies provide a foundation for more advanced Linux system administration tasks, including file management, permissions, process management and system troubleshooting.

### 11. Assessment Status

Project documentation and evidence files have been prepared. Final verification of the repository contents and practical evidence is required before publication to GitHub.
