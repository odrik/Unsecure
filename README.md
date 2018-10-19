# Welcome 

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/831b6679c05a4a1894ca12b802707d39)](https://app.codacy.com/app/odrik/Unsecure?utm_source=github.com&utm_medium=referral&utm_content=envt-collaboratif/Unsecure&utm_campaign=Badge_Grade_Dashboard)

  ## Verified commit

 - ## Installing GPG

	### Red Hat / CentOS

		yum install gnupg

	### Ubuntu / Debian 

		apt-get install gnupg

	### Mac OS X

		ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

		brew install gnupg

 - ## Create your GPG key

		gpg --gen-key

		gpg --list-secret-keys --keyid-format LONG

		git config --list

		git config --local user.signingkey #your key#

		git config --local user.email “#your git email#”

	

 - ## Commit

		git add #your files# or .
        
		git commit -S -m “commit”

