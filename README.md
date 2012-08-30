# Dash Docset Creator
Generate .docset 's from induvidial HTML files that are compatible with the
amazing [Dash App](http://kapeli.com/dash/) for Mac

## Instructions

1. Download / Extract Source to directory of your choosing
2. Place all HTML files into the <strong>files_go_here</strong> dir
3. Place an Icon (icon.png) into the <strong>icon_goes_here</strong> dir
4. Now edit the <strong>docset.config.php<strong> file
		
		´´´PHP
		/*DOCSET FILENAME*/
		/*MUST END WITH .docset !!!*/
		$config['docset_filename'] = 'laravel.docset';
		
		/*DOCSET TITLE*/
		$config['docset_title'] = 'Laravel Documentation';
		
		/*DOCSET PRETTYNAME (SINGLE WORD)*/
		$config['docset_prettyname'] = 'laravel';
		
		/*DOCSET INDEX PAGE*/
		$config['docset_index_page'] = 'index.html';
		
		/*DOCSET DOCSEUTIL PATH*/
		$config['docset_docseutil_path'] = '/Applications/Xcode.app/Contents/Developer/usr/bin/docsetutil';
		´´´