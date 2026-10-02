# roderio's Scoop bucket

[Scoop](https://scoop.sh) bucket for [YouputDesk](https://github.com/roderio/youputdesk), a desktop app for
YouTube Music on Windows.

```powershell
scoop bucket add roderio https://github.com/roderio/scoop-bucket
scoop install youputdesk
```

Your sign-in and settings live in Scoop's `persist` folder, so `scoop update youputdesk` keeps them.
The manifest is updated automatically (Excavator, every 4 hours) when a new YouputDesk release is published.
