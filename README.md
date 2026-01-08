# Silent Auction (Python)

A simple console-based silent auction program written in Python. Users place bids, which are stored in a dictionary, and the program determines the highest bidder.

---

## Features

* Accepts multiple bidders
* Stores bids in a dictionary
* Automatically finds the highest bid
* Displays the auction winner
* Optional ASCII logo using `art`

---


## How It Works

* Each bidder enters a name and bid amount
* Bidding continues until the user types `no`
* The program compares all bids
* The highest bidder is announced

---

## Example Output

```
What is your name?: Alex
What is your bid?: $150
Are there any other bidders? yes

What is your name?: Sam
What is your bid?: $200
Are there any other bidders? no
The winner is Sam with a bid of $200.
```

---

## Notes

* Bids are stored in a Python dictionary
* Screen is cleared using line breaks for privacy
* Highest bid is calculated manually

