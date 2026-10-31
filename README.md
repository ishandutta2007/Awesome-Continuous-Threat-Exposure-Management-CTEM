# Awesome-Continuous-Threat-Exposure-Management-CTEM

# PowerShell — resolves repo name, adds topics via gh CLI
$repo_name = [string]::IsNullOrEmpty($repo_name) ? (Get-Item .).Name : $repo_name
gh repo edit ishandutta2007/$repo_name --add-topic "curated-list,awesome-list"
git pull

github-tabs Discussions --token $GITHUB_TOKEN
git pull
github-tabs Sponsorships --token $GITHUB_TOKEN
git pull
github-protect --token $GITHUB_TOKEN
git pull

git add README.md
git commit -m "first code"
git pull
git push

cp ..\Awesome-BERT\.gitignore .
git add .\.gitignore
git commit -m .\.gitignore

cp ..\Awesome-BERT\LICENSE .
