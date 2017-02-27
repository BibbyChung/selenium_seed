# selenium_seed

It's my basic selenium project.

### Principle

- 能快就不要慢
- 一個 suit 由多個 test case 組合起來
- 每個 test case 就是個獨立模組

### Trick
- 在 angular 裡面的 type 動作，請換成 sendKeys 動作 （for two way binding）
- 讓每個 test case 結束，可以用 waitForPageToLoad 來確定

### 常用指令
- 取得 url => selenium.browserbot.getCurrentWindow().document.URL
- 使用 jquery => elementselenium.browserbot.getUserWindow().jQuery(".selector")
- 塞入變數 => storeEval | value | variable
- 驗證變數 => assertEval | ${variable} | value
- 執行 script => runScript | javascript{alert('xxx')} |
- 執行 runEval => getEval | alert('xxx') |
	
### Reference
- http://www.software-testing-tutorials-automation.com/p/learn-selenium-ide.html
