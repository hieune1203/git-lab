1, git version 2.34.1
2, user.name= PHAN TRONG HIEU
   user.email=24100082@st.phenikaa-uni.edu.vn
3, GIT-ADD(1)                      Git Manual                      GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in
       the working tree, to prepare the content staged for the next
       commit. It typically adds the current content of existing paths as
       a whole, but with some options it can also be used to add content
       with only part of the changes made to the working tree files
       applied, or remove paths that do not exist in the working tree
       anymore.

       The "index" holds a snapshot of the content of the working tree,
       and it is this snapshot that is taken as the contents of the next
       commit. Thus after making any changes to the working tree, and
       before running the commit command, you must use the add command to
       add any new or modified files to the index.

       This command can be performed multiple times before a commit. It
       only adds the content of the specified file(s) at the time the add
       command is run; if you want subsequent changes included in the next
 Manual page git-add(1) line 1 (press h for help or q to quit)
4, On branch main
nothing to commit, working tree clean
5,khong hien gi
6,khong hien gi
7,On branch main
nothing to commit, working tree clean
8, commit 32005bf5c6f25df47d49bbd780122eb0b93227a8 (HEAD -> main)
Author: PHAN TRONG HIEU <24100082@st.phenikaa-uni.edu.vn>
Date:   Fri Nov 29 16:05:59 2024 +0700

    Initial commit

commit 30b6d52e7adc020119749b70a7b33d48f4394429
Author: PHAN TRONG HIEU <24100082@st.phenikaa-uni.edu.vn>
Date:   Fri Nov 29 14:33:25 2024 +0700

    Initial commit

commit 2ace799e24ccb1358b836c74ed670c2e6e15c8a2
Author: PHAN TRONG HIEU <24100082@st.phenikaa-uni.edu.vn>
Date:   Fri Nov 29 14:26:00 2024 +0700

    Initial commit
9,git: 'credential-manager' is not a git command. See 'git --help'.
Username for 'https://github.com': hieune1203
Password for 'https://hieune1203@github.com':
git: 'credential-manager' is not a git command. See 'git --help'.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/hieune1203/git-lab.git/'