---
layout: post
title:  "Gems, rails developers cannot overlook"
date:   2016-09-07 04:41:00
categories: gem rails
---


We are talking about some powerful Gems in Rails. So first of all what
comes to our mind is that what are gems? There are some well known and
common genre of problems that web developers face everyday. Take *user
authentication* as an example. With technology, user wants to log in to
all the systems with one account (with just a single sign up!). Say, I
want to buy products from online but I do not want to create a new
account on each of these e-commerce sites rather I want to sign into
each one those with my gmail / facebook / twitter /… account. As these
common problems recur, trying to solve them again and again will be a
waste of our effort and this will take away the required attention from
the application we want to develop. Basically Gems are ruby software
packages which provide the solutions to these common problems. They are
not necessarily related to Rails but Ruby. Most of these gems are
available on github and developed by talented open-source developers.
Here are some of them, which will probably blow away most of the
headaches of Rails developers.

<span style="font-weight: 400;">In web development, developers have to
handle the authentication issues from the very beginning of their
development process. Even with the prototype, it is bound to have some
authentication system to identify and verify users. Device is a very
flexible authentication gem for rails based on Warden. It is completely
customizable and a complete MVC solution.</span>

<span style="font-weight: 400;">Capistrano in a server management,
deployment and automation tool written in Ruby. It is very easy to
integrate and becomes very powerful tool with rails. It can also work
with the version control systems like Git, Mercurial and SVN. Coding and
deploying becomes so much effortless with Capistrano. Capistrano has two
testing suites, RSpec and Cucumber. It is an MIT licensed open source
project.</span>

<span style="font-weight: 400;">Developers or DevOp engineers who
maintain software environments use cron jobs for scheduling jobs in a
periodical order. Whenever is a Ruby gem for writing and deploying cron
job with a very clear and human readable syntax. It can be integrated
with capistrano with very little effort and can use the built-in
Capistrano recipe for easy crontab updates with code deploys.</span>

<span style="font-weight: 400;">Carrierwave provides a super flexible
way to upload files in Rails applications. It is very easy to integrate
and use. It can work with any Rack based web applications. Multiple file
uploads, validations, configuring URL, testing, upload to Amazon S3 and
many more can be done so neatly with carrierwave.</span>

<span style="font-weight: 400;">In rails the complete bootstrap feature
is in a gem which is twitter-bootstrap. Web design came within the hands
of full stack developers with the tools like bootstrap.
Twitter-bootstrap-rails project add Bootstrap CSS toolkit to Rails Asset
Pipeline (Rails 4, 3.1, 3.2 are supported).</span>

<span style="font-weight: 400;">Active Admin is a Ruby on Rails
framework for creating sophisticated backend for web administration. It
gives the general business application tools to make it easy and
flexible for developers to implement beautiful interfaces with very
little effort.</span>

<span style="font-weight: 400;">Sunspot is made to be easily integrated
with any ORM. It can even work with non-database-backed objects like
file systems. It is written in Ruby with the strong interaction with
Solr search engine. It provides simple, intuitive, expressive DSL backed
by powerful features for indexing objects and searching for them.</span>

<span style="font-weight: 400;">CanCan is a gem for authorization in
Ruby on Rails which preserved the access or different resources in the
application. All permissions are defined in a single Ability class and
not duplicated anywhere in the application. The current user’s
permissions can then be checked using the can? and cannot? methods in
the view and controller.</span>

#Fun_Fact: Rails itself is a Ruby Gem, check gemfile for your Rails version.

Happy coding!


  [No Comments]: http://www.nascenia.com/gems-rails-developers-cannot-overlook/#respond
  [<span style="font-weight: 400;">Devise</span>]: https://github.com/plataformatec/devise
  [Database Authenticatable,]: http://rubydoc.info/github/plataformatec/devise/master/Devise/Models/DatabaseAuthenticatable
  [Omniauthable,]: http://rubydoc.info/github/plataformatec/devise/master/Devise/Models/Omniauthable
  [Confirmable,]: http://rubydoc.info/github/plataformatec/devise/master/Devise/Models/Confirmable
  [Recoverable,]: http://rubydoc.info/github/plataformatec/devise/master/Devise/Models/Recoverable