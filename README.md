# watchitCLI

A small command line tool to better understand the under the hood processes of node.js and STDIO while building it with Stephen Grider.

The program basically runs other scripts from the command-line with the watchit script.
USAGE: watchit <[filename]>
For instance, watchit test.js
if filename is not provided, looks for the index.js if existent.


Utilized chokidar, caporal, fs, child_process, lodash, and chalk.
