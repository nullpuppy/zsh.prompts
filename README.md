# Modified 'agnoster' theme

Modified specifically for use with [Prezto](https://github.com/sorin-ionescu/prezto).
Also fully compatible with [YADR](https://github.com/skwp/dotfiles) as it incorporates Prezto as a sub-module.

Please be aware that I've intentionally left this theme with the original name as I didn't create it.  All I did was modify it for use with Prezto/YADR.

## Prerequisites

-	A Powerline-patched font, as per the [original gist's documentation](https://gist.github.com/3712874)
-	If you have never used [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh/) and you're using [YADR](https://github.com/skwp/dotfiles), it's also highly recommended to get the [git.zsh](https://github.com/robbyrussell/oh-my-zsh/blob/master/lib/git.zsh) file from Oh-My-Zsh and put it in ~/.yadr/zsh/

## Installation - [Prezto](https://github.com/sorin-ionescu/prezto)

-	Grab prompt_agnoster_setup from this repo
-	Put the file in ~/.zprezto/modules/prompt/functions/
-	Restart your ZSH session
-	Run `prompt agnoster` to make sure the theme loaded properly
-	Modify ~/.zprezto to load this theme by looking for a line similar to the following:
	-	zstyle ':prezto:module:prompt' theme 'theme name here'
	-	Replace 'theme name here' with 'agnoster'
-	Restart your ZSH session, or start a new one
	
## Installation - [YADR](https://github.com/skwp/dotfiles)

-	Grab prompt_agnoster_setup from this repo
-	Put the file in ~/.zsh.prompts/
-	As per the YADR documentation, run `echo "prompt agnoster" > ~/.zsh.after/prompt.zsh`
-	Restart your ZSH session, or start a new one

## Preview/Screenshot

![agnoster for Prezto Screenshot](https://raw.github.com/digitalformula/zsh.prompts/gh-pages/img/screenshot.jpg)