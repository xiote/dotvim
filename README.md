# dotvim

## Install
```bash
git clone --recursive https://github.com/xiote/dotvim .vim
```

## 줄 이동

`myvim` 설정은 입력 모드의 `Ctrl+A`를 앞쪽 공백을 포함한 줄 맨 앞으로, `Ctrl+E`를 줄 끝으로 이동하도록 매핑합니다. 이동한 뒤에도 입력 모드를 유지합니다. macOS에서 Karabiner가 오른쪽 Command를 Control로 변환하는 터미널에서는 `오른쪽 Command+A/E`로 사용합니다.

현재 저장소가 가리키는 `myvim` 서브모듈 버전이 설치되어 있어야 합니다. 이미 열려 있는 Vim에 적용하는 방법은 [myvim 사용법](pack/plugins/start/myvim/README.md)을 참고하세요.

## List
```
xiote/myvim               ' Vimrc

tomtom/tcomment_vim       ' tcomment provides easy to use, file-type sensible comments for Vim.
jiangmiao/auto-pairs      ' Insert or delete brackets, parens, quotes in pair.
dense-analysis/ale        ' Asynchronous Lint Engine <For signcolumn>
vim-airline/vim-airline   ' Lean & mean status/tabline for vim that's light as air. <For seperating statusline>

pangloss/vim-javascript   ' JavaScript bundle for vim, this bundle provides syntax highlighting and improved indentation.
prettier/vim-prettier     ' An opinionated code formatter <Show quickfix and not focus, conflict with ale>
alvan/vim-closetag        ' Easy closetag plugin

fatih/vim-go              ' This plugin adds Go language support for Vim
```
