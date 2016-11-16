o
## Commands performed by Perl 5 in `said.pl`
All of these commands below have not been reimplemented in Perl 6 yet.

#### Transliterate
Usage: `!transliterate ありがとうございました`

Works for almost all languages or non language characters.  Converts into romanized ASCII text.

Output: `arigatougozaimasita`

#### Fortune
Usage: `!fortune`
Gets a short fortune using the Linux/Unix `fortune` program.

#### Unicode Lookup
Usage: `!ul 🐧`

Output: `https://www.fileformat.info/info/unicode/char/1f427/index.htm`

 `[ Unicode Character 'PENGUIN' (U+1F427) ] `

Will lookup a a unicode character at the fileformat.info website.
To get a response not for a character but for the codepoint you want, use:

`!unicodelookup 1F427`

#### Urban Dictionary
Usage: `!ud thing to look up`

Ouput: The top definition and example from urbandictionary.com

#### Questions
You can have the bot answer yes or no questions.  Just address the bot by name like so:

`mybot is the sky blue?`

Response will be either `Is the sky blue? No.` or `Is the sky blue? Yes.`

You can also ask it a this or that question, with a maximum number of arguments being three.
`mybot is it going to be a good day today or a bad day today?`

`It is going to be a good day today` or `A bad day today`

	fullwidth/fw
	uc
	ucirc
	lc
	lcirc
	help
	action
