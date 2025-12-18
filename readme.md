METHOD 1 : <br>
git - repo create <br>
Enter <br>
git clone < link > <br>
Enter <br>
git add . / git add index.html <br>
Enter <br>
git commit -m "msg" <br> 
Enter <br>
git push origin main <br>


#Tailwind CSS CLI
<h1>Website</h1> 
1. copy - npm install tailwindcss @tailwindcss/cli <br>
2. copy - @import "tailwindcss"; <br>
3. copy - npx @tailwindcss/cli -i ./input.css -o ./output. css --watch <br>


<h1>VS Code</h1>
1. Open Terminal <br>
2. Paste cmd <br>
3. Enter <br>
4. Create index.html and input.css <br>
5. index.html --> <link rel="stylesheet" href="./output.css"> <br>
6. input.css --> @import "tailwindcss"; <br>
7. package.json --> <br>
    "scripts": {
        "start" : "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch"
     }  <br>
8. npm run start