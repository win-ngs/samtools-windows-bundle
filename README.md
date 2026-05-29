# Samtools Windows Bundle

This repository publishes a small Windows x64 bundle of `samtools.exe` copied
from the MSYS2 UCRT64 environment, together with the runtime DLLs needed to run
it from a single directory.

## Included Version

- Samtools: 1.23.1
- HTSlib: 1.23.1
- Source environment: MSYS2 UCRT64
- Target platform: Windows x64

## Usage

Download the release ZIP from:

https://github.com/win-ngs/samtools-windows-bundle/releases/tag/v1.23.1-windows-ucrt64

Extract it, and run:

```powershell
.\samtools.exe --version
```

The executable and DLLs are intended to stay in the same directory. You can add
the extracted directory to `PATH` if you want to run `samtools` from any shell.

## License

Samtools is distributed under the MIT/Expat license. See `LICENSE.md`.

This bundle also includes third-party DLLs from MSYS2 packages. See
`THIRD_PARTY_NOTICES.md` and the `licenses/` directory in the release archive.
