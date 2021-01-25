# vimconf

.vimrc中引入vimconf文件夹下的vim自定义配置文件vimrc.customize
引入自定义配置文件的方式：
"""
" 加载自定义配置
if filereadable(expand($HOME . '/vimconfig/vimrc.customize'))
    source $HOME/vimconfig/vimrc.customize
endif
"""
