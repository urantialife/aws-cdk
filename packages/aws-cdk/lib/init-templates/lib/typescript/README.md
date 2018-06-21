# Installing Dependencies

Since CDK npm modules are not published to npm, use `cdk-beta-npm`
instead of `npm` when installing dependencies.

    cdk-beta-npm install @aws-cdk/dynamo
    
This wrapper falls-back to the public npm repository, and 
you should use it for installing all dependencies for this project:

    cdk-beta-npm i left-pad --save-dev

# Useful commands

 * `npm run prepare` compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `cdk docs`        open CDK documentation
 