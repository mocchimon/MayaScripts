import maya.cmds as cmds

objs = cmds.ls(selection=True)#scan for selected object
for obj in objs:
    cmds.setAttr( obj+'.visibility', 0 ) #0 = turn on visibility
