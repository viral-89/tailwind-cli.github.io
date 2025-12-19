METHOD 1 : <br>
```
git - repo create 
Enter 
git clone < link >
Enter
git add . / git add index.html 
Enter 
git commit -m "msg" 
Enter 
git push origin main 
```


## Tailwind CSS CLI
<h1>Website</h1> 

```
1. copy - npm install tailwindcss @tailwindcss/cli 
2. copy - @import "tailwindcss"; 
3. copy - npx @tailwindcss/cli -i ./input.css -o ./output. css --watch
```

<h1>VS Code</h1>

```
1. Open Terminal 
2. Paste cmd 
3. Enter 
4. Create index.html and input.css 
5. index.html --> <link rel="stylesheet" href="./output.css">
6. input.css --> @import "tailwindcss"; 
7. package.json --> 
    "scripts": {
        "start" : "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch"
     }  
8. npm run start
```
