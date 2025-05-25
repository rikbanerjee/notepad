git status | cat
git add frontend/src/App.jsx frontend/src/components/Home.jsx 
git add .
git commit -m "fix: update route paths to match backend API structure" | cat
git push origin feature-cursor | cat

//Merge and Push to Main
git status | cat

git checkout main | cat
git merge feature-cloud-deploy | cat
git push origin main | cat

git checkout feature-cloud-deploy | cat
//Switched to branch 'feature-cloud-deploy'
//Your branch is up to date with 'origin/feature-cloud-deploy'.


Once you change the Field in DB: add the field in the schema.prisma and run the below command
npx prisma generate
