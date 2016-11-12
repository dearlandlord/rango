Using Tango with Django: http://www.tangowithdjango.com
and using appendices: setting up your system

READ THIS BLOCK BEFORE STARTING A SETUP; guide not great for macs
{
        (not in setup guide: installed and opened xcode just in case dependencies needed)

        Installed Python 3.5.2: https://www.python.org/downloads/

        but used: http://docs.python-guide.org/en/latest/starting/install/osx/
        which installs homebrew and through that setup tools and pip; and then tells you how to install for python 3.5

        issues on mac for echo $PYTHONPATH solved by: http://stackoverflow.com/questions/27508202/pythonpath-disappears-on-mac-os-x-after-reopening-terminal
        Basically use: Michaels-MacBook-Air-2:~ michaelmchugh$ sudo nano ~/.bash_profile
        instead of .profile


        then back to TwD guide...

        then lots of messing and:http://cheng.logdown.com/posts/2016/08/12/install-python3-and-virtualenv-on-mac

        and then: http://virtualenvwrapper.readthedocs.io/en/latest/ to alter wrapper path (2nd and 4th lines in cheng bash_profile) to:
        /Library/Frameworks/Python.framework/Versions/3.5/bin/virtualenv and /Library/Frameworks/Python.framework/Versions/3.5/bin/
        virtualenvwrapper.sh (files found by using $ which virtualenvwrapper.sh)

}



Keep going to git
after setting up github etc. the rango app workspace can be cloned by:
$ git clone https://dearlandlord:Aseven89@github.com/dearlandlord/rango.git
(pg 245 TwD)

Further git set up
$ git config user.name "Mike McHugh"
$ git config user.email "mchughmp@tcd.ie"
