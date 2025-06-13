 1. **.git**

**Description:**  
`.git` is a hidden folder automatically created when a repository is initialized using `git init`. It contains all metadata, objects, and references needed for Git to track changes.

**Use Case:**  
Essential for Git to function; deleting it will remove all version control info.

**Example:**
```bash
ls -a  # to view hidden files
cd .git  # explore repository internals
