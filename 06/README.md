# COMP30022 Workshop 6

- Start at 12:05, please turn cameras on.

```txt
It will be quicker to sort breakout rooms if you add your team's name infront of your zoom name.
```

## Testing

![Alt text](https://www.seguetech.com/wp-content/uploads/2015/09/segue-blog-4levels-software-testing.png)

- Individual components / functions
- Multiple interlinked components / functions
- **System as a whole** : FE → BE → DB
- Load & Stress testing, User Experience testing ...

Useful testing libraries -

- [Playwright](https://playwright.dev/)
- [Cypress](https://docs.cypress.io/)
- [k6](https://k6.io/open-source/)
- Selenium, jMeter, Mocha, Chai

**Map system tests to `Acceptance Criteria`**

[Writing behaviour driven tests](https://cucumber.io/)

`Examples`

## CI/CD

![Alt text](https://wac-cdn.atlassian.com/dam/jcr:b2a6d1a7-1a60-4c77-aa30-f3eb675d6ad6/ci%20cd%20asset%20updates%20.007.png?cdnVersion=1785)

Here, integration & deployment

1. Write code → test on localhost
2. → create PR → test code through GitHub actions
3. → merge PR → automate deployment (either through Heroku/Netlify or GitHub actions)

`2` Can have 3 benefits

- Local environment is different from deployment environment. Test results can vary.
- Run tests against fresh database instantiated only for the duration of the pipeline
- Test connectivity to your publicly deployed database, external API's prior to deploying application.

[MongoDB CI](https://github.com/marketplace/actions/mongodb-in-github-actions#usage)
[Python CI](https://github.com/marketplace/actions/setup-python#usage)
[NodeJs CI](https://github.com/actions/setup-node#usage)

`Examples`

## Team updates

One member from each team will give a brief update on their teams progress

## Breakout rooms
