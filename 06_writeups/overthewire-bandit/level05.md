Level Goal: The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

Commands you may need to solve this level ls , cd , cat , file , du , find

Commands done:

ls

cd inhere

ls

find . -size 1033c -exec file {} \;

ls

cd maybehere07

ls

find

cat ./.file2

output: <REDACTED_LEVEL05>

Proof: Takeaways: figuring out the find command. Time: ~10 min
