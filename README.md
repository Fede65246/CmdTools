# CmdTools (for linux)
CmdTools are an set of commands that help creating new commands.
## Install
To install the tools create an folder called Cmds, Change /home/federico/Desktop/bACKUP to the path to your Cmds folder, put the downloaded files in it and run this cmd:

```bash
cd /ThePathToCmds/
sh NewCmd NewCmd
NewCmd UpdateCmd
NewCmd DeleteCmd
NewCmd NewPyCmd

```
## How to use It

All command's needs to be an bash file in the Cmds folder without extension (es: create not create.sh)\n
To Delete an command use\
`DeleteCmd TheCmdYouWantToDelete`\
To Add an command use\
`NewCmd TheCmdYouWantToAdd`\
To Update an command use\
`UpdateCmd TheCmdYouWantToDelete`\
To create an command from an python script create TheCmdYouWantToUse.py in the Cmds folder and run\
`NewPyCmd TheCmdYouWantToUse`\
It will be called TheCmdYouWantToUse
