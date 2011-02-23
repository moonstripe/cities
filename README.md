Using activerecord-import
===================
* This is an example showing usage of Zach Dennis' activerecord-import gem. Instead of playing with tutorial databases, I decided to create a somewhat real database that can be of use to all. I came across http://sourceforge.net/projects/zips/files/#files. So, this is a simple Rails application (nothing there yet) with three models: City, Code and State. Some may argue if we need the models this way, but that's a separate thing. 
* What I wanted to do was use Zach Dennis' [excellent activerecord-import gem](https://github.com/zdennis/activerecord-import/wiki/) to see if I can seed the database with the zips.csv I have created (modified from original at sf.net). Of course, the seeding should be fast. But more importantly, it should be correct. So, I am going to ask Zach if he can take a look here.
---
After you clone this repository, just do the following:
* Modify database.yml to your environment.
* See db/seeds.rb. It has two methods: seed__from and import__from
