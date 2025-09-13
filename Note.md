# Basic Operations

## File Management

## Permission Mangement

## File Search

## Software and Packages

## System Infomation

## Disks and Storage

# Network and Security

## Network Configuration

# Developer Tools

## git

reference : [Git Documentation](https://git-scm.com/docs)

| command                                    | directions                                                                                                                                                                  |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `git init`                                 | 初始化當前資料夾                                                                                                                                                            |
| `git status`                               | 顯示目前工作區狀態                                                                                                                                                          |
| `git add <filename>`                       | 將未被追蹤的檔案加入追蹤中                                                                                                                                                  |
| `git commit -m "<message>"`                | 對追蹤中的檔案拍照並輸入說明                                                                                                                                                |
| git config --global user.email "`<email>`" | 設定使用者電子郵件                                                                                                                                                          |
| git config --global user.name "`<name>`"   | 設定使用者名稱                                                                                                                                                              |
| git log                                    | 顯示當前所有的歷史紀錄(可以加 --all 顯示所有的紀錄（包含遠端）)                                                                                                             |
| git show`<commit id>`                      | 顯示此紀錄修改的內容有哪些                                                                                                                                                  |
| git diff`<filename>`                       | 顯示檔案目前與最後一次 commit 的差異                                                                                                                                        |
| git restore --staged`<filename>`           | 將檔案移出追蹤中（任何情境都可以達到效果）                                                                                                                                  |
| git restore`<filename>`                    | 將未追蹤的檔案還原成最後一次拍照的狀態                                                                                                                                      |
| git reset --`<mode>` `<commit id>`         | 模式: <br>soft: 將異動放回追蹤中區塊\mixed: 將異動放回未追蹤區塊\hard: 將異動刪除,Commit ID:可以給指定的 ID/也可以給 HEAD^ 表示往前 reset 一個 commit，^ 的數量代表往前幾個 |
|                                            |                                                                                                                                                                             |

## oh-my-zsh

reference : [Git Alias List](https://kapeli.com/cheat_sheets/Oh-My-Zsh_Git.docset/Contents/Resources/Documents/index)

| alias | command       |
| ----- | ------------- |
| g     | git           |
| ga    | git add       |
| gaa   | git add --all |
| gb    | git branch    |
| gl    | git pull      |

### Git Aliases

## Editors

# Other
