```bash
# KeyRepeat：字符连续输入间隔，此处为1（15ms），系统默认最低值2（30ms）。
defaults write -g KeyRepeat -int 1
# 响应连续输入的等待时间，此处为10（150ms），系统默认最低值15（225ms）。
defaults write -g InitialKeyRepeat -int 10
# 连续输入
defaults write -g ApplePressAndHoldEnabled -bool false
# 设置启动坞响应时间
defaults write com.apple.dock autohide-delay -int 0
```

