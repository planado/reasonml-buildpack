# reasonml-buildpack

## Installation

#### Heroku Dashboard

Add a custom buildpack to your to your applications Settings tab under
section Buildpacks by using the URL of this repository, instead of the
short name of Heroku's own buildpacks. It goes alongside your Ruby and
Node buildpacks, placed in last position.

#### Heroku CLI

First, check your environment has bs-platform installed (e.g., with npm or yarn).
To add the Webpack Rails buildpack in the last index, run this command:

    heroku buildpacks:add --index 3 https://github.com/reasonml/reasonml-buildpack.git

## Usage

On deployment, the buildpack runs the build command `bsb -make-world`.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Started on 1 December 2017.

## Credits

Created by Nikita Shilnikov.

## License

See LICENSE.md file.
