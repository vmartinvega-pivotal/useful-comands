# useful-comands

Ask for input in shell script.

## Default variables to use
export INTERACTIVE=${INTERACTIVE:="true"}
export USER=${USER:="admin"}

## Make the script interactive to set the variables
if [ "$INTERACTIVE" = "true" ]; then
	read -rp "User: ($USER): " choice;
	if [ "$choice" != "" ] ; then
		export USER="$choice";
	fi
fi
