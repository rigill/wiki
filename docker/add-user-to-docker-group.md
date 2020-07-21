### Adding user to docker group

This is on debian 10, doesn't have usermod.

```bash
sudo adduser <user> docker
```

If docker group isn't added might need to do this one. 

```bash
sudo adduser --group docker
```
