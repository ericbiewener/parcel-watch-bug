# parcel-watch-bug

`package.json` specifies that a target that should be compiled to `dist/target-1`. Running `yarn build` (which executes `parcel build`) correctly compiles to this `target-1` subdirectory. Running `yarn start` (which executes `parcel` in `watch` mode) compiles to the root `dist` directory. That is a bug.
