
RedLETR
=======


REDCAP Load Extract Translate Revise (REDLETR) - Web based tool for importing data into REDCap.

This repository contains the code for our use case involving the transformation clinical neuropsychology batteries (2010-2014) from various ad hoc solutions to a flexible, centrally-managed, REDCap-backed database.

Importantly, our new version contains added features not available in the basic functionality of REDCap such as norm scoring and report generation, facilitating its smooth integration into the clinical workflow.

We have provided our code and documentation as a resource for similar institutions likewise interested in moving clinical research stores to more flexible advanced databases.

Please check the WIKI and accompanying snippets; these provide the most useful design patterns for data cleanup and migration.


To set up a virtual environment, do the following (On an Ubuntu Linux Platform)

sudo pip install virtualenv
sudo pip install virtualenvwrapper

#I also recommend installing the workon code as it makes it easier

export WORKON_HOME=~/.virtualenvs
mkdir $WORKON_HOME
#Add this to your ~/.bashrc
echo "export WORKON_HOME=$WORKON_HOME" >> ~/.bashrc

#setup virtualenvwrapper

