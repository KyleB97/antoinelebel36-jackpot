# antoinelebel36-jackpot

Site:
	User: 
		Steam Login
		Set Trade Link
		Free Credits for site in name
	CSGO & Rust:
		Deposit 
		Withdraw
		Roulette
		Provability Fair Verify Page
	Rust:
		Deposit
		Jackpot
		Provability Fair Verify Page
	Admin:
		Users:
			List Users 
			Ban Users
		Settings:
			CSGO Settings: 
				Minimum item deposit
				Minimum bet amount
				New Round Time
			Rust Settings:
				Minimum item amount
				Minimum Items until roll
				Maximum pot items
				Time per round 
				Percentage cut per round
			Bot Settings:
				Master Steam Account
			Free Credit Settings:
				Amount
	Cron Jobs:
		CSGO Item Price Update
		Rust Item Price Update
Game Server:
	CSGO: 
		Roll New Round every X
			Pay Winners
	Rust:
		Wait for 2 Players To Enter, then start timer
		Send ALL items excluding house cut to winner

Steam Bot: 
	Check for trade requests, deny any that aren’t from Master
	Check for pending Rust Requests
		Send Pending Rust Requests
		Check status of pending requests 
	Check for pending CSGO Requests
		Send Pending CSGO Requests
		Check status for pending requests
	Check for Rust Jackpot winners
		Send Rust jackpot items to Winner
	Check for CSGO withdraw Request
		If withdraw fails, refund coins to player
