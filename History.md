
0.7.3.1 / 2016-05-17
====================

  * adding key to mkconfig

0.7.3 / 2016-05-01
==================

  * updating version
  * fixing hook names

0.7.2 / 2016-04-30
==================

  * update version
  * check if env is given first before doing config_section test

0.7.1 / 2016-04-30
==================

  * update version
  * fix bug with mkconfig
  * updated help command instructions
  * Configuration output command

0.7.0 / 2016-04-30
==================

  * updating Readme
  * updating Readme
  * show cluster required error if no args
  * Support for running commands on multiple environments
  * Create deploy-cluster script

0.6.0 / 2012-06-19 
==================

  * Changed `console` command to cd to current [bronson]
  * Changed `run` command to cd to current [bronson]

0.5.0 / 2012-04-29 
==================

  * Added forward agent directive support [bronson]

0.4.0 / 2011-07-27 
==================

  * Added console command [bronson]

0.3.2 / 2011-06-16 
==================

  * Trying `git fetch --all` to solve a ref issue we are having

0.3.1 / 2011-06-08 
==================

  * Fixed multi-arg refs

0.3.0 / 2011-06-08 
==================

  * Added optional ref support, defaults to latest tag
  * Added `-T, --no-tests`
  * Changed `branch` setting to `ref`

0.2.0 / 2011-06-07 
==================

  * Added `$SHARED` env var
  * Added; revert on failed tests
  * Added `test` hook
  * Changed; hooks are executed relative to `$path/current`
  * Changed; use ○ instead of ... for logs
  * Fixed hook pipe exit
  * Fixed hook commands cut issue

0.1.0 / 2011-06-06 
==================

  * Added; `tee` hook command stdio into __$LOG__
  * Changed hook message, looked like an error before

0.0.4 / 2011-06-03 
==================

  * ln -sfn. Closes #1

0.0.3 / 2011-06-02 
==================

  * Fixed rev support

0.0.2 / 2011-05-28 
==================

  * Added `update` command

0.0.1 / 2011-05-28 
==================

  * Initial release
