


## To contribute
Fork the this repo then clone from forked repo from your github account 

```git clone https://github.com/your_username/urbanite.git```  

or   
```git clone git@github.com:your_username/urbanite.git```

### Setting up environment



Our application is dependent on the following:

- ruby version 2.6.3

- rails v 6.0.2

- nodejs v 12 

The installation varies depending on the enviroment/ OS this guide dwells majorly on debian based linux
distros.You can update it to including any missing OS.In the meantime it always direct to the documentation of given dependecy if we feel it is not well covered.

#### Ruby installation

Install ruby version manager (rvm) by following  [these instructions](https://rvm.io/)

If you are using ubuntu or  debian based linux distro follow [these instructions](https://github.com/rvm/ubuntu_rvm)

After installation of rvm   install ruby-2.6.3 ruby this on terminal `rvm install 2.6.3`.

### Installing rails

Just run `gem install rails` for linux or unix

If you are on window  follow [these instructions](https://rubyinstaller.org/downloads/)

#### Node js and  installation 

TO install nodejs in debian based distros  run this commands

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

`sudo apt install nodejs`

Install yarn using this [link](https://classic.yarnpkg.com/en/docs/install/#debian-stable) follow 
instruction given depending on the OS you have


### Fetching deps and starting your server:

change your working directory  to *urbanite* `cd urbanite`

with working directory as `urbanite`

Now run `bundle` to get rails dependencies and `yarn install` to get  node dependencies

run serve like so: `rails s`

Now you can visit [`localhost:3000`](http://localhost:3000) from your browser.

### Navigating the git

Create a remote repo with name upstream, i.e 

```git remote add upstream https://github.com/okothkongo1/urbanite.git```

 or

`git remote add upstream git@github.com:okothkongo1/urbanite.git`

Before working on an issue, ensure your local repo is up-to-date, by running:

* Create a branch from develop like so: `git  checkout -b 3-updatecontribution-readme origin/develop`

* Ensure your work is upto date by pulling from upstream like so: ```git pull upstream develop```

When creating a branch, ensure it has an issue number.

For example, issue `3-update-contribution-readme` should be in the branch name:

`3-update-contribution-readme`




Upon making changes push to the `origin` remote 

```git push origin branchname```

Your last commit message should be in the form `Update contribution readme#fixes3`

Then create a pull request if you feel the issue is completed
