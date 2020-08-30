# LocalVolumeUpdate


Get-Partition -DriveLetter f | Remove-Partition -Confirm:$false ;

New-Partition -DiskNumber 0 -Size 150mb -DriveLetter f ;
 
Format-Volume -DriveLetter f -FileSystem NTFS -Force





## Source URL :- https://4sysops.com/archives/managing-disks-with-powershell/
