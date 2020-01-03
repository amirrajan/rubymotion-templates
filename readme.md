# RubyMotion Template

These are [RubyMotion](http://rubymotion.com) templates. Some are
provided by the community. Some are provided by RubyMotion
proper.

Testing out your template before sending a Pull Request (example):

```sh
env RUBYMOTION_TEMPLATES_OVERRIDE=~/projects/rubymotion-templates/motion/project/template/ motion create HelloWorld --template=ios
```

Also remember to change the following line in the Rakefile of your test project

```ruby
$:.unshift("~/.rubymotion/rubymotion-templates")
```

to

```ruby
$:.unshift("~/projects/rubymotion-templates")
```

When you send your PR. Be sure that your commits are in this format (take note of the bracket based tag at the beginning):

```sh
[ios] Fixed grammar and spelling mistakes.
```
