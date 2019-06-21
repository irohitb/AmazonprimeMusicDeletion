1. Go to `https://music.amazon.in/my/songs`
2. right click and select inspect elements 
3. click on console on the upper right handside 
4. Paste the following thing in your console 
```
const classesWithLabel = document.getElementsByClassName("checkboxLabel")
for (let i=0; i<classesWithLabel.length; i++) {
classesWithLabel[i].click()
}
```
5. This will select upto 100 songs, click on remove items to remove songs 
6. Refresh the window, redo it until all your songs are removed. 
