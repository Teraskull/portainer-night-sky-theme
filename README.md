<h1 align="center">
  Portainer Night Sky Theme
</h1>

<p align="center">
    Alternative dark theme for Portainer
</p>

![Containers](https://user-images.githubusercontent.com/24798198/147072878-0a40f8f5-8425-4189-b1fa-d83c497763f6.png)

No major changes, only created a blue-tinted palette for better contrast and less eyestrain than the default dark colors.

Font changed to [Inter](https://fonts.google.com/specimen/Inter) for improved readability.

Monospace font changed to [Fira Code](https://fonts.google.com/specimen/Fira+Code).


## Installing

### Using Stylus:

First, install the [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en) extension.

Next, install the [UserCSS](https://github.com/Teraskull/portainer-night-sky-theme/raw/master/style.user.css) theme.

Make sure to change the URL on [line 16](https://github.com/Teraskull/portainer-night-sky-theme/blob/811e7cb2b7e1dbb6cffd0da21a9f00e137aca454/style.user.css#L16) to match your Portainer URL.
If your Portainer is running on a different port, use `url` instead of `domain`.

Example:
```css
@-moz-document url("http://my-server.local:8080/") {
```

## License

Distributed under the AGPL-3.0 License. See [`LICENSE`](/LICENSE) for more information.
