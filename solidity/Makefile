node_modules:
	npm install

.PHONY: test
test: node_modules
	npm run test

.PHONY: deploy
deploy: node_modules
	truffle migrate

deploy-rinkeby: node_modules
	truffle migrate --network localrinkeby
deploy-ropsten: node_modules
	truffle migrate --network ropsten
deploy-mainnet: node_modules
	truffle migrate --network mainnet