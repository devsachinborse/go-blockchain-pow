## GoBlockchain
GoBlockchain is a simple implementation of a blockchain in Go, utilizing proof-of-work (PoW) consensus mechanism.

Installation
To install and run this project, follow these steps:

Clone the repository:
```
https://github.com/devsachinborse/go-blockchain-pow.git
```

To run the project -
```
go run main.go
```
Open `http://localhost:4040` in a browser and you will see one block. 


To add blocks, you send a POST request to `localhost:4040` using CURL.
Send a BPM like `{"BPM":75}` in the body of this post request.use another terminal to add block once you start the main server in another terminal
`curl -X POST -H "Content-Type: application/json" -d '{"name": "75"}' http://localhost:4040 `

Your terminal will start performing the work.
Thank You...!
