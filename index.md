## Portfolio

---

[dif](https://github.com/koknat/dif)

This is a project which grew from my day-to-day coding needs.<br>
dif is a preprocessing front-end for Linux tools such as diff, gvimdiff, kdiff3, meld, etc.<br>
Without a preprocessor, it can be difficult and time-consuming to visually compare large files because of formatting differences.

For example:
* Different versions of code may differ only in comments or whitespace
* Log files are often many MB of text, with some "don't care" information such as timestamps or temporary filenames
* json or yaml files may have ordering differences due to the library used to write the file

Features:
* Works together with any Linux diff tools
* Large number of options for preprocessing (grep, search/replace, timestamps, comments, whitespace, json, yaml, etc)
* Ability to generate reports and compare directories
* Supports SVN and Perforce
* Highly portable - just copy and run the script on any Linux system
* Free
