# Chymeric Gentoo Overlay

An overlay for Gentoo, with various packages chiefly maintained by [TheChymera](https://github.com/TheChymera). 
The repository structure is somewhat based on that of the *gentoo science overlay*, and we also use thin manifests.

## Enable this Overlay

Simply add the following commands as root:

```
echo >> PORTDIR_OVERLAY+=" /usr/local/portage/chymeric"
git clone https://github.com/gentoo-science/sci.git /usr/local/portage/chymeric
```

*Please report issues via the GitHub tracking system! Please fork and submit pull requests! We're happy to merge!*
