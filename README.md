# README #

FLMS means Fetch, Load, Merge and Sync.

### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

### Real Acquisitions Dashboard ###
- Link:  [dashboard.ratoolkit.com](http://dashboard.ratoolkit.com/)
- Email: support@realacquisitions.com
- Pass: qwe112233

### Modules ###
-	CAD
-	Tax
-	Grantor
-	Probate
-	Linebarger
-	Transcript
-	Divorce
-	MLS__
There are some screens.__
Screen list: `screen –ls`__
Screen New Name: screen –s <new_ screen _name>__
Screen Existing Name: screen –x/-rd <screen _name>  Ex: `screen -rd grantor`__
Shell file location: /opt/shared/nightly-scheduler__
Shell naming convention: run_<module_name>_TX<country_name><Fetch/Load/Marge/Sync>__
Example: `run_grantor_TXMontgomeryFetch.sh`__

###Run a Module###

*	./run_<module_name>_TX<country_name><FLMS>.sh
	Ex: `./run_mlsreport_TXHarrisSync.sh`
*	screen <-x/-rd> < screen _name >
	Ex: `screen -rd grantor`
	




