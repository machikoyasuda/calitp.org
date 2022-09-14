# calitp.org

A brief explainer website for the California Integrated Travel Project (Cal-ITP) <https://calitp.org>.

## Development

This is a [Jekyll][jekyll] static site. We include a [Devcontainer][devcontainer] configuration to help with local testing
and development.

1. Open the repository directory in VS Code
1. `Ctrl/Cmd+Shift+P` to bring up the Command Palette
1. Enter `Remote-Containers` to filter the command list
1. Enter or select `Rebuild and Reopen in Container` to start from scratch
1. Enter or select `Reopen in Container` to reopen the last devcontainer used

Once inside the devcontainer, you have the manually start the site:

1. `Ctrl/Cmd+Shift+P` to bring up the Command Palette
1. Enter `Tasks: Run Task`
1. Enter or select `Jekyll: Build Dev`

The site is running on <http://127.0.0.1>; check the VS Code _Ports_ tab for the exact port. Auto rebuild/reload will be active
and will watch the site files for changes.

## License

Content (including graphics, images, video, documents, and text) in this repository is licensed under [CC-BY 4.0][content-license].

The source code in this repository used to format and display the content is licensed under [GPL-3.0][code-license].

[code-license]: ./LICENSE
[content-license]: https://creativecommons.org/licenses/by/4.0/
[devcontainer]: https://code.visualstudio.com/docs/remote/remote-overview
[jekyll]: https://jekyllrb.com
