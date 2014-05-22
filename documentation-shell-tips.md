---
layout: default
title: Shell Tips - Documentation - iTerm2 - Mac OS Terminal Replacement
active-state: documentation
subhead: Shell Tips
---
<div class="doc-wrapper">
        {% include toc.html %}
	<section class="doc-section">
		<h6 class="question">UTF-8 patch for tcsh 6.12.00</h6>
		<p class="answer">
			By Yuichi Ohkawa.

			The tcsh pre-installed in Mac OS X has many problems dealing with UTF-8. If you input mult-bytes characters to tcsh, this patch may help you to edit the characters.

			Download from <a href="ftp://ftp.tba.org.tohoku.ac.jp/pub/tcsh-6.12-utf8.patch.gz">here</a>
		</p>
		<h6 class="question">Tips for using zsh with iTerm2</h6>
		<p class="answer">
			Provided by Marius Wyx.

			There are people with hints on ways to customize the title bar and tabs, a much simpler way when using zsh is to do the following:
		</p>
		<div class="panel code">
<pre>
bell=`tput bel` 
precmd () { 
echo -n "\033]1;$USERNAME@$HOST$bell\033]2;$PWD> - $USERNAME@$HOST ($status)$bell" 
} 
PROMPT='%m %B%3c%(#.#.>)%b ' 
RPROMPT=''
</pre>
	</div>
	<p class="answer">
		Much simpler and does not require anything special. (apart from zsh)
		
		Also in zsh, the command line completion I have expanded to be /Applications/ aware:
	</p>
	<div class="panel code">
<pre>
if [ "`uname`" = "Darwin" ]; then 
compctl -f -x 'p[2]' -s "`/bin/ls -d1 /Applications/*/*.app 
/Applications/*.app | sed 's|^.*/\([^/]*\)\.app.*|\\1|;s/ /\\\\ /g'`" 
-- open 
alias run='open -a' 
fi
</pre>
	</div>
	<p class="answer">
		typing: "open -a " and then pressing tab will try and complete any application... (added an alias run as well)
	</p>	
</section>
</div>