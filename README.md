# logs_archive

Hurray, another challenge from the lovely people over at Roadmap.sh. This is a script that archives all the .log files in a given directory and moves them to a different folder on the system. The requirements for this were pretty minimal so I created a super minimal script. Not gonna lie, this one is pretty useless but hey, it's done. Here's the url: https://roadmap.sh/projects/log-archive-tool

## Instructions:
---
In order to use the script, download the file to your machine and either move the script to `/usr/local/bin` and call it "log-archive" or just run it from the current directory. This is how you run it:

```bash
log-archive /path/to/the/log/folder/you/want/to/archive
```

You can pass in more than one directory if you want. The script will try to gzip all the .log files inside the directories and the output .tar.gz file will be in `/tmp`.

You're welcome!
