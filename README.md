ignorable
=========

Ignore columns in ActiveRecord 

Installation
============

Add this to your Gemfile: 
  
    gem 'ignorable'

Usage
=====

    class Topic < ActiveRecord::Base
       ignore_columns :attributes, :class, :meta_column_used_by_another_app
    end

