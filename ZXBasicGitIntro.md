# ZXBasic Programming git

Welcome to the ZX Basic Programming Facebook group's GitHub!

This is a page dedicated to programming in Basic on the ZX Sprectrum

We decided to utilise GitHub to help store code, examples and tecniques that get posted to the group as Facebook's handling of files and searching can be quite time consuming. It was also suggested that we have a repo where we can work on collaborations and doing so would mean we would need an SVN to handle multiple people working on the same project. GitHub allows us to keep historical versions after changes have been made to any file. 

Source code can be downloaded and used in tools such as Basinc, you may also find tap/sna versions of listing that can used in an emulator. Code stored here has been written by various members of the group and should be credited where possible. 

If you have not down already please come and join our group https://www.facebook.com/groups/ZXBasic

Thanks goes to Thomas Heckmann who created the GitHub home for us. 

## Getting started
The ZXBasic repositories are located here: https://github.com/ZXBasicProgamming

### Browse code
If you just want to browse the repository and have a peek of whats going on, you can do fine with the web interface on [Github](https://github.com/ZXBasicProgamming).

### Participate and submit code
If you want to participate, contribute code or just play around with the code for yourself, you will need a **git client** on your local machine and a github account (it's free as in free beer).

The following options are recommended:
* Windows
	* Desktop Client [GitHub Desktop](https://desktop.github.com/)
	* Git for Windows (includes Command line version) [here](https://git-for-windows.github.io/)
* OSX
	* Desktop Client [GitHub Desktop](https://desktop.github.com/)
	* Command line git (out-of-the-box)
* Linux / Unix
	* Command line git (usually out-of-the-box)

## Checkout the ZXBasic repository
To create a working local copy where all your local work will be maintained, clone the repository:

### Command line 'git'
If you want to clone the 'Examples' repository, use the following command: 
```
git clone https://github.com/ZXBasicProgamming/Examples.git
```
You should now have a local directory *Examples* with all the code from the repository. *NOTE* This is your own local copy, you can do all kind of changes without affecting the general repository.

### GitHub Desktop
With the GitHub Desktop it is only possible to clone repositories associated to your account. If you don't have access to the ZXBasic repository from your account, you first need to fork the ZXBasic repository into your own repository.
**TBD**

## Contribute to ZXBasic repository
Say you want to contribute with a new fine example to the repository.

* go to the Example repository on github - you will find it at https://github.com/ZXBasicProgamming/Examples
* Click the “Fork” button at the top right.
* You’ll now have your own copy of that repository in your github account.
* For command line - open a command line or shell and type
```
git clone https://github.com/<username>/Examples.git
```
where **username** is your github username.
* You’ll now have a local copy of your version of the Example repository.
* Change into that project directory (Example):
```
cd Example
```
* Add a connection to the original ZXBasic repository.
```
git remote add ZXBasicProgamming https://github.com/ZXBasicProgamming/Examples
```
* Add a folder for your example e.g.
```
mkdir AwesomeExample
```
* Create files for your example in the folder just created.
* git add and git commit those changes
```
git add AwesomeExample/*
git commit -m "Awesome example showing ZX Spectrum version of one of the most popular programs"
```
* git push them back to github. These will go to your version of the repository.
```
git push
```
* Go to your version of the repository on github, and you should see your changes.
* Click the “Pull Request” button at the top.
* Click the “Pull Request” button at the top.
* Note that the *ZXBasicProgramming Example* repository will be on the left and your repository will be on the right.
* Click the green button “Create pull request”. Give a succinct and informative title, in the comment field give a short explanation of the changes and click the green button “Create pull request” again.

Viola - your contribution are ready for review by the admins.


