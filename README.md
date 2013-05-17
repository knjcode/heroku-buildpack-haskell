# Heroku Buildpack: Haskell (Modified for Cloud Foundry)

More information can be found [here](http://catdevrandom.me/blog/2013/05/16/buildpacks-in-cloud-foundry-v2/)

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for Haskell apps. It uses GHC 7.4.1 and cabal-1.16.0.1.

Based on [https://github.com/puffnfresh/heroku-buildpack-haskell](https://github.com/puffnfresh/heroku-buildpack-haskell)

Tested with demo app found here:

https://github.com/pufuwozu/haskell-buildpack-demo

## Usage

    $ cf push myapp --buildpack=https://github.com/BrianMMcClain/heroku-buildpack-haskell
