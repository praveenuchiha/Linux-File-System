import os, sys
# Open a file
fd = os.open( "lind_fs_calls.py.0", os.O_RDWR)
#close file
os.close( fd )
# Now get  the tuple
info = os.lstat("lind_fs_calls.py.0")
#check deviceid

	if(info.st_rdev == 20):
        print " Device Id is correct"
	else:
        raise Exception("Device Id is wrong")
#check time
            accesstime=info.st_atime
			creationtime=info.st_ctime #ctime() does not refer to creation time on *nix systems, but rather the last time the inode data changed.
			modifiedtime=info.st_mtime	
if(accesstime < getRuntime())
			    raise Exception " Access time is not correct "
			if(creationtime < getRuntime())
			    raise Exception " Creation time is not correct "
			if(modifiedtime < getRuntime())
			    raise Exception " Modification time is not correct "	
#check directory count

link_count= info.st_nlink
            caluclatelength = len('filename_to_inode_dict')			
            if(link_count != caluclatelength):
                raise Exception " link count is incorrect"					
		
#check free blocks
start= statvfs.F_BFREE["freeStart"]
end= statvfs.F_BFREE["freeEnd"]
for a in range (start,end)
if object['status'] == 'T':
			    
				if len(fd) < 1:
				    continue
				else:
				     raise Exception " The free block list is inaccurate "
if  object['status'] == 'F':
			    
 				if len(metadatastring) < 1:
				    raise Exception " The free block list is inaccurate " 
					
					
#check if directory contains . and .. 
for x in fd:
innerdict= fd[x]
for y in innerdict

     if(parentDir = innerdict[B]['filename_to_inode_dict']['..']): #pointing to current directory
	     continue
  	else :	 
		raise Exception "not pointing to current block"


#check if size is valid for the number of block pointers in the location array

for x in range(27,9999):
  for metadata in fd(x):
    if(metadata['indirect']==0):
         try:
          index = deserialize(fd)
            
         else:
         raise Exception("Indirect = 0, but Location " + str(metadata['location']) + " is an index block!")
	else if(metadata['indirect']!=0):
	  try:
          index = deserialize(fd)
	     else:	  
	     raise Exception("Indirect = 1, but Location " + str(metadata['location']) + " is a data block!")
     else:
	 raise Exception("Indirect Error. Indirect > 1") 






		
			
		
