```
[filter "lfs"]
	smudge = git-lfs smudge -- %f
	process = git-lfs filter-process
	required = true
	clean = git-lfs clean -- %f
[user]
	name = bigym
	email = 595335057@qq.com
[gui]
	recentrepo = D:/GitHub/go

[http "https://github.com"]
	proxy = socks5://127.0.0.1:1080



```