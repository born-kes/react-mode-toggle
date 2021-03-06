# react-mode-toggle
![PrintScreen](https://born-kes.github.io/react-mode-toggle/icon.jpg)


## #Version Demo:
press key F12 or Ctrl+Shift+m - in presentation

=> and active view mobile (response mode) 

[GitHub Page Demo](https://born-kes.github.io/react-mode-toggle/)

---

## #Technologies
#### and use in project
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>

````
npx create-react-app
````
Add Component `SchemaColor`
````
[...]
<div className={'toggle-container'}>
    <input type="checkbox" id="toggleMode" onChange={handlerChange} />
    <label htmlFor="toggleMode" />
    <div />
</div>
````
and css
````
[...]
@media all and (max-width: 414px) {
    .container {
        --container-height: 80vh;
        --container-margin-left: 1em;
        --container-margin-right: 1em;
    }
}
@media all and (max-height: 414px) {
    .container {
        --container-height: 80vh;
        --container-margin-top: 1em;
        --container-margin-bottom: 1em;
    }
}
````

````
@media all and (max-width: 768px) {
    .container {
        --container-height: 50vh;
        grid-template-columns: 100%;
        grid-template-rows: 15% 15% auto;
        grid-template-areas: "switch" "title" "content";
    }
}
````

---
## When you want to run localhost

#### What you need?
- git
- node.js

### # step by step 

clone repository:
````
gh repo clone born-kes/react-mode-toggle
````

run Console ( CMD, PowerShell, ...)
````
cd react-mode-toggle
npm i
npm run start
````