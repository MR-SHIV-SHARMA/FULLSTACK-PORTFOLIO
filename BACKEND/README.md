# BACKEND_PRO

"Please keep the update files separate in the backend."


echo "# PORTFOLIO" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:MR-SHIV-SHARMA/PORTFOLIO.git
git push -u origin main




{
    "version":2,
    "builds": [
      { "src": "*.js", "use": "@vercel/node" }
    ],
    "routes": [
        {
          "src": "/(.*)",
          "dest": "/"
        }
    ]
  }