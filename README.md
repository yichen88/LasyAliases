# LasyAliases
```sh
alias gl='git log'
alias gs='git status'
alias gfp='git fetch -p'
alias gcm='git checkout master'
alias gc-='git checkout -'
alias gcp='git cherry-pick'
alias gaa='git add .'
alias gau='git add -u'
alias gpm='git pull origin master'
alias gnb='function _gnb { gcm; gpm ; git checkout -b $1 ;echo $1;}; _gnb'
alias amend='git add -u;git commit --amend --no-edit'
alias gr='function _gr()
	{ re='^[0-9]+$';
	if [[ $1 =~ $re ]] ; then
	 git rebase -i HEAD~$1;
	 else
	 git rebase -i $1; 
	fi;};_gr'
alias gz='git reset HEAD~1'

alias dmvn='mvn -Dmaven.test.skip=true -Dcheckstyle.skip'
alias mct='mvn clean test'

export LANG="en_US.UTF8"
alias fr="setxkbmap fr;echo \"AZERTY Loaded\""
alias us="setxkbmap us;echo \"QWERTY Loaded\""

alias idea='sh ~/idea2/bin/idea.sh > /dev/null 2>&1 &'
alias clion='sh ~/clion/bin/clion.sh > /dev/null 2>&1 &'

```
