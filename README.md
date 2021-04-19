# Contentstack's starter app content

This repository aims to provide sample stack content to users for the implementation of marketing websites. An easy way to import this stack content is by using the ‘seed’ command. 

To import this content to your stack, perform the following steps:

1. Install the CLI by running the following command in your terminal:

	```npm i -g @contentstack/cli``` 

2. By default, CLI uses the North America region. To use the Europe region, run this command in your terminal:

	```csdx config:set:region EU```

3. Next, log in to your Contentstack account via CLI:

	```csdx auth:login```

4. Run the ‘seed’ command to import content to your stack: 

	```csdx cm:seed -r "contentstack/stack-starter-app"```

Refer to the [Seed command documentation](https://www.contentstack.com/docs/developers/cli/import-content-using-the-seed-command/) to learn more. 

Also, we are soon coming up with starter apps where you can view this content instantly.
