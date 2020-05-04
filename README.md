# Post pull git hook


Post pull git hook is shared as an example on how to create a git hook that takes an action after pulling (actually merging). The example given:

  - Checks for changes in "static/" folder
  - If finds any change during the last pull/merge, it increments the number in a file
  - Updates the registry of the last head to the current

# How to install

  - copy **post-merge** file to the .git/hooks folder in your repo
  - give it run permission: 
  > *chmod +x .git/hooks/post-merge*


# License
----
[GNU General Public License][gnu]


[//]: # (Links)
[gnu]: <https://www.gnu.org/licenses/gpl-3.0.html>
