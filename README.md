### Hostme-Github-Deployment-Integration-Example

Just have a look inside `./github/workflows/main.yml` to see how the deployment is made !
The main project for that github action is available here : https://github.com/osscameroon/hostme.gh-action !

### What you need to do

- Generate/Create your Hostme api token, On your admin page, you have a section "Advanced" with API Tokens menu, click there, then click on "+  Generate new token". You will have a modal with a token, copy this token to a secured place

- [Create the github secret](https://docs.github.com/en/actions/reference/encrypted-secrets) `HOSTME_API_TOKEN`, that will contain your API TOKEN 


![screen](./screenshot.png)


## Result 

The Website is available [here](https://hostmegh-actionexample.hostme.space).

Have FUN :-)
