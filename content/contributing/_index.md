---
title: Contributing
geekdocFlatSection: true
---

## Installing Dependencies

If you just want to contribute small edits, then all you need is to have a GitHub account and click the `Edit Page` link in the upper right corner.

However, the recommended workflow entails editing the wiki locally, for which you'd also need git, Hugo and VSCode. You can install [git](https://git-scm.com/install/) and [VSCode](https://code.visualstudio.com/download) at their respective download links, if they aren't installed already. The setup for Hugo is a little more involved and will be explained in more detail further down.

This writeup will assume that you have a little experience with git already. So fork the repo first and clone it locally.  
Afterwards you can head to installing hugo:

{{< tabs "installing-hugo" >}}

{{< tab "Windows" >}} 
- Go to https://github.com/gohugoio/hugo/releases/latest
- Scroll down to `Assets`, and download the file `hugo_VERSION_windows-amd64.zip`
- Extract the file `hugo.exe` and place it into the directory where you cloned the repository to.
{{< /tab >}}

{{< tab "Linux" >}} 
- Follow the instructions at https://gohugo.io/installation/linux/#repository-packages to install hugo from your community's package repos
{{< /tab >}}

{{< tab "macOS" >}} 
To be filled out by someone who uses macos :)
{{< /tab >}}

{{< /tabs >}}

Afterwards you can open your cloned folder in VSCode. You should also mark it as a trusted folder if it asks you about it.  
Then, in the Menu Bar at the top, click `Terminal` -> `New Terminal`.  
Entering the following command opens a local webhost and prints the URL (typically `http://localhost:1313/`). You can open it in a web browser and then see feedback on your changes in real time.
{{< tabs "hugo-serve" >}}

{{< tab "Windows" >}} 
`.\hugo.exe serve` 
{{< /tab >}}

{{< tab "Linux" >}} 
`hugo serve`
{{< /tab >}}

{{< tab "macOS" >}} 
To be filled out by someone who uses macos :)
{{< /tab >}}

{{< /tabs >}}


## Writing pages

This wiki uses Hugo with the geekdoc theme, so looking at their documentation is generally helpful. For hugo you can find it [here](https://gohugo.io/documentation/) and for geekdocs [here](https://geekdocs.de/shortcodes/audio/). The most important gist though is.
- Pages go into `content`. Each page is symbolized by a folder and an `_index.md` file.
- If you want to use images/videos/files, place them into the same folder as the page they're used in.
- The structure of a page index file typically is: front matter and the content. 
    - The front matter is some page specific meta-information in yaml at the top of the file
    - The content is written in markdown, with some special features being used via shortcodes.\
    E.g. `{{</* button href="https://youtu.be/dQw4w9WgXcQ" */>}}Rick Roll{{</* /button */>}}` results in {{< button href="https://youtu.be/dQw4w9WgXcQ" >}}Rick Roll{{< /button >}}.\
    The most important shortcodes are in the linked geekdocs documentation above.