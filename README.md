# js-gherkin-ui-test-webdriverio
HOWTO update chromedriver

npm cache clean --force
npm install selenium-standalone@latest --save-dev
npx selenium-standalone install
If not works doenolad manually from
https://googlechromelabs.github.io/chrome-for-testing/#stable
remove .exe extension from chromedriver.exe 
And update necessary file in 
\node_modules\selenium-standalone\.selenium\chromedriver\chromedriver





HOWTO run

tasklist /v | findstr "java"
taskkill /IM java.exe /F
npm run wdio
// tskill /v java*
taskkill /IM java.exe /F  

