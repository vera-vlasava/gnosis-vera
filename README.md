# Gnosis Safe React Challenge

This repository is a fork of our actual [Gnosis Safe repo](https://github.com/gnosis/safe-react).

Your task is to make a pull request, much like our own developers do every day. Please read the task description below.

## Task description

In the Gnosis Safe app, we maintain a curated list of plugins called Safe Apps.
The list of Safe Apps is growing, and it's becoming harder for the user to find the apps they use often.

One solution to this problem is to add the ability to mark some Safe Apps as favorite ⭐️

<img width="1082" alt="Screenshot 2021-06-04 at 15 36 44" src="https://user-images.githubusercontent.com/381895/120810962-cac41800-c54b-11eb-97da-ec90f7ffb0cf.png">

### UI requirements

* When the user hovers over an app, a star-like button appears
* If the user clicks on it, the app becomes a favorite
* Favorite apps are displayed on top of the list
* A favorite is removed if the user clicks on the ⭐ button again
* The information about the user's favorite apps should be stored in the local storage

<img width="1085" alt="Screenshot 2021-06-04 at 15 43 17" src="https://user-images.githubusercontent.com/381895/120811557-63f32e80-c54c-11eb-8ea7-899a0cbab93c.png">

### Solution hints

The components you will need to modify are `AppsList`, `AppCard`, and possibly other modules.

Please feel free to use the [Icon](https://components.gnosis-safe.io/?path=/docs/data-display-icon--icons) component from our component library.

### Pull Request & Feedback

Once done with the coding, please create a PR to this repository.

**We'll review it and share our extensive feedback with you.**

In the PR description, please write up a bit about your solution:

* how you solved it
* what challenges you had to overcome
* what you learnt while working on it

### Bonus points

Unit tests for this feature would be greatly appreciated.

Enjoy coding! 😄

## Installing and running the app

Install dependencies for the project:
```
yarn
```

To run the app:
```
yarn start
```

## MetaMask and Rinkeby

By default, the app will be pointing to the Rinkeby test network. You'll need to install a Chrome extension called [MetaMask](https://metamask.io) and connect to this blockchain.

You can choose to add an existing safe when the app starts. Please use this existing safe address: `0xb3b83bf204C458B461de9B0CD2739DB152b4fa5A`.

After loading the safe, you can go to **Safe Apps** in the sidebar menu.

## Running the tests

To run the tests:
```
yarn test --watch
```

### Lint

ESLint will be run automatically before you commit. To run it manually:
```
yarn lint:fix
```
