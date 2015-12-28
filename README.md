# threejs-boilerplate

While playing with [three.js](https://github.com/mrdoob/three.js) and shaders I found myself writing up the
same boilerplate code again and again. So here is the template I kept writing.

[three.js](https://github.com/mrdoob/three.js) will be updated upon
every release.

## Getting started

1. Clone this repo `git clone git@github.com:olejrosendahl/threejs-boilerplate-shader.git`

2. Delete the existing git repository by running `rm -rf .git`.

3. Initialize a new git repository with `git init`, `git add .` and `git commit -m "Initial commit"`.

4. Run `python -m SimpleHTTPServer` to start the local web server.

5. Go to `http://localhost:8000` and you should see the app running!

## Dependencies

- three.js

## Changelog

#### Changed
- Use three.js r74

### [0.1.1] - 2015-10-06
#### Added
- Update viewport on window resize.

#### Changed
- Use three.js r72

### [0.1.0] - 2015-08-10
#### Added
- Added three.js setup code and spinning cube animation.
