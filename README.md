"# test" 

gtihub 說明書

# 錯誤訊息：	fatal: remote origin already exists.
		遠端分支已經存在。

# 解決方式：	git remote rm origin
		刪除遠端分支

		git remote add origin https://github.com/<USERNAME>/<REPO>.git
		重新設定分支

#首次使用：	1. github 建立repo
		2. 在自己的電腦建一個新的資料夾
		3. 開啟命令提示字元
		4. (移到你所在的磁碟機 如果不在C槽 --> D槽 就打"D:")
		5. cd 你的資料夾位置 ex: C:\Users\User\Desktop\github\
		
		** 如果有 "error: remote origin already exists. " 照上面的方法做
		6. echo "# test" >> README.md
		7. git init (git 的初始化)
		8. git add README.md (在git裡 待命一個叫README.md的檔案)
		9. git commit -m "first commit" (commit 待命的檔案 名稱叫"first commit")
		10. git branch -M main
		11. git remote add origin https://github.com/<USERNAME>/<REPO>.git