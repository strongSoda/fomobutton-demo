## Demo Sites for FOMO Button

### Steps

1. Create a new folder for the new client by copying the `template` folder and renaming it.

2. Substitute `{client_folder_name}` everywhere in the index.html file in this new folder with the folder name of the new client exactly as in the [plugin repo](https://github.com/strongSoda/fomo-btn-test)

3. Create a link entry for the new demo site in `index.html` at the root of this repo by copy & pasting the following and replacing the value of `{client_folder_name}` and `{ClientName}`

```jsx
<a href="./{client_folder_name}/index.html" rel="noopener noreferrer">
  {ClientName}
</a>
```
