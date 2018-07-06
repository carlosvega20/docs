## My Vim Setup

Install with
https://github.com/VundleVim/Vundle.vim

My vim vundle
https://gist.github.com/carlosvega20/19c7add0f1309a80f9df680fdb2c130f

My .vimrc
https://gist.github.com/carlosvega20/a66fe2ea76a6700e4ca6354a1787878f

My .zshrc
https://gist.github.com/carlosvega20/af3f779a98093403993c6a886256b178


Extra steps to get pathogen and zenburn colors

```bash
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

```bash
mkdir -p ~/.vim/colors && \
curl -LSso ~/.vim/colors/zenburn.vim https://raw.githubusercontent.com/jnurmine/Zenburn/master/colors/zenburn.vim
```
