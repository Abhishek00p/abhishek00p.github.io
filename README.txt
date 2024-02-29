


a music applicantion to listen and download your favourite songs
you can also upload your own music and get popular


some tips :

// to get total number of commit done by a user in a branch in last 1 year
git rev-list --count --author="usernmae" --since="1 year ago" branch-name

// to get total number of commits in a branch
git rev-list --count branch-name  --since=2.year


// to get number of lines added or removed or changes 
git log --author="username" --since="1 year ago" --oneline --shortstat branch--name | grep "files\? changed" | awk '{files+=$1; inserted+=$4; deleted+=$6} END {print "files changed:", files, "insertions(+):", inserted, "deletions(-):", deleted}'
