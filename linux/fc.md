You can edit the last terminal command you ran with `fc`

```bash
$ some command
$ fc
```

When you type `fc` it'll open 'some command' in your editor, you can edit save and exit and it'll run the command.

You can also fc to a specific history line. Using the history line id

```bash
5933  ls linux
5934  cd linux
5935  vim fc.md

$ fc 5933
```

This will allow you to edit 'ls linux'
