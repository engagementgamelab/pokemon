
# Pokémon Go! civic engagement project

### Setup
1. Install [el-web-sdk](https://github.com/engagementgamelab/el-web-sdk).
2. Clone this repo (https://github.com/engagementgamelab/pokemon.git).
3. Link this module to el-web-sdk: 

  ```
  cd pokemon
  npm-link
  ```
  
  ```
  cd ../el-web-sdk
  npm link pokemon
  ```
  
4. Start the module. **From el-web-sdk**, run:

  ```
  grunt --sites=pokemon
  ```
The site should now be running at http://localhost:3000.

(More docs coming soon.)