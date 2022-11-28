# TASKCTL

A program to launch batch tasks `taskrun` and another to read
it's results `taskctl`.

## Dependencies

A POSIX shell interpreter is enough. Mails are sent with `msmtp(1)`.

## Help

scron-run

    Usage: scron-run CRONTAB
    
    Run all the tasks in the crontab.

taskctl

    Usage: taskctl [TASK] : List/view task results.

taskrun

    Usage: taskrun [OPTS...] COMMAND...
    
    Run a command/script in the background.
    
        -V      : Show configuration.
        -m      : Send result by mail in case of error.
        -t NAME : Task name.
        -i      : Install a link in `/sbin/taskrun`.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

