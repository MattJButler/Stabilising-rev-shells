# Stabilising-rev-shells

''
python -c "import pty; pty.spawn('/bin/bash')"      //run on victim's machine
''


CTRL + Z                                            //switches over to your machine
stty raw -echo                                      //run on your machine
fg                                                  //switches back to victim machine
export TERM=xtrm                                    //run on victim machine
