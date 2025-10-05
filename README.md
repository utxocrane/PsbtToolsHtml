# Simple static html tool for BTC PSBT creation

This tool is for anyone who need to create a simple Bitcoin TX manually.

How it works?
1.Fetch the tx data from web api of the popular mempool(blockstream.info)
2.Create an unsigned tx hex
3.Sign the tx using your cold/hardware wallet
4.Preview and Broadcast the final tx hex using blockstream.info or other web service

Why this?
. No web server or runtime... required,all u need is just a browser with chrome and dbclick the html
. Precisely control the transaction fee to 1 sat/tx (rather than 1 sat/vB as most cold wallet)
