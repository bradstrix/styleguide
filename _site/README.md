# Lion Design System

![Lion Design System](../images/iconsArtboard 2.png)

The Lion Design System is created using the Style Guide Guide created by Brad Frost as a boilerplate for hetras' Style Guide.

[Brad Frost's Demo Here](http://bradfrost.github.io/style-guide-guide/)

## How it works
Style Guide Guide is built using [Jekyll](https://jekyllrb.com/), a static site generator which works quite well for managing the content of a style guide.

The tool can consume and display components from anywhere. 

## Getting Started
1. Download or clone the files from the [repository on Github](https://github.com/bradfrost/style-guide-guide).
2. In the command line, navigate to the root of the project and run the `jekyll serve` command. This will build the static site and watch for changes.
3. Visit `http://127.0.0.1:4000/` in your browser to see the style guide.

## Troubleshooting for Mac
If you try to install Jekyll and the error is returned that you cannot install with the following error

`Error installing jekyll: jekyll requires Ruby version >= 2.0.0.`

Try the following: 

1. Open your terminal and run `\curl -sSL https://get.rvm.io | bash -s stable`
2. When this is complete, you need to restart your terminal for the rvm to work.
3. Now run `rvm list known` - This shows the list of versions of the ruby.
4. Now, run `rvm install ruby-2.4.2`
5. If you type `ruby -v` in the terminal, it still shows you `ruby 2.0.`
6. To use the latest installed version. Run `rvm use ruby-2.4.2`
7. To set this as the default version, run `rvm use ruby-2.4.2 --default`

[Stackoverflow article] (https://stackoverflow.com/questions/38194032/how-to-update-ruby-version-2-0-0-to-the-latest-version-in-mac-osx-yosemite)

Alternatively use the following artivle for a Ruby and Jekyll install

[Installing Ruby & Jekyll on Mac OS X] (https://andytaylor.me/2012/11/03/installing-ruby-and-jekyll/)


## Feedback and Questions
If you have questions or issues with Lion Design System, please feel free to [open an issue](https://github.com/bradstrix/styleguide/issues). 