
0.5.0 / 2012-10-19 
==================

  * add "main" support
  * fix `component-search(1)` when description is missing. Closes #83 [Tim Oxley]

0.4.2 / 2012-10-17 
==================

  * fix silly component-install(1) bug attempting to read ./component.json. Closes #81

0.4.1 / 2012-10-16 
==================

  * update builder

0.4.0 / 2012-10-15 
==================

  * add `.remotes` support. Closes #6
  * add --name option to specify the base name of built files.
  * change --standalone name to be required. Closes #71
  * update builder dep, remove --dev cascading. Closes #69

0.3.0 / 2012-10-10 
==================

  * add readme template for `component-create(1)` with more boilerplate
  * add default of `{}` for conf for direct installs
  * add `auth` support for basic authentication [Dan Williams]

0.2.0 / 2012-10-06 
==================

  * add `component-search(1)` `--open` flag to view in browser. Closes #39
  * add `component-wiki(1)`. Closes #55
  * add "y" as "yes" support
  * add `component-install(1)` `--save` support
  * fix < 0.8.x support  

0.1.1 / 2012-09-19 
==================

  * add new "stdio" child process inherit option. Closes #45
  * update component(1) --help docs
  * remove special-casing of 127 exit status
  * remove component-register(1) from package.json
  * fix subcommand execution on windows [ForbesLindesay]

0.1.0 / 2012-09-18 
==================

  * add remote search
  * add ★ to search output
  * add sorting by stars
  * add --json to `component-search(1)`
  * remove `component-register(1)`
  * change `component-search(1)` to use only verbose output

0.0.7 / 2012-09-14 
==================

  * add `--standalone [name]` support to component-build(1). Closes #34
  * add memoized mkdir
  * add empty .development `{}` to component-create(1)
  * update component-builder
  * remove "which" dependency
  * remove logging from component-convert(1)
  * remove "component.json" dep of component target in component-create(1) makefile
  * rename devDependencies to development

0.0.6 / 2012-09-05 
==================

  * add `--dev` to `component-create(1)` build command
  * add `component-build(1)` --dev flag. Closes #25
  * rename `devDependencies` to `development`
  * fix `component-create(1)` undefined.css. Closes#24

0.0.5 / 2012-09-04 
==================

  * add `--standalone` to `component-build(1)`

0.0.4 / 2012-09-01 
==================

  * add `.repo` to `component-create(1)`
  * add `.files` support. Closes #11
  * fix installation of files nested in dirs
  * change `component-register(1)` to use .repo prop
  * change `component-search(1)` query to be optional
  * change `component-search(1)` to join args

0.0.3 / 2012-08-30 
==================

  * add missing commands to package.json

0.0.2 / 2012-08-30 
==================

  * update commander.js for pull-request fail
