[Sinatra][2], [Haml][3] and [Bootstrap][4] kick ass so I wanted to make a bare bones project to start from which would get the setup hassle out of the way. I thought remaking the example projects would be a good way to get comfortable with Bootstrap and this arangement. Here you can find the Sinatra + Haml + Bootstrap version of the following [layout examples] [1]:

##Setup

All of the example projects and the bare bones project are set up with:

* Bundler
* Shotgun
* Rack
* Haml
* Vlad the Deployer

To get up and running all that should be needed is to install the Ruby gem
Bundler if up don't already have it installed then run:

    $ bundle install

That should install everything that is need for the app to run. To start it
run:

    $ shotgun

As is the case with any **Shotgun** app, you can update the `config.ru` file to
change Shotgun settings. Likewise `/config/deploy.rb` for the **Vlad** settings, and `Gemfile` for your **bundler** install settings

enjoy!

[1]: http://twitter.github.com/bootstrap/getting-started.html#examples "Bootstrap example layouts"
[2]: http://www.sinatrarb.com/
[3]: http://haml.info/
[4]: http://twitter.github.com/bootstrap/
