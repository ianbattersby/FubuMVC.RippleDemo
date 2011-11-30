FubuMVC.RippleDemo
==
The Fubu projects use a utility called 'Ripple' to manage not only their own build dependencies but also to allow you to manage your project dependencies with the Fubu repository, thus allowing you to update your own projects with a local build of a Fubu project.

This is an demo of using Ripple to do just that, manage Fubu dependencies in your own solution.

Some (current) constraints to bear in mind;

* FubuMVC and your <project dir> must share a common parent, e.g. c:\mycode\fubumvc and c:\mycode\myproject
* You will need to install the buildsupport submodule or the contents thereof, this is where ripple lives
* Any package dependencies should be details in ripple.config
* It is advisable that you put ripple.cmd in your root project directory for ease (see fubumvc repo directory)