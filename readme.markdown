# iCalendar Notebook

Some very basic statistics for iCalendar/ICS files. You can use your private
Google Calendar Export as input for these.

![](screenshot.png)

## Setup

Docker makes this stuff so easy, I really would strongly recommend against
trying to set up Jupyter and dependencies locally, unless you already have it.

```bash
docker run --rm -it -p 8888:8888 -v "$(pwd):/home/jovyan/work" jupyter/scipy-notebook@8015c88c4b11
```
