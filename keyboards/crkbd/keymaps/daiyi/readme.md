## Prereqs

Download:

-   QMK toolbox
-   Docker Desktop
-   VS Code
-   VS Code extension `remote-containers`

## build

1. `reopen in remote container` to open in docker container
2. `qmk compile -kb crkbd/rev1 -km daiyi`

Flash with QMK toolbox:

-   connect USB and press tiny button next to trrs port
-   click "flash"
-   repeat with other side.
