# scts

Custom VS Code snippet to quickly add Typescript script tags into Svelte files.

## Configuration

⚠ You need to have the [Svelte extension for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) already installed.

1. Add the emmet snippets to Svelte files:
   
<img src="https://i.ibb.co/pW8tjGm/settings.png" alt="settings" width="550">

3. Add into your **$HOME/.vscode/snippets.json** file the following:

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
