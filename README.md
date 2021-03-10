# DNASC
Scripts for DNA (S)equencing (C)enter data management, configurable to your system.

ccs_chunk automates the process of submitting chunked ccs jobs to a SLURM scheduler.
See ccs.how for more info on PacBio's ccs tool for generating their proprietary HiFi reads.

remote2drive automates the process of downloading target data files from a remote location to another mounted location.
Downloading from remote location is accomplished via sshfs. Script manages connnection once properly configured.
Downloads target data files on remote location which aren't found on mounted location as long as available space is sufficient.

fixPermissions is designed to change permission on files on external hard drives.
Files must be structured predictably and the script altered according to this structure.
