####This one finally works: 

so ignore the [tutorial](https://medium.com/the-web-tub/creating-your-first-vue-js-pwa-project-22f7c552fb34), just checkout the git repo, 
change into it `cd pwa-vue-app-1`
and hit `npm install`. 

to develop, you can use 
`npm run dev` but with this you won't get a progressive webapp. 

This only works by running
* `npm run build`
* `serve -s dist -l 5000`
* `ngrok http 5000`

Now you will see a URL in the terminal which you can open in your mobile device.
Without paying for ngork, this URL will stay valid for 8 hours. 
 
Then I copied over my stuff from [here](https://read.acloud.guru/how-to-add-file-upload-features-to-your-website-with-aws-lambda-and-s3-48bbe9b83eaa)