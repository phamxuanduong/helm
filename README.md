helm package /folder

mv file.tgz charts/folder/

helm repo index charts/ --url https://phamxuanduong.github.io/helm/charts

git add .
git commit -m "."
git push
