You will have a file with all the conflicts in there

Just fix the errors

    <====
    code1
    ====
    code2
    ====>

result:

    code1

Now you can perform a git commit with:

`git add .`
`git commit -m "your message"` #this will create the merge commit
`git push`