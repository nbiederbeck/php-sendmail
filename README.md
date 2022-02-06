# php-sendmail
Mock sendmail for php debugging.

## Usage

In the file `/etc/php/php.ini` under the section `[mail function]` find the
line containing `sendmail_path` and change it to
```
sendmail_path = /path/to/this/directory/sendmail.sh
```

This needs `notify-send` installed (from `libnotify`) and a notification
daemon (e.g. `dunst`).
