## AutoLogin

Per effettuare l'autologin su lightdm aggiungere le seguente linee, occorre
specificare poi la sessione da utilizzare per effettuare il login

```
[Seat:*]
autologin-user=<USER>
autologin-user-timeout=0
user-session=openbox
```

Va poi impostato quello da eseguire all'interno di /etc/xdg/openbox/autostart
