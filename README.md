# ImageJ Macro Syntax Highlighter and AutoComplete update

Peter J. Lee NHFML

IJMacro_Lang.xml is a &quot;User Defined Language&quot; (UDL) file for highlighting macro functions when editing macro scripts in Notepad++.
For the current version of Notepad++ (for Windows) User Defined Language (UDL) files in xml format are placed in:
%AppData%\Roaming\Notepad++\userDefineLangs

The corresponding AutoComplete file (which also contains function usage information that will be dispayed in a pop-up window) is placed in the autoCompletion subfolder of the installation directory. This file must be given the same name as defined in the UDL file line:
<p>&lt;UserLang name=&quot;IJMacro&quot; ext=&quot;ijm&quot;, udlVersion=&quot;2.1&quot;&gt;</p>
In the case above the autoCompletion file should be renamed &quot;IJMacro.xml&quot;.

# ImageJ Macro Syntax Highlighter

Kota Miura (miura@embl.de)

##VIM

- filetype.vim

Place this file under 

	~/vimfile (Windows)
	~/.vim (Unix)

in case of MacVim, a bit complicated:
place the file under 

	~/.vim 

also add the contents of above filetype.vim to 

	/Applications/MacVim.app/Contents/Resources/vim/runtime/filetype.vim


- ijmacor.vim

Place this file under 

	~/vimfile/syntax (Windows)
	~/.vim/syntax (Unix)
	
in case of MacVim, a bit complicated:
Place the file under 
	
	~/.vim/syntax 
Also place another copy to 
	
	/Applications/MacVim.app/Contents/Resources/vim/runtime/syntax


##Notepad++

Notepad++ is a free software for Windows (http://notepad-plus-plus.org/).
For istallation of syntax highlighters, please refer to [this page](http://sourceforge.net/apps/mediawiki/notepad-plus/index.php?title=Syntax_Highlighting_Sharing)

- IJmacro_VIMlight.xml
	for bright background (white)

- IJmacro_VIMMonoIndustrial.xml
	for dark background (style "Mono Industrial", selectable from Settings -> Style Configurator)

##CotEditor

The definition file for CorEditor Could be found at:
[https://gist.github.com/1334472](https://gist.github.com/1334472)


