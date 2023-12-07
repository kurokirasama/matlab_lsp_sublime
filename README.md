# MATLAB lsp language server for sublime text
Here are the settings to get the official language server working within Sublime. See [MATLAB-language-server](https://github.com/mathworks/MATLAB-language-server).

## Install server
```bash
git clone https://github.com/mathworks/MATLAB-language-server
cd MATLAB-language-server/
npm install && npm run compile && npm run package
```

>Remember the PATH in which you installed this.
>**Needs MATLAB 2021+.**

## Setup up the server
1. Clone this repo: `git clone https://github.com/kurokirasama/matlab_lsp_sublime`
1. In sublime text install the LSP package.
2. Open `Preferences > Package Settings > LSP > Settings`
3. Add the content of the `lsp-matlab.sublime-settings` file to your clients (copy-paste if you have none).
4. **Modify paths accordingly**.

> MATLAB path should look like `/usr/local/MATLAB/R2023a` (in linux). Use `matlabroot` within MATLAB to get its value.
> **Tested in Ubuntu 20.04, steps my vary in other distributions or OS's.**