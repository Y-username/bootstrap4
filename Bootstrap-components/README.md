# Components

#### core components
1. add a nav bar at top of the page
- navbar-expand-sm make navbar responsive
- .mr-auto to force sibling columns away from one another
- <span class="d-inline d-sm-none"><br></span> 
2. add pictures for quotes, use <div class="media">
3. add icons for each Feature, use link of Font Awesome
4. add badge to show NEW feature
5. make the icons hidden on the mobile device
6. add an alert before callout for Promotion

#### Progressive Enhancement With JavaScript Components
1. add JS link at the end of index.html file
2. add functionality to compress menu into a <strong>menu button</strong>
3. add dropdown to one item in navbar
4. add a modal dialog (the in page overlay when user clicks a sign-up button) to the webpage
  -paste the code after </article> tag. cause moddal dialog is also top level element in the body
  -a modal is like an island of content siting in the middle of the page
  -bootstrap modal is hidden by default, it needs an ID to link to sign up button. data-toggle is the trigger for modal, and data-traget links to modal ID.
  -the sign up modal to functionality needs backend code to processing

#### Questions
1. Core Components - Part 2 at 2:26min, <div class="d-none d-sm-block">should means image only show up in small screen, why opposite effect?
2. Core Components - Part 2 at 6:19min, when try to make icons hidden on mobile, they appear on desktop screen with headers in two lines...
3. line15-17: Which class makes navbar button only show up when its a mobile screen??  
4. component quiz 2: a button is not a component???