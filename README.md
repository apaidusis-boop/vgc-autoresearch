# vgc-autoresearch
cd "/sessions/sharp-inspiring-knuth/mnt/A Very Good Company"
cat > .gitignore << 'EOF'
__pycache__/
*.py[cod]
*.pdf
*.docx
*.xlsx
*.skill
*.zip
*.ipynb
transcript-*/
download*
ziC7gAVx
EOF
git init
git add autoresearch/
git commit -m "VGC Autoresearch Phase 1 MVP — 40 casos, dashboard, auto-update"
git remote add origin https://github.com/apaidusis-boop/vgc-autoresearch.git
git branch -M main
git push -u origin main --force
