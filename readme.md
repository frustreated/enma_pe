<h1 align="center">ENMA PE</h1>
---

| License |  Windows x32 | Windows x64 | Linux |
| ------- |  ----------- | ----------- | ----- |
| [![License](https://img.shields.io/badge/license-LGPLv3%2B-blue.svg)](https://github.com/jnastarot/enma_pe/blob/master/LICENSE)  [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe?ref=badge_shield) | [![Build status](https://ci.appveyor.com/api/projects/status/ogdbdwhomqi1yoh1?svg=true)](https://ci.appveyor.com/project/jnastarot/enma-pe) | [![Build status](https://ci.appveyor.com/api/projects/status/b6bq9w9b1b7rjaoy?svg=true)](https://ci.appveyor.com/project/jnastarot/enma-pe-u6wir) | [![Build Status](https://api.travis-ci.org/jnastarot/enma_pe.svg?branch=master)](https://travis-ci.org/jnastarot/enma_pe) |




```
--------------------------------------------------------------------------------
Name....: enma pe
Author..: JNA
Date....: 2018
e.mail..: jnastarot@yandex.ru
--------------------------------------------------------------------------------
```
---
<h2 align="center">Supported PE\PE+ formats</h2>

| directory name | reading | building | getting placement |
| :-------------- | :-------: | :-------: | :-------: |
| `export` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `import default ` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `import bound ` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `import delay` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| `resources` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `exceptions` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `security` | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| `relocations` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `debug` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| `tls` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `load config` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `.NET meta data` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |

---

<h3 align="center">Additional features</h3>

| feature name | description |
| :------: | :-----------: |
| `map parser` | parsing .map file generated by delphi XE and Visual Studio |
| `tds parser` | parsing tds-styled debug info |
| `string finder` | finding ansi and unicode strings |
---

| TODO list |
| :-------: |
| `pe_section_io` for comfortable work with `pe_section` |
| `pe_image_io` for comfortable work with `pe_image`     |
| rewrite source on `pe_image_io` and `pe_section_io`    |
| `pe_demangler` for `gcc`, `visual studio`, `delphi` mangled names|
| do something for comfortable work with `TD32(.tds)`, `.pdb`, `.dbg`, `.map`|
---
 
| credits |
| ---------- |
| pe rich comp id [richprint](https://github.com/dishather/richprint/) |
| reading\building of export and resources [pe bliss kaimi](http://kaimi.io/) |
| tds parser [denisenkomik.narod.ru/main.cpp](http://denisenkomik.narod.ru/main.cpp) |
