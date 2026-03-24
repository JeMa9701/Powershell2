# Powershell2

Set-Location -Path C:\...  
Get-ChildItem  
New-Item -ItemType Directory -Path C:\ -Name EvenFolder
New-Item -ItemType Directory -Path C:\ -Name OddFolder  
Set-Location -Path C:\  
Move-Item -Path C:\FolderTest2\File6 -Destination EvenFolder  
Move-Item -Path C:\FolderTest2\File8 -Destination EvenFolder  
Move-Item -Path C:\FolderTest2\File10 -Destination EvenFolder  
Move-Item -Path C:\FolderTest1\File2 -Destination EvenFolder  
Move-Item -Path C:\FolderTest1\File4 -Destination EvenFolder  
Set-Location -Path C:\  
Move-Item -Path C:\FolderTest1\File1 -Destination OddFolder  
Move-Item -Path C:\FolderTest1\File3 -Destination OddFolder  
Move-Item -Path C:\FolderTest1\File5 -Destination OddFolder  
Move-Item -Path C:\FolderTest2\File7 -Destination OddFolder  
Move-Item -Path C:\FolderTest2\File9 -Destination OddFolder  
Get-ChildItem -Path *Folder* -Recurse > C:\Users\jeremy1\Documents\listing.txt  
Get-History > C:\Users\jeremy1\Documents\historique.txt  
