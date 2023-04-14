# Digital-twin

MMS and Goose digital twins

一、針對能源系統所需協定，建立數位分身模組，範圍主要以 IEC 61850、MMS、GOOSE、
Modbus 及 DNP3 等協定，透過剖析封包產出 SCL File 後，提供程式碼一式，模組／
程式碼架構說明文件，及環境安裝說明&操作說明手冊等項目。
須提供成功案例說明，包含但不限制以下：
1. 分析新加坡科技設計大學變電站測試平台封包，產製對應 SCL File，產製的 SCL 
File 相似度達 80%以上。
2. 分析台南沙崙變電站測試平台封包，產製對應 SCL File，產製的 SCL File 相似
度達 80%以上。
二、建立相似度分析演算法，針對數位分身之相似度建立起計算之演算式，以驗証數位
分身之真實度，提供相似度分析演算法之驗證程式一份、模組／程式碼架構說明文
件，及環境安裝說明&操作說明手冊等項目。
## begin
先確定有沒有安裝pipenv套件
pip install pipenv

1. pipenv --python 3.8
2. pipenv install -r requirements.txt
3. choose the interpreter of python

## git 

### init

1. git config --global user.name "name"
2. git config --global user.email "gitlab@mail"

### command
```bash
git status  # git 狀態
git add . # 將檔案加進stage 暫存
git branch name  # 建立新分支
git commit
git push
git pull
git merge # 合併分支
git checkout name #更換分支
```
