### gulp-jest issue

Need to test React component which has imported SASS with jest using gulp task. The issue here is that gulp-jest doesn't map module names (so it can't skip .scss files) and test fails (throws: "SyntaxError: Unexpected token"). I have no idea why it behaves this way.

The strangest thing is that is works perfectly via "npm test" and jest-cli, but doesn't with "gulp test" for some reason.
