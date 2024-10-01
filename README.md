_For the Fomantic Ui documentation, see the original repository._

## How to include this design in your project

1. Install this package directly from Github: `npm install https://github.com/TimKochDev/fomantic-ui#latest_commit_hash
2. Import `fomantic-ui/dist/semantic.min.css` in your project.
3. Set `font-weight: 300;` (recommendably in index.html)

## Troubleshooting

If gulp fails to build the project, try running `npm install` in the root directory of the project.

If this doesn't work, I suspect this is because of some gitignored files.
Checkout `ca88fb4` and run `npm install` again.
Then checkout `7c34c1b` and run `gulp build` again.
Then you should have all the necessary files.
Checkout the latest commit again. `gulp build` should work now.
