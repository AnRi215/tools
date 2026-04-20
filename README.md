# tools.anri215

PowerShell-Toolkit für Windows. Alle Skripte werden direkt per One-Liner ausgeführt – keine Installation, keine Abhängigkeiten.

## Verwendung

```powershell
irm "https://tools.anri.sh/<name>" | iex
```

## Übersicht

```powershell
irm "https://tools.anri.sh/help" | iex
```

## Voraussetzungen

- PowerShell 5.1 oder neuer
- Ausführungsrichtlinie einmalig setzen (falls noch nicht geschehen):

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

## Lizenz

MIT
