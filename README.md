# personal-project

## AWS Amplify
### Creating Amplify Project with Next and React:
```
sudo npm install -g yarn
yarn global add @aws-amplify/cli
amplify -v
amplify configure
npx create-next-app next-amplify
cd next-amplify/
```
- create src folder
- move pages and styles files to src folder 
```
amplify init
```
### Creating API
```
amplify add api
```
####  **API Settings** 
* ? Select from one of the below mentioned services: GraphQL
* ? Choose the default authorization type for the API API key
* ✔ Enter a description for the API key: · personalproject
* ✔ After how many days from now the API key should expire (1-365): · 365
* ? Configure additional auth types? Yes
* ? Choose the additional authorization types you want to configure for the API 
* ? Here is the GraphQL API that we will create. Select a setting to edit or continue Continue
* ? Choose a schema template: One-to-many relationship (e.g., “Blogs” with “Posts” and “Comments”)
* ✔ Do you want to edit the schema now? (Y/n) · yes
* ✅ Successfully added resource nextamplify locally
* ✅ Some next steps:
* "amplify push" will build all your local backend resources and provision it in the cloud
* "amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud
## backend commands
```
npm init -y
npm i nodemon
```

## frontend commands
```
npx create-react-app client
```

### configurations
- add package.json scripts`"dev": "nodemon server/index.js",`
- run

```
nodemon dev
```



