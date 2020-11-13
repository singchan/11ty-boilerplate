
1. Fork this repo in github or click "use this template" (/!\ be sure to select "Include all branches")
1. Create a [deploy token here](https://github.com/settings/tokens) with the access write `public_repo`
1. [In the settings of the website, "secret" section, create a new secret](./settings/secrets/actions/new), call it `DEPLOY_TOKEN` and paste the token as its value 
1. [In the settings of the website, "secret" section, create a new secret](./settings/secrets/actions/new), call it `BASE_URL` and set its value to the name of your repository (e.g. `11ty-boilerplate`)
1. Create a website with [Stastic designer](https://design.stastic.net/)
1. Publish your site from Stastic designer to github as 11ty layout
1. Create a file like [test.md](./test.md), add `layout: YOUR PAGE NAME IN STASTIC`
