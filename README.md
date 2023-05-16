## About

This repository creates a static HTML site for Whonix packages in the repository [whonix-packages-static](https://github.com/Whonix/whonix-packages-static). It uses markdown data generated by [package_parser](https://github.com/derivative-maker/package_parser) to create the site.

It is based on the Jekyll theme `just-the-docs`

## Dev Setup

1. Install a working version of ruby 3
2. Install bundler by running `gem install bundler`
3. `bundle install`
3. Copy the `./docs` folder from `package_parser` in to the `./docs` folder within this repository
4. Run `bundle exec jekyll build` 
5. Move the `_site` folder to your desired location to view the static site

## CI Setup

In the github settings for this repository, an environment variable `ACCESS_TOKEN` must be set for Github actions. This variable must correspond to a personal access token with read and write priviledges that can be created in your personal settings.

### WARNING

If you push any changes in `./docs` to main, it will automatically change the static site in the [whonix-packages-static](https://github.com/Whonix/whonix-packages-static). The docs folder should only contain changes generated by the `./publish-site.sh` script in the [package_parser](https://github.com/derivative-maker/package_parser/blob/main/build-site.sh) repository.
