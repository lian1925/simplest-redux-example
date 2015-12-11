
## 创建新分支

	git checkout -b redux-simple 
<!-- more --> 
## 提交更新log

	git commit -a -m 'three seconds is better' 

## 推送github

	git push origin redux-simple

## 免密码cache

	git config --global credential.helper 'cache --timeout 7200'