cd serena-lee-website
git init -b main
git remote add origin https://github.com/isaacbiziq/serena-lee-website.git
git pull origin main --allow-unrelated-histories   # pulls in the existing README commit
git add -A && git commit -m "Add Serena Lee website"
git push origin main
