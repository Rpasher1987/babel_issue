Hey Harry, looks like there have been updates to babel recently that are resulting in Rails 6 not compiling. I am experiencing that issue now, where I can not compile anything. Here is what I found on the web...
https://github.com/babel/babel/issues/15679
Do you know a work around for this by any chance?

[Bug]: Breaking change in a minor version bump · Issue #15679 · babel/babel
:computer: Would you like to work on a fix? How are you using Babel? babel-loader (webpack) Input code // Anything, the version release caused it to break old babel.config.js files Configuration file name... (108 kB)



Hey Ryan, let me take a look now

11:20
Which project are you working on?
11:20
Can you send me a link to your Github repository?
11:21
The Babel version should be locked, so it should still work on our projects



Hey Harry. So it's not a specific project at the moment but when I try to start a new one. So when I enter "rails _6.1.6_ new project_template --skip-spring --skip-listen --webpack=react --skip-turbolinks" the new project won't work because of the changed version of Babel