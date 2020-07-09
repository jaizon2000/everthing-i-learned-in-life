# everthing i learned in life
 Everthing I Learn in Life so I never forget

## Embedding Loom Videos: [loom.com](https://www.loom.com)

``` HTML
<div class="hidden" style="position: relative; padding-bottom: 56.25%; height: 0;">
    <iframe src="https://www.loom.com/embed/VIDEO_ID"
        frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen 
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
    </iframe>
<div>
```
Replace `VIDEO_ID` with the loom video key found in the **link of the loom video**.  
![](https://i.imgur.com/RiqpKDa.png)  
Here the `VIDEO_ID` is `5e1afc56171b4cf1abb7b1d9efbab33d`  

Make sure that the **source link** is **`.../embed/...`** inststead of `.../share/...`
