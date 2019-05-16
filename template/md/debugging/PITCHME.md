---?image=template/img/vscode.png
@title[Debugging]

## @color[white](Debugging)

@fa[arrow-down text-white]

@snap[south docslink span-50 text-white]
Debugging
@snapend

+++?image=template/img/bg/black.jpg&position=left&size=70% 100%
@title[How To Debug]

@snap[east text-14 text-bold text-black span-50]
Debugging
@snapend

@snap[west text-white]
@ul[split-screen-list text-08](false)
- F5
- breakpoints
- advanced
  - .gitignore
  - environments
  - launch.json

@ulend
@snapend

Note:
add to gitignore

```
.tmp
.vscode
*args.json
```

args
```
{
    "ANSIBLE_MODULE_ARGS": {
        "name": "hello",
        "new": true
    }
}
```

launch.json
```
"name": "[lanuage]: Current File (Integrated Terminal)",
...,
"args": ["tmp/args.json"]     // add this line
```