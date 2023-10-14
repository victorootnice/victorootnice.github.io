0. Currently, it can impact all known versions and bypass XSS defense measures under the highest security mode ( "protect_from_xss":true )
1. Create a new markdown note using vnote.
   ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/339b1449-e0ff-4609-b341-466f7b16fead)

2. Write an XSS payload into the markdown file.
  ```<xss onclick="alert(1)" style=display:block>Click here</xss>```
  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/b7668aa0-d96b-443e-96f6-e09ef0736d43)

3. Click the 'Click here' text to trigger XSS.
   ``` According to the project author's description, when the configuration file is set to "protect_from_xss":true, it enables the highest level of XSS defense. ```

  ![image](https://github.com/victorootnice/victorootnice.github.io/assets/147939577/c209c350-378b-44af-868c-86a1ba2e667a)


