github ===> repository / repo A B C

local machine clone A -----> 3 days // push operation =====> Publish to repo(online)

B -----------> 5 days // pull // auto merge // conflict // resolve // push

C ---------> 4 days // not allowed to push // pull origin // C + A code // conflict create A code , C code // push online origin

git init git remote add origin

git add . git commit -m "Commit message"

git push origin main/master git pull origin main/master/branch ---------------------- From main Branch Ends here -------------------------- ---------------------- From Sandesh branch starts here --------------------- git checkout -b branchName

git status

git branch ---------------------- From Sandesh branch ends here ----------------------
