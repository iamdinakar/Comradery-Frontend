This is the frontend repository for Comradery. If you haven't already, you should start with setting up the API server (Lionhearted, https://github.com/reparadocs/Comradery-API). This is a first pass at making this open source so there will be rough edges. Please email me at rishab at comradery dot io to let me know about any problems you run into, big or small, even if you figure out how to fix them yourself.

There should be minimal setup for this repo. It should be easy to run using `yarn install` and then `yarn run start` to run locally. Use next.js hosting on Vercel and it should work without any special settings or configuration. You will want to change `API_PRODUCTION_URL` and `API_DEV_URL` in `utils.js` to the relevant URLs for the API server (Lionhearted) and `CHAT_PRODUCTION_URL` and `CHAT_DEV_URL` to the relevant URLs for the Chat server (Spitfire).
