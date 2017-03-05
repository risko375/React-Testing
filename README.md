Using TDD to create a simple app which logs messsages to the screen typed in by user

First set up failing tests and move towards all passing (red to green) as app code develops

Uses Mocha to load tests, run them one by one, clean up after each
Uses Chai for helpers for asserting certain properties about the test subject 

Test_helper.js created to:
- Set up testing environment to run like a browser in command line
- build 'renderComponent' helper that should render a given react class
- build helper for simulating events
- set up chai-jquery

Test specs written for each component,action creator and reducer


