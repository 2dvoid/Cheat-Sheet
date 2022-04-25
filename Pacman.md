# Pacman

**Install {pkg}**
```
pacman -S {pkg}
```
  
**Update package database and upgrade installed packages**
```
pacman -Syu
```

**Update package database**
```
pacman -Sy
```

**Upgrade installed packages**
```
pacman -Su
```

**Force update of package database even if recently updated**
```
pacman -Syy
```

**Download programs but leave them uninstalled (for manual install)**
```
pacman -Syyuw
```

**Remove single package {pkg} (!!NOT RECOMMENDED!!)**
```
pacman -R {pkg}
```

**Remove package as well as unneeded dependencies**
```
pacman -Rs
```

**Remove package, dependencies, and system config files (Recommended for all package uninstallations)**
```
pacman -Rns
```

**Display all installed packages**
```
pacman -Q
```

**Display only packages explicitly installed**
```
pacman -Qe  
```

**Display only names of explicitly installed packages, and not version numbers ("quiet")**
```
pacman -Qeq
```

**Display only packages installed from main repositories**
```
pacman -Qn
```

**Display only packages installed from AUR**
```
pacman -Qm
```

**Display orphaned dependencies (no longer needed)**
```
pacman -Qdt
```

**Search remote repository for package**
```
pacman -Ss  
```

**Search local repository for package**
```
pacman -Qs
```
