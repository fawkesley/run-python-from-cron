# Run Python from Crontab

Run a Python program from crontab with these features:

- Log all output to log/ subdirectory
- Automatically source settings.sh|credentials.sh from repo directory
- Suppress stdout if the script exits successfully


# Get started

- Put the included `run.sh` script in the same directory as your python code.
- By default it will run `main.py` with no arguments.
- Run `run.sh` from cron - see the included example `crontab.txt`
