i tried to run 
```
systemctl --user enable --now ssh-agent.service
```

but i had error. the problem was i was a root user. but you must be a normal user.
so i ran `su - ubuntu` to fix that.
