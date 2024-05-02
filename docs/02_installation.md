# Installation

Most often people ditch LaTeX for difficulty in debugging the errors. And, the errors are primarily arise either from a missing style file or from the usage of special characters. We will discuss later in this documentation about the usage of special characters like `\` and `$` in LaTeX. However, my personal choice to avoid the first error is to install the complete package.

## Acquiring an ISO file

The complete installation can be done by downloading the `texlive` ISO file from [Tex Users Group (TUG) site](https://www.tug.org/texlive/acquire-iso.html). It is big about 3-4 GB, would take some time to download and install. However, it is worth to wait the time.

<video controls>
<source src="../media/acq.webm" type="video/webm">
</video>

Once downloaded, in linux, right-click the file and mount as a directory. In latest windows double click the file should mount the file as virtual drive. For older windows, extra software like [wincdemu](https://wincdemu.sysprogs.org/) is required to mount the file as drive.

## Installing the package

In linux, open terminal in the texlive directory and issue the command `./install-tl`. For windows double click the `install-tl-windows.bat` and this should open up the installation window.

Usually the default settings are enough. However, please make sure to create symlinks so that the package can be accessed system-wide.

[How this can be done?]

Another, optional tweak is to de-select unwanted language packages. This should save considerable space.

After this, press `y` to continue the installation and wait for sometime to complete the process. Once finished, open the terminal (or powershell) and then type `pdflatex --version`. If you got something like this, ensures the proper installation of texlive package in your system.

```
pdfTeX 3.141592653-2.6-1.40.25 (TeX Live 2023)
kpathsea version 6.3.5
Copyright 2023 Han The Thanh (pdfTeX) et al.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the pdfTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the pdfTeX source.
Primary author of pdfTeX: Han The Thanh (pdfTeX) et al.
Compiled with libpng 1.6.39; using libpng 1.6.39
Compiled with zlib 1.2.13; using zlib 1.2.13
Compiled with xpdf version 4.04
```
