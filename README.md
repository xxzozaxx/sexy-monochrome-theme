# Sexy monochrome theme for emacs
This theme is just fork from [sexy-monochrome-theme](https://github.com/voloyev/sexy-monochrome-theme) which is based on the Xavier Noria [monochrome-theme](https://github.com/fxn/monochrome-theme.el). And impressed by ["Monochrome color scheme for Vim"](https://github.com/fxn/vim-monochrome)

## Screenshots
### markdown(right) & Source Code(left)
![Simple monochrome theme source code](https://github.com/xxzozaxx/sexy-monochrome-theme/blob/master/simpleMonoSC.png?raw=true)

### Org-mode (spacemacs markdown layer README.org)
![Simple monochrome theme org-mode](https://github.com/xxzozaxx/sexy-monochrome-theme/blob/master/simpleMonoORG.png?raw=true)

### randowm file (racket)
![Simple monochrome theme racket](https://github.com/xxzozaxx/sexy-monochrome-theme/blob/master/simpleMonoR.png)

## Installation
 throw this file into ~/.emacs.d and_

```elisp
     (add-to-list 'custom-theme-load-path
                  "~/.emacs.d/YOUR_FOLDER_WITH_THEME/")
```
and

```elisp
     M-x load-theme RET simple-monochrome RET
```
then put in your init file
```elisp
    (load-theme 'simple-monochrome)
```

Works with Emacs >= 24.
