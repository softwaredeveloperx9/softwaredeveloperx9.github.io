# 1. Buat branch baru tanpa history
git checkout --orphan fresh-start

# 2. Stage semua file
git add .

# 3. Commit bersih
git commit -m "🚀 Commit beberapa file"

# 4. Hapus branch main lama
git branch -D main

# 5. Rename branch baru jadi main
git branch -m main

# 6. Force push ke GitHub
git push --force origin main
