# Address Bar Mod

Tablacus Exproler  Addon

### Features

- Support Linux Like Path
  - Convert slash path delimiter
    - `C:/foo/bar/hoge/fuga` → `C:\foo\bar\hoge\fuga`
  - Convert root directory to system drive
    - `/Windows/System32` → `C:\Windows\System32`
  - Extract `~` to home directory
    - `~/Downloads` → `C:\User\<your home>\Downloads`
    - `~someone/Downloads` → `C:\User\someone\Downloads`
- Add an option `Open in new tab`
  - This option will affect if RETRUN key is press in address bar.  
    Breadcrumbs navigation is not affected.
