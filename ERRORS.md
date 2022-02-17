
## Errors

- Terminal error: zsh: permission denied: ./myscript.sh

Fix: give it the execution permission: `chmod +x ./startup.sh` -his will give exec permission to user,
group and other, so beware of possible security issues. To restrict permission to a single access class,
you can use: `chmod u+x ./startup.sh` - this will grant exec permission only to user.

Alternatively you can use bash: `bash startup.sh` - then you don't need execution permission.
