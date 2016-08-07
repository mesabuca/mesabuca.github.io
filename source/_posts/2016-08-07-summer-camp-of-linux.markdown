---
layout: post
title: "Summer Camp of Linux"
date: 2016-08-05 01:09:08 +0300
comments: true
categories: 
---

Hello everyone. I'm in Bolu Turkey to day because of Linux camp. Today we start from begining of the ruby. I mean from setting up and I remember I didn't write anything about how to set up the ruby and rails. Firstly Ihad to say that ruby and their gems are have some compatibility problems because of 
their versions. So some people cant install the ruby with their gems and also rails is gem too. There is recommended versions and environment. These are ruby : 2.3.1 rails 4.2.6  ruby environment : rbenv.
Anyway lets start. <br>

Firstly we had to install some dependecies to install ruby 

 ```
 sudo apt-get update
 sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev

 ```
 And then we should install and set some settings on $PATH to use rbenv.
 
 ```
 cd
 git clone https://github.com/rbenv/rbenv.git ~/.rbenv
 echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
 echo 'eval "$(rbenv init -)"' >> ~/.bashrc
 exec $SHELL

 git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
 echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
 exec $SHELL
 ```
 
 Now we can install ruby.
 
 ```
 rbenv install 2.3.1
 rbenv global 2.3.1
 ruby -v
 ```
 
 If output is `ruby 2.3.1p112` it means ruby has been installed.

 Now we had to install bundler. Bundler is downloading up and setting up your gems which located in GemFile.
 
 ```
 gem install bundler
 ```
 
 And the last step is rails.
 
 ```
 gem install rails -v 4.2.6
 rbenv rehash
 rails -v
 ```
 
 If out put is `Rails 4.2.6` it means youre done. You are ready to go.
 C U on next post. ^_^