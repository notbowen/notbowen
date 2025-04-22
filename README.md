# Hi 👋, I'm Bowen

- 📚 I’m currently studying **Cybersecurity** at **Ngee Ann Polytechnic**

- 👨‍💻 Find out more about me at **[https://hubowen.dev/](https://hubowen.dev/)**

- 💌 Decrypt my email by running the following JS code in your console!

```js
(async()=>{const c="findmyemail",d="0000",eH="8b85ceb8a5c177e45d53f420fdb0b8afd64696d40b341e0c13d2e197901ac6c4",iH="f59c372d4a14228c544729d812997424",E=new TextEncoder(),h=x=>{const b=new Uint8Array(x.length/2);for(let i=0;i<b.length;i++)b[i]=parseInt(x.substr(i*2,2),16);return b},s=async m=>{const H=await crypto.subtle.digest("SHA-256",E.encode(m));return Array.from(new Uint8Array(H)).map(b=>b.toString(16).padStart(2,"0")).join("")},f=async()=>{console.log("Starting PoW...");let n=0;while(true){const S=await s(c+n);if(S.startsWith(d)){console.log("Nonce:",n);const kH=await crypto.subtle.digest("SHA-256",E.encode(n.toString())),k=new Uint8Array(kH).slice(0,16),i=h(iH),e=h(eH);try{const a={name:"AES-CBC",iv:i},cK=await crypto.subtle.importKey("raw",k,a,!1,["decrypt"]),dD=await crypto.subtle.decrypt(a,cK,e);console.log("Reward:",new TextDecoder().decode(dD))}catch(e){console.error("Decrypt failed:",e)}break}n++}};await f()})();
```

# My Stats

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=notbowen&theme=gruvbox&rank=-C,-B" alt="notbowen" /></a> </p>

<p>
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=notbowen&show_icons=true&locale=en&layout=compact&theme=gruvbox" alt="notbowen" />
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=notbowen&show_icons=true&locale=en&theme=gruvbox&hide_rank=true&include_all_commits=true" alt="notbowen" />
</p>

## Banger Quotes

> Some people, when confronted with a problem, think,  
“I know, I’ll use threads,”  
and then two they hav erpoblesms.
 
—Ned Batchelder
