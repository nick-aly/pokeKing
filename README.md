pokeKing App

An express.js app with monogo backend and minimum requirements wich is respsonsible of finding the next pokeking. 

Only 4 deps. The goal was to go as minimal as i could without any builde, framework or data lib. One js file for the server and one html to serve.

To run:

git clone https://github.com/nick-aly/pokeKing.git
cd ./pokeKing
npm install
npm start

Notes:

1. replace the url with whatever mongodb url you want
2. the app currenly drops the databases before init. comment the lines  
            PokemonProfileModel.collection.drop()
            PokemonSummaryModel.collection.drop()