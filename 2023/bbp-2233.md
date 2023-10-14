1. 通过vnote创建一个新的markdown笔记
   ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/339b1449-e0ff-4609-b341-466f7b16fead)
2. 写入XSS - payload到文件内
  ```<xss onclick="alert(1)" style=display:block>Click here</xss>```
  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/bb4724e7-64bd-49e7-b218-fa1aedb2e7c5)
3. 点击字体"click here"触发XSS
  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/7be8bf84-a1e2-4461-9027-4d9481430364)
