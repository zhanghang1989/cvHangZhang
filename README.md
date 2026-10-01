# Real-time Latex PDF Preview (Overleaf + GitHub)
Created by [Hang Zhang](https://hangzhang.org/).

## Two-page industry resume

- `cvHangZhang.tex` / `cvHangZhang.pdf`: OpenAI-oriented summary emphasizing multimodal foundation models, VLA, physical AI, and long-context architectures.
- `my.bib` retains the full bibliography; the resume shows eight selected research contributions and links to Google Scholar.

Build the resume from the repository root with Tectonic (downloads standard LaTeX dependencies on first use):

```sh
tectonic cvHangZhang.tex
```

The source also supports the repository's existing pdfLaTeX build workflow.

[[PDF](https://hangzhang.org/cvHangZhang/cvHangZhang.pdf), [Overleaf](https://www.overleaf.com/read/vdftpkdcbhhx)]


This is an example project, which automatically render the PDF. Feel free to fork for you own purpose. 

1. Overleaf is very convenient for editing PDF file, but it does not provide PDF preview service. You can use this project to generate an auto updating PDF (synced with overleaf) and link it to your website (e.g. resume). [[Overleaf](https://www.overleaf.com/read/vdftpkdcbhhx), [PDF](https://hangzhang.org/cvHangZhang/cvHangZhang.pdf)]
2. Some researchers enjoy using git to collaborate paper writting, but it is not straightforward to preview the PDF in a Pull Request. This project enables this feature. 

## Updating PDF

There are two ways of updating the PDF:

### Modify on Overleaf
You can easily modify the files and push it to GitHub using the built-in sync feature. The preview PDF will be automatically updated and renderred.

![](./fig/overleaf.png)


### Send A Pull Request
You may also send a pull request to this project, you can download the preview pdf from GitHub action.

![](./fig/pull_request.png)


