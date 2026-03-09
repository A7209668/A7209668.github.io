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
- [x] 📄 [範例2](#範例2)
- [x] 📄 [範例3](#範例3)
- [ ] 📄 [範例4](#範例4)
- [ ] 📄 [範例5](#範例5)
- [ ] 📄 [範例6](#範例6)
- [ ] 📄 [範例7](#範例7)
- [ ] 📄 [範例8](#範例8)
- [ ] 📄 [範例9](#範例9)
- [ ] 📄 [範例10](#範例10)

## 📄範例1
```C
// 範例1 比數值
#include<iostream>
using namespace std;

int main(){
int number, max, min; // 3整數，輸入值、最大值、最小值
cin >> number; // 輸入第1值
max = min = number; // 第1值為最大值、最小值
for(int i=0; i<4; i++){ // for迴圈輸入4值
cin >> number; // 輸入值
if(number > max)max = number; // 輸入值大於最大值，最大值為輸入值
if(number < min)min = number; // 輸入值小於最小值，最小值為輸入值
}cout << max << " " << min << endl; // 輸出最大值與最小值
return 0;}
```

## 📄範例2
```C
// 範例2 平均數
#include<iostream>
#include<iomanip>
using namespace std;

int main(){
int number, sum = 0; // 2整數，輸入值、總和
for(int i=0; i<5; i++){ // for迴圈輸入5值
cin >> number; // 每次輸入1值
sum += number; // 每次加總輸入值
}cout << fixed << setprecision(2) << sum/5.0 << endl; // 輸入5整數平均，2位小數
return 0;}
```

## 📄範例3
```C
// 範例3 最小公倍數
#include<iostream>
using namespace std;

int main(){
int num_1, num_2, mult; // 3整數，2輸入值、乘積
cin >> num_1 >> num_2; // 輸入2值 欲求最小公倍數
mult = num_1 * num_2; // 將兩數相乘存在mult變數
while(num_1*num_2){ // 運用while迴圈，直到兩數相乘為0結束迴圈
if(num_1 >= num_2)num_1 %= num_2; // 如果第一數大於第二數，則取第一數除第二數的餘數，並將第一數替換為該餘數
else num_2 %= num_1; // 如果第二數大於第一數，則取第二數除第一數的餘數，並將第二數替換為該餘數
}
if(num_1 == 0)cout << mult/num_2 << endl; // 若第一數為0，則用乘積除以第二數，即為最小公倍數，並輸出
else cout << mult/num_1 <<endl; // 若第二數為0，則用乘積除以第一數，即為最小公倍數，並輸出
return 0;}
```

## 📄範例4
```C
// 範例4
```

## 📄範例5
```C
// 範例5
```

## 📄範例6
```C
// 範例6
```

## 📄範例7
```C
// 範例7
```

## 📄範例8
```C
// 範例8
```

## 📄範例9
```C
// 範例9
```

## 📄範例10
```C
// 範例10
```

</details>
