git status | cat
git add frontend/src/App.jsx frontend/src/components/Home.jsx 
git add .
git commit -m "fix: update route paths to match backend API structure" | cat
git push origin feature-cursor | cat

Once you change the Field in DB: add the field in the schema.prisma and run the below command
npx prisma generate
