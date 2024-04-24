# scts

Custom VS Code snippet to quickly add Typescript script tags into Svelte files.

## Configuration

Add the following into your **$HOME/.vscode/snippets.json** file:

```
{
  "html": {
    "snippets": {
      "scts": "<script lang=\"ts\">\n\t${0}\n</script>"
    }
  }
}
```
The Windows address would be: **C:\Users\\{Username}\AppData\Local\Programs\Microsoft VS Code\snippets.json**

_If you don't have a **snippets.json** file, just create it._

## Result

<img src="https://i.ibb.co/FWkKbwp/scts.gif" alt="scts" width="700">
