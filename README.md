## Fayecom Assets
This repo contains the assets for fayecom, most importantly, the javascript.  

## Installation

In rails, use rails-assets in your gemfile

(Gemfile)

    source 'https://rails-assets.org' do
      gem 'rails-assets-fayecom'
    end

And serve the assets in your application.js file from the rails asset pipeline.  

(app/assets/javascripts/application.js)

    //= require fayecom

Finally, restart your app

    $  bundle
    $  r s



