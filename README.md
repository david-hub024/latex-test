## Task

Build an Angular 8+ application with the following:
1. User authentication: Use Firebase to support authentication in your application, so that the first screen a user sees, asks them to login via their google account. If the user is detected to have been already authenticated, then directly take them to the 2nd page.
2. Text editor: Once logged in, show a large textbox on the page integrated with the Medium editor (https://github.com/yabwe/medium-editor) and allow the user to write content in this editor area.
3. Everything the user writes here, should be synced into the Firebase database in real-time for that user’s account, automatically, without hitting a submit button.
4. When the user logs back in, retrieve their last written and auto-saved document and show it in the editor ready for editing.
5. Host your project using Firebase hosting and send us a link, along with your code on GitHub.
6. Allow the user to enter LaTeX equations into the editor inside 2 enclosing $ symbols (e.g. $1+1=2$) and once the user is done typing them out, render the actual equation.
We will not consider applications which do not do this.

## Installation Process
Run `npm install` to install all the required dependencies

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
