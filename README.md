# VMF Optimizer
Program to compress Valve Map Files (VMF) for archival purposes. Compatible with any Source Engine game.

# How it works
The program will remove parameters that have default values. When the modified file is opened, Hammer will fill the missing parameters with default values; nothing changes, hence lossless optimization.

Since saving the file will re-add the default values again, the tool is best used for archival purposes. (if you're like me and have a lot of vmfs of your previous map versions, this tool will be useful)

# Instruction
1. Launch vmfoptimizer.exe.
2. Drop your .vmf file into the command window or type its directory manually.
3. After several seconds, the optimized vmf will be created in the same directory as the original file.
4. To edit the settings, open "settings" file and change the parameters. The parameters are explained at the bottom.

# Credits
Code by dabmasterars
