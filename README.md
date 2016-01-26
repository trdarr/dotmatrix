DOTMATRIX
=========

This is a fork of [hashrocket/dotmatrix][]:

> Dotmatrix is a collection of dotfiles used at Hashrocket to customize various
> development tools. This project is the culmination of many years worth of
> tinkering with our favorite tools to get them to behave just right. We think
> using dotmatrix makes working with these tools more pleasant and hope you will
> too!


Differences
-----------

* Adds [jcoglan/vault][] tab-completion.
* Uses [brainsik/virtualenv-burrito][].
* Uses [chriskempson/base16-shell][] ([eighties][], specifically).
* Uses [rbenv][] instead of [RVM][].


Installation
------------

```zsh
git clone https://github.com/trdarr/dotmatrix.git .dotmatrix
cd .dotmatrix
bin/install
bin/vimbundles.sh
```

[brainsik/virtualenv-burrito]: https://github.com/brainsik/virtualenv-burrito
[chriskempson/base16-shell]: https://github.com/chriskempson/base16-shell
[eighties]: https://chriskempson.github.io/base16/#eighties
[hashrocket/dotmatrix]: https://github.com/hashrocket/dotmatrix
[jcoglan/vault]: https://github.com/jcoglan/vault
[rbenv]: http://rbenv.org/
[RVM]: https://rvm.io/
