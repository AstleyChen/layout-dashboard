# Taipei Layout Team Dashboard
A dashboard used for bugzilla bugs triage and dispatch as well as status management.

Work in progress at https://astleychen.github.io/layout-dashboard/

## Hacking

1. `npm install`
2. `npm start`
3. http://localhost:8080/

## Contributing

Submit pull requests to the `master` branch.

To update GitHub Pages, make sure your `master` branch is up to date, then:

1. `git checkout gh-pages`
2. `git merge --no-commit master`
3. `npm run build`
4. `git add dist/`
5. `git commit`
6. `git push`

