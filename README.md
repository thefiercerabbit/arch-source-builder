# arch-source-builder
A bash script using ABS and makepkg to download and build packages from 
sources.

# Usage
$ ./abs_build [-f] [-i] [-r] [-s] package1 package2 ...
See makepkg man to understand options.
If you just want to build package, without installing, you generally 
need -r and -s options (to download needed packages to compile, and then 
remove them). The -f option force the build of the package, even if the 
package is already build in the directory.

Do not use as root.
