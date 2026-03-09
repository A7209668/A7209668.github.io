<details open><summary>目錄</summary>

## 🗄️目錄

- [x] 📋 [範本](#範本)
- [ ] 💻 [代碼](#代碼)

</details>

---
<details open><summary>範本</summary>

# 📋範本

---
## 📄簡介
這是 README 範本，包含[標題](#網頁)、[副標題](#簡介)、[表格](#功能)、[範例](#範例)以及[進度](#進度)，用來快速建立 GitHub 頁面。
> 這是註解

---
## 🛠️功能
| 功能 | 說明 |
| ---- | ---- |
| 本地連結 | [首頁](./index.html) |
| 本地連結 | [頁面](./README.md) |
| 本地連結 | [頁面](./) |
| 同頁錨點 | [標題](#網頁) |
| 提示文字 | `提示` |
| 強調文字 | **重點** |

---
## 📌範例
```javascript
// 範例
console.log("Hello World");
```

---
## ⌛進度
- [x] 完成 README
- [ ] 完成網頁首頁
- [ ] 完成功能開發

</details>

---
<details open><summary>代碼</summary>

# 💻代碼

## 🗄️目錄

- [x] 📄 [範例1](#範例1)
- [ ] 📄 [範例2](#範例1)

## 範例1
```C
// 範例1
#include<iostream>
using namespace std;

int main(){
int number, max, min; //宣告三個數，分別為輸入值、最大值、最小值
cin >> number; //輸入第一個值
max = min = number; //將第一個值設定成最大值、最小值
for(int i=0; i<4; i++){ //使用for迴圈輸入後續4個值
cin >> number; //輸入值
if(number > max)max = number; //若輸入值比目前最大值大，則將最大值換成輸入值
if(number < min)min = number; //若輸入值比目前最小值小，則將最小值換成輸入值
}cout << max << " " << min << endl; //輸出最大值與最小值
return 0;}
```


</details>
