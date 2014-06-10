Before using these dict files you'd better install the plugins below:  

1. [AutoComplPop](https://github.com/vim-scripts/AutoComplPop)
2. [SuperTab](https://github.com/vim-scripts/SuperTab)  

This repo is also for [Vundle](https://github.com/gmarik/Vundle.vim), please install this repo by it.    

Add these sentences into your ```.vimrc``` file to use these files:  

	autocmd FileType javascript set dictionary=~/.vim/bundle/vim-dicts/javascript.dict
	autocmd FileType ruby set dictionary=~/.vim/bundle/vim-dicts/ruby.dict  
	
After finishing these steps, you can have auto completion for methods or functions when editing ruby and js files!  

