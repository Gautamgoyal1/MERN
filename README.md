# MERN

1..10 | ForEach-Object { $folder = "day_{0:D2}" -f $_ mkdir $folder "## $folder" | Out-File "$folder/README.md" }

1. git add . ---> this will stage your changes
2. git commit -m"anything" ---> saved changes here  
3. git push origin main