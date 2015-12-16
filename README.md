### Boilerplate to create new site using [CmsLess](https://github.com/alexanderbird/cms-less)

* fork this repo
  * note that CmsLess is included as a submodule, so [`git clone --recursive`](http://stackoverflow.com/questions/3796927/how-to-git-clone-including-submodules/4438292#4438292)

|URL|File Served|Contents of `#cms-less-destination` element|
|---|-----------|-------------------------------------------|
|example.com/|`./index.html`|`./cms-less-content/index.html`|
|example.com/index.html|`./index.html`|`./cms-less-content/index.html`|
|example.com/#index|`./index.html`|`./cms-less-content/index.html`|
|example.com/#other_page|`./index.html`|`./cms-less-content/other_page.html`|
|example.com/#any_missing_page|`./index.html`|`./cms-less-content/404.html`|
|example.com/#other_page-anchor|`./index.html`|`./cms-less-content/other_page.html`|

refer to [CmsLess documentation](https://github.com/alexanderbird/cms-less) for more details
