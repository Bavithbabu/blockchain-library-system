# blockchain-library-system
A  Go REST API that uses blockchain technology to securely track book checkouts in a library system. Demonstrates blockchain, Go web development, and API design.
Purpose
To demonstrate how blockchain concepts can be used to securely record transactions (in this case, book checkouts) in a library system using the Go programming language.

How it works
You can add new books to the system.
When a user checks out a book, a new block is created and added to the blockchain, recording the checkout details.
The blockchain ensures that each record is linked to the previous one, making the history immutable.
The API provides endpoints to view the blockchain and add new books or checkouts.
Technologies used :
. Go (Golang)
. Gorilla Mux (for routing)
. Standard Go libraries (crypto, net/http, encoding/json, etc.)
