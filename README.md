# SCA Technical Screening - Step 2 Notes

## Dependencies

1. NodeJS Latest CURRENT installation
2. Run command: npm install -g @angular\cli
3. Run command: npm install -g rimraf (to more quickly delete folders, specifically node_modules)

## Tech Stack & Tooling

+ Angular 6
+ Angular Material 6
+ Bootstrap 4.1
+ font-awesome
+ material-design-icons (generally used with ng-mat-2 components)
+ xlsx (for creating XSLX files from JSON)
+ file-saver (used in conjunction with xlsx to save the resulting file)

## NPM RUN COMMANDS

+ start - runs the ng-cli dev server with aot on
+ build - builds the ng-cli app with aot and build-optimizer
+ test - runs ng test

## Observations

1. I used this as a learning exercise to get up to speed on ng 6, ng-mat-6, and bootstrap 4, and made the task more difficult than it had to be given that I had to spend a fair amount of time learning, researching, and banging my head against the code at times (particularly trying to test against the HttpClient)
2. Made judgment calls on how far to take some aspects of writing this UI, and chose to hold back on how much testing I wrote -- specifically, I leaned away from integration testing the components using ng-mat

## Unit Tests

+ Could not get the Error `Error: Illegal state: Could not load the summary for directive NoticeDialogComponent.` and chose to ignore this failing test in favor of getting something done (yes, it annoys me to not have resolved this...yet)
+ Only exercised the components as opposed to the components + the views
