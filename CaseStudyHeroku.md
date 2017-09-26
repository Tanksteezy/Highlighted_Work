<h1> Heroku </h1>

  *Things to think about:*
  
  <h3> Development </h3>

  <h3> QA </h3>

  <h3> Pre-Production/Staging/Pilot </h3>

  <h3> Production </h3>
    
  *How does Heroku benifit these testing enviroments above? ^^^ Also, how would you use it for your next "online game project"?*
  
  <p1>Referencing from the website; You are able to add these test environment 'definitions', onto the files, as well as adding scripts IF they are needed. Then, in the end, you are able to see it in the Pipline; the CI is already implemented into the Heroku Pipline so no worries about not involving that. We can apply our testing environments individually by deploying codespace revisions to each of its own. Along with making our test environments in here, we can also take advantage of dependecies or third-party libraries, configuration or third-party credentials/database/etc, and backing services; which is stored in config and allows you to swap out providers or allows runtime services. There is also a different concept called the '**Rails Environment**'. Rails allows us to write custom logic, which can be great for code. Not only are we recommended to keep our pre-production close to our *Production* environment, but Heroku also recommends that we keep our *Development* close to *Production* and *Production* close to *Staging*. However, it is stated that if those environments are different from each other, it is not garenteed that some of the proccesses in *Production* will go through. This is called, **'Dev/Prov Parity'**. </p1>
