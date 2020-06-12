# HNG Hotel Beta

Created by team-neon beta sub-group

## How to Contribute

1. First, fork this repo to your account
2. Next, from your terminal, clone the repo you just forked to your local machine by running:

```sh
  git clone <put your repo url here>
```

3. Then, run be below command:

```sh
 git remote add upstream https://github.com/hngi/team-neon-hotel-beta.git
```

4. Create a new branch describing the component you are working on. E.g. If you are working on the footer, you should run:

```sh
 git checkout -b footer
```

Here, `footer` is the name of the branch. So change it according to what you are currently working on.

5. Next, start up the development server by running the below command:

```sh
  npm start
```

This will open up the project in your browser.

6. Now write production ready code! :)
7. When you are done writing code, commit your code and push to the branch you created.

```sh
  git add . && git commit -m "write something meaningfull here, describing what you did"
```
Push your changes:

```sh
  git push
```

8. Open a pull request and push to the develop branch


## HOW TO WORK WITH THE BOILER PLATE 

This app uses webpack to bundle code and it is very important that you write your code in the appropriate folder so that the bundler can find the file and serve it.

The only place you need to work on is in the src folder. There you have 

1. `views` folder which will contain your html files
2. `Styles` folder which will contain scss folder
3. `Media` folder which will contain pictures
4. `js` folder which will contain javascript code

Any new scss file for styling that that you create has to be declared in the entry.scss file. The file is located inside the views folder and is the scss entry point for webpack. 
For example, if you create a `nav.scss` file, you can declare it like this

```sh
@import './nav.scss';
```

> IF YOU ARE NOT COMFORTABLE WITH SCSS , YOU CAN USE CSS. THEY WORK THE SAME WAY.

Contact the subteam leads or @deji.ab on the slack channel if you have any issues
