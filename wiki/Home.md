# SigmaOS-openjpeg

SigmaOS integration component for **OpenJPEG JPEG2000**.

## Commands

```bash
sigmaos-openjpeg install   # install package + deploy defaults
sigmaos-openjpeg deploy    # copy config templates to $HOME
sigmaos-openjpeg status    # binary/package/config report
sigmaos-openjpeg reset     # remove deployed config
sigmaos-openjpeg open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
