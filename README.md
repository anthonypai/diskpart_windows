# diskpart_windows
#Disk formatting in cmd

### Open CMD with Admin Privilage ###

## List Disk ##
list disk
## Select Disk ##
select disk [index of the disk to be formatted]
## Clean all partitions ##
clean
## Create Primary Partition ##
create part pri
## Select Primary Partition ##
select part 1
## Formatting the disk with fast operation ##
format fs=ntfs quick
## Assign disk ID with next available ##
assign

### Disk format completed ###
