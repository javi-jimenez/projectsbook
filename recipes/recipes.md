Recipes
-------

Recipes.

## Recipes content

This is the recipes content.

## Progress `dd`

Source: https://askubuntu.com/questions/215505/how-do-you-monitor-the-progress-of-dd

`dd` status progress:

~~~~bash
dd if=... of=... bs=4M conv=fsync status=progress
~~~~

Some options include using `pv` program.

## Use rsync to copy files with progress status

Source: https://unix.stackexchange.com/questions/65077/is-it-possible-to-see-cp-speed-and-percent-copied

~~~~bash
rsync --info=progress2 source dest
~~~~

~~~~bash
rsync -avh --progress sourceDirectory destinationDirectory
~~~~

