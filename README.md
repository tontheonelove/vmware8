# vmware8


# Boot Esxi installation 

# SHIFT + O  before boot 

# spacebar and insert below 

cpuUniformityHardCheckPanic=FALSE autoPartitionOSDataSize=8192

# when install success 

# spacebar and insert below 

cpuUniformityHardCheckPanic=FALSE

open gui and enable SSH  login with root

cd bootblank

vi boot.cfg

# add this on row kernelopt

cpuUniformityHardCheckPanic=FALSE
