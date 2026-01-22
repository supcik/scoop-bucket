# supcik Scoop Bucket

A personal Scoop bucket containing custom manifests.

## Prerequisites
- Windows with [Scoop](https://scoop.sh) installed
- PowerShell 5+ or PowerShell 7+

## Add this bucket
```powershell
scoop bucket add supcik https://github.com/supcik/scoop-bucket
```

## Install an app from the bucket
Replace `<app>` with a manifest name from this bucket.
```powershell
scoop install <app>
```

## Update apps and bucket
```powershell
scoop update
scoop update <app>
```

## Remove an app
```powershell
scoop uninstall <app>
```

## Notes
- Manifests live in this repo alongside any helpers (e.g., zipserve.json).
- Open issues or PRs if you find problems with the manifests.
