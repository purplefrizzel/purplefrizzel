## :wave: Hey, I'm Lew

**Profiles**

<a href="https://dev.to/purplefrizzel">
  <img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="DEV Profile" width="32" height="32"/>
</a>

<a href="https://twitter.com/purplefrizzel">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9f/Twitter_bird_logo_2012.svg/100px-Twitter_bird_logo_2012.svg.png" alt="Twitter Profile" width="43" height="32" />
</a>


## Some random snippets :shrug:

**Loop of boom**

```javascript
while (true) {
  console.log(Math.floor(Math.random() * 100))
}
```
<small>If you are feeling brave paste this into the dev tools console :sweat_smile:</small>

**Random six digit generator**
```javascript
function randomizer(len) {
  const charSet = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789";
  let randomStr = "";

   for (let i = 0; i < len; i++) {
    const randomPoz = Math.floor(Math.random() * charSet.length);
    randomStr += charSet.substring(randomPoz, randomPoz + 1);
  }
  
  return randomStr
}
```
<small>I use this one a lot :joy:</small>
