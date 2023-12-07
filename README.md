# matlab lsp language server for sublime text
These are the settings to get working the official language server within sublime. See [MATLAB-language-server](https://github.com/mathworks/MATLAB-language-server).

## Install server
```bash
git clone https://github.com/mathworks/MATLAB-language-server
cd MATLAB-language-server/
npm install && npm run compile && npm run package
```

>Remember the path in which you installed this.

## Setup up the server
1. In sublime text install the lsp package
2. Open `Preferences > Package Settings > LSP > Settings`
3. Add the content of the `lsp-matlab.sublime-settings` file to your clients (copy-paste if you have non).
4. **Modify paths accordingly**.

> MATLAB path should look like `/usr/local/MATLAB/R2023a`. Use `matlabroot` within matlab to get its value.