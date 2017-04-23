# writeahead-word-add-ins
WriteAhead Word Add-ins 

Requirement:   
    Office for Mac 2016 - Word (15.22 or later)
    Node.js runtime

How to use:


git clone this project 

```
(in the project folder)

npm install 

mv ~/Library/Containers/com.microsoft.Word/Data/Documents ~/Library/Containers/com.microsoft.Word/Data/documents

mkdir ~/Library/Containers/com.microsoft.Word/Data/documents/wef

cp write-ahead-word-manifest.xml ~/Library/Containers/com.microsoft.Word/Data/documents/wef


```



Activate:
```
npm start

```

activate it in word >> insert >> my add-ins. >> WriteAhead
