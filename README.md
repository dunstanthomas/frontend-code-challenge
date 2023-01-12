# DT Frontend Code Challenge

### Intro

The objective of the DT frontend code challenge is to create a UI which matches as closely as possible the [example](example.png) image:

<img src="example.png" alt="example" width="400"/>

The code challenge UI you create should consist of static html and CSS/LESS updates to the files included in the repo.  

We are looking for attention to detail and code quality.

To run the code challenge you will need a version of node installed >=12.0.0.

### Extra credit

If you really want to show us what you can do, for extra credit, implement the following:

1. Make all fields required and disable the Next button until all fields are filled in.
2. Implement a date picker that only allows you to pick a date within the last 18 years for input 3.
3. Show on screen validation messages when you blur each field, or when the Next button is clicked.
4. Unit test all of the above.

*Please do not feel like you HAVE to implement the extra credit items.**

Getting started
---------------

### Initial setup

Click here to **[Fork](https://github.com/dunstanthomas/frontend-code-challenge/fork)** this repo, pull down your fork to your dev machine or you can use a GitHub codespace and do everything in your browser (just make sure you do your changes on your fork and not on our main branch.)

Once you have dev environment (local or the cloud) run the following commands in a terminal at the repo root:

```bash
npm install
```

This will install all the dependencies required to run the code challenge.

### Run the local server

```bash
npm run dev
```

Then navigate to [http://localhost:3000](http://localhost:3000) in your browser.

### Updates

Add all html markup updates to the index.html file. For CSS updates add selectors to styles.less. If you're unfamiliar with CSS  preprocessors don't worry, you can use standard CSS in the styles.less file. The code challenge uses [Vite](https://vitejs.dev/) for frontend tooling. When running in dev mode all files will be hot reloaded.

### Once you are finished...

Commit and Push your changes into your Fork ready for your second interview.


